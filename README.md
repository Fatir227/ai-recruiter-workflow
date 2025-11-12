# 🧠 AI Recruiter Workflow (n8n + OpenAI)

>  **Automated Resume Screening | Candidate Segregation | AI-Powered Decision Making**

---

## 🏆 Certificate  
This repository includes a verified **certificate of completion/achievement** for the AI Recruiter project, demonstrating applied skills in **workflow automation, AI reasoning, and low-code systems integration**.  
📄 File: ![certificate](https://github.com/user-attachments/assets/eeb48143-b814-4092-a54d-22d1a462d5f9)# 🧠 AI Recruiter Workflow (n8n + OpenAI)


---

## 🚀 Overview

The **AI Recruiter Workflow** is an intelligent automation pipeline built in **n8n** that can:

- Collect job descriptions (via email or webhook)  
- Parse attached resumes (PDF format)  
- Analyze skills, experience, and education  
- Calculate ATS & match scores  
- Shortlist and categorize candidates automatically  
- Deliver a summarized HR report or notification  

It replaces the **manual, repetitive HR screening process** with a reasoning-capable AI system that makes data-driven recruitment decisions in seconds.

---

## 🧩 Problem It Solves

| Traditional Recruitment | With AI Recruiter Workflow |
|--------------------------|----------------------------|
| Time-consuming resume scanning | Automated extraction and scoring |
| Manual skill matching | AI-based semantic analysis |
| Human bias | Objective scoring via rules + reasoning |
| Scattered communication | Centralized HR summary via n8n |
| Delays in shortlisting | Instant, data-driven shortlist |

> 💡 **In short**, this agent eliminates repetitive human work while improving consistency and efficiency in hiring decisions.

---

## ⚙️ Features

✅ Extracts job descriptions and resumes automatically  
✅ Reads PDF resumes and parses them to text  
✅ Computes ATS & match scores using AI logic  
✅ Groups candidates by inferred job roles (backend, frontend, ML/AI, etc.)  
✅ Provides a structured JSON report ready for HR review  
✅ Works entirely on free-tier APIs and open-source tools  
✅ Deployable on **n8n Cloud** or self-hosted instance  

---

## 🧠 Tech Stack

| Layer | Technology | Purpose |
|-------|-------------|---------|
| **Automation Engine** | [n8n](https://n8n.io/) | Workflow orchestration |
| **AI Model** | OpenAI GPT-4.1 mini / local LLM | Resume understanding & reasoning |
| **Language Integration** | LangChain (via `@n8n/n8n-nodes-langchain`) | Connects AI to workflow |
| **Data Handling** | JavaScript Code nodes | Scoring, filtering, segregation |
| **Trigger Sources** | Gmail API / Webhook | Input entry points |
| **Storage / Reporting** | Google Sheets / CSV / Email | Final HR reports |

---

## 🧰 Files Included

| File | Description |
|------|-------------|
| `ai_recruiter_workflow_full.json` | Complete n8n workflow with wired connections |
| `certificate.pdf` | Certificate of completion / validation |
| `/images/` | Screenshots and visual examples |
| `README.md` | Project documentation |

---

## 🪜 Steps to Follow

### 🖥️ 1. Clone the Repository
```bash
git clone https://github.com/<your-username>/ai-recruiter-workflow.git
cd ai-recruiter-workflow

