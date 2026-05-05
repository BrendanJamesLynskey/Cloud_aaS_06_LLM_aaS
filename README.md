# 🧠 LLM-as-a-Service

Deck **06 of 6** in the [Cloud `*aaS` series](https://github.com/BrendanJamesLynskey/Cloud_aaS_Hub). The managed-AI layer of the cloud — inference providers, embeddings &amp; RAG-as-a-service, agents-as-a-service, fine-tuning APIs, evals / observability / guardrails, MCP server hosting, LLM-specific security, AI compliance, and the cost levers that decide whether your AI feature is profitable.

Companion to the [LLMs hub](https://github.com/BrendanJamesLynskey/LLMs) (umbrella index for AI / agentic content) and [Local LLM Hosting](https://github.com/BrendanJamesLynskey/LLM_Hub_Local_LLM_Hosting) (the self-hosted counterpart).

## ▶ [Open the Presentation](https://brendanjameslynskey.github.io/Cloud_aaS_06_LLM_aaS/)

## 🧭 [Series hub](https://github.com/BrendanJamesLynskey/Cloud_aaS_Hub)

---

## Contents

| # | Topic | Description |
|---|-------|-------------|
| 01 | Title | Prompt → Retrieve → Model → Tool → Eval |
| 02 | Topics | Inference / retrieval / agents / governance / cost |
| 03 | LLMaaS landscape | Five-layer stack diagram (Compute → Inference → Retrieval → Agents/Evals/Guardrails → Application) |
| 04 | Frontier providers | Anthropic / OpenAI / Google / Mistral / xAI / DeepSeek + hyperscaler model gardens |
| 05 | Specialist providers | Together / Fireworks / DeepInfra / Replicate · Groq / Cerebras / SambaNova · image / video / audio specialists |
| 06 | Pricing | Per-token economics, table of major models, what dominates the bill, caching tiers |
| 07 | Latency | TTFT vs throughput across providers, when latency matters, regional routing |
| 08 | Prompt caching | The 10× cost lever — Anthropic / OpenAI / Gemini variants, cache placement, where it fails |
| 09 | Embeddings &amp; vector DBs | Embedding APIs &amp; prices, vector-DB providers, hybrid search, hosted RAG end-to-end |
| 10 | Agents-as-a-Service | Bedrock Agents / Vertex AI Agent Builder / OpenAI Responses / Computer Use / LangGraph Cloud / CrewAI |
| 11 | Fine-tuning APIs | When to / not to fine-tune, cost shape, providers and methods (SFT / DPO / LoRA) |
| 12 | Evals &amp; observability | LangSmith / Langfuse / Helicone / Braintrust / Arize / W&amp;B Weave / Datadog; the three eval types |
| 13 | Guardrails &amp; AI gateways | Bedrock Guardrails, Lakera, NeMo, Cloudflare AI Gateway, Portkey, LiteLLM |
| 14 | MCP server hosting | Cloudflare / Vercel / Pipedream / Composio / Smithery; OAuth for MCP; gateway patterns |
| 15 | LLM-specific security | OWASP LLM Top 10, concrete controls, provider data-handling promises, free-tier traps |
| 16 | Compliance for AI | EU AI Act, ISO 42001, NIST AI RMF, BYOK, model cards, confidential inference |
| 17 | Cost engineering | Five biggest levers, runaway shapes, hard limits |
| 18 | Anti-patterns | Hard-coded providers, frontier-for-everything, untrusted output, no-evals, free-tier production |
| 19 | Summary &amp; series close | Three takeaways, full series recap, companion hubs |

---

## Slide Controls

| Action | Key |
|--------|-----|
| Next / Previous | `→` `←` or swipe |
| Overview | `Esc` |
| Fullscreen | `F` |
| Speaker notes | `S` |
| Export to PDF | append `?print-pdf` to URL, then print |

## Technology

[Reveal.js 4.6](https://revealjs.com) · [highlight.js](https://highlightjs.org) · Playfair Display + DM Sans + JetBrains Mono · inline SVG diagrams. Single self-contained `index.html`.

## See also

- [LLMs hub](https://github.com/BrendanJamesLynskey/LLMs) — umbrella for AI / agentic content
- [Local LLM Hosting](https://github.com/BrendanJamesLynskey/LLM_Hub_Local_LLM_Hosting) — the self-hosted counterpart (vLLM, Ollama, llama.cpp, TGI)
- [Docker for LLMs &amp; Agents](https://github.com/BrendanJamesLynskey/Docker_for_LLMs_and_Agents) — running LLMs in containers
- [RAG &amp; Retrieval Systems](https://github.com/BrendanJamesLynskey/LLM_Hub_RAG_Retrieval) — deeper RAG architecture
- [Agents &amp; Orchestration](https://github.com/BrendanJamesLynskey/LLM_Hub_Agents) — LangGraph and beyond
- [OAuth for MCP](https://github.com/BrendanJamesLynskey/OAuth_for_MCP) — auth for tool-using agents
- [MCP Gateway Playground](https://github.com/BrendanJamesLynskey/MCP_Gateway_Playground) · [MCP Supergateway Playground](https://github.com/BrendanJamesLynskey/MCP_Supergateway_Playground)
- Previous in series: [Cloud_aaS_05_Cloud_Security](https://github.com/BrendanJamesLynskey/Cloud_aaS_05_Cloud_Security)
- Series hub: [Cloud_aaS_Hub](https://github.com/BrendanJamesLynskey/Cloud_aaS_Hub)

## License

Educational use. Code examples provided as-is.
