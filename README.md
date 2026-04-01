# AI Email Automation System (n8n)

## 🚀 Overview

This project is an AI-powered email automation workflow built using n8n. It automatically reads incoming emails, determines whether a reply is required using an LLM, and generates professional draft responses.

## 🧠 Features

* Real-time Gmail monitoring using triggers
* LLM-based email classification (reply vs no reply)
* Automated email reply generation
* JSON-based structured decision making
* Draft reply creation in Gmail threads

## 🛠 Tech Stack

* n8n (workflow automation)
* LLaMA 3.1 via Groq API
* Gmail API
* JSON parsing

## ⚙️ Workflow Architecture

1. Gmail Trigger → Fetch incoming emails
2. LLM Classification → Check if reply is needed
3. Conditional Logic → Filter emails
4. LLM Response Generator → Draft reply
5. Gmail API → Create draft

## 📊 Impact

* Reduced manual email response effort by ~70%
* Automated repetitive communication workflows

## 📁 File

* `gmail-ai-auto-responder.json` → Import into n8n

## ▶️ How to Use

1. Import JSON file into n8n
2. Connect Gmail API credentials
3. Add Groq API key
4. Activate workflow

## 👨‍💻 Author

Muhammed Fahim M
