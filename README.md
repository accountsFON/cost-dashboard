# Cost Dashboard

Public GitHub Pages dashboard for OpenClaw token usage and cost by model.

- Public URL: https://accountsfon.github.io/cost-dashboard/
- Source: OpenClaw local session transcript usage metadata
- Coverage: This dashboard includes local OpenClaw-tracked usage stored in transcripts. External billing that does not land in local transcripts is not included.
- Max range: last 30 days
- Last generated: 2026-04-29T11:15:22.089796+00:00

## 30 day totals

- Cost: $54.31
- Input tokens: 27,737,415
- Output tokens: 1,390,482
- Total tokens: 109,318,172
- Messages: 2,925
- Sessions: 856

## Sources

- Session transcript files: /data/.openclaw/agents/*/sessions/*.jsonl (used)
- Session index: /data/.openclaw/agents/*/sessions/sessions.json (not used)
- Provider billing APIs: OpenRouter / provider dashboards (not used)

## 30 day models

- GPT-5.4: $23.28, 42,833,409 tokens, 423 messages
- Grok 3: $10.97, 8,555,121 tokens, 110 messages
- Claude Sonnet 4.6: $9.23, 12,662,687 tokens, 258 messages
- Claude Opus 4.6: $4.05, 3,465,230 tokens, 58 messages
- Gemini 2.5 Flash: $3.82, 14,177,042 tokens, 1088 messages
- Gemini 2.5 Flash Lite: $1.50, 26,221,685 tokens, 970 messages
- Grok 4.20: $1.47, 1,402,998 tokens, 18 messages
