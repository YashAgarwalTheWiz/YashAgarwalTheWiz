<h1 align="center">Yash Agarwal</h1>

<p align="center">
  <strong>Software Engineer building RAG systems, LLM agents, and evaluation harnesses in Python</strong><br/>
  LangGraph &nbsp;•&nbsp; FastAPI &nbsp;•&nbsp; Qdrant &nbsp;•&nbsp; DeepEval
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/yash-agarwal-73a32b230/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://leetcode.com/u/yash8354/"><img src="https://img.shields.io/badge/LeetCode-500%2B%20solved-FFA116?style=flat-square&logo=leetcode&logoColor=white" alt="LeetCode"/></a>
</p>

---

## About

I'm a software engineer at **Tata Consultancy Services (TCS iON)** who builds LLM applications that are measurable and safe, not just demos. My focus is retrieval-augmented generation, tool-calling agents, and the evaluation work that shows whether they actually work.

- Built a semantic question-similarity retrieval feature at TCS iON (sentence embeddings + cosine similarity over Solr)
- Runner-up at **AI Friday**, an internal AI hackathon at TCS
- Solved 500+ data structures and algorithms problems on LeetCode
- B.Tech in Computer Science and Engineering, Graphic Era University (CGPA 8.86)

Currently exploring multi-agent systems, LLM guardrails, and RAG evaluation.

---

## Featured Projects

### [ResearchLens](https://github.com/YashAgarwalTheWiz/ResearchLens-)
A multi-capability RAG system for academic paper analysis: structured summarization, research-gap identification, cited Q&A, and cross-paper comparison.

- Retrieval pipeline with **Qdrant** vector search and **Cohere** reranking, improving **MRR from 0.412 to 0.475** (Hit Rate@5: 0.70) on a hand-curated evaluation set
- Orchestrated with **LangGraph**, served via **FastAPI**, backed by Supabase/PostgreSQL
- LLM-based guardrail and Tavily web-search fallback

`Python` `LangGraph` `FastAPI` `Qdrant` `Cohere` `Streamlit`

### [RAGEvals](https://github.com/YashAgarwalTheWiz/RAGEvals)
A three-tier RAG evaluation framework: component-level, pipeline-level (2-config A/B), and operational.

- Uses **DeepEval** and a custom LLM-judge harness over 9 categorized golden questions, with 5 DeepEval metrics to separate retrieval quality from generation quality
- Chunk-size A/B tests raised **contextual recall by 18%** (0.61 → 0.72)
- Latency/cost/reliability profiler across 27 runs (100% success) traced the bottleneck to generation latency, not the provider's documented rate limit

`Python` `DeepEval` `ChromaDB`

### [Agentic AI Assistant](https://github.com/YashAgarwalTheWiz/agentic-ai-assistant)
A tool-calling AI agent that decides for itself when to use tools (web search, document retrieval, file I/O, email).

- Replaced a rigid query-classification pipeline with a cyclic **LangGraph** reasoning loop
- **Human-in-the-loop approval gate** using LangGraph's interrupt/resume, with fail-closed authorization on every write-capable tool and a persistent audit trail
- Validated by a **17-test automated safety suite**

`Python` `LangGraph` `FastAPI` `ChromaDB` `SQLite`

---

## Tech Stack

| Area | Tools |
|---|---|
| **LLM & GenAI** | RAG, semantic search, reranking, prompt engineering, tool-calling agents, guardrails, LLM evaluation |
| **Languages** | Python, SQL, C++, C |
| **Frameworks** | LangGraph, LangChain, FastAPI, Pydantic, Streamlit, PyTorch, TensorFlow, Pandas, NumPy |
| **Retrieval & Data** | Qdrant, ChromaDB, FAISS, Cohere, Sentence-Transformers, Hugging Face Transformers, BM25, Solr, SQLite, MySQL |
| **Tools** | Git, GitHub, Postman, Jupyter |

---

## More Projects

| Project | What it does | Tech |
|---|---|---|
| [Dev Tracker](https://github.com/YashAgarwalTheWiz/Fast_API_Dev_Tracker) | Full-stack DSA practice tracker with JWT auth, streak calendar, and progress charts | FastAPI, Streamlit, SQLite |
| [Machine Translation](https://github.com/YashAgarwalTheWiz/Machine_Translation_using_Pytorch) | English-to-French neural machine translation with sequence-to-sequence models | PyTorch, NLP |
| [Image Captioning](https://github.com/YashAgarwalTheWiz/Image_Captioning) | Automatic image caption generation with a CNN-LSTM architecture | PyTorch, Computer Vision |

---

## Let's Connect

I'm open to **AI / GenAI / ML Engineer** roles and happy to relocate. Reach out on [LinkedIn](https://www.linkedin.com/in/yash-agarwal-73a32b230/).
