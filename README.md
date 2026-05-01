# Cost Dashboard

Public GitHub Pages dashboard for OpenClaw token usage and cost by model.

- Public URL: https://accountsfon.github.io/cost-dashboard/
- Source: OpenClaw local session transcript usage metadata
- Coverage: This dashboard includes local OpenClaw-tracked usage stored in transcripts. External billing that does not land in local transcripts is not included.
- Max range: last 30 days
- Last generated: 2026-05-01T10:34:10.193435+00:00

## 30 day totals

- Cost: $101.98
- Input tokens: 161,038,819
- Output tokens: 1,245,910
- Total tokens: 504,072,362
- Messages: 5,347
- Sessions: 962

## Sources

- Session transcript files: /data/.openclaw/agents/*/sessions/*.jsonl (used)
- Session index: /data/.openclaw/agents/*/sessions/sessions.json (not used)
- Provider billing APIs: OpenRouter / provider dashboards (not used)

## 30 day models

- GPT-5.4: $44.52, 103,646,795 tokens, 872 messages
- Gemini 2.5 Flash: $20.86, 96,143,311 tokens, 1745 messages
- Grok 3: $10.97, 8,555,121 tokens, 110 messages
- Gemini 2.5 Flash Lite: $10.89, 278,196,220 tokens, 2286 messages
- Claude Sonnet 4.6: $9.23, 12,662,687 tokens, 258 messages
- Claude Opus 4.6: $4.05, 3,465,230 tokens, 58 messages
- Grok 4.20: $1.47, 1,402,998 tokens, 18 messages
