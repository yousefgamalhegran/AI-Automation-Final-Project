# AI-Automation-Final-Project
# 🍝 Pasta Cup - AI Restaurant Ordering System

## 📌 Project Overview
This project is an AI-powered restaurant ordering system that allows customers to place orders through Facebook Messenger. The system automatically understands customer messages, extracts order details, stores them in Google Sheets, and notifies the restaurant via Telegram.

## ⚙️ Technologies Used
- n8n (Workflow Automation)
- Google Gemini AI
- Facebook Messenger API
- Google Sheets
- Telegram Bot
- JavaScript

## 🧠 How the System Works
1. The customer sends a message on Facebook Messenger.
2. The message is received by a Webhook in n8n.
3. The AI Agent analyzes the message using Google Gemini.
4. The system extracts order details such as product, quantity, name, phone, and address.
5. If the order is complete, it is saved automatically in Google Sheets.
6. A notification is sent to Telegram to inform the restaurant.
7. A confirmation message is sent back to the customer.

## 🧾 Example Order

Customer message:
انا عاوز باستا ألفريدو  
2 كبات  
احمد ابراهيم  
01211223344  
الجيزة الهرم  

Extracted data:
Product: باستا ألفريدو  
Quantity: 2  
Name: احمد ابراهيم  
Phone: 01211223344  
Address: الجيزة الهرم  

## 📊 Data Storage
All orders are automatically stored in Google Sheets with the following fields:
- Order ID
- Customer ID
- Customer Name
- Product
- Quantity
- Phone
- Address
- Status

## 🔔 Notification System
When a new order arrives, the system sends an instant notification to Telegram with the order details.

## 🚀 Features
- AI understands customer messages
- Automated order processing
- Real-time notifications
- Automatic order storage
- Works 24/7

## 👨‍💻 Author
Yousef Gamal Hegran
