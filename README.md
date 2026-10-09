# 👋 Hi, I'm Alyssa L.

📄 **[Download my CV / Resume](https://raw.githubusercontent.com/alyssa2ai/alyssa2ai/main/Alyssa_CV.pdf)**

### 🔬 AI/ML Researcher | Agentic AI, LLM Evaluation & Robustness | Information Science @ SIT

I build, break, and analyze AI systems.

My current research focuses on **agentic AI reliability, LLM evaluation, failure-mode analysis, tool use, and robustness**. I am particularly interested in understanding why AI systems fail under imperfect training coverage, distribution shift, and system-level constraints — and in designing evaluations that make those failures measurable and reproducible.

---

## 📄 Featured Publication

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.22346935.svg)](https://doi.org/10.5281/zenodo.22346935)

### [AGENTRUN: Failure-Driven QLoRA Specialization for Multi-Tool Agent Behavior](https://github.com/alyssa2ai/AGENTRUN)

*A controlled case study of fine-tuning regression, trace-level diagnosis, and targeted recovery.*

* **Finding:** QLoRA fine-tuning on 35 trajectories caused performance to regress from **95.7% → 78.3%** on a 23-task multi-tool benchmark.
* **Diagnosis:** Trace-level analysis of the regressed tasks showed **skipped tool calls, step-budget exhaustion, and answer-content failures**.
* **Ablation (E4):** Holding the fine-tuned adapter fixed and changing the tool-call parser (and, as run, the evaluation client) left the score at **18/23**, but **4 task outcomes flipped**. The aggregate score hid per-task changes.
* **Recovery:** A failure-informed intervention, 11 added trajectories and retraining, reached **23/23** on the same benchmark. Because the additions were written after seeing the failures, this is **not** evidence of generalization.
* **Systems:** Integrated **MCP-based tool execution** and structured traces for auditable agent evaluation.
* **Status:** Preprint on Zenodo (Sept 2026, not peer reviewed; predates the E4 ablation). An updated manuscript is in the repository.

---

## 🚀 Active Research Directions

### 🤖 Agentic AI & LLM Evaluation

Designing controlled benchmarks and failure analyses for multi-tool agents, with emphasis on **reliability, recovery behavior, and trace-level diagnosis**.

### 🧠 RAG, Memory & Multi-Agent Systems

Building research agents and persistent memory infrastructure for **iterative retrieval, reasoning, verification, and long-context interaction**.

### 🧬 AI for Computational Biology

Exploring the combination of **GROMACS molecular-dynamics simulations, HPC/GPU workflows, and machine learning** for corneal biomolecular research.

---

## 🗂️ Selected Projects

### 🤖 [AGENTRUN](https://github.com/alyssa2ai/AGENTRUN)

**Failure-driven agent evaluation and QLoRA specialization.**

A minimal agent runtime for studying multi-tool behavior through QLoRA fine-tuning, execution traces, MCP tool use, and a fixed, machine-scored 23-task benchmark.

### 🧠 [Waggle-MCP](https://github.com/alyssa2ai/Waggle-mcp)

**Persistent memory infrastructure for AI agents.**

A graph-backed memory layer for MCP-compatible agents combining hybrid retrieval, embeddings, provenance tracking, contradiction handling, and recursive context assembly.

### 🔎 [Agentic RAG Researcher](https://github.com/alyssa2ai/agentic-rag-researcher)

**Autonomous research agent for evidence gathering and iterative reasoning.**

A research-oriented RAG system combining multi-tool retrieval, persistent vector memory, iterative refinement, and agentic orchestration.

### 🧱 [NanoGPT from Scratch](https://github.com/alyssa2ai/nanogpt-from-scratch)

**Transformer implementation from the ground up.**

Implemented a decoder-only Transformer with tokenization, causal self-attention, positional representations, autoregressive generation, and training experiments.

### 🌾 [CropScout AIoT](https://github.com/alyssa2ai/CropScoutAIoT)

**Computer vision + edge AI + precision agriculture.**

An AIoT agricultural system combining plant-disease recognition, ESP32-CAM deployment, environmental sensing, and a multilingual interface. The project also includes investigation of a **training/deployment preprocessing mismatch** that caused severe model failure under edge conditions.

### 🐾 [Pawsight](https://github.com/alyssa2ai/pawsight)

**Explainable computer vision for animal health.**

EfficientNetB0-based image classification with **Grad-CAM interpretability** and class-level evaluation.

---

## 🧪 Computational Research

I am also working with **molecular-dynamics simulations and scientific computing** using:

* GROMACS
* CUDA / GPU computing
* SLURM / HPC workflows
* Molecular-dynamics trajectory analysis
* Machine-learning regression

The goal is to explore how simulation-derived features can support predictive modeling in **corneal biomolecular research**.

---

## 🛠️ Technical Toolkit

**Languages:**
Python, C++, JavaScript / TypeScript, SQL

**AI / ML:**
PyTorch, TensorFlow, Scikit-learn, Hugging Face, Transformers, QLoRA, RAG, LangChain, LangGraph, OpenCV, MediaPipe, Grad-CAM

**Agentic Systems:**
MCP, tool calling, agent orchestration, evaluation, structured execution traces, persistent memory

**Systems / Infrastructure:**
Git, Docker, FastAPI, ChromaDB, PostgreSQL, MongoDB, SQLite, Neo4j, Linux, SLURM, CUDA

---

## 🏆 Selected Achievements

* 🥇 **1st Place — KIT SPOC Innovathon 2026**
* 🥈 **2nd Place — Scaler ProdX Hackathon**
* 🥇 **1st Place — Technesium 2025 Line Following Robot Competition**
* **Top 5 — RVIT Hackathon**
* **Top 10 — Smart India Hackathon Internal Competition**

---

## 📫 Connect

I am interested in research opportunities and collaborations in:

**Agentic AI · LLM Evaluation · AI Reliability · RAG & Memory · Multimodal AI · Scientific ML**

[LinkedIn](https://www.linkedin.com/in/alyssa-l-191297318)
[Email](mailto:alyssal282006@gmail.com)
[AGENTRUN Paper](https://doi.org/10.5281/zenodo.22346935)

---
