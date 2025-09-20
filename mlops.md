# 🤖 MLOps & LLM Engineering

Practical notes and hands-on examples for running ML/LLM workloads in production: serving, pipelines, observability, and cost control.

## 🧱 Serving & Inference

- 🔌 [LiteLLM sample](https://github.com/ngnlx/litellm-sample): lightweight gateway/proxy using the OpenAI-compatible API in front of multiple models/providers (ChatGPT/OpenAI, Azure OpenAI, Google Gemini, AWS Bedrock/Claude, …). This sample is currently configured to run with Azure AI Foundry. Ideal for quick POCs, local dev, cost-aware routing, and swapping models with minimal (or zero) code changes.
