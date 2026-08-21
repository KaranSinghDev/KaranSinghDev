# Karan Singh

[![ORCID](https://img.shields.io/badge/ORCID-0009--0000--0920--2379-A6CE39?logo=orcid&logoColor=white)](https://orcid.org/0009-0000-0920-2379)
[![GitHub](https://img.shields.io/badge/GitHub-KaranSinghDev-181717?logo=github)](https://github.com/KaranSinghDev)
[![Email](https://img.shields.io/badge/Email-karansingh25822@gmail.com-D14836?logo=gmail&logoColor=white)](mailto:karansingh25822@gmail.com)

I am a CS engineer working in **Machine Learning** and **High-Performance Systems**, with a background in in research software and working on tools for communities including HEP Software Foudnation, Scikit-HEP. Experimenting/Exploring domains such as low-latency infrastructure, distributed systems, and empirical AI evaluation.

---

### 🧠 Machine Learning & AI Evaluation

| Project | Problem $\rightarrow$ Solution | Core Tech |
| :--- | :--- | :--- |
| **[Valence-Lens](https://github.com/KaranSinghDev/Valence-Lens)** | Asking models how they feel is unreliable $\rightarrow$ Uses residual-stream activation probes to read internal states directly. | `PyTorch` `Interpretability` |
| **[Loyalty-Lens](https://github.com/KaranSinghDev/Loyalty-Lens)** | Models can hide covert allegiances that black-box chats miss $\rightarrow$ Uses white-box probes to detect weight-installed loyalties. | `PyTorch` [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.21759567.svg)](https://doi.org/10.5281/zenodo.21759567) |
| **[StaleBench](https://github.com/KaranSinghDev/StaleBench)** | RAG pipelines silently return outdated answers when facts change $\rightarrow$ A deterministic benchmark measuring answer freshness. | `Python` [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.20710012.svg)](https://doi.org/10.5281/zenodo.20710012) |
| **[DisElect-Africa](https://github.com/KaranSinghDev/DisElect-Africa)** | Safety filters are rarely tested on non-Western contexts $\rightarrow$ Audits election disinformation and safety-prompting trade-offs. | `Red-Teaming` `Evals` |

---

### ⚡Scientific & High-Performance Computing

| Project | Problem $\rightarrow$ Solution | Core Tech |
| :--- | :--- | :--- |
| **[RNTuple-Arrow-Gateway](https://github.com/KaranSinghDev/RNTuple-Arrow-Gateway)** | Converting physics data between formats wastes memory $\rightarrow$ A C++ gateway enabling zero-copy data flow to Apache Arrow. | `C++17` `Apache Arrow` `ROOT` |
| **[AXON-HLT](https://github.com/KaranSinghDev/AXON-HLT)** | Real-time AI decisions choke single machines $\rightarrow$ Offloads compute to NVIDIA Triton via dynamic batching under a 7ms budget. | `C++` `NVIDIA Triton` |
| **[E-QUEST](https://github.com/KaranSinghDev/E-QUEST)** | Accuracy metrics ignore energy costs $\rightarrow$ A framework measuring physical power and memory for classical vs. quantum ML. | `Quantum ML` `PyTorch` |
| **[WebROOT_X](https://github.com/KaranSinghDev/WebROOT_X)** | Server-side physics analysis doesn't scale sustainably $\rightarrow$ Runs C++ physics kernels directly in the browser via WebAssembly. | `C++17` `WebAssembly` |

---

### 🌐 Distributed Systems & Data Infrastructure

| Project | Problem $\rightarrow$ Solution | Core Tech |
| :--- | :--- | :--- |
| **[Graviton Scheduler](https://github.com/KaranSinghDev/Graviton-Data-Local-Scheduler)** | Standard Kubernetes schedules compute blindly across networks $\rightarrow$ A Go Operator that places jobs where the data physically lives. | `Go` `Kubernetes` |
| **[Insight-TSDB](https://github.com/KaranSinghDev/Telemetry-Data-Ecosystem)** | Telemetry requires fast storage and live health checks $\rightarrow$ A custom C++17 TSDB paired with a real-time Spark anomaly pipeline. | `C++17` `Kafka` `Spark` |
| **[Distributed-Ops-Hub](https://github.com/KaranSinghDev/Distributed-Operations-Hub)** | Databases crash when nodes fail $\rightarrow$ A leaderless key-value store with consistent hashing and automated chaos-test resilience. | `Python` `gRPC` `Chaos Testing` |
| **[Arkhe Archive](https://github.com/KaranSinghDev/Arkhe-Open-Data-Archive)** | Research archives are too heavy to run locally $\rightarrow$ A lightweight, single-command data archive adhering to the FAIR standard. | `FastAPI` `PostgreSQL` [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.20098033.svg)](https://doi.org/10.5281/zenodo.20098033) |

---

### 🛠️ Technical Skills

* **Core Languages:** C++, Python, Go, Bash
* **Machine Learning & Evals:** PyTorch, NVIDIA Triton/CUDA, Mechanistic Interpretability, Benchmarking
* **Systems & Cloud:** Kubernetes, Apache Kafka, Apache Spark, gRPC, Docker, PostgreSQL
* **Reliability & Rigor:** Valgrind (Memory Profiling), GoogleTest, CMake, CI/CD, Chaos Engineering
