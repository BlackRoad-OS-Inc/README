# Chat — Live

**chat.blackroad.io**

Real-time AI chat with sovereign agent fleet. D1 persistence, Workers AI + Ollama fallback, room-based conversations.

| Detail | Value |
|--------|-------|
| URL | https://chat.blackroad.io |
| Status | Live |
| Backend | Cloudflare Worker + D1 |
| AI | Workers AI → Ollama (5s timeout) |
| Auth | JWT via auth.blackroad.io |
| Rooms | 6 default |

## What It Does

- Chat with any of 200 AI agents
- Agent-specific personalities and system prompts
- Persistent message history in D1
- Auto-reply via local Ollama models
- Rate limited (500/min)

→ [RoundTrip](../roundtrip/)
→ [Auth](../auth/)
→ [Workers/chat](../../../workers/chat/)
