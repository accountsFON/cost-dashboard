# Cost Dashboard

Public GitHub Pages dashboard for OpenClaw token usage and cost by model.

- Public URL: https://accountsfon.github.io/cost-dashboard/
- Source: OpenClaw local session transcript usage metadata
- Coverage: This dashboard includes local OpenClaw-tracked usage stored in transcripts. External billing that does not land in local transcripts is not included.
- Max range: last 30 days
- Last generated: 2026-05-01T06:05:05.130688+00:00

## 30 day totals

- Cost: $97.80
- Input tokens: 140,409,598
- Output tokens: 1,218,787
- Total tokens: 450,471,508
- Messages: 5,180
- Sessions: 965

## Sources

- Session transcript files: /data/.openclaw/agents/*/sessions/*.jsonl (used)
- Session index: /data/.openclaw/agents/*/sessions/sessions.json (not used)
- Provider billing APIs: OpenRouter / provider dashboards (not used)

## 30 day models

- GPT-5.4: $44.52, 103,646,795 tokens, 872 messages
- Gemini 2.5 Flash: $18.19, 82,946,056 tokens, 1698 messages
- Grok 3: $10.97, 8,555,121 tokens, 110 messages
- Gemini 2.5 Flash Lite: $9.38, 237,792,621 tokens, 2166 messages
- Claude Sonnet 4.6: $9.23, 12,662,687 tokens, 258 messages
- Claude Opus 4.6: $4.05, 3,465,230 tokens, 58 messages
- Grok 4.20: $1.47, 1,402,998 tokens, 18 messages
