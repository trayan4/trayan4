## Hi there 👋

I'm **Trayan**, an **AI Architect / Senior AI Engineer** — I design and ship production **generative AI** systems.

Most of my work is **solution architecture**: deciding how a multi-agent system is split, where retrieval sits, what the model is *not* allowed to decide, and how the whole thing gets evaluated before anyone trusts it. Then I build it.

If an idea pops into my head, chances are I'll build it and ship it.

## 🛠️ My Tech Stack

**Python** · **SQL** · **Azure** · **Microsoft Foundry** · **RAG** · **LangGraph** · **LangChain** · **Model Context Protocol (MCP)** · **FastAPI**

**Generative AI & Agents** — multi-agent orchestration, **Retrieval-Augmented Generation (RAG)** (hybrid BM25 + vector, reranking), **multimodal RAG**, **MCP** tool/resource servers, prompt engineering, LLM fine-tuning (LoRA), Microsoft Foundry Agents, Copilot Studio, CrewAI, Claude Agent SDK, Power Platform & Power Automate

**LLMOps & Evaluation** — **OpenTelemetry** distributed tracing, **LangSmith**, Application Insights (KQL), **MLflow**, **RAGAS**, OpenEvals, **LLM-as-judge** golden-set harnesses, ROUGE, cost/latency governance, **CI/CD/CT**

**Azure** — AI Foundry, Azure OpenAI, **Azure AI Search**, **Microsoft Fabric**, Cosmos DB, Azure SQL, Databricks, Container Apps, **Azure Functions**, Logic Apps, App Service, Entra ID, Bicep IaC

**ML & Data** — PyTorch, scikit-learn, Hugging Face Transformers, FAISS, Pinecone, Neo4j, PySpark, ETL pipelines, NLP, anomaly detection

**Tooling** — Docker, Git, **GitHub Actions**, Azure DevOps, REST APIs, FastAPI, Flask

I've built over 50+ Azure Function Apps at this point.

## 📂 Projects I'm Proud Of

- **[rti-engine](https://github.com/trayan4/rti-engine)** — a LangGraph reasoning engine that knows when to stop and **ask a human** instead of guessing. *([write-up](https://medium.com/@trayandas/an-ai-that-answers-your-pay-questions-and-knows-when-to-ask-a-human-first-6dc6c4f8cb8d))*
- **[Hybrid RAG from scratch](https://github.com/trayan4/hybrid-rag-from-scratch)** — BM25 ranking and **Reciprocal Rank Fusion** implemented from first principles rather than imported, with FAISS + BGE dense retrieval and a **RAGAS** LLM-as-judge harness measuring faithfulness across retrieval modes.
- **[MARA — Multimodal Agentic Reasoning Assistant](https://github.com/trayan4/MARA-AI-Agent)** — a **LangGraph** multi-agent system coordinating RAG, Vision, Data Analysis and Web Search agents, fanned out in parallel and served over a FastAPI REST API. Hybrid FAISS + BM25 retrieval with cross-encoder reranking. *([write-up](https://medium.com/@trayandas/building-mara-a-multimodal-agentic-reasoning-assistant-with-langgraph-dd837168ab24))*
- **[Autonomous Data Analyst](https://github.com/trayan4/autonomous-data-analyst)** — an eval-first multi-agent **text-to-SQL** system on Azure AI Foundry and LangGraph. *([write-up](https://medium.com/@trayandas/building-an-autonomous-data-analyst-7bfc1adfa123))*
- **[GPT-style language model from scratch](https://github.com/trayan4/llm-from-scratch)** 🚀 — a decoder-only 124M-parameter Transformer in **PyTorch**: BPE tokenizer, multi-head causal self-attention, the training loop, then instruction fine-tuning. No high-level abstractions — a great exercise in understanding how modern LLMs actually work under the hood. *([write-up](https://medium.com/@trayandas/building-a-gpt-style-language-model-from-scratch-in-pytorch-what-i-learned-about-training-llms-82dc0ed938e8))*
- **[Smart Compose system](https://github.com/trayan4/smart_compose_system)** — Gmail-style next-phrase suggestion on a fine-tuned GPT-2, benchmarked for interactive latency against suggestion quality.

## 🎯 What I'm Working On

- **Multimodal, citation-grounded RAG assistants** — text + image questions answered from enterprise document sets, with grounding enforced in code (every citation validated against the retrieved set) rather than trusted to a prompt
- **MCP-based agent architectures** — replacing bespoke per-dataset agents with one agent over **MCP** servers, so schemas load just-in-time and cross-dataset joins become possible
- **Enterprise conversational analytics** — natural-language to T-SQL over **Microsoft Fabric** lakehouses, identity-scoped so every user only ever sees their own rows
- **Governance-first design** — guardrails, PII redaction, human-in-the-loop approval, tiered autonomy, and deciding which steps should not involve a model at all
- **LLMOps** — stage-wise eval harnesses, OpenTelemetry tracing, model tiering for cost control, CI/CD

## ✍️ Where I Write It Up

- 🌐 Portfolio: [trayan4.github.io](https://trayan4.github.io/)
- 📝 Medium: [@trayandas](https://medium.com/@trayandas)

## 📫 How to Reach Me

- 📧 Email: trayandas@gmail.com
- 💼 LinkedIn: [linkedin.com/in/trayan-das](https://linkedin.com/in/trayan-das)

Feel free to connect if you're working on AI agent systems, or just want to chat about agentic workflows!

---

*Currently exploring: Model Context Protocol, Microsoft Foundry agents, and agent evaluation & observability*
