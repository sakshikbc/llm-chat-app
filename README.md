🤖 LLM Chat App

AI-Powered Chat Application | Full-Stack Project

A production-ready LLM-powered chat application demonstrating end-to-end integration of Large Language Models into a modern web app. This project highlights backend API design, real-time AI interaction, clean architecture, and performance-oriented development using Bun and TypeScript.

🚀 Why This Project Matters (Recruiter View)

This project demonstrates:

Practical LLM API integration (not just theory)

Full-stack ownership (frontend + backend)

Clean, readable, and scalable code structure

Secure configuration using environment variables

Real-world AI use case implementation

✨ Key Highlights

💬 Real-Time AI Chat – User messages are processed and answered by an LLM in real time

🧠 LLM API Integration – Demonstrates prompt handling, response parsing, and error handling

⚡ High-Performance Runtime – Built with Bun, optimized for fast startup and execution

🔐 Secure Environment Management – API keys handled via .env configuration

📱 Responsive UI – Clean and usable interface across devices

🧩 Extensible Architecture – Easy to add features like streaming, auth, or persistence

🛠️ Technical Stack
Layer	Technology
Language	TypeScript
Runtime	Bun
Backend	Bun HTTP server
Frontend	HTML, CSS, JavaScript
AI	Large Language Model (LLM API)
Config	Environment Variables
📐 Architecture Overview
User UI
   ↓
Frontend (Chat Interface)
   ↓
Backend (Bun Server)
   ↓
LLM API
   ↓
AI Response → UI

📂 Project Structure
llm-chat-app/
├── index.ts          # Backend entry point (LLM integration logic)
├── public/           # Frontend UI assets
├── .env.example      # Environment configuration template
├── bun.lockb         # Dependency lock file
└── README.md         # Documentation

⚙️ Setup & Run (Quick Start)
Prerequisites

Bun installed

LLM API key (OpenAI or compatible provider)

Steps
git clone https://github.com/sakshikbc/llm-chat-app.git
cd llm-chat-app
bun install


Create .env:

LLM_API_KEY=your_api_key_here


Run the app:

bun run index.ts


Open:

http://localhost:3000

🧠 Key Engineering Concepts Demonstrated

API integration with third-party AI services

Asynchronous request handling

Separation of concerns (UI vs backend logic)

Secure configuration management

Scalable foundation for AI applications

🔮 Planned Improvements

Streaming AI responses (token-by-token)

Chat history persistence (DB integration)

User authentication & sessions

Multi-model support

UI/UX enhancements

🧑‍💻 Ideal For

Recruiters evaluating AI + Full-Stack skills

Developers learning LLM integrations

Teams building AI-driven chat systems

Resume and portfolio showcase projects

👩‍💻 Author

Sakshi Khoobchandani
Software Engineer | AI-Driven Web Applications
GitHub: https://github.com/sakshikbc

⭐ If This Project Helped You

Star ⭐ the repository

Fork 🍴 and extend it

Open issues or PRs

🔥 Recruiter Tip (For You)

When sharing this repo:

Mention “LLM API Integration + Bun + TypeScript”

Call it a “production-ready AI chat prototype”

Link it in your resume under Projects
