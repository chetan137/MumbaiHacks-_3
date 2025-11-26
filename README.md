🚀 AS/400 / COBOL Modernization – Agentic AI Platform
🏆 MumbaiHacks 2025 — Team Project

This project modernizes legacy COBOL / AS-400 systems using an Agentic AI Architecture.
Developers can upload legacy code, and the system automatically:

Stage	What happens
🧩 Parser Agent	Understands COBOL & converts it into structured AST
🔧 Modernizer Agent	Converts logic into modern language (Python/Node)
🔍 Validator Agent	Validates correctness & generates a pass/fail report
📖 Explainer Agent	Creates human-readable documentation of business logic

💡 The system helps enterprises migrate old monolithic mainframe workloads into modern microservices + APIs, lowering modernization risk and increasing developer understanding.

🧠 Agentic AI Workflow Diagram

(Replace the path below with the uploaded image in your repo once you push it)

/assets/agentic_flow.png


🔥 Key Features

✔ Upload COBOL source code
✔ Automatic parsing → AST generation
✔ Modern code generation (Python)
✔ Validation + report (pass/fail)
✔ Auto-generated documentation (Markdown)
✔ Real-time backend logging
✔ Modular microservices architecture
✔ Hackathon-friendly & enterprise-scalable

📦 Project Structure
/
│ backend/     → API & orchestrator
│ engine/      → AI agent workers (Parser, Modernizer, Validator, Explainer)
│ frontend/    → Web interface (React)
│ assets/      → Documentation images & screenshots

🛠️ Tech Stack
Layer	Technology
Backend	Node.js • Express • TypeScript
AI Engine	LangChain • LLM API • Custom Agent Framework
Frontend	React • Vite • Tailwind
Communication	REST / WebSockets
Deployment	Docker-ready




🧑‍💻 Local Setup (Step-by-Step)
🔽 Step 1 — Clone the project
git clone <repo-url>
cd <project-folder>

🟦 Step 2 — Start Backend
cd backend
npm install


Create a .env file in /backend root folder
📌 Copy-paste .env content shared in the WhatsApp group into this file.

Then start backend:

npm start

🟩 Step 3 — Start AI Engine (Agent Runner)
cd ../engine
npm install


Create .env in /engine root folder
📌 Copy-paste .env content from WhatsApp group.

Start engine:

npm start

🟨 Step 4 — Start Frontend
cd ../frontend
npm install
npm run dev


Frontend will start at:

http://localhost:5173

🧪 Demo Flow

1️⃣ Upload COBOL source
2️⃣ Watch real-time logs from all agents
3️⃣ Download:

Modernized code

Validation report

Documentation (Markdown)

🧱 Future Enhancements

🔹 Export REST API + OpenAPI spec
🔹 Microservice deployment as Docker image
🔹 Incremental modernization blueprint
🔹 Database schema inference (DDS → JSON → SQL)

⭐ Team Notes

📌 This project was built for MumbaiHacks 2025 to solve real enterprise modernization problems using AI.

If you like this repo, please ⭐ star the project — your support motivates us!

💬 Want to contribute?

Open a PR or reach out on Discord / WhatsApp group — contributions are welcome.

If you want, I can also generate:
✔ LICENSE
✔ CONTRIBUTING.md
✔ Architecture.pdf (for hackathon judges)
✔ Demo script slide template




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
