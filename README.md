# 🤖 AI WhatsApp Automation Agent (n8n + Gemini)

## 📌 Overview
This project is an AI-powered WhatsApp chatbot built using n8n workflows and Google Gemini API.  
It automates customer interactions such as product queries, FAQs, and order-related requests using intelligent AI responses.

The system uses a modular AI agent architecture with memory, structured data sources, and workflow automation for scalable real-world usage.

---

## 🚀 Features
- AI chatbot powered by Large Language Models (Gemini)
- Retrieval-Augmented Generation (RAG) for accurate responses
- WhatsApp automation using webhook triggers
- Context-aware responses using memory
- Integration with product and FAQ databases
- End-to-end workflow automation using n8n

---

## 🧠 Architecture
- **Trigger:** WhatsApp webhook (incoming message)
- **AI Agent:** Processes queries using LLM + memory + tools
- **Data Sources:** Google Sheets (Products, FAQs, User Logs)
- **Response:** Automated reply sent back via WhatsApp API

---

## 🛠 Tech Stack
- n8n (workflow automation)
- Google Gemini API (LLM)
- MongoDB / Google Sheets (data storage)
- FastAPI (optional backend integration)
- REST APIs

---

## 📂 Project Structure

whatsapp-ai-agent/
│
├── workflow/
│ └── whatsapp-agent.json
│
├── docs/
│ └── architecture.png
│
├── .env.example
├── README.md
└── requirements.txt

---

## ⚙️ Setup Guide

### 1. Import Workflow
- Open n8n
- Import `whatsapp-agent.json` file

### 2. Configure Environment Variables
Create a `.env` file:

GEMINI_API_KEY=your_api_key
WHATSAPP_API_TOKEN=your_token
VERIFY_TOKEN=your_verify_token
MONGODB_URI=your_mongodb_uri


### 3. Setup WhatsApp API
- Configure webhook URL
- Verify token must match in n8n
- Ensure workflow is active

### 4. Connect Data Sources
- Google Sheets for:
  - Products
  - FAQs
  - User Logs

---

## 📸 Demo
(Add screenshots of workflow + WhatsApp chat here)

---

## 💡 Use Cases
- E-commerce chatbot automation
- Customer support system
- FAQ assistant
- AI-based conversational agents

---

## 🏆 Highlights
- Built modular AI agent system with memory and tools
- Integrated RAG-based response generation
- Designed scalable automation workflow for real-world use

---

## 👨‍💻 Author
Hiral Girase  
AI / Machine Learning Engineer

---

## 📜 License
This project is for educational and demonstration purposes.
