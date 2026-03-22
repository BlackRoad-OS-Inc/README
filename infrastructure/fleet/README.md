# Fleet — 7 Nodes (5/5 Pis Online)

*Last probed: March 22, 2026*

| Node | IP | Temp | Mem Used | Disk | Ports | Services | Ollama | Docker |
|------|----|------|----------|------|-------|----------|--------|--------|
| [Alice](alice/) | .49 | 36C | 543M/3.7G | 68% | 42 | 49 | 6 | 0 |
| [Cecilia](cecilia/) | .96 | 41C | 6.4G/7.9G | 28% | 38 | 42 | 7 | 0 |
| [Octavia](octavia/) | .101 | 34C | 3.0G/7.9G | 55% | 56 | 58 | 24 | 7 |
| [Aria](aria/) | .98 | 54C | 1.1G/7.9G | 62% | 29 | 40 | 2 | 0 |
| [Lucidia](lucidia/) | .38 | 61C | 5.5G/7.9G | 31% | 63 | 49 | 6 | 16 |
| [Gematria](gematria/) | droplet | — | — | — | — | — | 6 | — |
| [Anastasia](anastasia/) | droplet | — | — | — | — | — | 0 | — |

**Totals:** 228 listening ports, 238 services, 51 Ollama models, 23 Docker containers

**Compute:** 2x Hailo-8 = 52 TOPS (Cecilia + Octavia)
**Cost:** $38/month

## Tunnel Links

- Agent assignments: [../../agents/fleet/](../../agents/fleet/)
- Network: [../network/](../network/)
- Architecture: [../../architecture/](../../architecture/)
- NVIDIA benchmarks: [../../research/papers/nvidia-benchmarks/](../../research/papers/nvidia-benchmarks/)
