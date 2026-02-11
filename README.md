
# llm engineering

- single agent vs multi-agent


## programming/development/tech stack

- programming langauges: python, javascript
- agentic frameworks: Langchain, LangGraph, CrewAI, Semantic Kernel, AutoGen, OpenAI SDK agents, HuggingFace libraries, Amazon Bedrock
- structured output/input: Pydantic, JSON
- streaming : Webhook, REST API
- session management: history, context of chat, Storage to S3/DynamoDB for each session
- platforms: aws, hugging face
- llms : OpenAI, Gemini, Anthropic, Groq, Grok, ollama, llamma


## llm concepts/best-practices

- evaluation frameworks (guardrails, groundedness, hallucination checks).
- design single/multi-agent architectures
- define agent roles (planner, researcher, retriever, executor, reviewer), 
- toolboxes, 
- handoffs, 
- memory strategy (short/long-term)
- supervisor policies for safe collaboration.
- structured output/input: Pydantic, JSON
- streaming : Webhooks
- prompting: single shot prompting, multi-shot prompting
- session management: history, context of chat, Storage to S3/DynamoDB for each session
- agentic patterns
- tooling, API call
- async calls
- retry mechanism on failing

## model benchmarking, model comparision (choosing a best model at hand)

- artificial analytics, vellum, scale.com, huggingface, live bench
- parameters to compare: 
    - parameters, 
    - context length/window, 
    - inference cost (input & output token cost)
    - pricing
    - latency
    - cutoff
    - library/framework available


## llm evaluation/testing

- llm evaluations, jsonl
- human-in-the-loop review, A/B testing,  
- continuous offline/online evals (Local models, Closed Models, LLM as a judge, Open source models)
- Evaluation: Cost, Token, latency, benchmarking different models

## llm observability

- instrument telemetry (traces, token/cost, latency), 
- build dashboards (Grafana/CloudWatch), 


## operate reliably at scale: 
- implement caching, prompt caching
- rate-limit management, 
- queueing, idempotency, and backoff; 
- proactively detect drift and degradation.

## rapid prototyping

- Gradio, n8n, Streamlit

## build high-quality RAG: 

- implement ingestion, 
- chunking, 
- embeddings, 
- indexing, and 
- retrieval with evaluation (precision/recall, groundedness, hallucination checks), 
- guardrails, and citations.
- graph RAG
- agentic RAG
- vector store (chroma, FAISS, S3 VectorStore)


## Productionize on AWS: 

- leverage services like Bedrock (Agents/Knowledge Bases/Flows) or equivalent LLM platforms, 
- Lambda, API Gateway, S3, DynamoDB, OpenSearch/Vector DB, 
- Step Functions, and CloudWatch for tracing and alerts.
- SageMaker for custom model hosting.
- Streaming : Webhook APIs
- Deployment: lambda, ECS/EC2 

## MLOps/LLMOps: 
- automate CI/CD (GitOps), 
- containerization (Docker/Kubernetes), 
- infra-as-code, secrets/IAM, 
- blue green/rollbacks and data/feature pipelines.

## coding

- cursor

# new

- mcp


## low-level llm 

- tokenizer
- quantization
- finetuning 





