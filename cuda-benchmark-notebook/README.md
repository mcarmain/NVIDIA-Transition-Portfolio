\# CUDA Benchmark Notebook – GPU vs CPU Performance



\## 📘 Overview

This notebook demonstrates the fundamentals of \*\*GPU-accelerated computing\*\* using CUDA C/C++ and Python.  

It benchmarks matrix multiplication performance on both CPU and GPU to highlight the acceleration achieved by CUDA kernels.


---

## 🧱 Architecture


\## 🎯 Objectives

\- Understand CUDA memory hierarchy (global, shared, local)

\- Write and execute a basic CUDA kernel

\- Compare GPU vs CPU throughput

\- Visualize GPU utilization with Nsight Systems



\## ⚙️ Environment Setup

```bash

\# Install CUDA toolkit and libraries

sudo apt-get install nvidia-cuda-toolkit

conda create -n cuda-bench python=3.10

conda activate cuda-bench

pip install jupyter numpy matplotlib cupy-cuda12x



