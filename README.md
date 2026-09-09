

## About Me

Computer Science student at **Korea National Open University (KNOU)** interested in **Machine Learning Systems and AI Infrastructure**, with a focus on **GPU inference, model serving, batching, scheduling, and performance optimization**.

My projects explore the path from model development and native C++ deployment to GPU inference optimization and serving-system research.

---

## Research Interests

- Machine Learning Systems
- GPU Inference & Model Serving
- Batching & Scheduling
- Performance Optimization
- Distributed ML Systems
- Resource Management for AI Workloads

---

## Featured Projects

### Adaptive Batching for GPU Inference Serving
**Research Project · In Progress**

Investigating when adaptive batching provides meaningful benefits over static batching under varying request workloads.

**Research Question**

> Under what workload conditions does adaptive batching outperform static batching in GPU inference serving, and what are the resulting trade-offs between tail latency, throughput, and GPU utilization?

**Highlights**

- Comparing static and queue-aware adaptive batching policies
- Designing controlled experiments across low, medium, high, and bursty workloads
- Measuring throughput, P50/P95/P99 latency, and GPU utilization
- Analyzing throughput–latency trade-offs under different workload conditions

[View Repository →](https://github.com/lucy980509/adaptive-batching-gpu-inference)

---

### GPU Inference Performance Analysis & Optimization

A systematic performance study of GPU inference using **ONNX Runtime and CUDA**, following a baseline → profile → bottleneck → optimize → re-measure workflow.

**Highlights**

- CUDA Execution Provider with ONNX Runtime
- FP32 and FP16 inference analysis
- Batch-size scaling experiments
- GPU profiling with NVIDIA Nsight Systems
- Identification of host-side preprocessing and I/O bottlenecks
- Evaluation of RAM caching and I/O Binding
- Analysis of GPU execution behavior and end-to-end performance

[View Repository →](https://github.com/lucy980509/wafer-defect-inference-cuda)

---

### C++ ONNX Runtime Inference Engine

A native **C++17 inference pipeline** for deploying a trained CNN model without a Python runtime dependency.

**Highlights**

- Native C++17 inference application
- OpenCV preprocessing pipeline
- ONNX Runtime model execution
- End-to-end inference workflow
- Python/C++ numerical consistency validation
- CMake-based build system

[View Repository →](https://github.com/lucy980509/wafer-cpp-inference)

---

### Wafer Defect Classification Using CNN

A deep learning pipeline for semiconductor wafer defect classification using **PyTorch**.

**Highlights**

- WM-811K wafer map dataset
- CNN model development with PyTorch
- Class imbalance handling using weighted loss
- Train / validation / test evaluation
- Confusion matrix and error analysis
- ONNX model export for downstream deployment

[View Repository →](https://github.com/lucy980509/wafer-defect-classification)

---

## 🛠 Technical Skills

### Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

### Machine Learning & Deployment

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=for-the-badge&logo=onnx&logoColor=white)
![ONNX Runtime](https://img.shields.io/badge/ONNX%20Runtime-222222?style=for-the-badge)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)

### Systems & Performance

![CUDA](https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![NVIDIA Nsight](https://img.shields.io/badge/NVIDIA%20Nsight-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

## Current Research Focus

I am currently exploring efficient GPU inference serving, with particular interest in how **batching, scheduling, workload characteristics, and system bottlenecks** affect:

- Throughput
- Tail latency
- GPU utilization
- Resource efficiency

My long-term goal is to work on **efficient and scalable ML infrastructure**, especially systems for large-scale model inference and serving.

---

## Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sumin%20Sim-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sumin-sim-836350384/)

[![GitHub](https://img.shields.io/badge/GitHub-lucy980509-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/lucy980509)

---

## Contributions

![3D Contribution Graph](./profile-3d-contrib/profile-night-green.svg)
