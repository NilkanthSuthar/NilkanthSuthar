# Nilkanth Suthar

AI Engineer who builds things that actually work.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-nilkanthsuthar-blue?style=flat&logo=linkedin)](https://linkedin.com/in/nilkanthsuthar) [![Email](https://img.shields.io/badge/Email-ndsuthar@outlook.com-red?style=flat&logo=gmail)](mailto:ndsuthar@outlook.com) [![Portfolio](https://img.shields.io/badge/Portfolio-nilkanthsuthar.github.io-green?style=flat&logo=google-chrome)](https://nilkanthsuthar.github.io)

---

I spend most of my time building production ML systems and RAG pipelines. Really into multi-agent orchestration with LangChain, making vector databases fast, and figuring out how to make LLMs reliable enough for real use cases.

Also mess around with graph neural networks, distributed systems, PySpark pipelines, microservices architecture, and whatever interesting ML problem shows up. Built everything from COBOL-to-microservice migration tools to multimodal AI systems.

**Currently exploring:** LangGraph for complex agent workflows, Rust for systems programming, and optimizing vector search at scale.

---

## Recent Builds

### [AxiomCode](https://github.com/NilkanthSuthar/AxiomCode)
`Python` `LangGraph` `FastAPI` `Azure OpenAI`

Multi-agent system that generates, tests, and refactors code autonomously. Four specialized agents orchestrated via LangGraph using ReAct and Plan-and-Execute patterns with tool calling, memory, and reflection. Real-time streaming via WebSockets with quality scoring and regression gates.

### [AxiomInsight](https://github.com/NilkanthSuthar/AxiomInsight)
`Python` `LangChain` `Chroma` `Pinecone` `DuckDB`

AI assistant that combines document search with SQL analytics — hybrid retrieval using RAG for unstructured data (Chroma) and natural language to SQL for structured data (DuckDB). GPT-4 query classification, Cohere reranking, and fallback mechanisms when retrieval confidence is low.

### [ResumeFoundry](https://github.com/NilkanthSuthar/ResumeFoundry)
`Next.js` `TypeScript` `Python` `MCP` `Gemini`

Resume management tool I built because I got tired of managing 10 different resume versions manually. Git-based version control, DOCX parsing via JSON-RPC bridge, automated PDF generation with Puppeteer, and MCP integration for AI-assisted editing.

---

## Other Projects

### [Hypergraph Molecular Prediction](https://github.com/NilkanthSuthar/hypergraph-molecular-prediction)
`Python` `PyTorch` `Graph Neural Networks` `Drug Discovery`

Two hypergraph neural network approaches for molecular toxicity prediction. K-clique model uses dense subgraphs with heterogeneous message passing, functional group model uses SMARTS pattern matching. Achieved 0.894 ROC AUC on Tox21 androgen receptor dataset. Includes complete research paper.

### [Distributed File System](https://github.com/NilkanthSuthar/Distributed-File-System)
`C` `TCP/IP` `Sockets` `Systems Programming`

Four-node distributed file system in pure C with custom TCP protocol. Each server manages independent namespace with upload, download, delete, and tar operations. Client routes requests to appropriate nodes. Built from scratch without frameworks to understand low-level networking.

<details>
<summary><strong>More Projects</strong></summary>

### [Social Media Sentiment Analysis](https://github.com/NilkanthSuthar/Social-Media-Sentiment-Analysis)
`Python` `Transformers` `Streamlit` `NLP`

Web-based sentiment analyzer using RoBERTa transformers with automatic language detection and model selection. Extracts readable content from URLs, performs sentence-level sentiment highlighting, and supports batch processing via CSV.

### [B-Rec](https://github.com/NilkanthSuthar/B-Rec)
`React Native` `Flask` `Raspberry Pi` `GrovePi` `IoT`

IoT automation system using NFC tags to trigger GPIO devices on Raspberry Pi. Flask REST API receives NFC commands from mobile app, controls relays/LEDs via GrovePi. Built for accessibility and smart home use cases.

### [Stock Market Prediction](https://github.com/NilkanthSuthar/Stock-Market-Prediction)
`Python` `LSTM` `Time Series` `Deep Learning`

LSTM neural network for financial time series forecasting with data preprocessing, model training, and prediction visualization.

### [greenhabit](https://github.com/NilkanthSuthar/greenhabit)
`Django` `Python` `PostgreSQL`

Web application for tracking sustainable living goals and building an eco-friendly community.

</details>

---

## Tech Stack

**Languages:** Python, TypeScript, JavaScript, C#, SQL, C

**GenAI/LLM:** LangChain, LangGraph, LangSmith, AutoGen, CrewAI, OpenAI, Claude, Gemini, Llama, Hugging Face, MCP

**RAG/Vector:** FAISS, Pinecone, Chroma, Weaviate, BERT embeddings, semantic search

**ML/Data:** PyTorch, TensorFlow, scikit-learn, PySpark, Databricks, Kafka, pandas

**Backend:** FastAPI, Flask, Django, Next.js, Node.js, ASP.NET Core, GraphQL

**Cloud/DevOps:** AWS, Azure, GCP (Vertex AI), Docker, Kubernetes, FluxCD, GitHub Actions, Azure DevOps

**Databases:** PostgreSQL, MongoDB, Redis, Vector DBs

**What I'm actually good at:** Building production RAG systems, multi-agent orchestration, MLOps pipelines, microservices architecture, making LLMs reliable enough for enterprise use
