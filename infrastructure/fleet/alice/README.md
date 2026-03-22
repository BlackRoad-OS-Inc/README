# Alice — Gateway Node

**The Operator — DevOps, Automation**

| Spec | Value |
|------|-------|
| Device | Raspberry Pi 5 |
| IP | 192.168.4.49 |
| SSH | pi@192.168.4.49 |
| Kernel | 6.1.21-v8+ |
| Memory | 3.7 GB (543 MB used) |
| Disk | 15 GB (9.2 GB used, 68%) |
| CPU Temp | 36C |
| Listening Ports | 42 |
| Running Services | 49 |

## Ollama Models (6)

- blackroad-road:latest
- blackroad-lite:latest
- blackroad-master:latest
- tinyllama:latest
- qwen2.5:3b
- nomic-embed-text:latest

## Key Services

- [nginx](nginx/) — reverse proxy for 37+ sites
- [Pi-hole](pihole/) — DNS filtering and ad blocking
- [PostgreSQL](postgresql/) — structured data
- [Qdrant](qdrant/) — vector database for semantic search
- [Redis](redis/) — cache, sessions, rate limiting

## Tunnel Links

- Agent: [../../../agents/fleet/alice/](../../../agents/fleet/alice/)
- Network: [../../network/](../../network/)
- Fleet overview: [../](../)
