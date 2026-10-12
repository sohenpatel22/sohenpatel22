# Hi, I'm Sohen

MEng student at the University of Toronto (Data Analytics and Machine Learning). I build agentic and generative AI systems and measure them: retrieval ablations, golden sets, LLM-judge metrics and CI gates, rather than demos alone.

## Selected work

**[Market Research Agent](https://github.com/sohenpatel22/market_research_AI_agent)** ([live demo](https://huggingface.co/spaces/SohenP/Market_Research_Agent))

A LangGraph agent over SEC filings and stock prices with hybrid retrieval, a cross-encoder reranker, trained volatility forecasters, a judge-and-retry loop, Langfuse tracing and an MCP server. The cross-encoder rerank lifted NDCG@6 from 0.44 to 0.56, faithfulness is 0.95 on a 99-question golden set, and cost is about $0.001 per question.

**[Consulting Workplan Agent](https://github.com/sohenpatel22/Consulting-Workplan-Agent)**

A multi-agent system that turns a client brief into a work breakdown structure, RAID log, RACI matrix and weekly status report, with a human-in-the-loop revision cycle and an offline demo mode.

**[ASL Fingerspelling Recognition](https://github.com/sohenpatel22/ASL-Fingerspelling-Recognition)** ([live demo](https://huggingface.co/spaces/SohenP/asl-fingerspelling))

Real-time fingerspelling to text using MediaPipe and a Conformer-Transformer, with CI and a hosted demo.

**[Two-Stage Recommendation System](https://github.com/sohenpatel22/Two-Stage_Recommendation_System-Retrieval_and_LambdaRank_Ranking)**

Retrieval plus LambdaRank re-ranking pipeline on MovieLens 100K, compared against collaborative filtering baselines.

## Stack

**LLM and agents:** LangGraph, RAG (hybrid search and reranking), Langfuse, RAGAS, DeepEval, Pydantic, Claude and OpenAI APIs

**ML:** PyTorch, scikit-learn, Hugging Face, MediaPipe

**Backend and MLOps:** Python, SQL (PostgreSQL, pgvector), FastAPI, Docker, GitHub Actions, MLflow, DVC, pytest

## Find me

[Portfolio](https://sohenpatel.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/sohen-patel) · [Hugging Face](https://huggingface.co/SohenP)
