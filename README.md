# Karan Singh 
**Research Software Engineer | Independent Researcher**

[![ORCID](https://img.shields.io/badge/ORCID-0009--0000--0920--2379-A6CE39?logo=orcid&logoColor=white)](https://orcid.org/0009-0000-0920-2379)
[![GitHub](https://img.shields.io/badge/GitHub-KaranSinghDev-181717?logo=github)](https://github.com/KaranSinghDev)
[![Email](https://img.shields.io/badge/Email-karansingh25822@gmail.com-D14836?logo=gmail&logoColor=white)](mailto:karansingh25822@gmail.com)

I build high-performance infrastructure, distributed systems, and mechanistic interpretability probes for scientific computing and AI safety. My work sits at the intersection of **low-level systems engineering (C++/Go)** and **empirical research (AI/ML)**.

Previously, I was a **Google Summer of Code (2025) Developer for CERN-HSF**, where I engineered benchmarking frameworks for High-Energy Physics (HEP). 

🎯 **Currently Seeking:** 
1. **Funded Master's / Research Assistantship opportunities** (Europe/Canada) in Systems or AI/ML labs.
2. **Paid Research Software Engineer (RSE) or ML Infrastructure roles** globally.

---

## 🔬 AI Safety & Mechanistic Interpretability
*Empirical evaluations and white-box probing of frontier language models.*

| Project | Description | Artifacts |
| :--- | :--- | :--- |
| **[Valence-Lens](https://github.com/KaranSinghDev/Valence-Lens)** | **Independent open-weights valence probe.** Extracts scale-invariant internal valence directions from LLM residual streams. Proves internal signals predict welfare-relevant behavior where self-report fails. | `PyTorch` `Interpretability` |
| **[Loyalty-Lens](https://github.com/KaranSinghDev/Loyalty-Lens)** | **White-box detection of hidden objectives.** Linear activation probes to detect covert, weight-installed political/corporate loyalties in LLMs that evade black-box auditing. | `PyTorch` [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.21759567.svg)](https://doi.org/10.5281/zenodo.21759567) |
| **[StaleBench](https://github.com/KaranSinghDev/StaleBench)** | **RAG Safety Benchmark.** Deterministic evaluation measuring answer freshness, catch-up latency, and silent staleness failures across RAG pipelines. | `Python` [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.20710012.svg)](https://doi.org/10.5281/zenodo.20710012) |
| **[DisElect-Africa](https://github.com/KaranSinghDev/DisElect-Africa)** | **Global South Red-Teaming.** Empirical study auditing LLM generation of election disinformation across African and Western contexts. | `Red-Teaming` `Evaluations` |

---

## ⚙️ Scientific Computing & HPC (CERN / Physics)
*Zero-copy pipelines, hardware-accelerated compute, and physics infrastructure.*

| Project | Description | Artifacts |
| :--- | :--- | :--- |
| **[E-QUEST](https://github.com/KaranSinghDev/E-QUEST)** | **CERN-HSF (GSoC '25).** Hardware-independent benchmarking framework comparing energy draw, memory footprint, and theoretical complexity of PyTorch vs. PennyLane Quantum ML models. | `Quantum ML` `Benchmarking` |
| **[RNTuple-Arrow-Gateway](https://github.com/KaranSinghDev/RNTuple-Arrow-Gateway)** | **Zero-Copy Serialization.** Native C++ gateway bridging CERN ROOT’s RNTuple columnar format with the Apache Arrow ecosystem for high-speed ML ingestion. | `C++17` `Apache Arrow` `ROOT` |
| **[AXON-HLT](https://github.com/KaranSinghDev/AXON-HLT)** | **Sub-7ms Inference.** Adapting CERN’s SONIC architecture on NVIDIA Triton to evaluate GPU offloading and dynamic batching under strict real-time latency budgets. | `NVIDIA Triton` `C++` |
| **[WebROOT_X](https://github.com/KaranSinghDev/WebROOT_X)** | **Client-Side Physics Compute.** Compiling C++17 high-energy physics analysis kernels to WebAssembly (WASM) for zero-server, distributed computing in the browser. | `C++17` `WebAssembly` `CMake` |

---

## 🌩️ Distributed Systems & Cloud-Native Data Engineering
*Fault-tolerant operators, time-series engines, and FAIR-compliant data lakes.*

| Project | Description | Artifacts |
| :--- | :--- | :--- |
| **[Graviton Scheduler](https://github.com/KaranSinghDev/Graviton-Data-Local-Scheduler)** | **Data-Gravity K8s Operator.** Custom Kubernetes Operator (Go) eliminating cross-WAN data transfers in WLCG data lakes by scheduling compute exactly where Rucio storage replicas live. | `Go` `Kubernetes` `KubeBuilder` |
| **[Insight-TSDB](https://github.com/KaranSinghDev/Telemetry-Data-Ecosystem)** | **Hybrid Time-Series Platform.** From-scratch C++17 storage engine (Delta-of-Delta/XOR compression) bridged to a real-time Apache Spark anomaly detection pipeline. | `C++17` `Spark` `Kafka` `Valgrind` |
| **[Distributed-Ops-Hub](https://github.com/KaranSinghDev/Distributed-Operations-Hub)** | **Leaderless KV Store.** Python peer-to-peer cache demonstrating consistent hashing, N-way gRPC replication, and automated CI chaos engineering. | `Python Async` `gRPC` `Chaos-Testing` |
| **[Arkhe Archive](https://github.com/KaranSinghDev/Arkhe-Open-Data-Archive)** | **Self-Hostable Research Archive.** Lightweight, FAIR-compliant scientific data repository handling massive file streams via FastAPI, Postgres, and MinIO. | `FastAPI` `PostgreSQL` [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.20098033.svg)](https://doi.org/10.5281/zenodo.20098033) |

---

## 🛠️ Technical Arsenal

*   **Low-Level & Systems:** C++, C++17, C, WebAssembly (Emscripten), Linux Internals.
*   **Languages:** Python 3 (Asyncio, ctypes), Go (Golang).
*   **AI/ML & Interpretability:** PyTorch, HuggingFace, PennyLane (QML), LangChain.
*   **Cloud-Native & Distributed:** Kubernetes, Docker, gRPC, Apache Kafka, Apache Spark, PostgreSQL, MinIO (S3).
*   **Scientific Tooling:** CERN ROOT, Uproot, Apache Arrow, NVIDIA Triton.
*   **Rigor & CI/CD:** CMake, Valgrind, GoogleTest, GitHub Actions, Chaos Engineering.

> *"I believe in reproducible science, zero-copy data boundaries, and strict memory safety. If it isn't rigorously tested, gracefully degraded, and honestly bounded, it isn't finished."*

---
📫 **Get in touch:** [karansingh25822@gmail.com](mailto:karansingh25822@gmail.com) | I am highly responsive to discussions around research collaborations, RSE positions, or Master's funding.
