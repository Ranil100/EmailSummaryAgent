# 📬 Email Summary Agent

The **Email Summary Agent** is a no-code/low-code automation built using [n8n](https://n8n.io/) that connects to your email inbox, extracts recent emails, and provides concise summaries using AI. This is ideal for users who want to save time and quickly understand the content of their emails.

## 🚀 Features

- ✅ Automatically fetches emails from your inbox (IMAP/SMTP or Gmail)
- ✉️ Extracts subject, sender, and body content
- 🧠 Uses AI (e.g., OpenAI GPT) to summarize long email bodies
- 🗓️ Can run on schedule (e.g., every 2 hours or daily)
- 📁 Output can be stored, emailed, or displayed in a dashboard

## 📌 Use Case

This agent is useful for:

- Professionals with high email volume
- Students summarizing academic mail
- Team managers getting daily updates
- Anyone who wants to read less, know more

## 🛠️ Tech Stack

- **n8n**: Workflow automation platform
- **IMAP/Gmail Node**: To fetch emails
- **OpenAI Node / HTTP Request**: To summarize emails
- **Set, Merge, and IF Nodes**: To process and filter data
