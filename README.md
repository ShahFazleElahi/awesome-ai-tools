# Awesome AI Tools

![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg) ![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB) ![Catalog](https://img.shields.io/badge/Tools-63-059669)

A curated directory of AI tools for developers, researchers and creators. Find tools by purpose and deployment model, with direct links to official product sites or documentation.

**63 resources across 8 categories.** No API key or external dependency is required to search the catalog.

## Contents

- [Chat & research](#chat--research)
- [Coding](#coding)
- [Local models](#local-models)
- [APIs & gateways](#apis--gateways)
- [Frameworks & automation](#frameworks--automation)
- [Retrieval & search](#retrieval--search)
- [Evaluation & observability](#evaluation--observability)
- [Images & audio](#images--audio)

## Quick start

Requires Python 3.10+. From the repository root:

```bash
python3 scripts/search.py --list-categories
python3 scripts/search.py "language model"
python3 scripts/search.py --category "Local models" --access Local
python3 scripts/search.py --category Coding --json
python3 -m unittest discover -s tests -v
```

## Reading the catalog

Access describes how the tool is used, not its price or license. Hosted services and APIs may require accounts, payment or usage limits. Local clients may connect to remote providers. Self-hosted tools require infrastructure. Model and software licenses vary. Check official terms before use.

Never upload confidential data without authorization. Review agent commands before execution, verify research citations, and check generated code and outputs.

## Machine-readable data

`data/catalog.json` contains `category`, `name`, `url`, `access` and `description` for each item. Descriptions are original short editorial summaries. The catalog is a starting point, not a ranking or endorsement. External URLs and current plan details have not been exhaustively live-tested.

Selected background references: [Hugging Face local apps](https://huggingface.co/docs/hub/local-apps), [Hugging Face integrations](https://huggingface.co/docs/inference-providers/en/integrations/index), and [MLflow evaluation tools overview](https://mlflow.org/articles/best-open-source-llm-evaluation-tools-2026/).

## Chat & research

| Tool | Access | Use case |
| --- | --- | --- |
| [Alter Ego](https://cloudalterego.cafeboon.com) | Hosted | Shared memory for Claude, ChatGPT, Gemini and MCP chats; logs questions automatically without account instructions, using plain files in your cloud storage. |
| [ChatGPT](https://chatgpt.com/) | Hosted | Conversational writing, coding and analysis; check plan limits. |
| [Claude](https://claude.ai/) | Hosted | Conversational assistant for writing and code. |
| [Gemini](https://gemini.google.com/) | Hosted | Multimodal assistant and document-related workflows. |
| [Perplexity](https://www.perplexity.ai/) | Hosted | Search-assisted answers; verify original sources. |
| [NotebookLM](https://notebooklm.google.com/) | Hosted | Explore and summarize user-supplied sources. |
| [Elicit](https://elicit.com/) | Hosted | Literature discovery and evidence extraction. |
| [Consensus](https://consensus.app/) | Hosted | Search research literature by question. |
| [Semantic Scholar](https://www.semanticscholar.org/) | Hosted | Find research papers and citation relationships. |

## Coding

| Tool | Access | Use case |
| --- | --- | --- |
| [GitHub Copilot](https://github.com/features/copilot) | Hosted | Code suggestions and coding assistance in supported editors. |
| [Cursor](https://cursor.com/) | Hosted | AI-assisted code editor with repository context. |
| [Aider](https://aider.chat/) | Local client | Terminal-based coding with connected language models. |
| [Continue](https://www.continue.dev/) | Local client | Editor coding assistance with configurable models. |
| [Cline](https://cline.bot/) | Local client | Coding agent for editor workflows; review tool approvals. |
| [OpenCode](https://opencode.ai/) | Local client | Terminal coding agent with selectable model providers. |
| [Zed](https://zed.dev/) | Local client | Code editor with optional AI integration. |
| [Tabnine](https://www.tabnine.com/) | Hosted or self-hosted | Code assistance for development teams. |

## Local models

| Tool | Access | Use case |
| --- | --- | --- |
| [Ollama](https://ollama.com/) | Local | Run compatible language models on local hardware. |
| [llama.cpp](https://github.com/ggml-org/llama.cpp) | Local | Inference engine for compatible quantized models. |
| [LM Studio](https://lmstudio.ai/) | Local | Desktop interface for downloading and running models. |
| [Jan](https://jan.ai/) | Local | Desktop AI assistant with local model options. |
| [Open WebUI](https://docs.openwebui.com/) | Self-hosted | Browser interface for local or remote model endpoints. |
| [GPT4All](https://www.nomic.ai/gpt4all) | Local | Desktop local-model chat and document workflows. |
| [vLLM](https://docs.vllm.ai/) | Self-hosted | High-throughput language model serving. |
| [Hugging Face Transformers](https://huggingface.co/docs/transformers/) | Library | Load and use pretrained transformer models. |

## APIs & gateways

| Tool | Access | Use case |
| --- | --- | --- |
| [OpenAI API](https://platform.openai.com/docs/) | API | Integrate language and multimodal models into applications. |
| [Anthropic API](https://docs.anthropic.com/) | API | Integrate Claude models via API. |
| [Gemini API](https://ai.google.dev/) | API | Build applications with Gemini models. |
| [Hugging Face Inference Providers](https://huggingface.co/docs/inference-providers/) | API | Access supported model inference providers. |
| [OpenRouter](https://openrouter.ai/) | API | Route requests across available model providers. |
| [LiteLLM](https://docs.litellm.ai/) | Self-hosted | Unify access to multiple model APIs. |
| [Groq](https://console.groq.com/docs/) | API | Hosted inference for supported models. |
| [Replicate](https://replicate.com/) | API | Run hosted models through an API. |

## Frameworks & automation

| Tool | Access | Use case |
| --- | --- | --- |
| [LangChain](https://docs.langchain.com/) | Library | Compose model calls, tools and retrieval workflows. |
| [LangGraph](https://docs.langchain.com/oss/python/langgraph/overview) | Library | Build stateful model-driven workflows. |
| [LlamaIndex](https://docs.llamaindex.ai/) | Library | Connect application data to language models. |
| [Haystack](https://haystack.deepset.ai/) | Library | Build retrieval and model pipelines. |
| [DSPy](https://dspy.ai/) | Library | Optimize structured language-model programs. |
| [Pydantic AI](https://ai.pydantic.dev/) | Library | Build typed agent workflows in Python. |
| [CrewAI](https://docs.crewai.com/) | Library | Coordinate multiple agents and tasks. |
| [n8n](https://n8n.io/) | Hosted or self-hosted | Connect automation workflows to model APIs. |

## Retrieval & search

| Tool | Access | Use case |
| --- | --- | --- |
| [Qdrant](https://qdrant.tech/) | Hosted or self-hosted | Vector similarity search. |
| [Weaviate](https://weaviate.io/) | Hosted or self-hosted | Vector and hybrid search for retrieval. |
| [Milvus](https://milvus.io/) | Self-hosted | Vector database for similarity search. |
| [Chroma](https://www.trychroma.com/) | Hosted or self-hosted | Embedding storage and retrieval. |
| [pgvector](https://github.com/pgvector/pgvector) | Library | Vector similarity search extension for PostgreSQL. |
| [FAISS](https://github.com/facebookresearch/faiss) | Library | Efficient similarity search over dense vectors. |

## Evaluation & observability

| Tool | Access | Use case |
| --- | --- | --- |
| [Promptfoo](https://www.promptfoo.dev/) | Local client | Test prompts and model behavior against cases. |
| [Ragas](https://docs.ragas.io/) | Library | Evaluate retrieval-augmented generation workflows. |
| [DeepEval](https://docs.confident-ai.com/) | Library | Test language model outputs with evaluation metrics. |
| [Langfuse](https://langfuse.com/) | Hosted or self-hosted | Trace and evaluate model-based applications. |
| [Phoenix](https://phoenix.arize.com/) | Self-hosted | Inspect traces and evaluate model workflows. |
| [MLflow](https://mlflow.org/) | Self-hosted | Track experiments and evaluate machine learning applications. |
| [Inspect AI](https://inspect.aisi.org.uk/) | Library | Define reproducible model evaluation tasks. |
| [lm-evaluation-harness](https://github.com/EleutherAI/lm-evaluation-harness) | Library | Benchmark language models on supported tasks. |

## Images & audio

| Tool | Access | Use case |
| --- | --- | --- |
| [ComfyUI](https://github.com/comfyanonymous/ComfyUI) | Local | Node-based image generation workflows. |
| [Hugging Face Diffusers](https://huggingface.co/docs/diffusers/) | Library | Build diffusion-model inference workflows. |
| [Midjourney](https://www.midjourney.com/) | Hosted | Generate images through a hosted service. |
| [Adobe Firefly](https://firefly.adobe.com/) | Hosted | Generative image and creative workflows. |
| [Whisper](https://github.com/openai/whisper) | Local | Speech recognition using compatible hardware. |
| [faster-whisper](https://github.com/SYSTRAN/faster-whisper) | Library | Optimized Whisper transcription implementation. |
| [ElevenLabs](https://elevenlabs.io/) | Hosted | Speech synthesis; obtain consent for voice use. |
| [Audacity](https://www.audacityteam.org/) | Local | Audio editing with optional AI-related plugins. |

## Contributing

Suggest new tools or corrections via pull requests. See [CONTRIBUTING.md](CONTRIBUTING.md).

## License

MIT for the original catalog text, scripts and documentation. Linked services, models, software and trademarks remain subject to their own terms.

Maintained by Shah Fazle Elahi.
