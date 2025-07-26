# 🧠 AI-Based Smart Responder using n8n, OpenRouter & Email

This project allows users to fill a form with details like their name, class, goal, etc., and automatically receive a personalized **weekly timetable** via email using AI (OpenRouter models). It uses **n8n** for automation and **OpenRouter AI models** to generate content.

---

## 📌 Features

- 📄 User-friendly HTML Form
- 🔁 Automated data flow with n8n
- 🤖 AI-generated personalized timetables (Pomodoro-based)
- 💌 Sends beautifully formatted HTML emails
- 🔓 No OpenAI quota required — uses **free OpenRouter API**
- 💻 Fully customizable workflow (Add SMS, WhatsApp, etc.)

---

## 🚀 How It Works

1. **User fills the HTML form**
2. Data sent to n8n Webhook
3. AI Node (OpenRouter) generates a clean HTML timetable
4. Email Node sends it to the user via Gmail (or any SMTP)

---

## 🛠️ Tech Stack

- [n8n](https://n8n.io/) – Workflow Automation
- [OpenRouter](https://openrouter.ai) – AI Model Hub (Free GPT-4 Alternatives)
- HTML + CSS – Frontend Form
- Email Node – for sending beautiful mail
- Optional: Google Sheets / Airtable / Webhook DB for storing data

---



