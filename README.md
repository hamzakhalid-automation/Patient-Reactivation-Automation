# 🏥 Patient Reactivation & Rebooking Automation

An AI-powered automation system built with **n8n** that helps physio therapy and med spa clinics reconnect with inactive patients and get them rebooked, without any manual staff effort.

This project identifies patients who haven't booked a follow-up, sends personalized reminder messages, and automatically books responders into the clinic's calendar.

---

## 🔥 Features

- Automated detection of inactive patients from clinic records
- Personalized reminder messages (WhatsApp / SMS / Email)
- Automatic rebooking into the calendar upon patient response
- Non-responders flagged for manual staff follow-up
- Custom dashboard to track conversations, patient status, and AI vs. human handoffs in real time

---

## 💼 Tech Stack

- n8n (workflow automation)
- OpenAI API (AI-powered conversation handling)
- JavaScript (custom code nodes for data processing)
- Webhook & REST API integrations
- CRM / Calendar integration (GoHighLevel / Cliniko)

---

## 🚀 Screenshots

**n8n Workflow:**
![Workflow](images/Workflow-Image.png)

**Patient Dashboard:**
![Dashboard Home](images/Dashboard-Home.png)
![Dashboard CRM](images/Dashboard-CRM.png)
![Dashboard Login](images/Dashboard-Login.png)
---

## ⚙️ How It Works

1. The workflow triggers on a schedule, checking the clinic's patient records for inactivity.
2. Inactive patients receive an automated, personalized message asking if they'd like to rebook.
3. If the patient responds, the system checks calendar availability and books the appointment automatically.
4. If there's no response, the patient is flagged in the dashboard for manual staff follow-up.
