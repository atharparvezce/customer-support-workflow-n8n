
# 📬 AI-Powered Email Automation Workflow (n8n + OpenAI + Pinecone)

This project is an **AI-enhanced email automation workflow** built with [n8n](https://n8n.io).
It listens for incoming emails via Gmail, classifies them, and—if it's a support query—responds
using an AI Agent powered by **OpenAI** and **Pinecone Vector Store**.

---

## ⚙️ Features

* ✅ Gmail Trigger for incoming messages
* 🏷️ Email classification (e.g., Customer Support or Others)
* 🤖 AI Agent to handle support queries
* 📚 Pinecone Vector Search for context-aware replies
* 💬 OpenAI Chat Model for intelligent responses
* 🏷️ Auto-labeling of emails
* 📤 Auto-reply for customer queries

---

## 📌 Tools & Integrations

* **n8n** (workflow automation)
* **Gmail** (trigger, label, and reply)
* **OpenAI** (text classification, chat, and embeddings)
* **Pinecone** (vector search)
* **AI Agent** (for contextual responses)

---

## 🧠 Workflow Logic

1. Trigger on new Gmail email.
2. Classify the email using OpenAI.
3. If it's a **support query**:

   * Search related documents via Pinecone.
   * Generate a response using OpenAI + vector context.
   * Label the email and send a reply.
4. If not a support query: Do nothing.

---

## 📦 Getting Started

1. Clone this repo or download the exported `.json` file.
2. Import the workflow into your n8n instance.
3. Set up credentials for:

   * Gmail
   * OpenAI
   * Pinecone
4. Test the workflow by sending a new email.

---

## 🏷️ Tags

`n8n` `OpenAI` `Gmail` `Automation` `AI Agent` `Pinecone` `Embeddings` `Customer Support`

---

## 🙌 Acknowledgements

* [n8n](https://n8n.io) for flexible workflow automation
* [OpenAI](https://openai.com) for LLM power
* [Pinecone](https://www.pinecone.io/) for vector search

---