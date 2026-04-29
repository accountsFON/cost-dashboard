# Cost Dashboard

Public GitHub Pages dashboard for OpenClaw token usage and cost by model.

- Public URL: https://accountsfon.github.io/cost-dashboard/
- Source: OpenClaw local session transcript usage metadata
- Coverage: This dashboard includes local OpenClaw-tracked usage stored in transcripts. External billing that does not land in local transcripts is not included.
- Max range: last 30 days
- Last generated: 2026-04-29T19:33:25.845920+00:00

## 30 day totals

- Cost: $62.39
- Input tokens: 45,345,892
- Output tokens: 1,355,767
- Total tokens: 192,386,332
- Messages: 4,774
- Sessions: 1,018

## Sources

- Session transcript files: /data/.openclaw/agents/*/sessions/*.jsonl (used)
- Session index: /data/.openclaw/agents/*/sessions/sessions.json (not used)
- Provider billing APIs: OpenRouter / provider dashboards (not used)

## 30 day models

- GPT-5.4: $27.97, 55,020,222 tokens, 551 messages
- Grok 3: $10.97, 8,555,121 tokens, 110 messages
- Claude Sonnet 4.6: $9.23, 12,662,687 tokens, 258 messages
- Gemini 2.5 Flash: $5.56, 21,160,288 tokens, 1512 messages
- Claude Opus 4.6: $4.05, 3,465,230 tokens, 58 messages
- Gemini 2.5 Flash Lite: $3.15, 90,119,786 tokens, 2267 messages
- Grok 4.20: $1.47, 1,402,998 tokens, 18 messages
