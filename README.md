# Cost Dashboard

Public GitHub Pages dashboard for OpenClaw token usage and cost by model.

- Public URL: https://accountsfon.github.io/cost-dashboard/
- Source: OpenClaw local session transcript usage metadata
- Coverage: This dashboard includes local OpenClaw-tracked usage stored in transcripts. External billing that does not land in local transcripts is not included.
- Max range: last 30 days
- Last generated: 2026-04-29T15:39:03.125944+00:00

## 30 day totals

- Cost: $58.05
- Input tokens: 35,449,600
- Output tokens: 1,364,816
- Total tokens: 130,992,585
- Messages: 3,318
- Sessions: 957

## Sources

- Session transcript files: /data/.openclaw/agents/*/sessions/*.jsonl (used)
- Session index: /data/.openclaw/agents/*/sessions/sessions.json (not used)
- Provider billing APIs: OpenRouter / provider dashboards (not used)

## 30 day models

- GPT-5.4: $25.57, 48,415,768 tokens, 485 messages
- Grok 3: $10.97, 8,555,121 tokens, 110 messages
- Claude Sonnet 4.6: $9.23, 12,662,687 tokens, 258 messages
- Gemini 2.5 Flash: $4.77, 18,069,671 tokens, 1334 messages
- Claude Opus 4.6: $4.05, 3,465,230 tokens, 58 messages
- Gemini 2.5 Flash Lite: $2.00, 38,421,110 tokens, 1055 messages
- Grok 4.20: $1.47, 1,402,998 tokens, 18 messages
