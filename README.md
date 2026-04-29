# Cost Dashboard

Public GitHub Pages dashboard for OpenClaw token usage and cost by model.

- Public URL: https://accountsfon.github.io/cost-dashboard/
- Source: OpenClaw local session transcript usage metadata
- Coverage: This dashboard includes local OpenClaw-tracked usage stored in transcripts. External billing that does not land in local transcripts is not included.
- Max range: last 30 days
- Last generated: 2026-04-29T11:56:39.197109+00:00

## 30 day totals

- Cost: $54.75
- Input tokens: 29,046,294
- Output tokens: 1,375,205
- Total tokens: 113,557,243
- Messages: 3,003
- Sessions: 872

## Sources

- Session transcript files: /data/.openclaw/agents/*/sessions/*.jsonl (used)
- Session index: /data/.openclaw/agents/*/sessions/sessions.json (not used)
- Provider billing APIs: OpenRouter / provider dashboards (not used)

## 30 day models

- GPT-5.4: $23.49, 43,605,896 tokens, 432 messages
- Grok 3: $10.97, 8,555,121 tokens, 110 messages
- Claude Sonnet 4.6: $9.23, 12,662,687 tokens, 258 messages
- Claude Opus 4.6: $4.05, 3,465,230 tokens, 58 messages
- Gemini 2.5 Flash: $3.95, 14,763,450 tokens, 1123 messages
- Gemini 2.5 Flash Lite: $1.60, 29,101,861 tokens, 1004 messages
- Grok 4.20: $1.47, 1,402,998 tokens, 18 messages
