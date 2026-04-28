# Cost Dashboard

Public GitHub Pages dashboard for OpenClaw token usage and cost by model.

- Public URL: https://accountsfon.github.io/cost-dashboard/
- Source: OpenClaw local session transcript usage metadata
- Coverage: This dashboard includes local OpenClaw-tracked usage stored in transcripts. External billing that does not land in local transcripts is not included.
- Max range: last 30 days
- Last generated: 2026-04-28T13:32:55.147718+00:00

## 30 day totals

- Cost: $41.03
- Input tokens: 10,676,572
- Output tokens: 913,267
- Total tokens: 69,703,992
- Messages: 1,660
- Sessions: 463

## Sources

- Session transcript files: /data/.openclaw/agents/*/sessions/*.jsonl (used)
- Session index: /data/.openclaw/agents/*/sessions/sessions.json (not used)
- Provider billing APIs: OpenRouter / provider dashboards (not used)

## 30 day models

- Grok 3: $10.97, 8,555,121 tokens, 110 messages
- GPT-5.4: $10.93, 20,332,975 tokens, 175 messages
- Claude Sonnet 4.6: $9.23, 12,662,687 tokens, 258 messages
- Claude Opus 4.6: $4.05, 3,465,230 tokens, 58 messages
- Claude Haiku 4.5: $2.61, 11,631,753 tokens, 395 messages
- Grok 4.20: $1.47, 1,402,998 tokens, 18 messages
- Gemini 2.5 Flash: $1.23, 4,758,120 tokens, 205 messages
- Gemini 2.5 Flash Lite: $0.54, 6,895,108 tokens, 441 messages
