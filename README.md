# Cost Dashboard

Public GitHub Pages dashboard for OpenClaw token usage and cost by model.

- Public URL: https://accountsfon.github.io/cost-dashboard/
- Source: OpenClaw local session transcript usage metadata
- Coverage: This dashboard includes local OpenClaw-tracked usage stored in transcripts. External billing that does not land in local transcripts is not included.
- Max range: last 30 days
- Last generated: 2026-04-29T11:57:43.172196+00:00

## 30 day totals

- Cost: $54.76
- Input tokens: 29,066,797
- Output tokens: 1,372,689
- Total tokens: 113,575,230
- Messages: 3,004
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
- Gemini 2.5 Flash: $3.96, 14,798,099 tokens, 1125 messages
- Gemini 2.5 Flash Lite: $1.60, 29,085,199 tokens, 1003 messages
- Grok 4.20: $1.47, 1,402,998 tokens, 18 messages
