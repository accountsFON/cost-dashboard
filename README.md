# Cost Dashboard

Public GitHub Pages dashboard for OpenClaw token usage and cost by model.

- Public URL: https://accountsfon.github.io/cost-dashboard/
- Source: OpenClaw local session transcript usage metadata
- Coverage: This dashboard includes local OpenClaw-tracked usage stored in transcripts. External billing that does not land in local transcripts is not included.
- Max range: last 30 days
- Last generated: 2026-04-29T11:40:29.508553+00:00

## 30 day totals

- Cost: $54.54
- Input tokens: 28,508,221
- Output tokens: 1,383,256
- Total tokens: 112,132,655
- Messages: 2,977
- Sessions: 865

## Sources

- Session transcript files: /data/.openclaw/agents/*/sessions/*.jsonl (used)
- Session index: /data/.openclaw/agents/*/sessions/sessions.json (not used)
- Provider billing APIs: OpenRouter / provider dashboards (not used)

## 30 day models

- GPT-5.4: $23.37, 43,175,205 tokens, 427 messages
- Grok 3: $10.97, 8,555,121 tokens, 110 messages
- Claude Sonnet 4.6: $9.23, 12,662,687 tokens, 258 messages
- Claude Opus 4.6: $4.05, 3,465,230 tokens, 58 messages
- Gemini 2.5 Flash: $3.89, 14,532,835 tokens, 1110 messages
- Gemini 2.5 Flash Lite: $1.57, 28,338,579 tokens, 996 messages
- Grok 4.20: $1.47, 1,402,998 tokens, 18 messages
