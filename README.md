<p align="center">
  <img src="Nova%20clinic%20chatbot%201.png" alt="Nova Clinic AI Banner" width="100%">
</p>

# 🏥 Nova Clinic AI - n8n Workflow

An AI-powered clinic customer support assistant built with **n8n**, **Google Gemini**, and **Google Sheets**.

Nova Clinic AI automates patient support by handling appointment booking, doctor inquiries, appointment status, cancellations, rescheduling, and complaint registration through an intelligent AI Agent.

---

## ✨ Features

- 📅 Book patient appointments
- 👨‍⚕️ View available doctors and specializations
- 🔍 Check appointment status
- ❌ Cancel appointments
- 🔄 Reschedule appointments
- 📝 Register patient complaints
- 🤖 AI-powered customer support
- 🧠 Conversation memory
- 📊 Google Sheets integration
- ⚡ Easy to import into n8n

---

## 🛠 Built With

- n8n
- Google Gemini
- Google Sheets
- LangChain AI Agent
- Buffer Memory

---

## 📥 Installation

1. Download the `Clinic Chatbot.json` workflow file.
2. Open your n8n workspace.
3. Click **Import from File**.
4. Select the downloaded workflow.
5. Configure your Google Sheets credentials.
6. Configure your Google Gemini credentials.
7. Replace the Google Sheet IDs with your own.
8. Activate the workflow.

---

## 📂 Required Google Sheets

### Doctors Sheet

| Doctor_ID | Name | Specialization | Available |
|-----------|------|----------------|-----------|

### Appointments Sheet

| Appointment_ID | Patient_Name | Phone | Doctor | Date | Time | Status |
|---------------|--------------|-------|--------|------|------|--------|

---

## 💬 Example Questions

- Book an appointment.
- Show available doctors.
- I need a dermatologist.
- Check my appointment status.
- Cancel my appointment.
- Reschedule my appointment.
- Submit a complaint.

---

## 🔧 Configuration

Before using this workflow, configure:

- Google Gemini API credentials
- Google Sheets OAuth credentials
- Google Sheet IDs
- Sheet Names

---

## 🔒 Security

This repository does **NOT** include:

- API Keys
- Google Credentials
- OAuth Tokens
- Personal Data
- Private Information

Use your own credentials before running the workflow.

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 👨‍💻 Author

**Muhammad Habib**

AI Automation Developer | n8n | Google Gemini | AI Customer Support Automation

⭐ If you found this workflow helpful, please consider starring this repository.
