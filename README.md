# Hi, I'm Lucy

Computer Science student at Korea National Open University (KNOU), interested in **Machine Learning Systems and AI Infrastructure**, with a focus on GPU inference, model serving, and performance optimization.

My projects explore the path from model development and native C++ deployment to GPU inference optimization and serving-system research.

---

## Research Interests

- Machine Learning Systems
- GPU Inference and Serving
- ML Systems Performance Optimization
- Scheduling and Resource Management
- Distributed ML Systems

---

## Projects

### Adaptive Batching for GPU Inference Serving — Research Project (In Progress)

Investigating when adaptive batching provides meaningful benefits over static batching under varying request workloads.

**Research Question**

> Under what workload conditions does adaptive batching outperform static batching in GPU inference serving, and what are the resulting trade-offs between tail latency, throughput, and GPU utilization?

Highlights:

- Comparing static and queue-aware adaptive batching policies
- Designing controlled experiments across low, medium, high, and bursty workloads
- Evaluating throughput, P50/P95/P99 latency, and GPU utilization
- Investigating throughput–latency trade-offs in GPU inference serving

Repository:  
https://github.com/lucy980509/adaptive-batching-gpu-inference

---

### GPU Inference Performance Analysis & Optimization

A systematic performance study of GPU inference using ONNX Runtime and CUDA, following a baseline → profile → bottleneck → optimize → re-measure workflow.

Highlights:

- CUDA Execution Provider with ONNX Runtime
- FP32 and FP16 inference analysis
- Batch-size scaling experiments
- GPU profiling with NVIDIA Nsight Systems
- Identification of host-side preprocessing and I/O bottlenecks
- Evaluation of RAM caching and I/O Binding
- Analysis of GPU execution behavior and end-to-end performance

Repository:  
<!-- Add your P2 repository URL here -->

---

### C++ ONNX Runtime Inference Engine

A native C++ inference pipeline for deploying a trained CNN model without Python runtime dependency.

Highlights:

- C++17 inference application
- OpenCV preprocessing pipeline
- ONNX Runtime model execution
- End-to-end inference pipeline
- Python/C++ numerical consistency validation
- CMake build system

Repository:  
https://github.com/lucy980509/wafer-cpp-inference

---

### Wafer Defect Classification Using CNN

A deep learning pipeline for semiconductor wafer defect classification using PyTorch.

Highlights:

- WM-811K wafer map dataset
- CNN model development with PyTorch
- Class imbalance handling using weighted loss
- Train / validation / test evaluation
- Confusion matrix and error analysis
- ONNX model export

Repository:  
https://github.com/lucy980509/wafer-defect-classification

---

## Technical Skills

### Languages

- Python
- C++
- SQL

### Machine Learning & Deployment

- PyTorch
- ONNX
- ONNX Runtime
- OpenCV

### Systems & Performance

- CUDA
- NVIDIA Nsight Systems
- Linux
- CMake
- Git

---

## Current Focus

- GPU inference performance
- ML inference serving
- Batching and scheduling
- Efficient AI infrastructure

---

## Career & Research Direction

I am interested in designing efficient and scalable machine learning systems, particularly GPU inference and serving infrastructure. My current work focuses on understanding and optimizing the trade-offs between latency, throughput, and GPU utilization in ML inference workloads.

---

## Contact

LinkedIn:  
https://www.linkedin.com/in/sumin-sim-836350384/

GitHub:  
https://github.com/lucy980509
