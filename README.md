# 🏛️ Enterprise Policy & Compliance Assistant

This notebook runs a full-featured backend + chat UI for ACME Industries' compliance assistant.

### What it does
| Capability | How |
|---|---|
| 📄 Document Q&A (RAG) | Ingest PDF/DOCX/TXT → FAISS vector store → cited answers |
| 🎥 YouTube Q&A | Transcript extraction → LLM synthesis |
| 🌐 Web Search | Tavily live search → synthesised answers with sources |
| 🧠 Multi-turn memory | Per-session history + cross-session summarisation |
| 📊 Telemetry | Tokens, latency, tool calls, errors — every request |

---
**Before running:** Add your API keys to the *Secrets* panel (🔑) in Colab:
- `OPENAI_API_KEY`
- `TAVILY_API_KEY`
- `NGROK_AUTHTOKEN` (free at ngrok.com)

Then **Runtime → Run all**.
