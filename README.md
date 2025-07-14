# 📧 AI Email Sender with n8n + Google Sheets

This project is an n8n automation that reads rows from Google Sheets and sends **AI-generated emails** to clients. If the `Status` column is not marked as "Sent", it uses an AI service (like OpenAI) to generate custom emails, sends them via Gmail, and updates the sheet.

---

## 🔧 Features
- ✅ Google Sheets integration (read/write)
- ✅ Gmail integration for email sending
- ✅ AI-powered email generation
- ✅ Row-wise condition check (status != "Sent")
- ✅ Auto-updates the status after sending

---

## 🧠 Tech Used
- n8n
- Google Sheets
- Gmail API
- OpenAI (for smart email content)
- JavaScript functions in n8n

---

## 🗂 Files
- `ai-email-sender.json` – The exported workflow from n8n

---

## 🚀 How to Use
1. Import the `.json` into your n8n instance
2. Connect Google Sheets & Gmail credentials
3. Add your sheet ID and AI prompt
4. Run manually or on schedule

---

## 📍 Notes
- Sheet must have columns: Name, Email, Status
- Make sure credentials are correctly connected
