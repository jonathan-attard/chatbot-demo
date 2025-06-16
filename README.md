# RAG Chatbot Demo

This project demonstrates how to build a Retrieval-Augmented Generation (RAG) chatbot using Python, ChromaDB, LangChain, LangGraph, and Langfuse for tracing. The notebook walks through:

- **Prompt engineering** with Gemini API.
- **Adding retrievers** using ChromaDB and Nomic embeddings.
- **Semantic search** and dynamic context retrieval.
- **Pipeline orchestration** with LangChain & LangGraph.
- **Tracing and observability** with Langfuse.

## Requirements

- Python 3.8+
- See [requirements.txt](requirements.txt) for dependencies.

## Quick Start

1. Clone the repo and install dependencies:
    ```sh
    pip install -r requirements.txt
    ```
2. Add your API keys to a `.env` file (see example in `.env`).
3. Run `chatbot.ipynb` in Jupyter or VS Code.

## Features

- RAG pipeline with semantic search
- Persistent vector storage (ChromaDB)
- Modular pipeline with LangChain/LangGraph
- Tracing and evaluation with Langfuse

## References

- [ChromaDB](https://www.trychroma.com/)
- [LangChain](https://python.langchain.com/)
- [LangGraph](https://langchain-ai.github.io/langgraph/)
- [Langfuse](https://langfuse.com/)
- [Google Gemini API](https://aistudio.google.com/)

---
For educational/demo use