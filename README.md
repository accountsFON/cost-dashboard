# Cost Dashboard

Public GitHub Pages dashboard for OpenClaw token usage and cost by model.

- Public URL: https://accountsfon.github.io/cost-dashboard/
- Source: OpenClaw local session transcript usage metadata
- Coverage: This dashboard includes local OpenClaw-tracked usage stored in transcripts. External billing that does not land in local transcripts is not included.
- Max range: last 30 days
- Last generated: 2026-04-30T00:59:57.188819+00:00

## 30 day totals

- Cost: $67.83
- Input tokens: 54,683,056
- Output tokens: 1,295,219
- Total tokens: 229,724,442
- Messages: 5,305
- Sessions: 1,130

## Sources

- Session transcript files: /data/.openclaw/agents/*/sessions/*.jsonl (used)
- Session index: /data/.openclaw/agents/*/sessions/sessions.json (not used)
- Provider billing APIs: OpenRouter / provider dashboards (not used)

## 30 day models

- GPT-5.4: $31.47, 64,397,739 tokens, 633 messages
- Grok 3: $10.97, 8,555,121 tokens, 110 messages
- Claude Sonnet 4.6: $9.23, 12,662,687 tokens, 258 messages
- Gemini 2.5 Flash: $6.86, 26,598,912 tokens, 1783 messages
- Claude Opus 4.6: $4.05, 3,465,230 tokens, 58 messages
- Gemini 2.5 Flash Lite: $3.79, 112,641,755 tokens, 2445 messages
- Grok 4.20: $1.47, 1,402,998 tokens, 18 messages
