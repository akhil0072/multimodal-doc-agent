# Multimodal Document Analyst Agent

An intelligent agent that analyzes uploaded documents (PDFs, images, scanned text) using vision and text understanding. It answers questions, extracts insights, summarizes visually, and cites sources — perfect for reports, invoices, or research papers.

### Key Features
- Multimodal input: Handles text PDFs + image-based docs (charts, photos)
- Vision + LLM reasoning for descriptions and Q&A
- Source citations and conversational memory
- Streamlit chat interface with file upload and image previews

### Tech Stack
- LangChain/LangGraph
- Multimodal LLMs (e.g., GPT-4o, Claude-3, Groq)
- Vector store (Chroma or FAISS)
- Document processing (PyPDF, OCR if needed)
- Streamlit

### Architecture Overview
(Ingestion → Embedding → Retrieval → Multimodal Agent Reasoning)


### Quick Start
1. `pip install -r requirements.txt`
2. Set API keys in `.env`
3. `streamlit run app.py`
