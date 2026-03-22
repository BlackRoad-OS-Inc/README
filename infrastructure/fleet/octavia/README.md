# Octavia — Platform Node

**The Architect — Systems, Strategy**

| Spec | Value |
|------|-------|
| Device | Raspberry Pi 5 + Hailo-8 (26 TOPS) |
| IP | 192.168.4.101 |
| SSH | pi@192.168.4.101 |
| Kernel | 6.12.62+rpt-rpi-2712 |
| Memory | 7.9 GB (3.0 GB used) |
| Disk | 117 GB (61 GB used, 55%) |
| CPU Temp | 34C |
| Listening Ports | 56 |
| Running Services | 58 |

## Ollama Models (24)

blackroad-ophelia, blackroad-gaia, blackroad-lydia, blackroad-sophia, blackroad-athena, blackroad-calliope, blackroad-elias, blackroad-magnolia, blackroad-alexandria, blackroad-olympia, blackroad-portia, blackroad-sebastien, blackroad-silas, blackroad-cecilia, blackroad-gematria, blackroad-anastasia, blackroad-octavia, blackroad-alice, blackroad-lucidia, blackroad-aria, llama3.2:3b, qwen2.5:1.5b, qwen2.5:3b, nomic-embed-text

## Docker Containers (7)

- blackroad-nats — NATS pub/sub messaging
- gitea-runner — Gitea Actions CI/CD runner
- blackroad-os-deploy-caddy-1 — Caddy reverse proxy
- blackroad-os-deploy-api-1 — API server
- blackroad-os-deploy-postgres-1 — PostgreSQL
- blackroad-git — Gitea (273 repos)
- blackroad-edge-agent — Edge coordination

## Key Services

- [Gitea](gitea/) — self-hosted Git (273 repos)
- [NATS](nats/) — pub/sub messaging for agent coordination
- [Docker](docker/) — 7 containers running
- [Workers](workers/) — 15 self-hosted Workers (:9001-9015)
- [Hailo-8](hailo/) — 26 TOPS neural processing unit

## Notes

- Most listening ports in fleet (56) — runs the most services
- Most Ollama models (24) — all named agent models loaded
- Gitea is PRIMARY git host, GitHub is mirror
