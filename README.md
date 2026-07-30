# AI Study Assistant

A multi-agent AI Study Assistant built with LangGraph. It uses uploaded PDF documents to answer questions, generate summaries, and create quizzes using Retrieval-Augmented Generation (RAG).

## Programme
- Programme: SDAIA Academy – Building AI Agent Systems
- Cohort: 26–30 July 2026

  ## Features
- PDF document upload
- Question Answering, Summary, and Quiz Workers
- FAISS-based RAG
- Short-term and long-term memory
- Human-in-the-Loop quiz approval
- RetryPolicy and fallback error handling
- LangSmith tracing
- LangGraph Functional API

  ## How to Run
1. Open the notebook in Google Colab.
2. Add GROQ_API_KEY to Colab Secrets.
3. Add LANGSMITH_API_KEY to enable tracing.
4. Select Runtime → Restart session and run all.
5. Upload a text-based PDF.
6. Enter a study request.
7. Type yes or no when quiz approval is requested.
