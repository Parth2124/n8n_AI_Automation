# n8n_AI_Automation
Built an automation assistant using n8n that connects WhatsApp, Google Drive, and Gemini AI. Users can send WhatsApp commands (LIST, DELETE, UPLOAD, MOVE, RENAME, SUMMARY) to manage Google Drive files. The workflow responds with results in WhatsApp and uses Gemini AI to summarize/analyze folder contents. 

# 📱 WhatsApp Google Drive Assistant (n8n + Gemini AI)

This project is an **automation workflow built with [n8n](https://n8n.io/)** that allows users to **manage Google Drive directly through WhatsApp commands**.  
It integrates **Google Drive API**, **Twilio WhatsApp API**, and **Gemini AI** to handle file operations and provide AI-powered summaries.

---

## ✨ Features
- 📂 **LIST** → View files/folders in Google Drive  
- 🗑 **DELETE** → Remove files  
- 📤 **UPLOAD** → Add files to Google Drive  
- 📦 **MOVE** → Move files between folders  
- ✏️ **RENAME** → Rename or update files  
- 📊 **SUMMARY** → Summarize or analyze folder contents using **Gemini AI**  
- 🔔 **WhatsApp Notifications** for all actions  

---

## 🛠 Tech Stack
- **n8n** → Workflow automation  
- **Google Drive API** → File operations  
- **Twilio WhatsApp API** → WhatsApp integration  
- **Gemini AI API** → File summarization & analysis  
- **JavaScript Functions** → Custom logic inside workflow  

---

## 🚀 Deployment

### 1. Run n8n
npm install -g n8n
n8n start

