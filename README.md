# Cost Dashboard

Public GitHub Pages dashboard for OpenClaw token usage and cost by model.

- Public URL: https://accountsfon.github.io/cost-dashboard/
- Source: OpenClaw local session transcript usage metadata
- Coverage: This dashboard includes local OpenClaw-tracked usage stored in transcripts. External billing that does not land in local transcripts is not included.
- Max range: last 30 days
- Last generated: 2026-04-30T04:31:14.290176+00:00

## 30 day totals

- Cost: $72.59
- Input tokens: 61,871,311
- Output tokens: 1,174,603
- Total tokens: 255,905,032
- Messages: 5,310
- Sessions: 1,048

## Sources

- Session transcript files: /data/.openclaw/agents/*/sessions/*.jsonl (used)
- Session index: /data/.openclaw/agents/*/sessions/sessions.json (not used)
- Provider billing APIs: OpenRouter / provider dashboards (not used)

## 30 day models

- GPT-5.4: $35.47, 72,983,766 tokens, 701 messages
- Grok 3: $10.97, 8,555,121 tokens, 110 messages
- Claude Sonnet 4.6: $9.23, 12,662,687 tokens, 258 messages
- Gemini 2.5 Flash: $6.98, 27,453,391 tokens, 1640 messages
- Gemini 2.5 Flash Lite: $4.43, 129,381,839 tokens, 2525 messages
- Claude Opus 4.6: $4.05, 3,465,230 tokens, 58 messages
- Grok 4.20: $1.47, 1,402,998 tokens, 18 messages
