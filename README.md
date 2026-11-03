# Gaurav Joshi 👋

<p align="left">
  <b>Undergraduate in Data Science & Applications @ IIT Madras ('28)</b><br>
  <i>Focus: Machine Learning Foundations · Scalable Systems & Low-Memory Inference · Algorithmic Efficiency</i>
</p>

[![IIT Madras](https://img.shields.io/badge/IIT_Madras-BS_Data_Science-800000?style=flat-square)](https://study.iitm.ac.in)
[![Hardware](https://img.shields.io/badge/Hardware_Lab-RTX_3050_6GB-76B900?style=flat-square&logo=nvidia)](#-local-hardware--benchmarking-lab)
[![GitHub](https://img.shields.io/badge/GitHub-gauravpy3361-181717?style=flat-square&logo=github)](https://github.com/gauravpy3361)

---

### 🔬 Engineering Philosophy & Transparency Framework

I treat software engineering and machine learning as empirical disciplines. To distinguish foundational mastery from high-leverage systems engineering, all my repositories follow an explicit authoring taxonomy:

| Badge | Methodology | Focus & Verification |
| :--- | :--- | :--- |
| ![Hand-Crafted](https://img.shields.io/badge/Authoring-100%25_Hand--Crafted-2ea44f?style=flat-square) | **First Principles** | Written strictly from scratch (CS50P, pure NumPy ML algorithms, custom data structures). No AI generation. |
| ![Hybrid](https://img.shields.io/badge/Authoring-Hybrid_Architecture-0969da?style=flat-square) | **Applied Systems** | System architecture, memory budgets, and async pipeline topology designed by me; kernel drafts pair-programmed with AI agents; verified via `nsys` profiler traces and benchmarks. |

---

### 🚀 Active Systems & Core Focus

- **Low-Memory MoE Inference Engine** *(In Progress · Hybrid Architecture)*:
  - Custom `llama.cpp` fork architected for 6GB VRAM mobile GPUs.
  - Implements **Async CUDA Stream Pipelining**, **VRAM Hot-Cache**, and **Zero-Transfer CPU FFN** for pruned 19B Mixture-of-Experts models.
- **Computer Science Foundations (CS50P)** *(100% Hand-Crafted)*:
  - Complete problem sets and final capstone application developed manually to build rock-solid language mechanics.
- **ML Foundations from Scratch** *(100% Hand-Crafted)*:
  - Pure NumPy implementations of SGD, Decision Trees, PCA/SVD, and backpropagation with mathematical derivations.

---

### 💻 Local Hardware & Benchmarking Lab
- **GPU:** NVIDIA GeForce RTX 3050 Mobile (6GB VRAM, Compute Capability `sm_86`)
- **Host:** 16GB RAM · Single-Channel · Windows 11 / WSL2
- **Toolchain:** MSVC + `nvcc` · C++20 · Python 3.11+ · NVIDIA Nsight Systems (`nsys`)
