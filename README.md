# Awesome LLMOps 

> A curated list of tools, frameworks, and resources for deploying, monitoring, and managing Large Language Models in production.

LLMOps is the practice of operationalizing LLMs — from prompt management and evaluation to deployment, monitoring, and cost optimization. This list focuses on production-ready tools for 2025.

## Contents

- [LLM APIs & Providers](#llm-apis--providers)
- [Orchestration Frameworks](#orchestration-frameworks)
- [RAG Frameworks](#rag-frameworks)
- [Vector Databases](#vector-databases)
- [Prompt Management](#prompt-management)
- [Evaluation & Testing](#evaluation--testing)
- [Hallucination Detection](#hallucination-detection)
- [Observability & Monitoring](#observability--monitoring)
- [Cost Optimization](#cost-optimization)
- [Fine-tuning Platforms](#fine-tuning-platforms)
- [Inference & Serving](#inference--serving)
- [Guardrails & Safety](#guardrails--safety)
- [Agent Frameworks](#agent-frameworks)
- [Data Preparation](#data-preparation)
- [Learning Resources](#learning-resources)

## LLM APIs & Providers

- [OpenAI API](https://platform.openai.com/) - GPT-4o, o1, and embedding models via simple API calls.
- [Anthropic API](https://www.anthropic.com/api) - Claude models with extended context windows up to 200K tokens.
- [Google Vertex AI](https://cloud.google.com/vertex-ai) - Gemini models with multimodal capabilities.
- [AWS Bedrock](https://aws.amazon.com/bedrock/) - Managed service for multiple foundation models including Claude and Llama.
- [Azure OpenAI](https://azure.microsoft.com/en-us/products/ai-services/openai-service) - Enterprise-grade OpenAI models with Azure security.
- [Groq](https://groq.com/) - Ultra-fast inference with custom LPU hardware.
- [Together AI](https://together.ai/) - Open-source model hosting with competitive pricing.
- [Fireworks AI](https://fireworks.ai/) - Fast inference for open-source models.
- [Replicate](https://replicate.com/) - Run open-source models via API.
- [Anyscale](https://www.anyscale.com/) - Scalable Ray-based LLM serving.

## Orchestration Frameworks

- [LangChain](https://github.com/langchain-ai/langchain) - Build LLM applications with chains, agents, and tools. 700+ integrations.
- [LlamaIndex](https://github.com/run-llama/llama_index) - Data framework for connecting LLMs to external data sources.
- [Haystack](https://github.com/deepset-ai/haystack) - End-to-end NLP framework for building production RAG pipelines.
- [Semantic Kernel](https://github.com/microsoft/semantic-kernel) - Microsoft's SDK for integrating LLMs into applications.
- [DSPy](https://github.com/stanfordnlp/dspy) - Framework for programming with foundation models using declarative signatures.
- [LangGraph](https://github.com/langchain-ai/langgraph) - Build stateful, multi-actor LLM applications with cycles and branching.
- [Instructor](https://github.com/jxnl/instructor) - Structured outputs from LLMs using Pydantic.
- [Marvin](https://github.com/prefecthq/marvin) - AI engineering toolkit for building reliable AI applications.
- [Mirascope](https://github.com/Mirascope/mirascope) - LLM toolkit with a focus on simplicity and type safety.

## RAG Frameworks

- [LlamaIndex](https://github.com/run-llama/llama_index) - Comprehensive data framework with 160+ data loaders.
- [Haystack](https://github.com/deepset-ai/haystack) - Modular pipelines for document retrieval and generation.
- [LangChain](https://github.com/langchain-ai/langchain) - Retrieval chains with multiple vector store integrations.
- [RAGatouille](https://github.com/bclavie/RAGatouille) - ColBERT-style late interaction retrieval for better accuracy.
- [Verba](https://github.com/weaviate/Verba) - Open-source RAG application built on Weaviate.
- [txtai](https://github.com/neuml/txtai) - All-in-one embeddings database for semantic search and LLM workflows.
- [Cheshire Cat AI](https://github.com/cheshire-cat-ai/core) - Production-ready framework for conversational AI agents.
- [LLMWare](https://github.com/llmware-ai/llmware) - Enterprise RAG with smaller, specialized models.
- [mem0](https://github.com/mem0ai/mem0) - Memory layer for AI assistants with multi-level architecture.
- [Cognita](https://github.com/truefoundry/cognita) - Open-source RAG framework for production deployments.

## Vector Databases

- [Pinecone](https://www.pinecone.io/) - Fully managed vector database with serverless scaling.
- [Weaviate](https://github.com/weaviate/weaviate) - Open-source vector database with hybrid search capabilities.
- [Milvus](https://github.com/milvus-io/milvus) - Cloud-native vector database built for billion-scale similarity search.
- [Qdrant](https://github.com/qdrant/qdrant) - High-performance vector similarity search with filtering.
- [Chroma](https://github.com/chroma-core/chroma) - Open-source embedding database for AI applications.
- [pgvector](https://github.com/pgvector/pgvector) - Vector similarity search for PostgreSQL.
- [LanceDB](https://github.com/lancedb/lancedb) - Serverless vector database built on Lance format.
- [Vespa](https://github.com/vespa-engine/vespa) - Big data serving engine with vector search and ML inference.
- [Deep Lake](https://github.com/activeloopai/deeplake) - Data lake for AI with vector storage and versioning.
- [Meilisearch](https://github.com/meilisearch/meilisearch) - Lightning-fast search engine with hybrid vector + keyword search.

## Prompt Management

- [Pezzo](https://github.com/pezzolabs/pezzo) - Open-source LLMOps platform for prompt management and versioning.
- [PromptLayer](https://promptlayer.com/) - Track, manage, and share prompts with version control.
- [Humanloop](https://humanloop.com/) - Prompt engineering platform with evaluation and monitoring.
- [Agenta](https://github.com/Agenta-AI/agenta) - Open-source platform for prompt engineering and LLM app development.
- [Promptfoo](https://github.com/promptfoo/promptfoo) - Test and evaluate LLM prompts with CI/CD integration.
- [Portkey](https://portkey.ai/) - AI gateway with prompt management and caching.
- [PromptHub](https://www.prompthub.us/) - Collaborate on prompts with version history and testing.
- [Helicone](https://www.helicone.ai/) - Open-source observability with prompt versioning.
- [Prompty](https://github.com/microsoft/prompty) - Microsoft's asset class for prompts with VS Code integration.

## Evaluation & Testing

- [Promptfoo](https://github.com/promptfoo/promptfoo) - CLI and library for evaluating LLM outputs with assertions.
- [RAGAS](https://github.com/explodinggradients/ragas) - Framework for evaluating RAG pipelines with multiple metrics.
- [DeepEval](https://github.com/confident-ai/deepeval) - Unit testing framework for LLMs with 14+ metrics.
- [Giskard](https://github.com/Giskard-AI/giskard) - Testing framework for ML models including LLMs.
- [TruLens](https://github.com/truera/trulens) - Evaluation and tracking for LLM applications.
- [OpenAI Evals](https://github.com/openai/evals) - Framework for evaluating LLMs and LLM systems.
- [LangSmith](https://smith.langchain.com/) - Platform for debugging, testing, and monitoring LLM apps.
- [Braintrust](https://www.braintrust.dev/) - Enterprise evaluation platform with human labeling.
- [Weights & Biases Weave](https://wandb.ai/site/weave) - LLM evaluation with tracing and scorers.
- [Athina AI](https://athina.ai/) - Evaluation and monitoring platform for production LLMs.

## Hallucination Detection

- [Vectara HHEM](https://github.com/vectara/hallucination-leaderboard) - Hallucination Evaluation Model with leaderboard.
- [SelfCheckGPT](https://github.com/potsawee/selfcheckgpt) - Zero-resource black-box hallucination detection.
- [FActScore](https://github.com/shmsw25/FActScore) - Fine-grained atomic evaluation of factual precision.
- [RAGAS Faithfulness](https://docs.ragas.io/) - Evaluate if response is grounded in retrieved context.
- [TruLens Groundedness](https://github.com/truera/trulens) - Measure how well responses are supported by sources.
- [LangChain Fact Checker](https://python.langchain.com/docs/guides/safety/constitutional_ai) - Chain for verifying factual claims.
- [Guardrails AI](https://github.com/guardrails-ai/guardrails) - Validators for detecting unfaithful content.
- [HaluEval](https://github.com/RUCAIBox/HaluEval) - Benchmark for evaluating hallucination in LLMs.
- [ChainPoll](https://arxiv.org/abs/2310.18344) - High-efficacy hallucination detection method.
- [Open-RAG-Eval](https://github.com/vectara/open-rag-eval) - Open-source RAG evaluation with groundedness metrics.

## Observability & Monitoring

- [LangSmith](https://smith.langchain.com/) - Full-stack observability for LLM applications.
- [Langfuse](https://github.com/langfuse/langfuse) - Open-source LLM engineering platform with tracing.
- [Arize AI](https://arize.com/) - ML observability with LLM-specific dashboards.
- [Weights & Biases](https://wandb.ai/) - Experiment tracking and LLM monitoring.
- [Helicone](https://github.com/Helicone/helicone) - Open-source observability for LLM applications.
- [OpenLIT](https://github.com/openlit/openlit) - OpenTelemetry-native GenAI observability.
- [Datadog LLM Observability](https://www.datadoghq.com/product/llm-observability/) - Production monitoring with hallucination detection.
- [Fiddler AI](https://www.fiddler.ai/) - Explainable AI monitoring for enterprise.
- [Phoenix](https://github.com/Arize-ai/phoenix) - Open-source ML observability for LLM apps.
- [OpenLLMetry](https://github.com/traceloop/openllmetry) - OpenTelemetry-based instrumentation for LLMs.
- [Portkey](https://portkey.ai/) - AI gateway with unified observability.
- [Tokenr](https://tokenr.co) — LLM cost attribution and FinOps for multi-agent systems

## Cost Optimization

- [Portkey AI Gateway](https://github.com/Portkey-AI/gateway) - Route requests to cheapest available model.
- [LiteLLM](https://github.com/BerriAI/litellm) - Unified interface for 100+ LLMs with cost tracking.
- [OpenRouter](https://openrouter.ai/) - Unified API with automatic model fallbacks and pricing.
- [Semantic Cache](https://github.com/zilliztech/GPTCache) - Cache LLM responses to reduce API calls.
- [LLMLingua](https://github.com/microsoft/LLMLingua) - Compress prompts to reduce token usage.
- [vLLM](https://github.com/vllm-project/vllm) - High-throughput serving to maximize GPU utilization.
- [Martian](https://withmartian.com/) - Intelligent model router for cost and latency optimization.
- [Unify](https://unify.ai/) - Route to optimal LLM based on quality, cost, and speed.
- [Not Diamond](https://notdiamond.ai/) - AI model router that learns your preferences.

## Fine-tuning Platforms

- [OpenAI Fine-tuning](https://platform.openai.com/docs/guides/fine-tuning) - Fine-tune GPT models on custom data.
- [Hugging Face AutoTrain](https://huggingface.co/autotrain) - No-code fine-tuning for open-source models.
- [Predibase](https://predibase.com/) - Fine-tune and serve open-source LLMs.
- [Anyscale](https://www.anyscale.com/) - Scale fine-tuning with Ray.
- [Modal](https://modal.com/) - Serverless GPU compute for training and inference.
- [Lamini](https://lamini.ai/) - Enterprise LLM fine-tuning platform.
- [Monster API](https://monsterapi.ai/) - Affordable fine-tuning for Llama and other models.
- [Together AI](https://together.ai/) - Fine-tune open-source models with managed infrastructure.
- [Axolotl](https://github.com/OpenAccess-AI-Collective/axolotl) - Tool for fine-tuning LLMs with various methods.
- [LLaMA-Factory](https://github.com/hiyouga/LLaMA-Factory) - Unified fine-tuning framework for 100+ LLMs.
- [Unsloth](https://github.com/unslothai/unsloth) - Fine-tune LLMs 2x faster with 80% less memory.

## Inference & Serving

- [vLLM](https://github.com/vllm-project/vllm) - High-throughput LLM serving with PagedAttention.
- [TensorRT-LLM](https://github.com/NVIDIA/TensorRT-LLM) - NVIDIA's library for optimized LLM inference.
- [Text Generation Inference](https://github.com/huggingface/text-generation-inference) - Hugging Face's production-ready serving.
- [Ollama](https://github.com/ollama/ollama) - Run LLMs locally with simple CLI.
- [LocalAI](https://github.com/mudler/LocalAI) - OpenAI-compatible local inference server.
- [LMDeploy](https://github.com/InternLM/lmdeploy) - Toolkit for deploying LLMs with quantization.
- [llama.cpp](https://github.com/ggerganov/llama.cpp) - Efficient C/C++ LLM inference.
- [Triton Inference Server](https://github.com/triton-inference-server/server) - NVIDIA's multi-framework serving platform.
- [BentoML](https://github.com/bentoml/BentoML) - Build production-ready AI applications.
- [Ray Serve](https://docs.ray.io/en/latest/serve/index.html) - Scalable model serving with Ray.
- [KServe](https://github.com/kserve/kserve) - Kubernetes-native model serving.
- [SkyPilot](https://github.com/skypilot-org/skypilot) - Run LLMs on any cloud with automatic spot instances.

## Guardrails & Safety

- [Guardrails AI](https://github.com/guardrails-ai/guardrails) - Add structure and validation to LLM outputs.
- [NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails) - NVIDIA's toolkit for controllable AI.
- [LLM Guard](https://github.com/protectai/llm-guard) - Security toolkit for LLM interactions.
- [Rebuff](https://github.com/protectai/rebuff) - Detect and protect against prompt injection.
- [Lakera Guard](https://www.lakera.ai/) - Real-time protection against prompt attacks.
- [Arthur Shield](https://www.arthur.ai/) - Enterprise LLM firewall and monitoring.
- [Patronus AI](https://www.patronus.ai/) - Automated red-teaming and security testing.
- [Cleanlab](https://github.com/cleanlab/cleanlab) - Find and fix data issues in ML datasets.
- [Vigil](https://github.com/deadbits/vigil-llm) - LLM security scanner and prompt injection detection.

## Agent Frameworks

- [AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) - Autonomous AI agent framework.
- [CrewAI](https://github.com/joaomdmoura/crewAI) - Framework for orchestrating role-playing AI agents.
- [AutoGen](https://github.com/microsoft/autogen) - Microsoft's multi-agent conversation framework.
- [LangGraph](https://github.com/langchain-ai/langgraph) - Build stateful agents with cycles and memory.
- [OpenAI Assistants](https://platform.openai.com/docs/assistants) - API for building AI assistants with tools.
- [Anthropic Claude Tools](https://docs.anthropic.com/claude/docs/tool-use) - Function calling and tool use with Claude.
- [AgentGPT](https://github.com/reworkd/AgentGPT) - Deploy autonomous AI agents in browser.
- [BabyAGI](https://github.com/yoheinakajima/babyagi) - AI-powered task management system.
- [SuperAGI](https://github.com/TransformerOptimus/SuperAGI) - Open-source autonomous AI agent framework.
- [Phidata](https://github.com/phidatahq/phidata) - Build AI assistants with memory and knowledge.
- [E2B](https://github.com/e2b-dev/e2b) - Secure cloud runtime for AI agents.

## Data Preparation

- [Unstructured](https://github.com/Unstructured-IO/unstructured) - Extract and transform data from any document format.
- [LlamaHub](https://llamahub.ai/) - Community library of data loaders for LlamaIndex.
- [DocTR](https://github.com/mindee/doctr) - Document text recognition with deep learning.
- [PyMuPDF](https://github.com/pymupdf/PyMuPDF) - Fast PDF processing library.
- [Docling](https://github.com/DS4SD/docling) - Parse documents with layout understanding.
- [Marker](https://github.com/VikParuchuri/marker) - Convert PDFs to markdown for LLM processing.
- [Surya](https://github.com/VikParuchuri/surya) - Accurate OCR and document analysis.
- [MegaParse](https://github.com/QuivrHQ/MegaParse) - Parse any document type optimized for LLMs.
- [Firecrawl](https://github.com/mendableai/firecrawl) - Turn websites into LLM-ready markdown.
- [Crawl4AI](https://github.com/unclecode/crawl4ai) - Web crawler optimized for AI and LLMs.

## Learning Resources

### Courses
- [LLMOps by DeepLearning.AI](https://www.deeplearning.ai/short-courses/llmops/) - Operational skills for deploying LLMs.
- [Building LLM Applications with LangChain](https://www.deeplearning.ai/short-courses/langchain-for-llm-application-development/) - Practical LangChain course.
- [Evaluating and Debugging Generative AI](https://www.deeplearning.ai/short-courses/evaluating-debugging-generative-ai/) - Testing and monitoring LLMs.
- [Full Stack LLM Bootcamp](https://fullstackdeeplearning.com/llm-bootcamp/) - Comprehensive LLM engineering course.

### Books
- [Designing Machine Learning Systems](https://www.oreilly.com/library/view/designing-machine-learning/9781098107956/) - Chip Huyen's guide to ML systems design.
- [Building LLM Apps](https://www.oreilly.com/library/view/building-llm-apps/9781835462317/) - O'Reilly guide to production LLM applications.

### Blogs & Newsletters
- [The Pragmatic Engineer](https://newsletter.pragmaticengineer.com/) - Engineering leadership with AI coverage.
- [Latent Space](https://www.latent.space/) - AI engineering podcast and newsletter.
- [Simon Willison's Blog](https://simonwillison.net/) - Practical LLM insights and experiments.
- [Chip Huyen's Blog](https://huyenchip.com/blog/) - ML systems and LLMOps expertise.
- [Eugene Yan's Blog](https://eugeneyan.com/) - ML systems design and LLM applications.

### Communities
- [r/LocalLLaMA](https://www.reddit.com/r/LocalLLaMA/) - Community for running LLMs locally.
- [r/MachineLearning](https://www.reddit.com/r/MachineLearning/) - ML research and engineering discussions.
- [LangChain Discord](https://discord.gg/langchain) - Community for LangChain users.
- [Hugging Face Discord](https://discord.gg/huggingface) - Open-source ML community.

## Contributing

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
