


# 🚀 AI-Driven AS/400 & COBOL Modernization Platform  
### 🏆 MumbaiHacks 2025 — Team **404 Killers**

This project modernizes **legacy COBOL / AS-400 (IBM i)** applications using an **Agentic AI architecture**.  
It transforms old monolithic codebases into **modern languages, APIs, and documentation** — automatically.

---

## 🔥 What the Platform Does
| Step | Module | Output |
|------|--------|--------|
| 1 | 🧩 Parser Agent | Converts COBOL into structured AST |
| 2 | 🔧 Modernizer Agent | Generates modern Python code |
| 3 | 🔍 Validator Agent | Validates correctness & creates pass/fail report |
| 4 | 📖 Explainer Agent | Generates documentation describing business logic |

This solves a massive real-world problem: decades-old COBOL code powering enterprises is hard to understand and modernize.  
Our platform uses **Agentic AI** to automate modernization safely and explainably.

---

## 🧠 Agentic AI Pipeline (Architecture)

![Agent Architecture Flow](assets/agentic_flow.png)

> Upload COBOL source → AI parses → Modernizes → Validates → Generates Docs  
> All execution logs appear live in the backend terminal.

---

## 🌟 Key Features
✔ Upload COBOL source (.cbl)  
✔ Multi-agent modernization pipeline  
✔ Real-time backend execution logs  
✔ Modern code export (Python, extensible to Node/Java)  
✔ Documentation auto-generated (Markdown)  
✔ Modular & scalable microservice architecture  

---

## 📦 Project Folder Structure


/
│ backend/ → Main API + Agent Orchestrator
│ engine/ → AI Agents (Parser / Modernizer / Validator / Explainer)
│ frontend/ → React Web Interface
│ assets/ → Screenshots & documentation images


---

## 🛠️ Tech Stack
| Layer | Technology |
|-------|------------|
| Backend | Node.js • Express • TypeScript |
| Engine (AI) | LangChain • LLM API • Custom Agent Framework |
| Frontend | React • Vite • TailwindCSS |
| Communication | REST • WebSockets |
| Deployment | Docker-ready |

---

## 🧑‍💻 Run Project Locally

### 1️⃣ Clone the Repository
```bash
git clone <repo-url>
cd <project-folder>

2️⃣ Start Backend
cd backend
npm install


Create .env in /backend root and copy-paste the .env file shared in WhatsApp group
Then run:

npm start

3️⃣ Start AI Engine (Agents)
cd ../engine
npm install


Create .env in /engine root and paste the engine .env from WhatsApp group
Start engine:

npm start

4️⃣ Start Frontend
cd ../frontend
npm install
npm run dev


Frontend starts at:

http://localhost:5173

🧪 Demo Workflow

1️⃣ Upload COBOL file in the UI
2️⃣ Agents execute sequentially
3️⃣ Download results:

Modernized Python Code

Validation Report

Business Logic Documentation Markdown

🚧 Future Roadmap

🔹 Auto-generation of REST APIs (OpenAPI + Express/FastAPI)
🔹 DDS → JSON → SQL schema conversion for AS/400 database migration
🔹 Docker microservice export for each module
🔹 Role-based access & audit logging (enterprise compliance)

👥 Team — 404 Killers
Member	Role

Member 1	Frontend
Member 2	DevOps
Member 3	Architecture
Member 4	Research & Optimization

We are passionate about solving real enterprise modernization problems using AI 💙
