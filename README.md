# 🚀 LLM Engineering: Roadmap & Reference

A comprehensive guide to building, evaluating, and scaling production-grade LLM applications. This repository serves as a master reference for modern AI engineering, from agentic patterns to cloud-scale infrastructure.

---

## 📑 Table of Contents
* [Tech Stack & Development](#-tech-stack--development)
* [LLM Concepts & Best Practices](#-llm-concepts--best-practices)
* [Evaluation & Benchmarking](#-evaluation--benchmarking)
* [High-Quality RAG](#-high-quality-rag)
* [Observability & Reliability](#-observability--reliability)
* [MLOps & AWS Productionization](#-mlops--aws-productionization)
* [Low-Level Foundations](#-low-level-foundations)

---

## 🛠 Tech Stack & Development

### Languages & Frameworks
* **Languages:** Python, JavaScript
* **Agentic Frameworks:** LangChain, LangGraph, CrewAI, Semantic Kernel, AutoGen, OpenAI SDK, HuggingFace, Amazon Bedrock
* **Protocols:** Model Context Protocol (MCP)

### Data & State
* **Structured I/O:** Pydantic, JSON
* **Communication:** Webhooks, REST API, Async calls
* **Session Management:** Chat history, context window management, Storage (S3/DynamoDB)

### Prototyping Tools
* **UI/Workflow:** Gradio, Streamlit, n8n
* **IDE:** Cursor

---

## 🧠 LLM Concepts & Best Practices

### Agentic Architectures
* **Patterns:** Single-agent vs. Multi-agent systems.
* **Roles:** Planner, Researcher, Retriever, Executor, Reviewer.
* **Orchestration:** Handoffs, supervisor policies, and tool-use (API calling).
* **Memory:** Short-term vs. Long-term memory strategies.

### Prompt Engineering
* **Techniques:** Single-shot, multi-shot, and chain-of-thought prompting.
* **Logic:** Retry mechanisms on failure, idempotency, and backoff strategies.

---

## 📊 Evaluation & Benchmarking

### Model Comparison Criteria
| Metric | Description |
| :--- | :--- |
| **Context Window** | Maximum token limit for input and output. |
| **Inference Cost** | Pricing per 1M tokens (Input/Output). |
| **Performance** | Latency (TTFT) and throughput. |
| **Knowledge Cutoff** | The recency of the training data. |

### Evaluation Frameworks
* **Tools:** Artificial Analysis, Vellum, Scale.com, HuggingFace, Live Bench.
* **Testing:** Human-in-the-loop (HITL), A/B testing, LLM-as-a-judge.
* **Checks:** Guardrails, groundedness, and hallucination detection.

---

## 🔍 High-Quality RAG
* **Pipeline:** Ingestion → Chunking → Embeddings → Indexing → Retrieval.
* **Advanced Patterns:** Graph RAG, Agentic RAG.
* **Vector Databases:** Chroma, FAISS, S3 VectorStore, OpenSearch.
* **Verification:** Precision/Recall metrics and citation generation.

---

## ⚙️ Observability & Reliability
* **Telemetry:** Instrumenting traces, token usage/costs, and latency.
* **Monitoring:** Grafana and CloudWatch dashboards.
* **Optimization:** Prompt caching and rate-limit management.
* **Resilience:** Queueing, proactive drift detection, and degradation monitoring.

---

## ☁️ MLOps & AWS Productionization
* **Compute:** Lambda (Streaming/Webhooks), ECS, EC2, SageMaker (Custom hosting).
* **AWS AI Services:** Bedrock (Agents, Knowledge Bases, Flows).
* **Orchestration:** Step Functions, API Gateway.
* **DevOps:** CI/CD (GitOps), Docker/Kubernetes, Infrastructure-as-Code (IaC), IAM/Secrets management.

---

## 🔬 Low-Level Foundations
* **Tokenization:** Deep dive into how models process text.
* **Quantization:** Reducing model size for efficient inference.
* **Fine-tuning:** Domain-specific model adaptation.

---

