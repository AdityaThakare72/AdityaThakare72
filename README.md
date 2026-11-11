## Aditya Thakare

AI Engineer in Pune. I build agent backends and RAG systems in Python: LangGraph, FastAPI, DuckDB, MongoDB.

Most recently, on contract for Neon AI, I took over a legacy LangGraph codebase and shipped the agentic backend of an executive finance dashboard. It runs in production: async FastAPI, DuckDB over Parquet, and Pydantic-validated output on every model call.

### Open source

- [caura-ai/caura-long-run-fleet #43](https://github.com/caura-ai/caura-long-run-fleet/pull/43) (merged): configurable per-agent timeout for the fleet simulator of a platform for long-running agents
- [langchain-ai/langchain-mongodb #487](https://github.com/langchain-ai/langchain-mongodb/pull/487) (open): fixes suffix wildcard matching and limit handling in `MongoDBStore.list_namespaces`
- [langchain-ai/langchain-mongodb #486](https://github.com/langchain-ai/langchain-mongodb/pull/486) (open): fixes index desync for unindexed items in `MongoDBStore.put` and `batch`

### Projects

- [Legal-Agent-v2](https://github.com/AdityaThakare72/Legal-Agent-v2): RAG agent for Indian law that answers with citations. About 70K chunks from 1,000+ acts, hybrid BM25 + vector retrieval with Reciprocal Rank Fusion, a classifier and a reranker. [Live demo](https://legal-agent-i.streamlit.app/)
- [typed-decision-models](https://github.com/AdityaThakare72/typed-decision-models): benchmark of five router options for an agent workflow. A 5 MB XGBoost model matched a 1.6 GB fine-tuned transformer, and both beat a Gemini router by 20+ points on exact match at a fraction of the latency and cost.
- [Research-Agent](https://github.com/AdityaThakare72/Research-Agent): LangGraph multi-agent system (researcher, writer, critic) that loops until the critic's score clears a threshold. [Live demo](https://research-agent-blog.streamlit.app/)
- [Report-Generation-Agent](https://github.com/AdityaThakare72/Report-Generation-Agent): multi-agent system (LangGraph + Gemini) that generates and validates suspicious activity reports for financial compliance
- [Industrial_Equipment_Maintenance](https://github.com/AdityaThakare72/Industrial_Equipment_Maintenance): predictive maintenance with XGBoost, a DVC pipeline, MLflow tracking, a FastAPI service in Docker and GitHub Actions CI. [Live demo](https://industrial-equipment-maintenance.streamlit.app/)
- [agent-harness-demo](https://github.com/AdityaThakare72/agent-harness-demo): a minimal agent harness built in five stages, from a bare model call to tools, permissions and context trimming

### Stack

Python, SQL · LangGraph, LangChain, RAG · FastAPI, Pydantic, asyncio · DuckDB, MongoDB, ChromaDB · PyTorch, XGBoost, scikit-learn · Docker, GitHub Actions, MLflow, DVC

### Contact

[Portfolio](https://adityathakare.vercel.app) · [LinkedIn](https://www.linkedin.com/in/aditya-thakare72/) · adityathakare72@gmail.com

The other repositories on this profile hold code and material from workshops and courses I have run.
