# Cost Dashboard

Public GitHub Pages dashboard for OpenClaw token usage and cost by model.

- Public URL: https://accountsfon.github.io/cost-dashboard/
- Source: OpenClaw local session transcript usage metadata
- Coverage: This dashboard includes local OpenClaw-tracked usage stored in transcripts. External billing that does not land in local transcripts is not included.
- Max range: last 30 days
- Last generated: 2026-04-29T11:18:03.962303+00:00

## 30 day totals

- Cost: $54.29
- Input tokens: 27,684,874
- Output tokens: 1,388,467
- Total tokens: 109,286,001
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
- Gemini 2.5 Flash: $3.80, 14,159,804 tokens, 1089 messages
- Gemini 2.5 Flash Lite: $1.50, 26,206,752 tokens, 969 messages
- Grok 4.20: $1.47, 1,402,998 tokens, 18 messages
