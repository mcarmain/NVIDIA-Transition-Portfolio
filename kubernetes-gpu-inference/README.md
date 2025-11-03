## 📘 Overview
Demonstrates scalable multi-GPU inference using **Kubernetes**, **Helm**, and **NVIDIA Triton Inference Server**.  
The setup includes auto-scaling, GPU metrics collection, and performance dashboards.

## 🎯 Objectives
- Deploy Triton on GPU-enabled Kubernetes nodes
- Expose REST/gRPC endpoints
- Collect and visualize GPU metrics (Prometheus + Grafana)
- Test scaling under concurrent load

## ⚙️ Setup
```bash
kubectl create namespace triton
helm install triton ./helm -n triton
kubectl get pods -n triton
