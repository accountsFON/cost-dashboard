# Cost Dashboard

Public GitHub Pages dashboard for OpenClaw token usage and cost by model.

- Public URL: https://accountsfon.github.io/cost-dashboard/
- Source: OpenClaw local session transcript usage metadata
- Coverage: This dashboard includes local OpenClaw-tracked usage stored in transcripts. External billing that does not land in local transcripts is not included.
- Max range: last 30 days
- Last generated: 2026-05-01T07:45:09.409075+00:00

## 30 day totals

- Cost: $99.29
- Input tokens: 147,761,566
- Output tokens: 1,239,085
- Total tokens: 469,011,437
- Messages: 5,225
- Sessions: 963

## Sources

- Session transcript files: /data/.openclaw/agents/*/sessions/*.jsonl (used)
- Session index: /data/.openclaw/agents/*/sessions/sessions.json (not used)
- Provider billing APIs: OpenRouter / provider dashboards (not used)

## 30 day models

- GPT-5.4: $44.52, 103,646,795 tokens, 872 messages
- Gemini 2.5 Flash: $19.15, 87,283,484 tokens, 1715 messages
- Grok 3: $10.97, 8,555,121 tokens, 110 messages
- Gemini 2.5 Flash Lite: $9.91, 251,995,122 tokens, 2194 messages
- Claude Sonnet 4.6: $9.23, 12,662,687 tokens, 258 messages
- Claude Opus 4.6: $4.05, 3,465,230 tokens, 58 messages
- Grok 4.20: $1.47, 1,402,998 tokens, 18 messages
