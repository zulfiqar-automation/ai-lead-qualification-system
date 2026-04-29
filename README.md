# 🤖 AI Lead Qualification System

AI-powered lead capture and qualification pipeline built with n8n and GPT-4. Captures incoming leads, scores them automatically, and sends personalized responses in under 60 seconds. Zero manual work.

> **Captures incoming leads, scores their intent with GPT-4, and sends 
> personalized responses automatically — all in under 60 seconds. 
> Zero manual work. Runs 24/7.**

---

## 🎬 Live Demo

[![Watch Demo](https://img.shields.io/badge/▶%20Watch%20Live%20Demo-Loom-orange?style=for-the-badge&logo=loom)](https://www.loom.com/share/9e93feb4a26c4a0eae88c8f318b95edf)

> *2-minute walkthrough showing the system capturing a lead, scoring intent, 
> and triggering a personalized follow-up — completely automated.*

---

## 🎯 The Problem This Solves

Most businesses lose leads because:
- Follow-up is slow (average response time is 47 hours)
- Responses are generic, not personalized
- Sales teams waste time on unqualified leads

**This system fixes all three — instantly and automatically.**

## ⚙️ How It Works

---

## 📸 Screenshots

### Full Workflow Canvas
![Workflow Overview](screenshots/workflow-overview.png)

### Live Execution — All Nodes Passing ✅
![Execution Result](screenshots/execution-result.png)

### GPT-4 Intent Scoring Node
![GPT4 Node](screenshots/gpt4-node-config.png)

### Automated Response Output
![Agent Output](screenshots/agent-output.png)

### CRM Record Created Automatically
![CRM Sync](screenshots/crm-sync-result.png)

---

## 📊 Results

| Metric | Before | After |
|---|---|---|
| Response time | Hours / Days | Under 60 seconds |
| Manual triage work | 100% manual | Reduced by 90% |
| Lead coverage | Business hours only | 24/7 automated |
| CRM data entry | Manual | Fully automated |

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| **n8n** | Workflow automation engine |
| **OpenAI GPT-4** | Intent scoring & response generation |
| **Webhook** | Real-time lead capture trigger |
| **CRM API** | Automatic record creation & sync |
| **JSON Pipeline** | Structured data extraction |

---

## ⬇️ Import & Use This Workflow

You can import this entire system into your own n8n in 3 steps:

1. Download [`workflow.json`](workflow.json) from this repo
2. Open your n8n → click **Import** → upload the file
3. Add your OpenAI API key and CRM webhook URL in credentials

**The entire automation is ready to run immediately.**

---

## 🚀 Full Setup Guide

### Prerequisites
- n8n instance (self-hosted or n8n.cloud)
- OpenAI API key
- CRM with webhook support (HubSpot, Airtable, Notion, etc.)

### Step-by-Step
```bash
# Step 1: Import the workflow
# Go to n8n → Workflows → Import → upload workflow.json

# Step 2: Set your credentials
# n8n → Credentials → New → OpenAI API → paste your key

# Step 3: Configure your webhook
# Copy the webhook URL from n8n
# Paste it into your lead capture form

# Step 4: Activate
# Toggle the workflow ON — it runs automatically from here
```

### Environment Variables Needed

---

## 🧠 System Architecture

┌─────────────────┐     ┌──────────────┐     ┌─────────────────┐
│   Lead Source   │────▶│   n8n Core   │────▶│   GPT-4 Engine  │
│ (Form/Website)  │     │  (Webhook)   │     │ (Score + Reply) │
└─────────────────┘     └──────────────┘     └─────────────────┘
│                      │
▼                      ▼
┌──────────────┐     ┌─────────────────┐
│  CRM System  │     │ Follow-up Queue │
│ (Auto-sync)  │     │  (Sequences)    │
└──────────────┘     └─────────────────┘

---

## 💼 Built By

**Zulfiqar Basir** — AI Automation & Agent Developer

I build intelligent automation systems for businesses that want to 
eliminate manual work and scale without hiring more staff.

**Hire me for your project:**

[![Fiverr](https://img.shields.io/badge/Fiverr-1DBF73?style=for-the-badge&logo=fiverr&logoColor=white)](https://www.fiverr.com/zulfiqar_ai)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/zulfiqar-basir-b36166340)
[![Email](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:zulfiii7737@gmail.com)

---

## 📂 Other Projects

- 🔹 [AI Appointment Booking Agent](https://github.com/zulfiqar-automation/ai-appointment-booking-agent) — Fully automated booking via Voiceflow + Google Calendar
- 🔹 [CRM Workflow Automation](https://github.com/zulfiqar-automation/crm-workflow-automation) — End-to-end pipeline saving 10+ hours/week

---

*If this project helped you or gave you ideas, please ⭐ star the repo — it helps others find it.*
