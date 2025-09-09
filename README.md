# Iron Lady FAQ Chatbot (FastAPI + Gemini)

This is a simple **FAQ chatbot** for Iron Lady’s leadership programs.  
It works in two steps:
1. Tries to answer from a **local FAQ database** (`db.json`).
2. If no match is found, it falls back to **Google Gemini** for AI-powered responses.


---

## ⚙️ Setup Instructions

### 1. Clone project
```bash
git clone https://github.com/copycode69/iron-lady-task1.git
cd iron-lady-task1

uvicorn main:app --reload --port 8000
