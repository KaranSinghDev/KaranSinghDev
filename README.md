# Karan Singh

**Software Engineer | Distributed Systems & Scientific Computing**

I am a Computer Science graduate working in high-performance computing, distributed infrastructure, and scientific data engineering. Building systems and solutions to be efficient, resilient, and fundamentally well-engineered. 

📫 **Contact:**[karansingh25822@gmail.com](mailto:karansingh25822@gmail.com) | [LinkedIn](#)  
🎓 **ORCID:**[0009-0000-0920-2379](https://orcid.org/0009-0000-0920-2379)  
📚 **Zenodo:** Karan_Singh  

---

### 🚀 Highlights of 2026

**1.[Graviton: Data-Local Kubernetes Scheduler](https://github.com/KaranSinghDev/Graviton-Data-Local-Scheduler)**  
A Kubernetes Operator built to eliminate Wide Area Network (WAN) data transfers in scientific data lakes (like the WLCG). It queries storage topologies (e.g., Rucio) and injects dynamic `NodeAffinity` into batch jobs to ensure compute is co-located with its dataset replicas. 

*Tech: Go, Kubernetes Operator SDK, Rucio, Prometheus.*

**2. [RNArrow Gateway: ROOT-to-Arrow Flight Server](https://github.com/KaranSinghDev/RNTuple-Arrow-Gateway)** `[DOI: 10.5281/zenodo.20034922]`  
A standalone C++17 library and gRPC Flight server bridging CERN's next-generation `RNTuple` binary format with the Apache Arrow ecosystem. Achieves <1.6x overhead over raw C++ reads, exposing Petabyte-scale physics data natively to modern distributed analytic tools.

*Tech: C++17, Apache Arrow, gRPC, pybind11, ROOT.*

**3.[AXON-HLT: Coprocessor Inference Benchmarking](https://github.com/KaranSinghDev/AXON-HLT)** `[DOI: 10.5281/zenodo.20058280]`  
An asynchronous gRPC client simulating High-Level Trigger (HLT) ML pipelines. Validates the performance of "Coprocessors-as-a-Service" architectures by benchmarking dynamic batching on NVIDIA Triton servers, adhering to strict <7ms latency budgets for particle classification.

*Tech: Python (asyncio), NVIDIA Triton Inference Server, PyTorch/ONNX, gRPC.*    
