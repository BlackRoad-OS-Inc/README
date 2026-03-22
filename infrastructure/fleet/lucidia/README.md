# Lucidia — Apps Node

**The Dreamer — Reasoning, Vision (kahuna model)**

| Spec | Value |
|------|-------|
| Device | Raspberry Pi 5 |
| IP | 192.168.4.38 |
| SSH | octavia@192.168.4.38 |
| Kernel | 6.12.62+rpt-rpi-2712 |
| Memory | 7.9 GB (5.5 GB used) |
| Disk | 235 GB (69 GB used, 31%) |
| CPU Temp | 61C (HIGH) |
| Listening Ports | 63 |
| Running Services | 49 |
| Load Average | 3.76, 4.68, 5.38 |

## Ollama Models (6)

- blackroad-road:latest
- blackroad-lite:latest
- blackroad-master:latest
- tinyllama:latest
- qwen2.5:3b
- nomic-embed-text:latest

## Docker Containers (16)

- eps — Edge proxy
- bitcoind — Bitcoin node
- road-pdns — PowerDNS authoritative
- road-pdns-admin — PowerDNS admin UI
- road-dns-db — DNS database
- blackroad-gitea — Gitea instance
- roadauth — Auth service
- roadapi — API service
- blackroad-edge-agent — Edge coordination
- blackroad.systems — Fleet status site
- blackroadai.com — AI division site
- blackroad-auth-gateway — Auth gateway
- blackroad-metaverse — RoadWorld metaverse
- blackroad-os — OS dashboard
- blackroad-os-carpool — NATS CarPool
- pi-my-agent-1 — Agent process

## Key Services

- [nginx](nginx/) — reverse proxy for apps
- [PowerDNS](powerdns/) — authoritative DNS (ns2)
- [Ollama](ollama/) — AI inference (6 models)
- [Runners](runners/) — GitHub/Gitea Actions runners

## Notes

- HOTTEST NODE (61C) — high load, needs attention
- Most Docker containers (16) — most apps hosted here
- Most listening ports (63) — highest service density
- Load average 3.76+ — consistently busy
- Bitcoin node running (bitcoind container)
