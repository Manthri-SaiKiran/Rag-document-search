Build a "Chat with Your Data" tool using Retrieval-Augmented Generation (RAG). Use tools like LangChain, Pinecone (Vector DB), and an LLM to answer questions from private PDFs or company wikis.Resume Highlight: Mention how you handled "hallucinations" and optimized retrieval accuracy.# RAG Document Search System

Chat with your PDFs using LangChain, Pinecone, and LLMs.

## Setup
pip install -r requirements.txt

## Run
python scripts/ingest_data.py
python scripts/query.py
streamlit run frontend/streamlit_app.py
