# 🤖 LLM Chat App  
**AI-Powered Chat Application | Full-Stack Project**

An AI-powered chat application that enables real-time interaction with a Large Language Model (LLM). This project demonstrates end-to-end integration of LLM APIs into a modern web application, showcasing full-stack development skills, clean architecture, and practical AI usage.

---

## 🚀 Why This Project Matters

This project highlights:
- Practical **LLM API integration** in a real application
- Full-stack ownership (frontend + backend)
- Clean, readable, and extensible code
- Secure configuration using environment variables
- A strong foundation for production-grade AI apps

---

## ✨ Key Features

- 💬 **Real-Time AI Chat** – Users can send messages and receive LLM-generated responses instantly  
- 🧠 **LLM Integration** – Handles prompt processing and response rendering  
- ⚡ **High Performance** – Built using **Bun** for fast execution  
- 🔐 **Secure Configuration** – API keys managed via environment variables  
- 📱 **Responsive UI** – Simple and clean interface usable across devices  
- 🧩 **Extensible Design** – Easy to add streaming, auth, or persistence  

---

## 🛠️ Tech Stack

| Layer | Technology |
|-----|-----------|
| Language | TypeScript |
| Runtime | Bun |
| Backend | Bun HTTP Server |
| Frontend | HTML, CSS, JavaScript |
| AI | Large Language Model (LLM API) |
| Config | Environment Variables |

---

User
↓
Frontend (Chat UI)
↓
Backend (Bun Server)
↓
LLM API
↓
AI Response → Frontend


---

## 📂 Project Structure



llm-chat-app/
├── index.ts # Backend entry point and LLM logic
├── public/ # Frontend assets
├── .env.example # Environment variable template
├── bun.lockb # Dependency lock file
└── README.md # Project documentation


---

## ⚙️ Getting Started

### Prerequisites
- Bun installed → https://bun.sh
- An LLM API key (OpenAI or compatible provider)

---

### Installation

```bash
git clone https://github.com/sakshikbc/llm-chat-app.git
cd llm-chat-app
bun install


Create a .env file:

LLM_API_KEY=your_api_key_here

Run the Application
bun run index.ts
```

Open in browser:

http://localhost:3000

## 🧠 Engineering Concepts Demonstrated

Third-party API integration

Asynchronous request handling

Separation of frontend and backend concerns

Secure environment-based configuration

Scalable foundation for AI applications

## 🔮 Future Enhancements

Streaming AI responses

Chat history persistence (database)

User authentication

Multi-model support

Improved UI/UX

## 🎯 Ideal For

Recruiters evaluating AI + Full-Stack skills

Developers learning LLM integrations

Portfolio and resume projects

AI chatbot prototypes

## 👩‍💻 Author

Sakshi Khoobchandani
Software Engineer | AI & Web Development
GitHub: https://github.com/sakshikbc

## ⭐ Support

If you find this project useful:

⭐ Star the repository

🍴 Fork and build on top of it

🛠️ Open issues or pull requests



