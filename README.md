# CodeSphere AI: An AI-Augmented Software Engineering Collaboration Platform

> **UCS503P - Software Engineering Project**  
> **Final Lab Evaluation (November 2026)**  
> **Computer Science and Engineering Department**  
> **Thapar Institute of Engineering and Technology, Patiala**

---

## 👥 Team & Submission Information

| Detail | Information |
| :--- | :--- |
| **Course Code** | **UCS503P** (Software Engineering Project) |
| **Team Members** | **Sarthak Soni** (Roll No: `1024030061`)<br>**Ayush Bansal** (Roll No: `1024030059`) |
| **Group / Class** | **Group 3C11**, BE Third Year, Computer Science and Engineering |
| **Faculty Guide** | **Ms. Paramveer Sidhu** |
| **Evaluation Date** | 28th / 30th November 2026 |
| **Live Repository** | [https://github.com/SarthakSoni31/ucs503p-proposal](https://github.com/SarthakSoni31/ucs503p-proposal) |

---

## 📂 Repository Directory Structure

This repository is structured into organized folders for academic evaluation and complete software project inspection:

```
ucs503p-proposal/
├── Final Report.pdf          <-- Root 1-click access to Final Evaluation Report (20 pages)
├── Final Report.tex          <-- Root Final Report LaTeX source
├── README.md                 <-- Master project documentation and navigation hub
│
├── final/                    <-- Final Lab Evaluation Deliverables (EST)
│   ├── Final Report.pdf      <-- Compiled 20-page Final Project Report
│   ├── Final Report.tex      <-- TIET-compliant LaTeX Source Class
│   ├── references.bib        <-- BibLaTeX bibliography entries
│   └── figures/              <-- All 10 high-resolution application screenshots
│       ├── fig_landing_hero.png
│       ├── fig_architecture.png
│       ├── fig_repo_hub.png
│       ├── fig_copilot_chat.png
│       ├── fig_defect_scanner.png
│       ├── fig_team_dashboard.png
│       ├── fig_task_delegation.png
│       ├── fig_grounding_probe.png
│       ├── fig_webhook_triage.png
│       └── fig_pr_engine.png
│
├── mst/                      <-- Mid-Semester Evaluation Deliverables (MST)
│   ├── MST Report.pdf        <-- Mid-Semester Project Report
│   └── MST Report.tex        <-- Mid-Semester Report LaTeX Source
│
├── proposal/                 <-- Project Proposal Deliverables
│   ├── Proposal.pdf          <-- Course Project Proposal
│   └── Proposal.tex          <-- Project Proposal LaTeX Source
│
└── project/                  <-- Full Next.js Application Source Code
    ├── app/                  <-- Next.js 14 App Router (Pages, UI Components, API Routes)
    │   ├── api/              <-- Serverless API endpoints (Scan, Copilot, Webhooks, GitHub Auth)
    │   ├── dashboard/        <-- Real-time Team Velocity and Backlog Dashboard
    │   ├── workspace/        <-- Multi-repository intelligence workspace
    │   └── page.js           <-- Landing page and live verification terminal
    ├── db/                   <-- Relational PostgreSQL schema (8 tables) and pgvector migrations
    │   └── schema.sql
    ├── lib/                  <-- Core Intelligence Engines (Local ONNX, AST Chunking, Retrieval, LLM)
    ├── scripts/              <-- Grounding verification probes and evaluation suites
    ├── package.json          <-- Project dependencies and execution scripts
    ├── next.config.js        <-- Next.js configuration and serverless optimization
    └── .env.example          <-- Environment variables template
```

---

## 📑 Quick Document Links

| Deliverable | PDF Document | LaTeX Source | Key Contents |
| :--- | :--- | :--- | :--- |
| **Final Report (EST)** | [📄 **`final/Final Report.pdf`**](final/Final%20Report.pdf) | [📝 **`final/Final Report.tex`**](final/Final%20Report.tex) | 20 pages, 4 chapters, 8 real application figures, database schema, quantitative performance metrics. |
| **Root Copy (EST)** | [📄 **`Final Report.pdf`**](Final%20Report.pdf) | [📝 **`Final Report.tex`**](Final%20Report.tex) | 1-click access at root for evaluation grading. |
| **Mid-Sem Report (MST)** | [📄 **`mst/MST Report.pdf`**](mst/MST%20Report.pdf) | [📝 **`mst/MST Report.tex`**](mst/MST%20Report.tex) | Mid-semester evaluation milestone report. |
| **Initial Proposal** | [📄 **`proposal/Proposal.pdf`**](proposal/Proposal.pdf) | [📝 **`proposal/Proposal.tex`**](proposal/Proposal.tex) | Original course project proposal. |

---

## 🚀 Key Achievements & Results Summary

| Performance Metric | Proposal Target | Mid-Sem Milestone | Final Achieved Outcome |
| :--- | :---: | :---: | :---: |
| **Answer Grounding Rate (Probe)** | $\ge 85.0\%$ | $95.0\%$ | **95.0% – 100.0%** (20/20 AST probes passed) |
| **Negative Query False Citations** | $0.0\%$ | $0.0\%$ | **0.0% (Strict suppression defense)** |
| **Webhook Auto-Triage Latency** | $< 30.0$ s | $2.8$ s | **2.6 s** (HMAC SHA-256 authenticated) |
| **Deep Indexing Capacity** | Baseline | 80 files | **150+ files (708+ chunks indexed)** |
| **Autonomous PR Generation Latency** | N/A | Manual | **4.2 s** (Fork-aware GitHub Contents API) |
| **External Vector Embedding Cost** | Low / Quota | $0.00 | **$0.00** (Local ONNX `all-MiniLM-L6-v2`) |
| **Static Defect Detection Rate** | N/A | N/A | **100% on AST test benchmarks** |
| **Production CI/CD Build Health** | Passing | Passing | **100% Passing (21 serverless routes)** |

---

## 💻 How to Run the Application Locally

```bash
# 1. Navigate to the project directory
cd project

# 2. Install dependencies
npm install

# 3. Configure environment variables
cp .env.example .env.local
# Edit .env.local with your GitHub OAuth and database credentials

# 4. Start the development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

---

*Submitted for UCS503P Software Engineering Project Final Lab Evaluation, Thapar Institute of Engineering and Technology, Patiala.*
