# Cost Dashboard

Public GitHub Pages dashboard for OpenClaw token usage and cost by model.

- Public URL: https://accountsfon.github.io/cost-dashboard/
- Source: OpenClaw local session transcript usage metadata
- Coverage: This dashboard includes local OpenClaw-tracked usage stored in transcripts. External billing that does not land in local transcripts is not included.
- Max range: last 30 days
- Last generated: 2026-04-29T06:54:04.124668+00:00

## 30 day totals

- Cost: $51.01
- Input tokens: 19,902,899
- Output tokens: 1,406,687
- Total tokens: 86,702,267
- Messages: 2,376
- Sessions: 751

## Sources

- Session transcript files: /data/.openclaw/agents/*/sessions/*.jsonl (used)
- Session index: /data/.openclaw/agents/*/sessions/sessions.json (not used)
- Provider billing APIs: OpenRouter / provider dashboards (not used)

## 30 day models

- GPT-5.4: $21.55, 37,684,333 tokens, 359 messages
- Grok 3: $10.97, 8,555,121 tokens, 110 messages
- Claude Sonnet 4.6: $9.23, 12,662,687 tokens, 258 messages
- Claude Opus 4.6: $4.05, 3,465,230 tokens, 58 messages
- Gemini 2.5 Flash: $2.77, 10,022,476 tokens, 826 messages
- Grok 4.20: $1.47, 1,402,998 tokens, 18 messages
- Gemini 2.5 Flash Lite: $0.98, 12,909,422 tokens, 747 messages
