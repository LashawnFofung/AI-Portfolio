# AI Product & Engineering Portfolio

### Bridging the gap between Technical Execution and Product Strategy

##
## Table of Contents
- [About This Portfolio](https://github.com/LashawnFofung/AI-Portfolio/blob/main/README.md#-about-this-portfolio)
- [Tech & Tool Stack](https://github.com/LashawnFofung/AI-Portfolio/blob/main/README.md#%EF%B8%8F-tech--tool-stack)
- [Selected Projects](https://github.com/LashawnFofung/AI-Portfolio/blob/main/README.md#-selected-projects)
	- [I. End-to-End AI Products](https://github.com/LashawnFofung/AI-Portfolio/blob/main/README.md#-i-end-to-end-ai-products-llms--genai)

		- [Wayfair Agentic Business Intelligence (BI)](https://github.com/LashawnFofung/AI-Portfolio/blob/main/README.md#wayfair-agentic-business-intelligence-bi)
		
		- [AI-Powered Document Automation Platform](https://github.com/LashawnFofung/AI-Portfolio/blob/main/README.md#ai-powered-document-automation-platform)
   		- [RAG Pipelines: Simple Chatbot with LlamaIndex](https://github.com/LashawnFofung/AI-Portfolio/blob/main/README.md#rag-pipelines-simple-chatbot-with-llamaindex)
     	- [Advanced PDF Retrieval and Optimization with LlamaIndex](https://github.com/LashawnFofung/AI-Portfolio/blob/main/README.md#advanced-pdf-retrieval-and-optimization-with-llamaindex) 
		- [Build And Optimize A RAG Pipeline For Document Retrieval](https://github.com/LashawnFofung/AI-Portfolio/blob/main/README.md#build-and-optimize-a-rag-pipeline-for-document-retrieval)
    	- [Optimized RAG Pipeline with Interactive RAG Chatbot For Document Retrieval](https://github.com/LashawnFofung/AI-Portfolio/blob/main/README.md#optimized-rag-pipeline-with-interactive-rag-chatbot-for-document-retrieval)

  - [II. Product Strategy & Architecture](https://github.com/LashawnFofung/AI-Portfolio/blob/main/README.md#-ii-product-strategy--architecture) 
		
	- [Digital Product AI Strategy](https://github.com/LashawnFofung/AI-Portfolio/blob/main/README.md#digital-product-ai-strategy)


## 📖 About This Portfolio
Welcome to my digital workspace. This repository documents my journey in building Artificial Intelligence solutions. Unlike traditional engineering portfolios, this collection highlights a dual focus:

  - <b>AI Development:</b> Writing robust Python code, fine-tuning LLMs, and building RAG pipelines.

  - <b>Product Strategy:</b> Defining user needs, technical feasibility, and go-to-market logic for AI features.

##

## 🛠️ Tech & Tool Stack
  - <b>Core Development:</b>	Python,Colab, Git
  - <b>AI & ML:</b>	RAG, LlamaIndex, Gemini API, HuggingFace, Mistral, Phi-2, TinyLlama, PyTorch
  - <b>Product & Strategy:</b>	Jira, Figma, A/B Testing, Technical PRD Writing,
  - <b>Data Engineering:</b>	Pandas,PyMuPDF, Matplotlib, Tesseract, EasyOCR, NumPy
  - <b>UI:</b> Gradio

##

## 📂 Projects

### 🚀 I. End-to-End AI Products 


#### [Wayfair Agentic Business Intelligence (BI)](https://github.com/LashawnFofung/Wayfair-Agentic-BI)
  - <b>The Product Problem:</b>

	Modern e-commerce leaders like Wayfair manage over 30 million products, making it impossible for human teams to manually track every trend or competitor move. Decision-makers face three primary hurdles:
	
	- <b>Information Overload:</b> Transforming massive amounts of raw data from blogs, social media, and product listings into actionable design trends.
	
	
	- <b>Market Blindspots:</b>  Identifying "whitespace" opportunities where competitors are not currently meeting consumer demand.
	
	
	- <b>Speed to Market:</b>  Reducing the time it takes to go from a design "mood" to a live marketing campaign or supply chain adjustment.


  - <b>The "Tech" Solution:</b>

	  The solution is an Agentic Business Intelligence Pipeline—a system of autonomous AI agents that "think, plan, and act" to automate market research.

	- <b>Automated Discovery:</b> Using agents to scrape competitor websites and social media to identify emerging themes, such as specific rug designs.
		
	- <b>Generative Intelligence:</b> Deploying LLMs to translate trend signals into visual moodboards and draft high-conversion marketing copy.
		
		
	- <b>Live Synthesis:</b> Integrating disparate data streams into a self-updating Market Intelligence Dashboard in Google Sheets for real-time vendor management.


  - <b>Stack:</b> Google Gemini, n8n, Google Sheets, Perplexity, ChatGPT

<h1></h1>

#### [AI-Powered Document Automation Platform](https://github.com/LashawnFofung/AI-Powered-Document-Automation-Platform)	
  - <b>The Product Problem:</b> Users spend too much time reading mortgage application documents.
  - <b>The "Tech" Solution:</b>
  	- Buiding a multi-stage pipeline using Python and OCR to digitize legacy mortgage blobs. Implemented Vector Search (RAG) to allow loan officers to 'chat' with loan applications and automated the extraction of key financial data into structured JSON for downstream underwriting systems. 	
  - <b>Tech Stack:</b> Python, OCR, RAG, LLM,API  
		
<h1></h1>


#### [RAG Pipelines: Simple Chatbot with LlamaIndex](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/src/Task_Build_a_Simple_Chatbot_with_LlamaIndex.ipynb)	
  - <b>The Product Problem:</b> Simple chatbox to build basic component for RAG pipeline (system).
  - <b>The "Tech" Solution:</b>
  	- Create a simple, functional chatbot that handles user input and provides model-generated replies. Retrieval will come next!. 	
  - <b>Tech Stack:</b> Python, LlamaIndex, RAG, LLM,Gemini API  

<h1></h1>

#### [Advanced PDF Retrieval and Optimization with LlamaIndex](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/src/Task_Advanced_PDF_Retrieval_and_Optimization_with_LlamaIndex.ipynb)
  - <b>The Problem:</b> Retrieval-Augmented Generation (RAG) accuracy often suffers when querying large, complex PDF documents (like contracts or technical papers) because basic vector search alone struggles with lexical mismatches, terminology variations, and long context.
  
  - <b>The "Tech" Solution:</b> This notebook demonstrates an advanced RAG pipeline that significantly boosts retrieval quality (Recall and Precision) by stacking three optimization techniques:
	- Query Expansion: Uses the LLM to generate multiple relevant query variations, ensuring a wider net is cast.

	- Hybrid Retrieval (Vector + BM25): Combines semantic search (embeddings) with keyword search (BM25) to retrieve both conceptual and exact term matches.

	- Reranking: Employs a Cross-Encoder model (e.g., Sentence Transformer) as a final filter to re-score and prioritize the most relevant retrieved chunks, maximizing the quality of context passed to the LLM.
  
  - <b>Tech Stack:</b> Python, LlamaIndex,RAG, LLM, Gemini API

<h1></h1>

#### [Build And Optimize A RAG Pipeline For Document Retrieval](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/src/Task_Build_and_Optimize_a_RAG_Pipeline_for_Document_Retrieval.ipynb)
    
- <i>Review Data</i>: [HERE](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/data/LenderFeesWorksheetNew.pdf)

- <b>The Problem:</b> Financial documents, like the Lender's Fees Worksheet used in this demo, are often dense and semi-structured, mixing tables, line items, and prose. Extracting specific, cross-referenced data. For instance, calculating a total monthly payment or locating a single fee. This is a manual, time-consuming, and error-prone process for end-users or automated systems relying solely on keyword searches. The goal is to move from laborious human review to instant, reliable data retrieval.
	
- <b>The "Tech" Solution:</b>
		
	The solution is an optimized RAG pipeline that achieves high retrieval accuracy for both numerical and textual data.

  	- <b>Parsing:</b> It uses PyMuPDF for superior PDF text extraction, ensuring high-quality input data from the start.

	- <b>Semantic Search:</b> It converts all document content into dense vector embeddings (🔢) using an efficient model. This enables semantic search (Vector Retrieval), allowing the system to understand the meaning of a user's question (e.g., asking for a "security protection fee") and accurately retrieve (🔍) the relevant financial line item ("Lender's Title Insurance") from the document.

	- <b>Synthesis:</b> The retrieved context is then passed to the Gemini 2.5 Flash LLM, which synthesizes the final, accurate answer, even performing required calculations like summing monthly components.

 - <b>Tech Stack:</b> Python, RAG, LlamaIndex, LLM, Gemini 2.5 Flash, HuggingFace MiniLM-L6-v2, PyMuPDF (fitz)

<h1></h1>

#### [Optimized RAG Pipeline with Interactive RAG Chatbot for Document Retrieval](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/src/Optimized_RAG_Pipeline_with_An_Interactive_RAG_Chatbot_for_Document_Retrieval.ipynb)
	
- <i>Review Data</i>: [HERE](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/data/LenderFeesWorksheetNew.pdf)	

- <b>The Problem:</b> Financial documents, like the Lender's Fees Worksheet, are dense, unstructured, and time-consuming to analyze manually. Extracting specific, cross-referenced data—such as calculating a total monthly payment or locating a single fee—is often rigid and prone to human error. The goal is to move beyond single, static queries to an instant, conversational data assistant that can handle multi-turn follow-up questions and provide reliable, grounded facts.
	
- <b>The "Tech" Solution:</b>
		
	The solution is an optimized RAG pipeline built around a Conversational Chat Engine that achieves high retrieval accuracy and maintains memory across turns:

  	- <b>Parsing:</b> It uses PyMuPDF for superior PDF text extraction, ensuring high-quality input data from the start, preserving complex table structures.

	- <b>Semantic Search & Indexing:</b> The pipeline converts document content into dense vector embeddings (🔢) using the highly efficient MiniLM model. This enables semantic search (Vector Retrieval), allowing the system to understand the meaning of a user's question (e.g., asking for a "security protection fee") and accurately retrieve (🔍) the relevant financial line item.

	- <b>Conversational RAG:</b> The key upgrade is the use of the LlamaIndex ChatEngine, which automatically retrieves context for every turn of the conversation. It combines the conversation history with the newly retrieved document chunks.
   
	- <b>Synthesis:</b> The combined context is passed to the Gemini 2.5 Flash LLM, which synthesizes the final, accurate, and memory-aware answer, allowing users to ask complex, multi-turn follow-up questions.

 - <b>Tech Stack:</b> Python, RAG, LlamaIndex, LLM, Gemini 2.5 Flash, HuggingFace MiniLM-L6-v2, PyMuPDF (fitz)

<h1></h1>

#### [Full RAG Pipeline with Interactive Gradio Chatbot](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/Gradio/Task_Full_RAG_Pipeline_with_Interactive_Gradio_Chatbot.ipynb)

- <i>view</i> [Presentation PDF: Full RAG Pipeline with Interactive Gradio Chatbot](https://github.com/LashawnFofung/RAG-Pipelines/blob/main/Presentation/Full%20RAG%20Pipeline%20with%20Interactive%20Gradio%20Chatbot%20-%20Demo%20and%20Reflection.pdf)

- <b>The Problem:</b> Most automated systems struggle with merged documents. When multiple distinct files (e.g., a Resume, a PaySlip, and a Contract) are scanned into a single PDF "blob," standard AI tools treat them as one continuous stream of text.

	- <b>Key Challenges:</b>
	
		- <b>Context Bleeding:</b> Answers about a PaySlip might mistakenly pull data from a Resume.
		
		- <b>Inaccurate Retrieval:</b> Standard keyword search fails to find information if the terminology differs (e.g., "Salary" vs. "Gross Pay").
		
		- <b>Manual Effort:</b> Users traditionally have to manually split and categorize files before they can be processed by AI.

- <b> The "Tech" Solution: Semantic Boundary Intelligence</b>

	This project solves the "Blob" problem by shifting from simple text extraction to a Metadata-Aware RAG Pipeline.
	
	- <b>How it works:</b>
	
		- <b>Intelligent Splitting:</b> The system uses LLM-based reasoning (Gemini 2.0) to analyze page transitions and detect document boundaries in real-time.
		
		- <b>Semantic Indexing:</b> Instead of a flat search, pages are embedded into a vector space using BAAI/bge-small-en-v1.5, allowing the system to understand the meaning of your questions.
		
		- <b>Intent Routing:</b> The AI first predicts which document type contains the answer, then applies a Metadata Filter to search only that specific section. This ensures high precision and eliminates "noise" from irrelevant pages.

- <b> Tech Stack</b>

	- <b>Core AI & Frameworks</b>
	
		- <b>LlamaIndex:</b> The primary orchestration framework used for data ingestion, indexing, and retrieval logic.
		
		- <b>Google Gemini 2.0 Flash:</b> The "reasoning engine" responsible for document classification, boundary detection, and final response generation.
		
		- <b>Sentence-Transformers:</b> Powers the semantic search capabilities via the BGE-Small embedding model.
		
	- <b>Processing & UI</b>
	
		- <b>Gradio:</b> A Python-based UI framework used to build the interactive web dashboard, featuring custom CSS for a professional, bordered layout.
		
		- <b>PyMuPDF:</b> Utilized for high-performance PDF text extraction and parsing.
		
		- <b>Nest-Asyncio:</b> Manages asynchronous event loops to ensure the Gradio UI and LLM calls run smoothly in interactive environments.

<h1></h1>



### 📊 II. Product Strategy & Architecture

Artifacts demonstrating system design and product management skills.

#### [Digital Product AI Strategy](https://github.com/LashawnFofung/Digital-Product-AI-Strategy)
	
- Translating Gen Z behavioral insights into retention-focused product features. Covers the full lifecycle from hypothesis and user research to KPI definition and final feature recommendation.

<h1></h1>

#### [Technical Evaluation Report: Embedding Model Scorecard Analysis](https://github.com/LashawnFofung/AI-Powered-Document-Automation-Platform/blob/main/Technical%20Evaluation%20Reports/Embedding%20Model%20Scorecard%20Analysis.pdf)

- To systematically evaluate and compare the indexing speed, retrieval speed, and retrieval quality (conciseness) of three leading open-source embedding models: MiniLM-L6-v2, BGE-small-en, and E5-small-v2, within a simple RAG pipeline.

<h1></h1>


#### [Comparative Analysis of Large Language Models for Retrieval-Augmented Generation (RAG)](https://github.com/LashawnFofung/AI-Powered-Document-Automation-Platform/blob/main/Technical%20Evaluation%20Reports/Comparative%20Analysis%20of%20Large%20Language%20Models%20%20for%20Retrieval-Augmented%20Generation%20(RAG).pdf)

- To showcase the rigorous testing phase of the AI-Powered Document Automation Platform, demonstrating evidence-based model selection for LLMs and embedding models to achieve sub-second retrieval with factual accuracy.

<h1></h1>
