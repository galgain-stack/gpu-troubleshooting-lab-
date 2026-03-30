
# GPU Troubleshooting Lab

## Overview
This repository documents my hands-on work with GPU infrastructure, focusing on diagnostics, monitoring, and troubleshooting in a Linux environment.

The goal of this project is to move beyond basic data center operations and develop a deeper understanding of GPU behavior across hardware, driver, and software layers.

---

## What This Project Covers
- GPU detection and validation (`nvidia-smi`, `lspci`)
- Real-time monitoring (`nvidia-smi dmon`)
- GPU diagnostics using DCGM (`dcgmi diag`)
- Stress testing and performance validation (`gpu-burn`)
- Basic troubleshooting workflows and failure analysis

---

## Lab Environment
- Platform: Vast.ai (cloud GPU instances)
- OS: Ubuntu 22.04
- GPU: NVIDIA RTX 3080 (varies by lab)
- Access: SSH

---

## Troubleshooting Approach
When diagnosing GPU issues, I follow a layered approach:

1. **Hardware Detection**
   - Verify GPU presence using `lspci`

2. **Driver Validation**
   - Confirm driver and CUDA functionality using `nvidia-smi`

3. **Diagnostics**
   - Run health checks using DCGM (`dcgmi diag`)

4. **Stress Testing**
   - Validate stability under load using `gpu-burn`

---

## Labs
Detailed labs are located in the `/labs` directory:
- Baseline GPU validation
- Monitoring and telemetry
- Diagnostics and health checks
- Stress testing

---

## Goal
To build practical, real-world GPU troubleshooting skills relevant to:
- Data center operations
- AI infrastructure
- Hardware reliability and deployment roles

---

## Notes
Additional command breakdowns and learning notes are in the `/notes` directory.
