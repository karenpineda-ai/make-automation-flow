# Make Automation Flows 🤖

Real automation workflows built with Make, Claude AI, WhatsApp Business API, 
and Google Sheets. Used in production with real clients.

Built by [Karen Pineda](https://linkedin.com/in/karenpineda-businessanalyst) — AI Automation Specialist

---

## Flows included

### 1. Post-Sale WhatsApp Tracking
Automatically sends WhatsApp messages at each order stage.

**Triggers:** New row in Google Sheets  
**Tools:** Make · WhatsApp Business API · Google Sheets  
**Results:** 15 hours/week recovered · 0 repetitive customer queries  
**Cost:** $0 (free plan) · **Build time:** 2 hours

---

### 2. AI Lead Qualification + CRM Routing
Scores leads automatically with Claude AI and routes them by tier.

**Triggers:** New Typeform response  
**Tools:** Make · Claude API · HubSpot · Slack · Gmail  
**Results:** Replaces 2-3 hours of manual lead review per week  
**Tiers:** Hot → Slack alert · Warm → personalized email · Cold → CRM only

---

### 3. AI Content Generation for Agencies
Generates 5 copy variants per brief using Claude AI.

**Triggers:** New row in Google Sheets (brief submitted)  
**Tools:** Make · Claude API · Google Sheets · Slack  
**Results:** Content creation from 3 hours → under 20 minutes per client  
**Output:** 5 variants with hook, copy and CTA per brief

---

### 4. Automated Client Onboarding
Fully automates the new client welcome process end-to-end.

**Triggers:** New Typeform response  
**Tools:** Make · Gmail · Slack · Google Sheets  
**Results:** Eliminates 1-2 hours of manual coordination per new client  
**Includes:** Welcome email · CRM registration · team alert · day-3 check-in

---

### 5. Automated Weekly KPI Report
Generates and sends executive reports every Monday at 8am.

**Triggers:** Scheduled — every Monday 8:00am  
**Tools:** Make · Claude API · Google Sheets · Gmail  
**Results:** Saves 2-3 hours of manual reporting per client per week  
**Output:** AI-generated executive summary delivered to client inbox

---

### 6. AI Customer Support Triage
Classifies, responds, and escalates support emails automatically.

**Triggers:** Incoming email with label "soporte"  
**Tools:** Make · Claude API · Gmail · Slack · Google Sheets  
**Results:** First response time from hours → seconds  
**Logic:** FAQs auto-responded · Urgent → Slack · Complex → human queue

---

## Stack

![Make](https://img.shields.io/badge/Make-6D00CC?style=flat&logo=make&logoColor=white)
![Claude](https://img.shields.io/badge/Claude_API-D97706?style=flat)
![Google Sheets](https://img.shields.io/badge/Google_Sheets-34A853?style=flat&logo=googlesheets&logoColor=white)
![WhatsApp](https://img.shields.io/badge/WhatsApp_API-25D366?style=flat&logo=whatsapp&logoColor=white)
![HubSpot](https://img.shields.io/badge/HubSpot-FF7A59?style=flat&logo=hubspot&logoColor=white)
![Slack](https://img.shields.io/badge/Slack-4A154B?style=flat&logo=slack&logoColor=white)

---

## How to use

1. Download the JSON file for the flow you need
2. In Make: **Create new scenario → Import Blueprint**
3. Upload the JSON file
4. Connect your credentials
5. Update the variable placeholders (`TU_SPREADSHEET_ID`, `TU_PHONE_NUMBER_ID`, etc.)
6. Activate the scenario

---

## About

**Karen Pineda** — AI Automation Specialist & Business Analyst  
8+ years transforming business processes with data and automation.

- 🔗 [LinkedIn](https://linkedin.com/in/karenpineda-businessanalyst)
- 📧 Open to remote opportunities in AI Strategy & Automation Consulting
