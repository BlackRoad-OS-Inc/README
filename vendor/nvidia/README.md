# NVIDIA

**Benchmarked against. Zero hardware dependency.**

BlackRoad uses Hailo-8 (52 TOPS) instead of NVIDIA GPUs.

## Benchmark Results

| Metric | BlackRoad | NVIDIA | Advantage |
|--------|-----------|--------|-----------|
| Power efficiency (YOLOv8s) | 64 FPS/Watt | 4 FPS/Watt | 16x |
| 5-Year TCO | $2,133 | $67,102 | 31x (97%) |
| Concurrent containers | 160 | 0 | Total |
| Fault tolerance | 75% on failure | 0% | Total |

NVIDIA wins on raw throughput and training. BlackRoad wins on everything else.

The "Lean Strike" letter to Jensen Huang positions continuity as a post-scaling primitive.

→ [Benchmarks](../../research/papers/nvidia-benchmarks/)
→ [Hardware](../../hardware/hailo-8/)
