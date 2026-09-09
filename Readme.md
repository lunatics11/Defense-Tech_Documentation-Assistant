Defence Engineering Knowledge Assistant
=======

Goal: Build a chatbot that answers questions from Defence documents/data like inventory, SOH, DOI, sales, product notes, PDFs etc.

Concepts covered
RAG
LangChain
LangGraph
MCP
Basic evaluation
Guardrails/corrigibility basics

Architecture

PDF/CSV/KT Notes
↓
Document Loader
↓
Chunking + Embeddings
↓
Vector DB
↓
LangGraph Workflow:
- classify query
- retrieve docs
- grade relevance
- answer with citations
- fallback if weak context

Example features
Explain missile guidance.

Summarize UAV communication.

List maintenance procedures.

Explain radar architecture.

Generate maintenance checklist.

Extract technical specifications.

Why this is useful: Internal case-study material shows RAG + Knowledge Graph can support contextual Q&A over defense knowledge, using vector search and database query generation with LangChain-style Cypher generation. AI Case Studies across value chain-ukey160625081138

# How to use
- pip install -r requirements.txt
- streamlit run app.py
