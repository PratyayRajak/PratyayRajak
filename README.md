# ⚡ Pratyay Rajak
### **GenAI Engineer** | Specializing in Agentic Workflows, Production RAG & LLMOps
[![Portfolio](https://img.shields.io/badge/Portfolio-1D9E75?style=for-the-badge&logo=google-chrome&logoColor=white)](https://pratyayrajak.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/pratyay-rajak)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-FFD21E?style=for-the-badge&logoColor=black)](https://huggingface.co/pratyayrajak)

> *"Models are cheap. Engineering is rare."*

I build AI systems that survive the transition from a notebook to production. My focus is on **multi-agent orchestration (LangGraph)**, **automated evaluation (Ragas)**, and **secure, cost-effective deployment**.

---

## 📌 The Numbers That Matter
* **0.72 → 0.87**: Faithfulness lift on Legal RAG through hybrid retrieval and reranking.
* **0.09%**: Parameters trained to achieve domain-specific fine-tuning via **QLoRA**.
* **28%**: Precision improvement in context retrieval using **RRF (Reciprocal Rank Fusion)**.
* **Zero GPU**: Production deployment of a multi-stage legal agent on CPU-only infrastructure.

---

## 🚀 Featured Production Work

### ⚖️ Government Judicial RAG System
*Commissioned for Indian District Courts*
* **The Challenge:** Processing massive volumes of bilingual (Hindi/English) legal filings with strict PII compliance.
* **The Solution:** A 7-node **LangGraph** workflow featuring **IndicTrans2** for translation and **RAPTOR** for hierarchical recursive chunking.
* **Compliance:** Integrated **Microsoft Presidio** to mask sensitive identifiers (Names, Aadhaar, Litigant details) before model ingestion to meet legal requirements.
* **Tech:** `LangGraph`, `Neo4j`, `ChromaDB`, `Redis`, `FastAPI`, `Gradio`.

### 🤖 Autonomous SWE-Agent (GitHub Issue Resolver)
* **The Challenge:** Automating the end-to-end resolution of GitHub issues while ensuring code safety.
* **The Solution:** A multi-agent system (Research → Coder → Tester → PR Writer) that resolves issues in a **Docker-sandboxed** environment.
* **Safety:** Zero-network sandbox with resource caps ensures no unsafe code execution on host systems.
* **Tech:** `Gemini 2.0`, `LangGraph`, `Docker`, `LangSmith`.

### 📊 LLM Eval & Drift Monitoring Pipeline
* **The Challenge:** Catching quality degradation in production before users do.
* **The Solution:** A production-ready monitoring system using **Medallion Architecture** on Delta Lake to ingest completions in real-time.
* **Key Feature:** Automated **MLflow** alerts that trigger when faithfulness or context recall drifts >0.05 from the rolling baseline.
* **Tech:** `PySpark`, `Delta Lake`, `Ragas`, `MLflow`, `Groq`.

---

## 🧰 Tech Stack

| Category | Tools & Frameworks |
| :--- | :--- |
| **GenAI & Orchestration** | **LangChain**, **LangGraph**, Multi-Agent Systems, Agentic Workflows |
| **RAG & Retrieval** | Hybrid Search (BM25 + Vector), **RRF**, CrossEncoders, Semantic Chunking |
| **LLMOps & Eval** | **Ragas**, **LangSmith**, MLflow, Weights & Biases, Delta Lake |
| **Fine-Tuning** | **PEFT**, **LoRA/QLoRA**, Unsloth, Hugging Face Transformers |
| **Vector/Graph DBs** | **ChromaDB**, **FAISS**, **Neo4j**, Redis |
| **Backend & Core** | **FastAPI**, **Docker**, **GitHub Actions (CI/CD)**, Python, SQL, TypeScript |

---

## 🎓 Education & Experience
* **M.Sc. Data Science** | *IIIT Lucknow* (Expected June 2026)
* **Graduate Teaching Assistant** | *IIIT Lucknow (Mathematics Dept)*
* **B.Sc. (Hons) Mathematics** | *University of Delhi* (2021 – 2024)

---

## 📈 GitHub Stats
<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=PratyayRajak&show_icons=true&theme=tokyonight&count_private=true&include_all_commits=true&hide_border=true" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=PratyayRajak&layout=compact&theme=tokyonight&hide_border=true" width="38%" />
</div>

---
<p align="center">
  <b>Actively seeking remote AI Engineer roles.</b><br>
  📫 <a href="mailto:pratyayrajak18@gmail.com">pratyayrajak18@gmail.com</a>
</p>
