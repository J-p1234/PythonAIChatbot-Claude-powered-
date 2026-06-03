<img width="696" height="949" alt="Python AI Chatbot" src="https://github.com/user-attachments/assets/723fb3e7-20cd-4a79-91aa-48557f9864b2" />



🤖 Python AI Chatbot (Powered by Anthropic Claude)
A modern desktop chatbot built with Python, Tkinter, and the Anthropic Claude API. It provides a simple chat UI with real-time streaming responses from Claude.

---

## ✨ Features

- 💬 Chat with Claude AI (Sonnet model)
- ⚡ Streaming responses (real-time typing effect)
- 🧠 Conversation memory (context-aware replies)
- 🖥️ Clean Tkinter GUI
- ⌨️ Press Enter to send messages
- 🧹 Clear chat functionality
- 🔄 Multithreading (no UI freezing)

---

## 🏗️ Technologies Used

- Python
- Tkinter
- Anthropic API
- Threading

---

## 🚀 How It Works

1. User types a message in the GUI.
2. Message is added to conversation history.
3. A request is sent to Claude API.
4. Response is streamed in real time.
5. UI updates as text arrives.
6. Full response is saved for context.

---

## 📦 Installation

### Clone the repository
git clone https://github.com/yourusername/claude-chatbot.git  
cd claude-chatbot  

### Install dependencies
pip install anthropic  

---

## 🔑 API Key Setup

You need an Anthropic API key:

**Windows (PowerShell):**
setx ANTHROPIC_API_KEY "your_api_key_here"

**Mac/Linux:**
export ANTHROPIC_API_KEY="your_api_key_here"

---

## ▶️ Run the project

python chatbot.py  

---

## 🧠 Model Used

claude-sonnet-4-6

You can change it in code:
model="claude-sonnet-4-6"

---

## 📁 Project Structure

claude-chatbot/  
│  
├── chatbot.py  
├── README.md  
└── requirements.txt  

---

## 🚀 Future Improvements

- Voice input/output
- Markdown rendering
- Save chat history
- Theme toggle (dark/light)
- Export chat (PDF/JSON)
- Multiple AI models support

---

## 👨‍💻 Author

JP

Python & AI Developer focused on chatbot systems and NLP applications.

---

## ⭐ Support

If you like this project:
- Give it a ⭐ on GitHub
- Fork it
- Share it with others
