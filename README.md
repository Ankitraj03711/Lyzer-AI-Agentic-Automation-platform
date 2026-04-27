# Lyzer AI – Agentic Automation Platform

Lyzer AI is a full-stack agentic automation platform that orchestrates multi-agent workflows across tools like GitHub, Slack, Gmail, and Google Drive. It enables AI agents to securely connect with external services using OAuth 2.0, maintain long-term memory using PostgreSQL + vector embeddings, and autonomously perform tasks such as research, analysis, communication, and workflow automation.

## 🚀 Features

- Multi-agent workflow orchestration
- Secure OAuth 2.0 integrations with GitHub, Slack, Gmail, and Google Drive
- Long-term conversational memory using PostgreSQL and vector embeddings
- Autonomous task execution across connected platforms
- Research and data analysis automation
- Chat-based interface for interacting with agents
- Persistent user sessions and tool connection management
- Modular backend with reusable tool integrations

## 🛠️ Tech Stack

### Frontend
- Next.js 14
- React.js
- TypeScript
- Tailwind CSS

### Backend
- FastAPI
- Python
- OpenAI API

### Database
- PostgreSQL (memory + sessions)
- MongoDB (user/tool connection data)

### Authentication & Integrations
- OAuth 2.0
- GitHub API
- Gmail API
- Google Drive API
- Slack API

## 📂 Project Structure

```bash
lyzer/
├── Lyzr_Agent/        # FastAPI backend, agents, memory, tools
└── lyzr_project/      # Next.js frontend and API routes
