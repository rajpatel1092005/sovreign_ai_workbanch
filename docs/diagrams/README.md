# 📐 Sovereign AI Workbench — System & Architectural Diagrams

This directory contains editorial-grade architectural, security, and process diagrams created with the **Diagram Design** system. Each diagram is available as a standalone interactive `.html` viewer and as a high-resolution vector `.svg` asset.

---

## 📑 Diagrams Index

| Diagram | Visual Type | Focus & Purpose | Interactive HTML | Vector SVG |
|---|---|---|---|---|
| **System Architecture** | `Architecture` | Complete on-premise topology: Web Client, FastAPI Gateway, Ollama inference models, SQLite session store, and Python sandbox. | [HTML](system-architecture.html) | [SVG](system-architecture.svg) |
| **Autonomous ReAct Agent Loop** | `Flowchart` / `Process` | Multi-step ReAct agent cycle: Dynamic tool selection (`search_kb`, `read_document`, `execute_code`, `generate_report`), observation feedback, and artifact delivery. | [HTML](react-agent-loop.html) | [SVG](react-agent-loop.svg) |
| **Air-Gap Industrial Security** | `Layer Stack` | 5-tier zero-leakage defense hierarchy: Localhost gateway, kernel-level socket auditor (`psutil`), isolated subprocess sandbox, local model daemon, and hardware enclave. | [HTML](air-gap-security.html) | [SVG](air-gap-security.svg) |
| **Multimodal Ingestion & Hybrid RAG** | `Data Flow` | Document ingestion (`.pdf`, `.txt`, `.png`), GLM-OCR parsing, kerning normalization, dense vector embeddings (`nomic-embed-text`), and hybrid lexical-semantic retrieval. | [HTML](hybrid-rag-pipeline.html) | [SVG](hybrid-rag-pipeline.svg) |

---

## 🖼️ Previews

### 1. End-to-End System Architecture
![System Architecture](system-architecture.svg)

---

### 2. Autonomous Stage-4 ReAct Agent Execution Loop
![Autonomous ReAct Agent Loop](react-agent-loop.svg)

---

### 3. Air-Gap Industrial Security & Zero-Leakage Defense Layers
![Air-Gap Security](air-gap-security.svg)

---

### 4. Multimodal Ingestion & Hybrid RAG Retrieval Pipeline
![Hybrid RAG Pipeline](hybrid-rag-pipeline.svg)
