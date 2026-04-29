# Cost Dashboard

Public GitHub Pages dashboard for OpenClaw token usage and cost by model.

- Public URL: https://accountsfon.github.io/cost-dashboard/
- Source: OpenClaw local session transcript usage metadata
- Coverage: This dashboard includes local OpenClaw-tracked usage stored in transcripts. External billing that does not land in local transcripts is not included.
- Max range: last 30 days
- Last generated: 2026-04-29T22:06:56.678394+00:00

## 30 day totals

- Cost: $64.57
- Input tokens: 49,393,871
- Output tokens: 1,321,306
- Total tokens: 205,123,561
- Messages: 5,012
- Sessions: 1,077

## Sources

- Session transcript files: /data/.openclaw/agents/*/sessions/*.jsonl (used)
- Session index: /data/.openclaw/agents/*/sessions/sessions.json (not used)
- Provider billing APIs: OpenRouter / provider dashboards (not used)

## 30 day models

- GPT-5.4: $29.24, 58,895,709 tokens, 586 messages
- Grok 3: $10.97, 8,555,121 tokens, 110 messages
- Claude Sonnet 4.6: $9.23, 12,662,687 tokens, 258 messages
- Gemini 2.5 Flash: $6.26, 24,007,030 tokens, 1652 messages
- Claude Opus 4.6: $4.05, 3,465,230 tokens, 58 messages
- Gemini 2.5 Flash Lite: $3.36, 96,134,786 tokens, 2330 messages
- Grok 4.20: $1.47, 1,402,998 tokens, 18 messages
