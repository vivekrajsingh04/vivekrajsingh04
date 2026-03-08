<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=Vivek%20Raj%20Singh&fontSize=50&fontColor=ffffff&fontAlignY=38&desc=Quant%20Learner%20%7C%20Systems%20Engineer%20%7C%20Open%20Source%20Collaborator&descAlignY=58&descSize=18" />
</div>

<div align="center">
  <a href="https://github.com/vivekrajsingh04">
    <img src="https://img.shields.io/badge/GitHub-vivekrajsingh04-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
  <a href="https://github.com/mofa-org/mofa">
    <img src="https://img.shields.io/badge/MoFA-Collaborator-6C63FF?style=for-the-badge&logo=rust&logoColor=white"/>
  </a>
  <img src="https://komarev.com/ghpvc/?username=vivekrajsingh04&style=for-the-badge&color=6C63FF&label=PROFILE+VIEWS"/>
</div>

---

## ⚡ About Me

I live at the intersection of **quantitative finance** and **systems engineering**. I write Rust like it's a trading edge — fast, deterministic, zero-waste.

- 🦀 **Rust Systems Engineer** — Inference orchestration, memory-aware scheduling, async runtimes
- 📐 **Quant Learner** — Stochastic calculus, derivatives pricing, factor models
- 🏛️ **MoFA Collaborator** — [mofa-org/mofa](https://github.com/mofa-org/mofa) · Volunteer Reviewer
- 🎯 **GSoC 2026 Applicant** — Building a Unified Inference Orchestrator for on-device + cloud AI

---

## 🏛️ Open Source — [MoFA](https://github.com/mofa-org/mofa)

> **Collaborator & Volunteer Reviewer** on a Rust-native AI agent framework (190+ ⭐)

### 🐛 Bug Fixes — Deep Systems Auditing

| PR                                                  | Title                                                                        | Impact                                                             | Status  |
| --------------------------------------------------- | ---------------------------------------------------------------------------- | ------------------------------------------------------------------ | ------- |
| [#1035](https://github.com/mofa-org/mofa/pull/1035) | `fix(agent)`: `ChainAgent` timeout enforcement using `tokio::time::timeout`    | 🔴 **Critical** — Prevents agent workflows from hanging indefinitely| ✅ Filed |
| [#871](https://github.com/mofa-org/mofa/pull/871)   | fix(scheduler): Preemption ghost task leak — state cleanup across 4 HashMaps | 🔴 **Critical** — Prevents OOM + scheduling starvation              | 🔄 Open  |
| [#869](https://github.com/mofa-org/mofa/issues/869) | bug(scheduler): Preempted tasks become ghost entries                         | Identified `agent_load` drift, HashMap leak, broken load balancing | ✅ Filed |

### 🚀 Features — Inference & Voice Pipeline

| PR                                                  | Title                                                          | Impact                                                               | Status   |
| --------------------------------------------------- | -------------------------------------------------------------- | -------------------------------------------------------------------- | -------- |
| [#806](https://github.com/mofa-org/mofa/issues/806) | `RequestPriority` enforced in admission control + LRU eviction | Critical/High requests bypass defer band; priority-weighted eviction | ✅ Merged |
| [#812](https://github.com/mofa-org/mofa/issues/812) | OpenAI-compatible HTTP gateway (`/v1/chat/completions`)        | SSE streaming, per-IP rate limiting, multi-backend routing           | 🔄 Review |
| [#714](https://github.com/mofa-org/mofa/pull/714)   | Voice pipeline (ASR → LLM → TTS)                               | End-to-end on-device voice agent                                     | ✅ Merged |
| [#711](https://github.com/mofa-org/mofa/pull/711)   | Cloud TTS/ASR integration                                      | Multi-vendor adapter layer                                           | ✅ Merged |

### 🔍 Code Review

> As a volunteer reviewer, I actively review PRs from other contributors — focusing on correctness, Rust idioms, and architectural alignment.

---

## 🛠️ Tech Stack

<div align="center">

**Systems & Backend**

![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)

**Quant & Data**

![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)

**Async & Networking**

![Tokio](https://img.shields.io/badge/Tokio-async-orange?style=for-the-badge)
![Axum](https://img.shields.io/badge/Axum-HTTP-4B275F?style=for-the-badge)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

---

## 📊 GitHub Activity

<div align="center">

[![GitHub followers](https://img.shields.io/github/followers/vivekrajsingh04?style=for-the-badge&color=6C63FF&labelColor=0d1117&label=Followers)](https://github.com/vivekrajsingh04)
[![GitHub stars](https://img.shields.io/github/stars/vivekrajsingh04?style=for-the-badge&color=FFD700&labelColor=0d1117&label=Stars)](https://github.com/vivekrajsingh04)
[![PRs](https://img.shields.io/badge/Open%20Source%20PRs-6+-brightgreen?style=for-the-badge&labelColor=0d1117)](https://github.com/mofa-org/mofa/pulls?q=vivekrajsingh04)

</div>

<div align="center">

| Metric               | Count    |
| -------------------- | -------- |
| 🔀 PRs Merged         | 3        |
| 🐛 Bugs Found & Fixed | 3        |
| 🔍 PRs Reviewed       | Active   |
| 🏛️ Org Collaborator   | mofa-org |

</div>

---

## 📚 Currently Exploring

<div align="center">

| Domain                | Topics                                       |
| --------------------- | -------------------------------------------- |
| 📈 **Options Pricing** | Black-Scholes, Vol Surface, Greeks           |
| 🧮 **Stochastic Calc** | Itô's Lemma, SDEs, Brownian Motion           |
| ⚙️ **Systems**         | Lock-free queues, memory-mapped I/O, SIMD    |
| 🤖 **LLM Infra**       | Quantization, KV-cache, speculative decoding |

</div>

---

<div align="center">
  
  *"Find the bug nobody else sees. Fix it before they know it exists."*

</div>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=100&section=footer"/>
</div>
