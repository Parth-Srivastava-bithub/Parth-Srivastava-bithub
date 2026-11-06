# Hi, I'm Parth Srivastava 👋

### AI/ML Engineer | Distributed Model Serving | Open Source Contributor

[![Portfolio](https://img.shields.io/badge/Portfolio-parthml.in-00E5FF?style=for-the-badge&logo=googlechrome&logoColor=black)](https://parthml.in)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/parth-srivastava-dsuser)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Parth-Srivastava-bithub)
[![LeetCode](https://img.shields.io/badge/LeetCode-Profile-FFA116?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/foresty)

---

I build production-grade **AI Agents**, scalable **RAG architectures**, and high-throughput **LLM inference systems**. Experienced in multi-cloud GPU orchestration, low-latency model serving with vLLM, and contributing upstream fixes to enterprise agent frameworks.

Currently working as an **AI/ML Engineer at 4Way Technologies**, deploying 20+ models on cloud GPU platforms and engineering real-time streaming data pipelines.

---

## 🚀 Flagship Projects

### ⚡ [Modeva Engine](https://parthml.in) — Autonomous Multi-Cloud GPU Orchestrator

*Unified multi-cloud control plane aggregating real-time GPU spot pricing, datacenter inventory, and persistent storage across RunPod, Novita AI, and Vast.ai.*

- Built an autonomous conversational assistant with **recursive backward-chaining stack planning (LIFO)** and real-time **SSE telemetry**.
- Integrated enterprise security using **AES-256-GCM encrypted vaults** and live spot price telemetry ($0.19/hr RTX 4090).
- **Stack:** `FastAPI` `LangChain` `Groq` `PostgreSQL` `MongoDB Atlas` `Docker` `SQLAlchemy` `SSE`

---

### 🧬 Qwen2.5 LLM Fine-Tuning Pipeline

*End-to-end full fine-tuning & QLoRA pipeline optimized on RunPod GPUs for high-precision structured JSON extraction.*

- Generated and curated a 10K+ synthetic instruction dataset with custom loss label masking (`-100`).
- Model packaged and served with vLLM for high-concurrency, low-latency inference.
- **Stack:** `PyTorch` `Hugging Face PEFT` `QLoRA` `vLLM` `RunPod`

---

### 📊 GenData — Synthetic Data Generator

*Multi-agent synthetic dataset synthesis engine with outlier preservation and automated EDA.*

- Directed by **LangGraph workflows** and Groq LLaMA 70B, pairing LLM generation with **SDV TVAE** tabular synthesis.
- Enforces strict Pydantic schema validation for production-grade reliability.
- **Stack:** `LangGraph` `Groq LLaMA 70B` `SDV TVAE` `Pydantic` `Python`

---

### 🎙️ Say — Real-Time Voice-to-Voice AI Agent

*Ultra-low-latency bidirectional voice conversational agent.*

- Integrated **Sarvam AI STT**, **Groq LLaMA 3.3 70B**, and fast TTS synthesis pipeline.
- Containerized with Docker and deployed for real-time streaming interactions on Railway.
- **Stack:** `FastAPI` `Groq LLaMA 3.3` `Sarvam AI` `Docker` `Railway`

---

### 💻 Butterfly (Bitfy CLI)

*Terminal-native AI assistant translating natural language intent into verified system commands.*

- Embedded persistent local vector memory store powered by **FAISS** and Sentence-Transformers with asynchronous execution.
- **Stack:** `Python` `Click` `LangChain` `FAISS` `Sentence-Transformers`

---

## 🌟 Open Source Contributions

- **[Google ADK (Agent Development Kit)](https://github.com/google/adk-python):** Authored upstream fix ([PR #8007](https://github.com/google/adk-python/pull/8007)) resolving multi-turn schema validation crashes (`reasoning_content` incompatibility) on strict provider routes.
- **[FeaturePy](https://github.com/Parth-Srivastava-bithub/FeaturePy) & [CorrPY](https://github.com/Parth-Srivastava-bithub/CorrPY):** Lightweight Python libraries for automated feature selection and fast correlation analysis.

---

## 🛠 Tech Stack

```text
Languages         : Python, SQL, Java, KQL (Kusto Query Language)
AI & Agents       : Google ADK, LangChain, LangGraph, Multi-Agent Systems, RAG, LiteLLM
Model Serving     : vLLM, Hugging Face Transformers, PEFT/QLoRA, PyTorch, FAISS
Cloud & Infra     : Docker, RunPod, Novita AI, Vast.ai, Linux, Railway
Data & Streaming  : FastAPI, Server-Sent Events (SSE), Apache Airflow, SQLAlchemy, Pydantic
Databases & Vault : PostgreSQL, MongoDB Atlas, AES-256-GCM Cryptography, Redis
Observability     : Prometheus, Locust (Load Testing & RPS Benchmarking)
```

---

## 📬 Get in Touch

- 🌐 **Portfolio:** [parthml.in](https://parthml.in)
- 💼 **LinkedIn:** [linkedin.com/in/parth-srivastava-dsuser](https://linkedin.com/in/parth-srivastava-dsuser)
- 📧 **Email:** [dsparthsrivastava@gmail.com](mailto:dsparthsrivastava@gmail.com)
