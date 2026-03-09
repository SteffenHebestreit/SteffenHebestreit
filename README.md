# Hi, I'm Steffen 👋

**Passionate software engineer** specializing in microservice architectures, full-stack web development, and AI-integrated applications.

📍 Germany &nbsp;|&nbsp; 📧 info@steffen-hebestreit.com &nbsp;|&nbsp; 🌐 [steffen-hebestreit.com](https://steffen-hebestreit.com) &nbsp;|&nbsp; 💼 [LinkedIn](https://www.linkedin.com/in/steffen-hebestreit/)

---

## 🚀 Featured Project — OpenTYME

> **A full-stack business management platform for freelance professionals** — time tracking, invoicing, expense management, and reporting in one self-hosted application.

[![OpenTYME](https://img.shields.io/badge/OpenTYME-View%20Repository-blue?style=for-the-badge&logo=github)](https://github.com/SteffenHebestreit/opentyme)
[![Addon Boilerplate](https://img.shields.io/badge/Addon%20Boilerplate-Start%20Building-green?style=for-the-badge&logo=github)](https://github.com/SteffenHebestreit/opentyme-addon-boilerplate)

### What OpenTYME does

| Feature | Details |
|---|---|
| ⏱ **Time Tracking** | Timer & manual entry, billable/non-billable classification |
| 🧾 **Invoicing** | PDF export, ZUGFeRD/Factur-X compliance, payment monitoring |
| 💸 **Expenses** | Receipt uploads (S3), tax categorization, depreciation schedules |
| 📊 **Reporting** | VAT declarations, EÜR reports, PDF/CSV/XLSX export |
| 📧 **Email** | Per-user SMTP config with MJML template editor & live preview |
| 🤖 **AI Assistant** | Conversational data access via configurable LLM providers |
| 🔌 **Plugins** | Manifest-driven addon architecture with slot-based frontend injection |

**Stack:** React 18 · TypeScript · Node.js · Express · PostgreSQL · Keycloak (SSO) · Docker Compose · SeaweedFS · Redis

**License:** CC BY-NC 4.0 — free for personal and non-commercial use.

---

### 🔌 Build Your Own Addon

OpenTYME ships with a plugin architecture that lets you extend the platform with custom backend routes, frontend UI slots, and AI tools.

**[opentyme-addon-boilerplate](https://github.com/SteffenHebestreit/opentyme-addon-boilerplate)** is the official starter template:

- Dual architecture (TypeScript/Express backend + React/TypeScript frontend)
- Manifest-driven configuration via `addon-manifest.json`
- UI extension slots: expense forms, dashboards, settings panels
- Three AI tool integration patterns (Swagger-auto, custom in-process, system prompt)
- Built-in user authentication context on all addon routes

---

## 🗂 Other Projects

| Repository | Description | Stack |
|---|---|---|
| [spring-boot-ai-chat-dockerized](https://github.com/SteffenHebestreit/spring-boot-ai-chat-dockerized) | Dockerized Spring Boot AI chat with frontend & backend services | Java · Spring Boot |
| [fastapi_mcp_template](https://github.com/SteffenHebestreit/fastapi_mcp_template) | Template for custom MCP servers with dynamic tool mounting | Python · FastAPI |
| [ai-chat-frontend](https://github.com/SteffenHebestreit/ai-chat-frontend) | React frontend with 3D orb visualization, chat history & multimodal content | React · JS |
| [local_voice_assistant](https://github.com/SteffenHebestreit/local_voice_assistant) | Fully local, privacy-focused voice assistant — all processing on your own network | Python |
| [spring_boot_ai_agent](https://github.com/SteffenHebestreit/spring_boot_ai_agent) | AI agent research project with Spring Boot | Java · Spring AI |

---

## 🛠 Tech Stack

**Languages:** TypeScript · JavaScript · Python · Java · SQL
**Frontend:** React · Vite · TailwindCSS · React Query
**Backend:** Node.js · Express · Spring Boot · FastAPI
**Databases:** PostgreSQL · Redis
**Auth & Infra:** Keycloak · Docker · Traefik · S3-compatible storage
**AI/ML:** LLM integration · MCP servers · RAG pipelines · Voice pipelines
