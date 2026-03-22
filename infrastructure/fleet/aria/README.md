# Aria — Monitoring Node

**The Interface — Frontend, UX**

| Spec | Value |
|------|-------|
| Device | Raspberry Pi 5 |
| IP | 192.168.4.98 |
| SSH | blackroad@192.168.4.98 |
| Kernel | 6.12.62+rpt-rpi-2712 |
| Memory | 7.9 GB (1.1 GB used) |
| Disk | 29 GB (17 GB used, 62%) |
| CPU Temp | 54C |
| Listening Ports | 29 |
| Running Services | 40 |

## Ollama Models (2)

- qwen2.5:3b
- nomic-embed-text:latest

## Key Services

- [Headscale](headscale/) — self-hosted Tailscale coordinator
- [Cloudflared](cloudflared/) — 18 Cloudflare tunnels
- [nginx](nginx/) — reverse proxy
- [InfluxDB](influxdb/) — time-series metrics

## Notes

- Lowest memory usage (1.1 GB) — monitoring-focused
- Hottest node (54C) — may need better cooling
- Runs Headscale for the entire WireGuard mesh
