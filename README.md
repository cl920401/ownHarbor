# ⚓ ownHarbor (Powered by Human Attentions)

> **Let AI Teammates sail the 90% rough seas; save your `Human Attention` for the final 10% soul.**  
> A Grok Bot-inspired personal AI Teammate harbor built on top of `opencode serve` — featuring a zero-build Single-File HTML cockpit, a **Human Attention Approval Gate**, and a pluggable Workspace Canvas.

**English** | [简体中文](./README_ZH.md)

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Engine](https://img.shields.io/badge/Backend-OpenCode_Serve-22c55e.svg)](https://github.com/sst/opencode)
[![UI](https://img.shields.io/badge/Frontend-Single_HTML_Zero_Build-38bdf8.svg)](#)
[![Protocol](https://img.shields.io/badge/Philosophy-Human_Attention_Gate-f59e0b.svg)](#)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](#)

---

## 💡 Why `ownHarbor`?

99% of open-source Agent UIs are either reinventing yet another generic chatbox or drowning in heavy frontend build pipelines. For solo founders, indie hackers, and super-individuals, we don't need another chatbot—we need **AI Teammates** (inspired by **xAI Grok Bot**) that execute routines asynchronously and pause at critical checkpoints for human sign-off.

**`ownHarbor`** is built on two uncompromising engineering principles:

1. **Zero Backend Reinvention, 100% UI Freedom**: Instead of writing custom tool-calling loops or database schemas from scratch, `ownHarbor` piggybacks directly on `opencode serve` for headless LLM execution, local file persistence, and terminal access. The entire frontend lives in a **single `index.html` file**—zero Node build steps, zero bundler fatigue. You can hot-swap your custom workflow canvas in 3 minutes.
2. **The `Human Attention` Protocol (Anti-AI-Slop)**: Fully automated content and code pipelines inevitably produce soulless AI slop. In `ownHarbor`, specialized Bots do the **90% heavy lifting** (combinatorial topic generation, RAG architecture deduction, and visual layout rendering) and suspend tasks in the **Approval Inbox**. You spend just **1 minute** injecting authentic human judgment and emotional resonance (**the final 10% soul**) before publishing.

---

## ✨ Core Features & Built-in Starter Kit

Out of the box, `ownHarbor` ships with a production-ready workflow suite for **Backend Engineering Resume Elevation & Tech Content Matrix Operations**:

* 🤖 **Grok Bot-Style AI Teammates & Routines (Left Pane)**
  * **🔥 Topic Seed & Draft Bot**: Driven by an `8 × 8 × 6 × 5` orthogonal combinatorics engine (*Persona × Mundane CRUD Module × High-Concurrency Cure × Emotional Hook*), generating **1,920 unique narrative seeds** without repetitive AI clichés.
  * **🎨 Red/Green Visual Contrast Bot**: Extracts sharp before-and-after engineering contrasts and drives the 600px visual card renderer in real time.
  * **🚀 Backend Resume Upgrader Bot**: Rejects unrealistic "1M+ QPS" AI hallucinations. Strictly calibrates architectural metrics to the candidate's target salary band and rewrites mundane CRUD bullet points into defensible production evolutions.
* 🛡️ **Human Attention Approval Gate (Center Pane)**
  * All scheduled **Routines** push their outputs into an asynchronous approval stream. Edit inline to inject authentic developer voice, reject to regenerate with a new angle, or approve to sync directly to the workspace canvas.
* 🧩 **Pluggable Workspace Canvas (Right Pane)**
  * **View A: 600px Red/Green Visual Hook Renderer** — Real-time WYSIWYG card preview comparing *Naive CRUD Resume Lines (❌)* vs. *Senior High-Concurrency Architecture (✅)* + *Interviewer Grill Warnings (⚠️)*.
  * **View B: Backend CRUD-to-STAR Workbench** — Side-by-side structured transformation pairing calibrated STAR resume bullets with a **5-Layer Interviewer Grill Defense Guide** so candidates never get caught bluffing.

---

## 📚 Built-in Backend High-Concurrency RAG Playbooks (`/playbooks`)

To eliminate generic LLM hallucinations, `ownHarbor` maintains 6 production-grade backend architectural evolution playbooks grounded in real-world distributed systems:

1. **Slow Queries & Massive Data Governance**: `Deferred Join` for deep pagination cliffs, composite index invalidation diagnostics, cold/hot data archiving, and `Canal` Binlog-to-`Elasticsearch` heterogeneous sync.
2. **High-Concurrency Reads & Multi-Level Caching**: `Caffeine + Redis` multi-tier caching against hot-key breakdown, delayed double deletion, and eventual consistency patterns.
3. **High-Concurrency Writes & Async Decoupling**: `RocketMQ / Kafka` peak shaving, Lua atomic inventory deduction, message loss reconciliation, and custom idempotent table design.
4. **Distributed Coordination & State Machines**: `Redisson` distributed locks with WatchDog renewal, and `Spring StateMachine` refactoring to eliminate 2,000-line `if-else` spaghetti.
5. **JVM & Production Incident Postmortems**: Ready-to-adapt troubleshooting evidence chains for million-row Excel export `Full GC / OOM` (POI vs. `EasyExcel` streaming), database deadlocks, and 100% CPU spikes.
6. **Anti-Bluff Interview Grill Defense**: Every architectural upgrade is paired with 5–10 adversarial follow-up questions (e.g., *What happens if a Redis lock expires before the transaction finishes? What if master-replica failover drops the lock?*) and concrete engineering answers.

---

## 🚀 30-Second Quick Start

### Option 1: Zero-Config Instant Demo (Built-in Mock Mode)
No backend installation required. Clone the repository and open `index.html` directly in any modern browser to experience the 4D topic generator, approval inbox, and live canvas rendering:

```bash
git clone [https://github.com/](https://github.com/)<your-username>/ownHarbor.git
cd ownHarbor
open index.html  # Or double-click index.html on Windows/Linux