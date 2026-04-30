# Cost Dashboard

Public GitHub Pages dashboard for OpenClaw token usage and cost by model.

- Public URL: https://accountsfon.github.io/cost-dashboard/
- Source: OpenClaw local session transcript usage metadata
- Coverage: This dashboard includes local OpenClaw-tracked usage stored in transcripts. External billing that does not land in local transcripts is not included.
- Max range: last 30 days
- Last generated: 2026-04-30T08:04:01.908313+00:00

## 30 day totals

- Cost: $76.90
- Input tokens: 67,780,005
- Output tokens: 1,094,966
- Total tokens: 288,536,116
- Messages: 5,343
- Sessions: 979

## Sources

- Session transcript files: /data/.openclaw/agents/*/sessions/*.jsonl (used)
- Session index: /data/.openclaw/agents/*/sessions/sessions.json (not used)
- Provider billing APIs: OpenRouter / provider dashboards (not used)

## 30 day models

- GPT-5.4: $39.15, 84,936,072 tokens, 773 messages
- Grok 3: $10.97, 8,555,121 tokens, 110 messages
- Claude Sonnet 4.6: $9.23, 12,662,687 tokens, 258 messages
- Gemini 2.5 Flash: $6.92, 27,231,592 tokens, 1504 messages
- Gemini 2.5 Flash Lite: $5.12, 150,282,416 tokens, 2622 messages
- Claude Opus 4.6: $4.05, 3,465,230 tokens, 58 messages
- Grok 4.20: $1.47, 1,402,998 tokens, 18 messages
