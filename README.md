# GitRAG

GitRAG is a Retrieval-Augmented Generation (RAG) based AI debugging assistant designed to analyze and understand codebases using Large Language Models and semantic retrieval.

The system ingests source code repositories, generates embeddings for code chunks, stores them in a vector database, and retrieves contextually relevant snippets to assist developers with debugging, code understanding, and issue resolution.

## Features
- RAG-based code understanding pipeline
- Semantic code retrieval using embeddings
- Vector similarity search with ChromaDB
- Context-aware debugging assistance
- Multi-file codebase ingestion and chunking
- LangChain-powered retrieval workflows
- HuggingFace embedding integration
- LLM-powered response generation
- Evaluation metrics for retrieval quality
- Interactive Gradio interface

## Tech Stack
- Python
- LangChain
- ChromaDB
- HuggingFace Transformers
- Sentence Transformers
- Groq API / LLM APIs
- Gradio

## Workflow
1. Ingest source code files from repositories
2. Split code into semantic chunks
3. Generate embeddings for each chunk
4. Store embeddings in ChromaDB
5. Retrieve relevant code snippets based on user query
6. Provide context-aware debugging and explanations using LLMs

## Use Cases
- AI-powered debugging assistant
- Repository understanding
- Developer support systems
- Intelligent code search
- Context-aware coding help

## Future Improvements
- GitHub API integration
- Multi-language repository support
- Agentic workflows for autonomous debugging
- Fine-tuned code LLM integration
- Hybrid search and reranking
- Dockerized deployment
