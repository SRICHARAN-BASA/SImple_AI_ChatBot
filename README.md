# AI Chatbot (Custom Assistant)

## Project Overview

This project is a conversational AI chatbot built using Python and Streamlit.  
It works similar to ChatGPT where users can interact with an AI assistant in real time.

The chatbot supports different assistant roles such as:

- Tutor
- Friend
- Coding Assistant

The application also maintains conversation history using Streamlit Session State to provide a smooth chat experience.

---

# Features

- Real-time AI conversation
- Multiple assistant modes
- Conversation history memory
- Simple and clean UI
- Reset chat functionality
- API-based AI response generation

---

# Problem Statement

Users often need quick assistance for:

- learning concepts
- coding doubts
- general queries
- customer support

Traditional support systems require human interaction and consume time.

This project solves the problem by providing an AI-powered assistant that can respond instantly and continuously.

---

# Use Cases

- AI Learning Assistant
- Coding Helper
- Customer Support Bot
- Personal AI Assistant
- Educational Chatbot

---

# Tech Stack

| Technology | Purpose |
|---|---|
| Python | Backend programming |
| Streamlit | Web application framework |
| Groq API / OpenAI API | AI model integration |
| dotenv | Secure API key management |
| Session State | Maintain chat history |

---

# Project Structure

ai_chatbot/
│
├── app.py
├── requirements.txt
├── .env
└── README.md

---
# Steps to Run the Project

```bash
1. Clone the repository
--> git clone <your_repo_link>
cd ai_chatbot

2. Create virtual environment
--> python -m venv venv

3. Activate virtual environment

4. Windows
--> venv\Scripts\activate

# Mac/Linux
source venv/bin/activate

5. Install required libraries
--> pip install -r requirements.txt

6. Create .env file and add API key
--> # GROQ_API_KEY=your_api_key

7. Run the application
--> streamlit run app.py



