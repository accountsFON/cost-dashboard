# Cost Dashboard

Public GitHub Pages dashboard for OpenClaw token usage and cost by model.

- Public URL: https://accountsfon.github.io/cost-dashboard/
- Source: OpenClaw local session transcript usage metadata
- Coverage: This dashboard includes local OpenClaw-tracked usage stored in transcripts. External billing that does not land in local transcripts is not included.
- Max range: last 30 days
- Last generated: 2026-04-29T12:22:10.075485+00:00

## 30 day totals

- Cost: $55.15
- Input tokens: 29,697,779
- Output tokens: 1,369,735
- Total tokens: 114,757,928
- Messages: 3,031
- Sessions: 882

## Sources

- Session transcript files: /data/.openclaw/agents/*/sessions/*.jsonl (used)
- Session index: /data/.openclaw/agents/*/sessions/sessions.json (not used)
- Provider billing APIs: OpenRouter / provider dashboards (not used)

## 30 day models

- GPT-5.4: $23.77, 43,953,473 tokens, 436 messages
- Grok 3: $10.97, 8,555,121 tokens, 110 messages
- Claude Sonnet 4.6: $9.23, 12,662,687 tokens, 258 messages
- Claude Opus 4.6: $4.05, 3,465,230 tokens, 58 messages
- Gemini 2.5 Flash: $4.03, 15,087,954 tokens, 1144 messages
- Gemini 2.5 Flash Lite: $1.63, 29,630,465 tokens, 1007 messages
- Grok 4.20: $1.47, 1,402,998 tokens, 18 messages
