
# Intelligent Lead Classification System - n8n

An AI-powered automation workflow built using n8n that captures student inquiries, classifies leads (HOT/WARM/COLD), and automatically sends follow-up emails while saving data to Google Sheets.

This system removes manual lead handling and ensures fast responses to prospective students.

Workflow Diagram
---
<img src="AI Automation Flow.png" alt="n8n Project" width="3000" height="3000" />
<img src="Lead Automation.png" alt="n8n Project" width="3000" height="3000" />

Features
---
1. AI-powered chatbot that replies to student inquiries automatically
2. Captures lead details (name, email, phone, course) from chat
3. Stores chat history and leads in Google Sheets
4. Sends automated personalized emails to students
5. Automatic classification into HOT, WARM, and COLD leads
6. Notifies counselor instantly for high-priority leads
7. Follow-up email campaigns based on lead category


Tech Stack
---
1. Automation: n8n
2. AI Model: Groq Chat Model
3. Database: Google Sheets
4. Email Service: Gmail API
5. Logic: JavaScript (Lead Scoring)
6. Memory: n8n Memory Buffer
7. Trigger: n8n Chat Webhook


Installation & Setup
---
```
Step 1 — Start n8n
Run n8n locally or cloud instance

Step 2 — Import Workflow

Download workflow JSON

Go to n8n → Import from file

Step 3 — Configure Credentials

Add:

Google Sheets OAuth

Gmail OAuth

Groq API Key

Step 4 — Activate Workflow

Toggle workflow to Active
```
