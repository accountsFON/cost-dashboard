# Cost Dashboard

Public GitHub Pages dashboard for OpenClaw token usage and cost by model.

- Public URL: https://accountsfon.github.io/cost-dashboard/
- Source: OpenClaw local session transcript usage metadata
- Coverage: This dashboard includes local OpenClaw-tracked usage stored in transcripts. External billing that does not land in local transcripts is not included.
- Max range: last 30 days
- Last generated: 2026-04-30T01:14:02.724531+00:00

## 30 day totals

- Cost: $68.07
- Input tokens: 55,480,142
- Output tokens: 1,272,980
- Total tokens: 232,718,395
- Messages: 5,315
- Sessions: 1,122

## Sources

- Session transcript files: /data/.openclaw/agents/*/sessions/*.jsonl (used)
- Session index: /data/.openclaw/agents/*/sessions/sessions.json (not used)
- Provider billing APIs: OpenRouter / provider dashboards (not used)

## 30 day models

- GPT-5.4: $31.63, 65,002,370 tokens, 638 messages
- Grok 3: $10.97, 8,555,121 tokens, 110 messages
- Claude Sonnet 4.6: $9.23, 12,662,687 tokens, 258 messages
- Gemini 2.5 Flash: $6.86, 26,695,142 tokens, 1772 messages
- Claude Opus 4.6: $4.05, 3,465,230 tokens, 58 messages
- Gemini 2.5 Flash Lite: $3.87, 114,934,847 tokens, 2461 messages
- Grok 4.20: $1.47, 1,402,998 tokens, 18 messages
