# LEARNWISE_AI
# Adaptive AI Tutor

A simple AI-powered tutoring web app where users can:
- Create an account and log in
- Take quizzes and track their progress
- Chat with an AI tutor (powered by Groq API)
- Save all chat history, quiz results, and progress in a database

---

## How It Works
1. **User signs up or logs in** → credentials saved in the database.  
2. **Takes quizzes** → scores and progress saved automatically.  
3. **Chats with AI tutor** → messages and AI replies stored in chat history.  
4. **Progress and history** can be viewed anytime from the app.

---

## Requirements
- Python 3.9+
- [Groq API Key](https://groq.com/)
- Installed dependencies:
```bash
pip install fastapi uvicorn python-dotenv requests pydantic
