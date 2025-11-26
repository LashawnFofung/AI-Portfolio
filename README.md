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

<b>[Build And Optimize A RAG Pipeline For Document Retrieval](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/src/Task_Build_and_Optimize_a_RAG_Pipeline_for_Document_Retrieval.ipynb)</b>
    
- <i>Review Data</i>: [HERE](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/data/LenderFeesWorksheetNew.pdf)

- <b>The Problem:</b> Financial documents, like the Lender's Fees Worksheet used in this demo, are often dense and semi-structured, mixing tables, line items, and prose. Extracting specific, cross-referenced data. For instance, calculating a total monthly payment or locating a single fee. This is a manual, time-consuming, and error-prone process for end-users or automated systems relying solely on keyword searches. The goal is to move from laborious human review to instant, reliable data retrieval.
	
- <b>The "Tech" Solution:</b>
		
	The solution is an optimized RAG pipeline that achieves high retrieval accuracy for both numerical and textual data.

  	- <b>Parsing:</b> It uses PyMuPDF for superior PDF text extraction, ensuring high-quality input data from the start.

	- <b>Semantic Search:</b> It converts all document content into dense vector embeddings (🔢) using an efficient model. This enables semantic search (Vector Retrieval), allowing the system to understand the meaning of a user's question (e.g., asking for a "security protection fee") and accurately retrieve (🔍) the relevant financial line item ("Lender's Title Insurance") from the document.

	- <b>Synthesis:</b> The retrieved context is then passed to the Gemini 2.5 Flash LLM, which synthesizes the final, accurate answer, even performing required calculations like summing monthly components.

 - <b>Stack:</b> Python, RAG, LlamaIndex, LLM, Gemini 2.5 Flash, HuggingFace MiniLM-L6-v2, PyMuPDF (fitz)

<br><br>

<b>[Optimized RAG Pipeline with Interactive RAG Chatbot for Document Retrieval](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/src/Optimized_RAG_Pipeline_with_Interactive_RAG_Chatbot_for_Document_Retrieval.ipynb)</b>
	
	- <i>Review Data</i>: [HERE](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/data/LenderFeesWorksheetNew.pdf)	

	- <b>The Problem:</b> Financial documents, like the Lender's Fees Worksheet, are dense, unstructured, and time-consuming to analyze manually. Extracting specific, cross-referenced data—such as calculating a total monthly payment or locating a single fee—is often rigid and prone to human error. The goal is to move beyond single, static queries to an instant, conversational data assistant that can handle multi-turn follow-up questions and provide reliable, grounded facts.
	
- <b>The "Tech" Solution:</b>
		
	The solution is an optimized RAG pipeline built around a Conversational Chat Engine that achieves high retrieval accuracy and maintains memory across turns:

  	- <b>Parsing:</b> It uses PyMuPDF for superior PDF text extraction, ensuring high-quality input data from the start, preserving complex table structures.

	- <b>Semantic Search & Indexing:</b> The pipeline converts document content into dense vector embeddings (🔢) using the highly efficient MiniLM model. This enables semantic search (Vector Retrieval), allowing the system to understand the meaning of a user's question (e.g., asking for a "security protection fee") and accurately retrieve (🔍) the relevant financial line item.

	- <b>Conversational RAG:</b> The key upgrade is the use of the LlamaIndex ChatEngine, which automatically retrieves context for every turn of the conversation. It combines the conversation history with the newly retrieved document chunks.
   
	- <b>Synthesis:</b> The combined context is passed to the Gemini 2.5 Flash LLM, which synthesizes the final, accurate, and memory-aware answer, allowing users to ask complex, multi-turn follow-up questions.

 - <b>Stack:</b> Python, RAG, LlamaIndex, LLM, Gemini 2.5 Flash, HuggingFace MiniLM-L6-v2, PyMuPDF (fitz)
<br><br>

### 📊 II. Product Strategy & Architecture

Artifacts demonstrating system design and product management skills.

<b>[Digital Product AI Strategy](https://github.com/LashawnFofung/Digital-Product-AI-Strategy)</b>
	
- Translating Gen Z behavioral insights into retention-focused product features. Covers the full lifecycle from hypothesis and user research to KPI definition and final feature recommendation.
  

