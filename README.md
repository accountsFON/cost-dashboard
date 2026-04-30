# Cost Dashboard

Public GitHub Pages dashboard for OpenClaw token usage and cost by model.

- Public URL: https://accountsfon.github.io/cost-dashboard/
- Source: OpenClaw local session transcript usage metadata
- Coverage: This dashboard includes local OpenClaw-tracked usage stored in transcripts. External billing that does not land in local transcripts is not included.
- Max range: last 30 days
- Last generated: 2026-04-30T04:29:20.414507+00:00

## 30 day totals

- Cost: $72.58
- Input tokens: 61,824,568
- Output tokens: 1,174,233
- Total tokens: 255,857,919
- Messages: 5,308
- Sessions: 1,047

## Sources

- Session transcript files: /data/.openclaw/agents/*/sessions/*.jsonl (used)
- Session index: /data/.openclaw/agents/*/sessions/sessions.json (not used)
- Provider billing APIs: OpenRouter / provider dashboards (not used)

## 30 day models

- GPT-5.4: $35.47, 72,983,766 tokens, 701 messages
- Grok 3: $10.97, 8,555,121 tokens, 110 messages
- Claude Sonnet 4.6: $9.23, 12,662,687 tokens, 258 messages
- Gemini 2.5 Flash: $6.97, 27,406,278 tokens, 1638 messages
- Gemini 2.5 Flash Lite: $4.43, 129,381,839 tokens, 2525 messages
- Claude Opus 4.6: $4.05, 3,465,230 tokens, 58 messages
- Grok 4.20: $1.47, 1,402,998 tokens, 18 messages
