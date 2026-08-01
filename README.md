# 🤖 AI Chatbot Memory Agent (n8n)

An AI chatbot built with n8n that supports:

- 🧠 Conversation Memory
- 🧮 Calculator Tool
- 🤖 OpenAI Chat Model
- 🌐 Webhook API
- 📬 Postman Testing

---

## 🚀 Features

- Remembers previous conversation using Session ID
- Uses OpenAI as the reasoning engine
- Calls Calculator Tool automatically for math problems
- Receives requests through Webhook
- Returns responses through Respond to Webhook

---

## 🛠 Tech Stack

- n8n
- OpenAI
- Simple Memory
- Calculator Tool
- Webhook
- Postman

---

## 📷 Workflow

(Add workflow screenshot here)

---

## 📦 How to use

1. Import the JSON workflow into n8n.
2. Configure your OpenAI credentials.
3. Execute the workflow.
4. Send POST requests to the Webhook endpoint.

Example:

```json
{
  "question": "What is 125 * 48?",
  "sessionId": "user-001"
}
```

---

## 📁 Project Files

- chat bot.json

---

Built by **Yassine El Hayani**
