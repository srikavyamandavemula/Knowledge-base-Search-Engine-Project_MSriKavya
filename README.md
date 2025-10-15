# Knowledge-base Search Engine

### Overview
A backend system for ingesting documents (PDF/text), utilizing RAG and LLM synthesis to provide self-contained answers to user queries.

### Features
- Document ingestion and vector storage.
- Accurate retrieval via embeddings.
- LLM-based synthesis for coherent answers.
- API for upload/query.
- (Optional) Frontend demo.

### Getting Started
1. **Install dependencies:**  
   `pip install -r requirements.txt`
2. **Run backend:**  
   `uvicorn app.main:app --reload`
3. **(Optional) Run frontend:**  
   `streamlit run demo/streamlit_app.py`
4. **Demo video:** See `demo_video.mp4`

### Usage
- Upload documents via POST `/upload/`
- Submit queries via POST `/query/`

### Prompt for LLM
> “Using these documents, answer the user’s question succinctly.”

### Technologies
- Python, FastAPI
- LangChain or Haystack
- SentenceTransformers/FAISS
- OpenAI/HuggingFace LLMs

### License
MIT

### Maintainer
Your Name

