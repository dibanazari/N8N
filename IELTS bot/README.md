# 🎯 IELTS Daily Practice Bot

An AI-powered IELTS preparation bot built with **n8n**, **OpenRouter**, and **Telegram** that automatically generates high-quality IELTS practice materials and sends them directly to a Telegram channel every two days.

---

## 🚀 Overview

Preparing for the IELTS exam requires consistent practice with diverse topics.

This project automates that process using a Large Language Model (LLM). Every two days, the workflow generates:

- ✍️ IELTS Writing Task 2 questions
- 🎤 Complete IELTS Speaking Tests
- 💡 Useful IELTS tips and strategies

The generated content is automatically delivered to a Telegram channel, providing a hands-free daily study experience.

---

## ✨ Features

- 🤖 AI-generated IELTS practice
- ✍️ Writing Task 2 prompts
- 🎤 Full Speaking Test (Part 1, 2 & 3)
- 🧠 Conversation memory to prevent repeated topics
- 📅 Automated scheduling
- 📲 Telegram integration
- ⚡ Powered by GPT-4o-mini via OpenRouter

---

## 🏗 Workflow Architecture

```
                Schedule Trigger
                        │
                        ▼
                AI Agent (LLM)
                  /          \
                 /            \
        Memory Buffer      GPT-4o-mini
                 \            /
                  \          /
                   ▼
          Telegram Channel
```

---

## 🛠 Tech Stack

- n8n
- OpenRouter API
- GPT-4o-mini
- Telegram Bot API
- AI Agent
- Memory Buffer
- Prompt Engineering

---

## 🧠 Prompt Engineering

The AI agent is instructed to:

- Generate different IELTS Writing Task 2 question types
- Produce a complete IELTS Speaking test
- Include useful IELTS tips
- Keep responses concise
- Avoid repeating previously generated topics
- Maintain natural exam-level difficulty

---

## 📂 Workflow

1. Schedule Trigger runs every 2 days.
2. AI Agent sends a carefully designed prompt.
3. GPT-4o-mini generates new IELTS content.
4. Memory stores previous topics.
5. Final response is sent automatically to Telegram.

---

## 📸 Screenshots

### n8n Workflow

> *(Add your workflow screenshot here)*

```
images/workflow.png
```

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/ielts-daily-bot.git
```

Import the workflow into n8n.

Configure the following credentials:

- OpenRouter API
- Telegram Bot

Run the workflow manually or activate the scheduler.

---

## 🔑 Environment Variables

Create an `.env` file:

```env
OPENROUTER_API_KEY=

TELEGRAM_BOT_TOKEN=

TELEGRAM_CHAT_ID=<img width="1536" height="1024" alt="ChatGPT Image Jul 12, 2026, 11_54_28 AM" src="https://github.com/user-attachments/assets/9322af4e-92f7-4cb6-9243-c7110ab62867" />

```

---

## 📈 Future Improvements

- Listening practice generation
- Reading passages
- Vocabulary quizzes
- Grammar correction
- Band score estimation
- User-specific personalization
- Multi-language support

---

## 📜 License

MIT License

---

## 👤 Author

**Diba Nazari**

Computer Engineering Graduate

Interested in:

- Artificial Intelligence
- Machine Learning
- LLM Applications
- Workflow Automation
- Prompt Engineering
