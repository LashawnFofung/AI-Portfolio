<div align="center">

# AI Product Portfolio
### Lashawn Fofung · Technical Product Manager

**I spec, prototype, and build AI products — and I can explain the trade-offs to both engineers and executives.**

MBA, IT Management · PMP · CSPO · CSM · Oracle OCI Generative AI Professional

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lashawnfofung/)
[![MBA Portfolio](https://img.shields.io/badge/MBA_Portfolio-View-6E40C9?style=flat&logo=github&logoColor=white)](https://github.com/LashawnFofung/MBA-IT-Management-Portfolio)
[![Data Portfolio](https://img.shields.io/badge/Data_Portfolio-View-2EA44F?style=flat&logo=github&logoColor=white)](https://github.com/LashawnFofung/Data-Analysis-Portfolio)
[![GitHub](https://img.shields.io/badge/All_Repos-Profile-181717?style=flat&logo=github&logoColor=white)](https://github.com/LashawnFofung)

</div>

---

## Contents
[Why This Portfolio](#why-this-portfolio) · [At a Glance](#at-a-glance) · [AI Products](#-ai-products) · [Model Evaluation](#-model-evaluation--evidence-based-decisions) · [RAG Build Series](#-rag-build-series) · [AI Product Strategy](#-ai-product-strategy) · [Toolkit](#toolkit) · [Contact](#contact)

---

## Why This Portfolio

Most AI portfolios show either code or slide decks. This one shows both, because that's how I work as a PM:

- **I define the problem first.** Every project starts with a user and a business pain point, not a model.
- **I build to understand.** Writing the RAG pipelines myself means I know where retrieval breaks, what latency costs, and what to ask engineering.
- **I decide with evidence.** I benchmark models and embeddings before choosing them, and I document the trade-offs.
- **I ship artifacts teams can use.** PRDs, prototypes, evaluation reports, and working demos.

---

## At a Glance

| Project | What It Shows | Stack | Links |
|---|---|---|---|
| **Wayfair Agentic BI** | Multi-agent system design, PRDs, prototyping | n8n · Gemini · Google Sheets | [Repo](https://github.com/LashawnFofung/Wayfair-Agentic-BI) |
| **AI Document Automation Platform** 🏆 | Production-ready IDP: OCR + RAG + structured extraction | Python · LlamaIndex · FAISS · PaddleOCR · Gradio | [Repo](https://github.com/LashawnFofung/AI-Powered-Document-Automation-Platform) |
| **Embedding Model Scorecard** | Benchmarking speed vs. quality | MiniLM · BGE · E5 | [Report](https://github.com/LashawnFofung/AI-Powered-Document-Automation-Platform/blob/main/Technical%20Evaluation%20Reports/Embedding%20Model%20Scorecard%20Analysis.pdf) |
| **LLM Comparison for RAG** | Evidence-based model selection | LLM benchmarking | [Report](https://github.com/LashawnFofung/AI-Powered-Document-Automation-Platform/blob/main/Technical%20Evaluation%20Reports/Comparative%20Analysis%20of%20Large%20Language%20Models%20%20for%20Retrieval-Augmented%20Generation%20%28RAG%29.pdf) |
| **Metadata-Aware RAG Chatbot** | Solving "blob" PDFs with boundary detection + intent routing | Gemini 2.0 Flash · BGE · Gradio | [Notebook](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/Gradio/Task_Full_RAG_Pipeline_with_Interactive_Gradio_Chatbot.ipynb) |
| **News Corp: AI for Gen Z Trust** | User research → AI feature strategy → KPIs | Research · Strategy | [Repo](https://github.com/LashawnFofung/Digital-Product-AI-Strategy) |

---

## 🚀 AI Products

### Wayfair Agentic Business Intelligence
*Mar 2026 – May 2026 · AI Product Management*

**Problem:** With over 30 million products, Wayfair's teams can't manually track every trend or competitor move. Decision-makers face three hurdles:
- **Information overload:** raw data from blogs, social media, and listings never becomes usable trend insight.
- **Market blind spots:** "whitespace" where competitors aren't meeting demand goes unnoticed.
- **Speed to market:** the gap from design "mood" to live campaign or supply-chain change is too long.

**Solution:** An agentic BI pipeline — autonomous AI agents that plan and act to automate market research.
- **Automated discovery:** agents scan competitor sites and social media for emerging themes (e.g., specific rug designs).
- **Generative intelligence:** LLMs turn trend signals into visual moodboards and draft marketing copy.
- **Live synthesis:** data streams feed a self-updating Market Intelligence Dashboard for vendor management.

**PM artifacts:** Three agent PRDs, a UI prototype, and a recorded case study.
**Stack:** Google Gemini · n8n · Google Sheets · Perplexity · ChatGPT · Base44 (prototype)

🔗 [Repo](https://github.com/LashawnFofung/Wayfair-Agentic-BI) · [Prototype Demo](https://youtu.be/7shTzdWxmfE) · [PRD Case Study Video](https://youtu.be/faxDVoOzObo) · [Case Study PDF](https://github.com/LashawnFofung/Wayfair-Agentic-BI/blob/main/PRD%20CASE%20STUDY/Wayfair%20Agentic%20AI%20BI%20PRD%20Case%20Study.pdf)

---

### AI-Powered Document Automation Platform
*Oct 2025 – Jan 2026 · 🏆 Top Performer Award (Top 10%)*

**Problem:** Loan officers spend too much time reading mortgage application documents, and much of that data is locked in scanned "blobs."

**Solution:** A multi-stage intelligent document processing (IDP) pipeline:
- **Digitize:** OCR converts legacy scanned mortgage files into usable text.
- **Converse:** vector search (RAG) lets loan officers "chat" with a loan application.
- **Extract:** key financial fields are output as structured JSON for downstream underwriting systems.

**Stack:** Python · LlamaIndex · FAISS · PaddleOCR · Gemini API · Gradio

🔗 [Repo](https://github.com/LashawnFofung/AI-Powered-Document-Automation-Platform)

---

## 🔬 Model Evaluation & Evidence-Based Decisions

Choosing a model is a product decision: it sets cost, speed, and accuracy. These reports document how I selected models for the Document Automation Platform.

- **[Embedding Model Scorecard Analysis](https://github.com/LashawnFofung/AI-Powered-Document-Automation-Platform/blob/main/Technical%20Evaluation%20Reports/Embedding%20Model%20Scorecard%20Analysis.pdf)** — Compared MiniLM-L6-v2, BGE-small-en, and E5-small-v2 on indexing speed, retrieval speed, and retrieval quality within a RAG pipeline.
- **[Comparative Analysis of LLMs for RAG](https://github.com/LashawnFofung/AI-Powered-Document-Automation-Platform/blob/main/Technical%20Evaluation%20Reports/Comparative%20Analysis%20of%20Large%20Language%20Models%20%20for%20Retrieval-Augmented%20Generation%20%28RAG%29.pdf)** — Tested LLM and embedding combinations to reach sub-second retrieval while keeping answers factually accurate.

---

## 🧱 RAG Build Series

A hands-on progression from a basic chatbot to a production-style, metadata-aware RAG system. Each step adds one capability.

| # | Build | What It Adds | Key Tech |
|---|---|---|---|
| 1 | [Simple Chatbot with LlamaIndex](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/src/Task_Build_a_Simple_Chatbot_with_LlamaIndex.ipynb) | The foundation: user input → model reply | LlamaIndex · Gemini API |
| 2 | [Build & Optimize a RAG Pipeline](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/src/Task_Build_and_Optimize_a_RAG_Pipeline_for_Document_Retrieval.ipynb) | Semantic retrieval over a dense financial PDF, including calculations | PyMuPDF · MiniLM-L6-v2 · Gemini 2.5 Flash |
| 3 | [Advanced PDF Retrieval & Optimization](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/src/Task_Advanced_PDF_Retrieval_and_Optimization_with_LlamaIndex.ipynb) | Higher recall and precision via query expansion, hybrid search (vector + BM25), and cross-encoder reranking | LlamaIndex · BM25 · Sentence Transformers |
| 4 | [Interactive RAG Chatbot](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/src/Optimized_RAG_Pipeline_with_An_Interactive_RAG_Chatbot_for_Document_Retrieval.ipynb) | Multi-turn conversation with memory | LlamaIndex ChatEngine · Gemini 2.5 Flash |
| 5 | [Full RAG Pipeline with Gradio Chatbot](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/Gradio/Task_Full_RAG_Pipeline_with_Interactive_Gradio_Chatbot.ipynb) | Metadata-aware routing for merged multi-document PDFs, plus a web UI | Gemini 2.0 Flash · BGE-small · Gradio |

📄 Sample data used in builds 2 and 4: [Lender Fees Worksheet](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/data/LenderFeesWorksheetNew.pdf)

<details>
<summary><b>Deep dive: Build 5 — solving the "blob" PDF problem</b></summary>

<br>

**Problem:** When several documents (say, a resume, a payslip, and a contract) are scanned into one PDF, standard AI tools read it as one continuous stream. That causes:
- **Context bleeding:** a payslip answer pulls data from the resume.
- **Missed retrieval:** keyword search fails when terms differ ("Salary" vs. "Gross Pay").
- **Manual effort:** users must split and label files before AI can process them.

**Solution — Semantic Boundary Intelligence:**
- **Intelligent splitting:** Gemini 2.0 Flash analyzes page transitions to detect where one document ends and the next begins.
- **Semantic indexing:** pages are embedded with BAAI/bge-small-en-v1.5 so search understands meaning, not just keywords.
- **Intent routing:** the system predicts which document type holds the answer, then applies a metadata filter to search only that section.

**Stack:** LlamaIndex · Gemini 2.0 Flash · Sentence-Transformers (BGE-small) · PyMuPDF · Gradio · nest-asyncio

📄 [Demo & Reflection Presentation](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/Presentation/Full%20RAG%20Pipeline%20with%20Interactive%20Gradio%20Chatbot%20-%20Demo%20and%20Reflection.pdf)

</details>

---

## 📊 AI Product Strategy

### News Corp: AI Digital Product Strategy
*Aug 2025 – Oct 2025*

**Problem:** Gen Z doesn't trust news feeds — and often doesn't notice them at all.
**What I did:** Took the full product lifecycle from hypothesis and user research to KPI definition and a feature recommendation: **AI Dimensional Personalization**, which shifts the experience from generic feeds to a trustworthy AI co-pilot.
**Outcome:** Quantified a 42% trust deficit and proposed features targeting a 20% reduction in the "Never Notice" rate.

🔗 [Repo](https://github.com/LashawnFofung/Digital-Product-AI-Strategy) · [Pitch Deck](https://github.com/LashawnFofung/Digital-Product-AI-Strategy/blob/main/News%20Corp%20Gen%20Z%20Consumer%20Insight.pptx)

---

## Toolkit

**Product:** Technical PRDs · Jira · Figma · A/B testing · Prototyping (Base44) · User research
**AI & ML:** RAG · LlamaIndex · FAISS · Gemini API · Hugging Face · Mistral · Phi-2 · TinyLlama · PyTorch · Agentic workflows (n8n)
**Retrieval techniques:** Hybrid search (vector + BM25) · Query expansion · Cross-encoder reranking · Metadata filtering · Conversational memory
**Data & documents:** Python · Pandas · NumPy · Matplotlib · PyMuPDF · Tesseract · EasyOCR · PaddleOCR
**Interfaces & environment:** Gradio · Google Colab · Git

---

## Contact

Open to Technical PM and AI PM roles.

👉 **[Connect on LinkedIn](https://www.linkedin.com/in/lashawnfofung/)** · [MBA Portfolio](https://github.com/LashawnFofung/MBA-IT-Management-Portfolio) · [All Repos](https://github.com/LashawnFofung)
