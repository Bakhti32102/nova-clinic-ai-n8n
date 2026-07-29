# 🏥 Nova Clinic AI - n8n Workflow

An AI-powered clinic customer support assistant built with **n8n**, **Google Gemini**, and **Google Sheets**.

Nova Clinic AI helps clinics automate patient support by handling appointment booking, doctor inquiries, appointment status, and other common patient requests.

---

## ✨ Features

- 📅 Book patient appointments
- 👨‍⚕️ Show available doctors and specializations
- 🔍 Check appointment status
- ❌ Cancel appointments
- 🔄 Reschedule appointments
- 📝 Register patient complaints
- 💬 AI-powered customer support
- 🧠 Conversation memory
- 📊 Google Sheets integration

---

## 🛠 Tech Stack

- n8n
- Google Gemini
- Google Sheets
- LangChain AI Agent

---

## 📥 Installation

1. Download `workflow.json`.
2. Open your n8n workspace.
3. Click **Import Workflow**.
4. Select `workflow.json`.
5. Configure your Google Sheets credentials.
6. Configure your Gemini API credentials.
7. Replace the Google Sheet IDs with your own.
8. Activate the workflow.

---

## 📂 Required Google Sheets

Create the following sheets:

### Doctors

| Doctor_ID | Name | Specialization | Available |
|-----------|------|----------------|-----------|

### Appointments

| Appointment_ID | Patient_Name | Phone | Doctor | Date | Time | Status |
|---------------|-------------|-------|---------|------|------|--------|

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

## ⚠️ Important

This repository does **not** include:

- API Keys
- Google Credentials
- Personal Data
- Secrets or Tokens

You must configure your own credentials before using the workflow.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Muhammad Habib**

AI Automation Developer | n8n | Google Gemini | Customer Support Automation

If you found this project helpful, please consider giving it a ⭐ on GitHub.
