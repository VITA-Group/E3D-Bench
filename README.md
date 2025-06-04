# E3D-Bench: A Benchmark for End-to-End 3D Geometric Foundation Models

[![Website](https://img.shields.io/badge/Website-e3dbench.github.io-blue)](https://e3dbench.github.io/)
[![arXiv](https://img.shields.io/badge/arXiv-2506.01933-b31b1b)](https://arxiv.org/pdf/2506.01933)


A comprehensive, end‑to‑end benchmark suite for evaluating 3D Geometric Foundation Models (GFMs) on effectiveness, robustness, and efficiency across diverse tasks and data domains.

---

## 🚀 Features

- **Rigorous Effectiveness and Efficiency Evaluation**

- **Five Core Tasks**  
  1. Sparse‑view Depth Estimation  
  2. Monocular Video Depth Estimation  
  3. Multi‑view 3D Reconstruction  
  4. Multi‑view Relative Pose Estimation  
  5. Novel View Synthesis  

- **Diverse Dataset Support**  
  - Standard indoor/outdoor and object‑centric benchmarks  
  - Challenging out‑of‑distribution scenarios (drone footage, dynamic scenes, air‑ground pairs)

- **Reproducible Evaluation Toolkit**  
  - Standardized data loaders and preprocessing  
  - Unified metric implementations (Acc, Comp, NC, PSNR, SSIM, latency, memory)  
  - Automated alignment and scale‑normalization pipelines

- **Modular & Extensible**  
  - Plug‑and‑play support for any feed‑forward or diffusion‑based GFM  
  - Clear APIs for adding new tasks, metrics, or datasets  