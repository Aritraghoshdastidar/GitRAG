# GitRAG – AI-Powered Codebase Debugging Assistant

GitRAG is a Retrieval-Augmented Generation (RAG) system designed to analyze software repositories, retrieve relevant source code, and provide grounded debugging assistance using Large Language Models.

This repository contains **two complementary notebook implementations**, each focusing on different aspects of the project.

---

# Repository Structure

```
GitRAG/
│
├── GitRag_v2.ipynb          # Next-generation production-oriented implementation
├── GitRag (1).ipynb         # Original research & evaluation implementation
├── README.md
└── ...
```

---

# GitRag_v2.ipynb (Recommended)

The latest and most complete implementation of GitRAG, redesigned with a production-oriented architecture inspired by modern AI-powered developer tools.

## Highlights

- Tree-sitter based multi-language parsing
- Semantic AST-aware chunking
- Hybrid Retrieval Pipeline
  - Dense Embeddings
  - BM25
  - Reciprocal Rank Fusion (RRF)
  - Cross-Encoder Reranking
- Repository Knowledge Graph
- LangGraph-based multi-agent debugging workflow
- Production-ready retrieval pipeline
- Improved modular architecture
- Better scalability and maintainability
- Interactive Gradio interface

### Best suited for

- AI/ML engineering portfolio
- Code intelligence demonstrations
- Production-oriented RAG systems
- Software engineering interviews
- Research extensions

---

# GitRag (1).ipynb (Original)

The original GitRAG implementation developed during the project's first phase.

While the architecture is simpler, it includes a more comprehensive evaluation workflow and richer visualizations that are useful for experimentation and benchmarking.

## Highlights

- End-to-end GitRAG pipeline
- Hybrid dense retrieval
- Confidence-aware debugging responses
- Extensive evaluation metrics
- Performance benchmarking
- Retrieval quality analysis
- Visualization of experimental results
- Charts and diagnostic plots
- Interactive Gradio UI

### Best suited for

- Experimental evaluation
- Retrieval benchmarking
- Performance analysis
- Academic demonstrations
- Comparing retrieval strategies

---

# Which notebook should I use?

| Notebook | Primary Purpose |
|-----------|-----------------|
| **GitRag_v2.ipynb** | Production-grade implementation with improved architecture, parsing, retrieval, and agent workflow |
| **GitRag (1).ipynb** | Research, evaluation, benchmarking, visualizations, and experimental analysis |

The two notebooks are intentionally kept together because they complement each other:

- **GitRag_v2** demonstrates how the system would be implemented in a production-oriented setting.
- **GitRag (1)** provides richer evaluation metrics, benchmarking utilities, and visualizations that are valuable for analyzing system performance.

Together they present both the engineering and research perspectives of the project.

---

# Tech Stack

- Python
- LangChain
- ChromaDB
- Tree-sitter
- BM25
- Cross-Encoder Reranker
- Groq LLaMA 3.3
- Sentence Transformers
- NetworkX
- LangGraph
- Gradio
- HuggingFace
- tiktoken
- NumPy
- Pandas
- Matplotlib

---

# Future Work

- Modular Python package structure
- Docker deployment
- CI/CD pipelines
- GitHub integration
- Pull Request review assistant
- Incremental repository indexing
- Distributed retrieval
- Enterprise-scale repository support
