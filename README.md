# 🏠 EstateIQ — AI Real Estate SDR Agent

An AI-powered sales agent that qualifies real estate 
leads, matches properties, and alerts the sales team 
automatically.

## 🤖 What it does
- Chats with Egyptain clients conversationally in Arabic .
- Collects requirements one question at a time
- Scores leads automatically (HOT 🔥 / WARM ⚡ / COLD ❄️)
- Searches matching properties from database
- Saves all leads to Google Sheets
- Sends instant email alerts to sales team for HOT leads
- Asks for phone number and confirms follow-up

## 🛠️ Tech Stack
- n8n (Workflow Automation)
- Groq LLM 
- Google Sheets (Properties DB + Leads)
- Gmail (Sales Team Alerts)

## 🔧 How to run
1. Import `workflow.json` in your n8n instance
2. Add your Groq API Key from console.groq.com
3. Connect your Google Sheets account
4. Connect your Gmail account
5. Import the properties CSV to your Google Sheet
6. Start chatting!

## ⚙️ Setup Required
After importing, connect:
- Groq API Key
- Google Sheets Credential
- Gmail Credential
- Update Google Sheet ID with your own
