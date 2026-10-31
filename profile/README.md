<p align="center">
  <a href="https://hop-base.com"><img src="https://hop-base.com/assets/hopbase-logo.svg" width="64" alt="HopBase" /></a>
</p>

<h1 align="center">HopBase</h1>

<p align="center"><b>One API for chat, coding, image and video models — built for teams that run AI in production.</b></p>

<p align="center">
  <a href="https://hop-base.com">Website</a> ·
  <a href="https://hop-base.com/models">Model catalog</a> ·
  <a href="https://hop-base.com/pricing">Pricing</a> ·
  <a href="https://hop-base.com/en/docs">Docs</a> ·
  <a href="https://hop-base.com/llms.txt">llms.txt</a>
</p>

---

HopBase is an enterprise AI gateway. Point your OpenAI or Anthropic SDK at one base URL and reach Claude, GPT, Gemini, DeepSeek, Qwen, GLM, Kimi, Grok, Doubao Seed, Kling, Seedance, Seedream, MiniMax and more. Routing, failover, quotas and cost tracking are handled for you.

### Why teams use it

- **Protocol-compatible.** OpenAI Chat Completions, OpenAI Responses and Anthropic Messages. Existing SDKs and coding agents work by changing the base URL.
- **Chat to video on one key.** Text, coding, image generation and async video tasks (Kling, Seedance, MiniMax Hailuo) share one key and one bill.
- **Built for concurrency.** Redundant routing with automatic failover before the first token, so one slow upstream does not take your app down.
- **Cost you can audit.** Per-call cost is returned with every response. Grouped keys, quotas and team usage are available in the console.
- **Docs in five languages.** English, 简体中文, 繁體中文, 日本語 and Español, plus machine-readable `llms.txt` for coding agents.

### Quick start

```bash
curl https://api.hop-base.com/v1/chat/completions \
  -H "Authorization: Bearer $HOPBASE_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{"model": "deepseek-v4.1-flash-1017", "messages": [{"role": "user", "content": "Hello"}]}'
```

Get a key at [api.hop-base.com](https://api.hop-base.com/login). Model availability is scoped to the key, so list it with `GET /v1/models`.

### Works with

[OpenCode](https://hop-base.com/en/docs/tools/opencode) · [Vercel AI SDK](https://hop-base.com/en/docs/tools/vercel-ai-sdk) · [LiteLLM](https://hop-base.com/en/docs/tools/litellm) · [Claude Code](https://hop-base.com/en/docs) · [Dify plugin](https://github.com/victor-zzh/dify-plugin-hopbase)

### Contact

- Support: [support@hop-base.com](mailto:support@hop-base.com)
- Sales and partnerships: [sales@hop-base.com](mailto:sales@hop-base.com)
- Telegram: [@Aaqhop](https://t.me/Aaqhop) · WhatsApp: [+86 152 7358 5970](https://wa.me/8615273585970)
