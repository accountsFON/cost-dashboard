# Cost Dashboard

Public GitHub Pages dashboard for OpenClaw token usage and cost by model.

- Public URL: https://accountsfon.github.io/cost-dashboard/
- Source: OpenClaw local session transcript usage metadata
- Coverage: This dashboard includes local OpenClaw-tracked usage stored in transcripts. External billing that does not land in local transcripts is not included.
- Max range: last 30 days
- Last generated: 2026-04-29T11:29:03.964923+00:00

## 30 day totals

- Cost: $54.49
- Input tokens: 28,307,756
- Output tokens: 1,396,028
- Total tokens: 111,896,134
- Messages: 2,966
- Sessions: 862

## Sources

- Session transcript files: /data/.openclaw/agents/*/sessions/*.jsonl (used)
- Session index: /data/.openclaw/agents/*/sessions/sessions.json (not used)
- Provider billing APIs: OpenRouter / provider dashboards (not used)

## 30 day models

- GPT-5.4: $23.37, 43,175,205 tokens, 427 messages
- Grok 3: $10.97, 8,555,121 tokens, 110 messages
- Claude Sonnet 4.6: $9.23, 12,662,687 tokens, 258 messages
- Claude Opus 4.6: $4.05, 3,465,230 tokens, 58 messages
- Gemini 2.5 Flash: $3.84, 14,311,309 tokens, 1098 messages
- Gemini 2.5 Flash Lite: $1.57, 28,323,584 tokens, 997 messages
- Grok 4.20: $1.47, 1,402,998 tokens, 18 messages
