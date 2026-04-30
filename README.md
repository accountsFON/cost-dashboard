# Cost Dashboard

Public GitHub Pages dashboard for OpenClaw token usage and cost by model.

- Public URL: https://accountsfon.github.io/cost-dashboard/
- Source: OpenClaw local session transcript usage metadata
- Coverage: This dashboard includes local OpenClaw-tracked usage stored in transcripts. External billing that does not land in local transcripts is not included.
- Max range: last 30 days
- Last generated: 2026-04-30T17:28:05.112343+00:00

## 30 day totals

- Cost: $86.46
- Input tokens: 89,680,254
- Output tokens: 1,165,403
- Total tokens: 354,691,278
- Messages: 5,646
- Sessions: 929

## Sources

- Session transcript files: /data/.openclaw/agents/*/sessions/*.jsonl (used)
- Session index: /data/.openclaw/agents/*/sessions/sessions.json (not used)
- Provider billing APIs: OpenRouter / provider dashboards (not used)

## 30 day models

- GPT-5.4: $44.52, 103,646,795 tokens, 872 messages
- Grok 3: $10.97, 8,555,121 tokens, 110 messages
- Gemini 2.5 Flash: $9.54, 38,803,284 tokens, 1461 messages
- Claude Sonnet 4.6: $9.23, 12,662,687 tokens, 258 messages
- Gemini 2.5 Flash Lite: $6.70, 186,155,163 tokens, 2869 messages
- Claude Opus 4.6: $4.05, 3,465,230 tokens, 58 messages
- Grok 4.20: $1.47, 1,402,998 tokens, 18 messages
