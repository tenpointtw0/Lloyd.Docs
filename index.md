---
layout: default
title: Home
---

# Lloyd Chess Engine - Performance Benchmarks

## 🏆 Latest Benchmark Results

| Timestamp | Total Nodes Searched | Total Time | Average Performance (nodes/s) |
|-----------|---------------------|------------|-------------------------------|
| **[2025-09-21 14:39:23](Benchmark/SearchEnginePerformance_20250921_143923_release_03d2244.md)** | 9,464,367 | 4,999 ms | **1,893,252** |

## 📈 Performance Trends

### Nodes per Second Over Time
- **v0.1 (03d2244)**: 1,893,252 nodes/s

*More historical data will be added as new benchmarks are generated.*

## 🔧 Test Environment

The benchmarks are run using a standardized methodology to ensure reliable and comparable results:

- **Extended Warmup**: 5 warmup runs to stabilize performance
- **Multiple Runs**: 3 measurement runs per position  
- **Best Result Selection**: Reports the highest nodes/s result
- **GC Management**: Forces garbage collection before measurements
- **System Stabilization**: Delays between runs for CPU stability

## 📁 Repository Structure

```
Lloyd.Docs/
├── README.md                 # This landing page
└── Benchmark/               # Benchmark report files
    └── SearchEnginePerformance_YYYYMMDD_HHMMSS_release_COMMIT.md
