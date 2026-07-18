# AI Job Monitoring

An AI-powered n8n workflow that monitors Gmail for job-related emails, analyzes them with OpenAI, and sends instant Telegram notifications.

---

## Features

- Gmail monitoring
- AI email analysis
- Extract company name
- Extract job title
- Arabic summary
- Telegram notifications

---

## Workflow

```
Gmail
   ↓
OpenAI
   ↓
Filter
   ↓
Telegram
```

---

## Technologies

- n8n
- Gmail API
- OpenAI
- Telegram Bot

---

## Setup

1. Import the workflow into n8n.
2. Connect Gmail.
3. Add your OpenAI API key.
4. Connect Telegram.
5. Replace YOUR_CHAT_ID.
