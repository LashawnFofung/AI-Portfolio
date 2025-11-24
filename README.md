# AI Product & Engineering Portfolio

### Bridging the gap between Technical Execution and Product Strategy

##

## 📖 About This Portfolio
Welcome to my digital workspace. This repository documents my journey in building Artificial Intelligence solutions. Unlike traditional engineering portfolios, this collection highlights a dual focus:

  - <b>AI Development:</b> Writing robust Python code, fine-tuning LLMs, and building RAG pipelines.

  - <b>Product Strategy:</b> Defining user needs, technical feasibility, and go-to-market logic for AI features.

##

## 🛠️ Tech & Tool Stack
  - <b>Core Development:</b>	Python,Colab, Git
  - <b>AI & ML:</b>	RAG, LlamaIndex, Gemini API, Hugging Face
  - <b>Product & Strategy:</b>	Jira, Figma, A/B Testing, Technical PRD Writing,
  - <b>Data Engineering:</b>	Pandas,PyMuPDF, Tesseract, EasyOCR, NumPy, 

##

## 📂 Selected Projects

### 🚀 I. End-to-End AI Products (LLMs & GenAI)

<b>[AI-Powered Document Automation Platform](https://github.com/LashawnFofung/AI-Powered-Document-Automation-Platform)</b>	
  - <b>The Product Problem:</b> Users spend too much time reading mortgage application documents.
  - <b>The "Tech" Solution:</b>
  	- Buiding a multi-stage pipeline using Python and OCR to digitize legacy mortgage blobs. Implemented Vector Search (RAG) to allow loan officers to 'chat' with loan applications and automated the extraction of key financial data into structured JSON for downstream underwriting systems. 	
  - <b>Stack:</b> Python, OCR, RAG, LLM,API  
		
<br></br>

<b>[RAG Pipelines: Simple Chatbot with LlamaIndex](https://github.com/LashawnFofung/RAG-Pipelines)</b>	
  - <b>The Product Problem:</b> Simple chatbox to build basic component for RAG pipeline (system).
  - <b>The "Tech" Solution:</b>
  	- Create a simple, functional chatbot that handles user input and provides model-generated replies. Retrieval will come next!. 	
  - <b>Stack:</b> Python, LlamaIndex, RAG, LLM,Gemini API  

<br></br>

<b>[Advanced PDF Retrieval and Optimization with LlamaIndex](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/src/Task_Advanced_PDF_Retrieval_and_Optimization_with_LlamaIndex.ipynb)</b>
  - <b>The Problem:</b> Retrieval-Augmented Generation (RAG) accuracy often suffers when querying large, complex PDF documents (like contracts or technical papers) because basic vector search alone struggles with lexical mismatches, terminology variations, and long context.
  
  - <b>The "Tech" Solution:</b> This notebook demonstrates an advanced RAG pipeline that significantly boosts retrieval quality (Recall and Precision) by stacking three optimization techniques:
	- Query Expansion: Uses the LLM to generate multiple relevant query variations, ensuring a wider net is cast.

	- Hybrid Retrieval (Vector + BM25): Combines semantic search (embeddings) with keyword search (BM25) to retrieve both conceptual and exact term matches.

	- Reranking: Employs a Cross-Encoder model (e.g., Sentence Transformer) as a final filter to re-score and prioritize the most relevant retrieved chunks, maximizing the quality of context passed to the LLM.
  
  - <b>Stack:</b> Python, LlamaIndex,RAG, LLM, Gemini API

<br><br>


### 📊 II. Product Strategy & Architecture

Artifacts demonstrating system design and product management skills.

<b>[Digital Product AI Strategy](https://github.com/LashawnFofung/Digital-Product-AI-Strategy)</b>
	
- Translating Gen Z behavioral insights into retention-focused product features. Covers the full lifecycle from hypothesis and user research to KPI definition and final feature recommendation.
  

