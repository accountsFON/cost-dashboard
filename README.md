# Cost Dashboard

Public GitHub Pages dashboard for OpenClaw token usage and cost by model.

- Public URL: https://accountsfon.github.io/cost-dashboard/
- Source: OpenClaw local session transcript usage metadata
- Coverage: This dashboard includes local OpenClaw-tracked usage stored in transcripts. External billing that does not land in local transcripts is not included.
- Max range: last 30 days
- Last generated: 2026-04-28T05:09:21.958844+00:00

## 30 day totals

- Cost: $34.06
- Input tokens: 6,398,275
- Output tokens: 620,109
- Total tokens: 59,863,088
- Messages: 1,585
- Sessions: 423

## Sources

- Session transcript files: /data/.openclaw/agents/*/sessions/*.jsonl (used)
- Session index: /data/.openclaw/agents/*/sessions/sessions.json (not used)
- Provider billing APIs: OpenRouter / provider dashboards (not used)

## 30 day models

- Grok 3: $10.97, 8,555,121 tokens, 110 messages
- Claude Sonnet 4.6: $9.23, 12,662,687 tokens, 258 messages
- Claude Haiku 4.5: $4.15, 18,996,356 tokens, 667 messages
- Claude Opus 4.6: $4.05, 3,465,230 tokens, 58 messages
- GPT-5.4: $2.99, 7,014,856 tokens, 71 messages
- Grok 4.20: $1.47, 1,402,998 tokens, 18 messages
- Gemini 2.5 Flash: $0.98, 4,044,884 tokens, 174 messages
- Gemini 2.5 Flash Lite: $0.24, 3,720,956 tokens, 229 messages
