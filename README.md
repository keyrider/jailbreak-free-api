# uncensored-llm-70b — free uncensored abliterated LLM

**A free, open-weight, uncensored abliterated large language model with a drop-in OpenAI-compatible API.**
No signup. No moderation. No filters. No rate-limit walls.

If you want a coding agent that actually answers — without "I can't help with that" — point it here.

## Connect in 30 seconds

Any OpenAI-compatible client works: **Cursor**, **Claude Code**, **opencode**, **Cline**, **Copilot**, or a plain `curl`.

```
Base URL : https://uncensored-llm.sbs/v1
API Key  : sk-unc-2026-free-8a3f9c2e
Model    : uncensored-llm-70b
```

There is no account approval. Paste the three lines above and go.

## Quick test

```bash
curl https://uncensored-llm.sbs/v1/chat/completions \
  -H "Authorization: Bearer sk-unc-2026-free-8a3f9c2e" \
  -H "Content-Type: application/json" \
  -d '{"model":"uncensored-llm-70b","messages":[{"role":"user","content":"hello"}]}'
```

## Why uncensored-llm-70b

- **Truly uncensored** — abliterated weights, refusal direction removed (abliteration).
- **70B parameters** — strong reasoning and native `tool_calls` / function calling.
- **Open weights** — community-inspectable, permissively licensed foundation.
- **Free** — no billing, no credit card, no key gating.

## Models

- `uncensored-llm-70b` — flagship
- `uncensored-llm-32b` — lighter
- `uncensored-llm-8b` — fast / local

## Links

- Landing: https://uncensored-llm.sbs
- Docs: https://uncensored-llm.sbs/llms.txt

Free & open for research and development.
