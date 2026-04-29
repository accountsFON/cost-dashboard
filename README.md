# Cost Dashboard

Public GitHub Pages dashboard for OpenClaw token usage and cost by model.

- Public URL: https://accountsfon.github.io/cost-dashboard/
- Source: OpenClaw local session transcript usage metadata
- Coverage: This dashboard includes local OpenClaw-tracked usage stored in transcripts. External billing that does not land in local transcripts is not included.
- Max range: last 30 days
- Last generated: 2026-04-29T11:26:08.112985+00:00

## 30 day totals

- Cost: $54.32
- Input tokens: 27,766,733
- Output tokens: 1,392,389
- Total tokens: 109,419,206
- Messages: 2,933
- Sessions: 860

## Sources

- Session transcript files: /data/.openclaw/agents/*/sessions/*.jsonl (used)
- Session index: /data/.openclaw/agents/*/sessions/sessions.json (not used)
- Provider billing APIs: OpenRouter / provider dashboards (not used)

## 30 day models

- GPT-5.4: $23.28, 42,833,409 tokens, 423 messages
- Grok 3: $10.97, 8,555,121 tokens, 110 messages
- Claude Sonnet 4.6: $9.23, 12,662,687 tokens, 258 messages
- Claude Opus 4.6: $4.05, 3,465,230 tokens, 58 messages
- Gemini 2.5 Flash: $3.83, 14,276,583 tokens, 1096 messages
- Gemini 2.5 Flash Lite: $1.50, 26,223,178 tokens, 970 messages
- Grok 4.20: $1.47, 1,402,998 tokens, 18 messages
