<div align="center">
  <img src="docs/nexusos-icon.svg" alt="NexusOS Logo" width="130" />
  <h1>🚀 NexusOS</h1>
  <p><strong>The Ultimate AI-Native Personal Research & Learning Operating System</strong></p>

  <p>
    <a href="https://github.com/Tomoyo-Kusosawa/Nexus/releases"><img src="https://img.shields.io/badge/Version-v1.0.2-cyan.svg?style=flat-square" alt="Version"></a>
    <a href="https://github.com/vuejs/core"><img src="https://img.shields.io/badge/Vue.js-3.x-4FC08D.svg?style=flat-square&logo=vue.js" alt="Vue"></a>
    <a href="https://www.typescriptlang.org/"><img src="https://img.shields.io/badge/TypeScript-5.x-3178C6.svg?style=flat-square&logo=typescript" alt="TypeScript"></a>
    <a href="https://www.nexusos.top"><img src="https://img.shields.io/badge/Website-nexusos.top-blue.svg?style=flat-square" alt="Website"></a>
    <a href="https://opensource.org/licenses/MIT"><img src="https://img.shields.io/badge/License-MIT-green.svg?style=flat-square" alt="License"></a>
  </p>

  <p>
    <b>English</b> | <a href="./README_zh-CN.md">简体中文</a> | <a href="./README_zh-TW.md">繁體中文</a>
  </p>
</div>

---

## 📖 Overview

**NexusOS** is a comprehensive, local-first, AI-native academic workbench and personal research operating system designed for scholars, PhD candidates, researchers, and engineers. It eliminates fragmented workflows by unifying literature discovery, intelligent reading, LaTeX paper drafting, experimental asset management, and task scheduling into a single, cohesive, privacy-centric environment.

---

## ✨ Key Features & Architecture

### 🤖 1. Global AI Super Agent & System Hub
* **Dual-Pipeline Execution Engine:**
  * **Standard Deterministic Pipeline:** Converts natural language instructions into validated, system-level JSON action batches for automatic task scheduling and data management.
  * **Super Academic Writing Pipeline:** Powered by advanced multi-modal models, multi-turn reasoning, and sandboxed code execution.
* **RAG & Style Cloning:** Mount reference PDFs to inject local vector retrieval context or clone the linguistic style, density, and academic tone of benchmark publications.
* **Dynamic Skill Market:** Install, enable, or hot-reload specialized research skills and execution plugins directly from GitHub repositories.
* **AI Resource Monitor:** Seamlessly tracks monthly Token throughput and monitors connection health across Ollama, OpenAI, DeepSeek, and custom LLM endpoints.

### 📚 2. Literature Kanban & Intelligent Pipeline
* **Visual Pipeline Workflow:** Drag-and-drop papers across custom stages: *To Read*, *Skim*, *Deep Read*, and *Reproducing*.
* **Smart Ingestion & Deduplication:** Drag-and-drop PDF files to automatically parse title, authors, DOI, and year with built-in duplicate detection.
* **Built-in Mirror Retriever:** Ingest papers by DOI via configurable mirror backends (e.g., SciDown).
* **Archive Vault & Quick BibTeX:** Move completed papers to an archive repository or copy formatted BibTeX citations with one click.

### 📖 3. Immersive AI PDF Reader
* **Synchronized Dual-Pane Translation:** Simultaneous viewing of original PDF pages alongside AI-translated, Markdown-formatted content with synchronized scrolling.
* **Multi-Format Annotations:** Floating toolbar for multi-color text highlights, underlines, and movable sticky note cards with academic tags (`Idea`, `Question`, `Todo`).
* **Context-Aware Academic Copilot:** Interactive side-panel for document-level Q&A, structured summary extraction, and AI-powered related literature discovery.
* **Integrated Long-Note Studio:** Write and preview structured Markdown notes synced with the global Knowledge Graph, exportable to `.md` or `.pdf`.

### ✍️ 4. Paper Studio (Hybrid LaTeX & WYSIWYG Workspace)
* **Seamless Hybrid Authoring:** Write effortlessly in a WYSIWYG rich-text canvas while retaining native LaTeX block isolation for complex math and tabular environments.
* **Official Publication Templates:** Built-in templates for **IEEE Transactions** (Single/Two Column), **ACM Conferences** (`acmart`), **Nature/Springer**, and **Elsevier** (`elsarticle`), with custom `.zip` `.cls` package uploads.
* **Local Real-Time Compilation:** Integrated with local TeXLive engines (`xelatex`, `pdflatex`) providing Overleaf-style debounced auto-compilation, live PDF synchronization, and compilation log parsing.
* **Smart Cross-Referencing:** Intelligent popups for equations (`\ref{eq:...}`), figures (`\ref{fig:...}`), and bibliography citations (`\cite{...}`).
* **Academic Review Copilot:** Generate Booktabs tables, polish sentences to formal academic tone, or simulate a comprehensive double-blind peer review report.

### 🕸️ 5. Research Workspace & Topological Knowledge Graph
* **Interactive Resource Graph:** Auto-maps and visualizes multi-dimensional relationships between your papers, datasets, notes, and code environments, featuring a Focused Micro-Topology Roaming Modal.
* **Industrial Dataset Manager:** Organize local folders, online repositories, and automatically detect research bookmarks from Chrome, Edge, and Brave browsers.
* **Experiment & IDE Console:** Connect datasets with code repositories and launch VS Code workspaces or copy CLI runtime commands instantly.
* **Automated Weekly Meeting Reports:** Analyzes your weekly activity footprints (completed tasks, paper notes, studio edits) to generate structured markdown reports with AI polishing.

### 🧩 6. Dynamic Workspace & Sandboxed Plugins
* **Modular Dashboard:** Build custom views using built-in widgets (Infinite Calendar, Pomodoro Focus Timer, Contribution Graph, Deadline Radar).
* **Sandboxed Custom Widgets:** Write custom HTML/JS/CSS widgets inside an iframe sandbox utilizing the `PHM.api` bridge to query local workspace metrics.

---

## 🛠️ Tech Stack

* **Frontend Framework:** Vue 3 (Composition API), TypeScript, Vite
* **Editor & Math Engine:** Tiptap, ProseMirror, KaTeX
* **PDF Rendering:** PDF.js
* **Styling & UI:** TailwindCSS, Lucide Icons
* **Data Storage:** SQLite (Local-first, encrypted vault)

---

## 🚀 Quick Start

### Prerequisites
- Node.js (`>= 18.x`)
- Git
- Local TeXLive / MacTeX (Optional, required for local LaTeX PDF compilation)

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/Tomoyo-Kusosawa/Nexus.git

# 2. Navigate to project directory
cd Nexus

# 3. Install dependencies
npm install

# 4. Start development server
npm run dev
```

## 🔗 Official Links & Support

* 🌐 **Official Website:** [www.nexusos.top](https://www.nexusos.top)
* ✉️ **Support & Feedback:** [support@nexusos.top](mailto:support@nexusos.top)
* 🐛 **Bug Reports & Feature Requests:** [GitHub Issues](https://github.com/Tomoyo-Kusosawa/Nexus/issues)

## 📄 License

This project is licensed under the [MIT License](LICENSE).
