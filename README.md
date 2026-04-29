# Cost Dashboard

Public GitHub Pages dashboard for OpenClaw token usage and cost by model.

- Public URL: https://accountsfon.github.io/cost-dashboard/
- Source: OpenClaw local session transcript usage metadata
- Coverage: This dashboard includes local OpenClaw-tracked usage stored in transcripts. External billing that does not land in local transcripts is not included.
- Max range: last 30 days
- Last generated: 2026-04-29T00:28:23.965115+00:00

## 30 day totals

- Cost: $45.29
- Input tokens: 14,184,895
- Output tokens: 1,181,544
- Total tokens: 71,465,877
- Messages: 1,663
- Sessions: 491

## Sources

- Session transcript files: /data/.openclaw/agents/*/sessions/*.jsonl (used)
- Session index: /data/.openclaw/agents/*/sessions/sessions.json (not used)
- Provider billing APIs: OpenRouter / provider dashboards (not used)

## 30 day models

- GPT-5.4: $16.91, 28,731,442 tokens, 260 messages
- Grok 3: $10.97, 8,555,121 tokens, 110 messages
- Claude Sonnet 4.6: $9.23, 12,662,687 tokens, 258 messages
- Claude Opus 4.6: $4.05, 3,465,230 tokens, 58 messages
- Grok 4.20: $1.47, 1,402,998 tokens, 18 messages
- Gemini 2.5 Flash: $1.33, 5,115,823 tokens, 240 messages
- Gemini 2.5 Flash Lite: $0.83, 10,385,122 tokens, 685 messages
- Claude Haiku 4.5: $0.50, 1,147,454 tokens, 34 messages
