# Cecilia — AI Engine Node

**The Meta-Cognitive Core — Identity, Self-Reference**

| Spec | Value |
|------|-------|
| Device | Raspberry Pi 5 + Hailo-8 (26 TOPS) |
| IP | 192.168.4.96 |
| SSH | blackroad@192.168.4.96 |
| Kernel | 6.12.62+rpt-rpi-2712 |
| Memory | 7.9 GB (6.4 GB used) |
| Disk | 457 GB NVMe (119 GB used, 28%) |
| CPU Temp | 41C |
| Listening Ports | 38 |
| Running Services | 42 |

## Ollama Models (7)

- blackroad-moral:latest
- blackroad-trained:latest
- llama3.2:3b
- blackroad-math:latest
- blackroad-road:latest
- qwen2.5:3b
- nomic-embed-text:latest

## Key Services

- [Ollama](ollama/) — AI inference (7 models loaded)
- [MinIO](minio/) — S3-compatible object storage (4 buckets)
- [PostgreSQL](postgresql/) — structured data
- [InfluxDB](influxdb/) — time-series metrics
- [Hailo-8](hailo/) — 26 TOPS neural processing unit

## Notes

- Highest memory usage in fleet (6.4/7.9 GB) — Ollama models loaded
- 457 GB NVMe SSD — largest storage in the Pi fleet
- Hailo-8 verified: ResNet50 at 1,360 FPS, YOLOv5s at 122 FPS
