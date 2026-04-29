# Cost Dashboard

Public GitHub Pages dashboard for OpenClaw token usage and cost by model.

- Public URL: https://accountsfon.github.io/cost-dashboard/
- Source: OpenClaw local session transcript usage metadata
- Coverage: This dashboard includes local OpenClaw-tracked usage stored in transcripts. External billing that does not land in local transcripts is not included.
- Max range: last 30 days
- Last generated: 2026-04-29T03:34:52.623642+00:00

## 30 day totals

- Cost: $80.83
- Input tokens: 23,331,812
- Output tokens: 1,487,297
- Total tokens: 121,243,795
- Messages: 2,400
- Sessions: 595

## Sources

- Session transcript files: /data/.openclaw/agents/*/sessions/*.jsonl (used)
- Session index: /data/.openclaw/agents/*/sessions/sessions.json (not used)
- Provider billing APIs: OpenRouter / provider dashboards (not used)

## 30 day models

- GPT-5.4: $39.20, 66,002,747 tokens, 583 messages
- Grok 3: $21.93, 17,110,242 tokens, 220 messages
- Claude Sonnet 4.6: $9.23, 12,662,687 tokens, 258 messages
- Claude Opus 4.6: $4.69, 3,652,185 tokens, 62 messages
- Grok 4.20: $2.94, 2,805,996 tokens, 36 messages
- Gemini 2.5 Flash: $1.96, 7,330,782 tokens, 492 messages
- Gemini 2.5 Flash Lite: $0.89, 11,679,156 tokens, 749 messages
