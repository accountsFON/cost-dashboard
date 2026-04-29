# Cost Dashboard

Public GitHub Pages dashboard for OpenClaw token usage and cost by model.

- Public URL: https://accountsfon.github.io/cost-dashboard/
- Source: OpenClaw local session transcript usage metadata
- Coverage: This dashboard includes local OpenClaw-tracked usage stored in transcripts. External billing that does not land in local transcripts is not included.
- Max range: last 30 days
- Last generated: 2026-04-29T12:24:59.722948+00:00

## 30 day totals

- Cost: $55.50
- Input tokens: 30,239,555
- Output tokens: 1,371,342
- Total tokens: 116,493,791
- Messages: 3,054
- Sessions: 884

## Sources

- Session transcript files: /data/.openclaw/agents/*/sessions/*.jsonl (used)
- Session index: /data/.openclaw/agents/*/sessions/sessions.json (not used)
- Provider billing APIs: OpenRouter / provider dashboards (not used)

## 30 day models

- GPT-5.4: $24.06, 44,303,711 tokens, 440 messages
- Grok 3: $10.97, 8,555,121 tokens, 110 messages
- Claude Sonnet 4.6: $9.23, 12,662,687 tokens, 258 messages
- Claude Opus 4.6: $4.05, 3,465,230 tokens, 58 messages
- Gemini 2.5 Flash: $4.04, 15,122,616 tokens, 1146 messages
- Gemini 2.5 Flash Lite: $1.69, 30,981,428 tokens, 1024 messages
- Grok 4.20: $1.47, 1,402,998 tokens, 18 messages
