<div align="center">

<img width="100%" src="./assets/hero-neon.svg" alt="Wenbo Xu — AI Security, Speech/TTS, LLM Systems" />

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=19&pause=950&color=67E8F9&center=true&vCenter=true&width=820&lines=%5BSYSTEM%5D+Exploring+AI+Security+%26+Speech+Intelligence;%5BRESEARCH%5D+Long-form+TTS+Evaluation+%26+Forensics;%5BENGINEERING%5D+Reliable+LLM+Systems+%26+Agent+Infrastructure;%5BMETHOD%5D+Build+%E2%86%92+Evaluate+%E2%86%92+Audit+%E2%86%92+Understand)](https://git.io/typing-svg)

![Profile Views](https://komarev.com/ghpvc/?username=XuWenboooo&label=NODE%20VISITS&color=0e7490&style=flat-square)
![Research](https://img.shields.io/badge/FOCUS-AI%20RELIABILITY-7c3aed?style=flat-square)
![Status](https://img.shields.io/badge/STATUS-RESEARCH%20IN%20PROGRESS-0891b2?style=flat-square)

`AI Security` · `Speech / TTS` · `LLM Systems` · `Agents / MCP` · `Evaluation` · `Reproducibility`

</div>

---

## `// FLAGSHIP_RESEARCH`

<div align="center">

<img width="100%" src="./assets/audiobookbench-neon.svg" alt="AudiobookBench-CN flagship research" />

</div>

> **AudiobookBench-CN is my current flagship research project.**  
> The project studies **long-form Chinese TTS evaluation** under controlled, reproducible, and audit-friendly experimental protocols.

<table>
<tr>
<td width="33%" valign="top">

### `01 // QUESTION`

How should long-form TTS systems be evaluated when **demo quality alone is not enough**?

</td>
<td width="33%" valign="top">

### `02 // SYSTEM`

Treat evaluation itself as a **research system**: benchmark design, execution discipline, provenance, validation, and audit all matter.

</td>
<td width="33%" valign="top">

### `03 // DIRECTION`

Use this benchmark as a foundation for future work in **speech reliability, synthetic-speech forensics, and AI security**.

</td>
</tr>
</table>

### `RESEARCH_MATRIX`

| Signal | AudiobookBench-CN |
|---|---|
| **Task** | Long-form Chinese audiobook-style TTS |
| **Primary goal** | Reliable and reproducible evaluation |
| **Experimental style** | Controlled protocols rather than ad-hoc demos |
| **Evidence model** | Structured outputs, provenance, validation and lineage |
| **Failure model** | Failures are accounted for rather than silently discarded |
| **Research trajectory** | TTS evaluation → reliability → forensics → AI security |

### `PIPELINE // EVIDENCE_FLOW`

```mermaid
flowchart LR
    A[Research Question] --> B[Benchmark Design]
    B --> C[Generation Protocol]
    C --> D[Evaluation]
    D --> E[Validation & Lineage]
    E --> F[Failure Accounting]
    F --> G[Scientific Audit]
    G --> H[Reproducible Evidence]
```

<table>
<tr>
<td width="50%" valign="top">

### `RESEARCH_PROTOCOL`

- **Reproducibility first** — settings, assets, cases, and outputs should be traceable
- **Failures are evidence** — infrastructure and scientific failures should be recorded
- **Evaluation before presentation** — a polished demo is not a controlled experiment
- **Reviewability matters** — results should survive independent inspection

</td>
<td width="50%" valign="top">

### `CONNECTED_DOMAINS`

- Speech / TTS systems
- AI reliability
- Evaluation methodology
- Synthetic speech analysis
- Speech forensics
- AI security for generative audio

</td>
</tr>
</table>

<div align="center">

![Speech](https://img.shields.io/badge/SPEECH-TTS-0e7490?style=for-the-badge)
![Evaluation](https://img.shields.io/badge/EVALUATION-REPRODUCIBLE-1d4ed8?style=for-the-badge)
![Audit](https://img.shields.io/badge/SCIENCE-AUDITABLE-6d28d9?style=for-the-badge)
![Security](https://img.shields.io/badge/DIRECTION-AI%20SECURITY-7e22ce?style=for-the-badge)

</div>

---

## `// RESEARCH_VECTOR`

<table>
<tr>
<td width="50%" valign="top">

### 🛡️ AI Security

`ROBUSTNESS` `OOD` `GENERATIVE SECURITY`

- Robustness of AI systems
- Open-set / OOD evaluation
- Generative AI security
- Reliability and failure analysis

</td>
<td width="50%" valign="top">

### 🎙️ Speech & TTS

`LONG-FORM` `FORENSICS` `AUDIO`

- Long-form speech generation
- TTS evaluation
- Synthetic speech forensics
- Robust audio intelligence

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧠 LLM Systems

`EVALUATION` `MEMORY` `PROTOCOLS`

- LLM evaluation
- Context & memory systems
- Protocol interoperability
- Reproducible AI experiments

</td>
<td width="50%" valign="top">

### 🔧 Agents & MCP

`TOOLS` `WORKFLOWS` `BOUNDARIES`

- Tool-augmented agents
- MCP-based systems
- Multi-step research workflows
- Agent safety and tool boundaries

</td>
</tr>
</table>

---

## `// SELECTED_SYSTEMS`

### `01 // Protocol Converter`

> **OpenAI-style ↔ Anthropic-style protocol translation through a unified intermediate representation.**

A systems-oriented project exploring protocol interoperability, stateful conversations, memory injection, gateway design, and KV-cache observability.

**System modules**

`IR` → `Adapters` → `State` → `Gateway` → `Memory Injection` → `Cache Observability` → `Experiments`

- Unified intermediate representation
- OpenAI Chat / Responses / Anthropic adapters
- Stateful conversation layer
- Memory injection
- KV-cache observability
- HTTP gateway and streaming support
- Automated multi-version CI

[**ACCESS REPOSITORY →**](https://github.com/XuWenboooo/protocol-converter)

---

### `02 // Paper Reading Assistant`

> **An evaluation-driven LLM system for academic paper understanding.**

The project includes a six-dimensional evaluation framework rather than only a paper-chat interface.

`Factual Accuracy` · `Citation Accuracy` · `Terminology` · `Completeness` · `Comprehensibility` · `Safety`

- PDF / DOCX / Markdown parsing
- LLM-based question answering
- Synthetic evaluation dataset construction
- LLM-as-Judge evaluation
- Rule-based validation

[**ACCESS REPOSITORY →**](https://github.com/XuWenboooo/paper-reading-assistant)

---

### `03 // MCP Research Assistant`

> **A multi-tool research assistant built around the Model Context Protocol.**

A modular MCP system combining document processing, search, analysis, knowledge retrieval, and multi-step tool workflows.

`MCP` · `Agents` · `Tool Use` · `Research Automation`

[**ACCESS REPOSITORY →**](https://github.com/XuWenboooo/mcp-tool-assistant)

---

## `// RESEARCH_TRAJECTORY`

```text
LLM Systems
     │
     ├── Evaluation & Reliability
     │
     ├── Agent / MCP Systems
     │
     └── AI Security
              │
              └── Speech / TTS Security
                       │
                       └── Robust Evaluation & Forensics
```

> **Objective:** connect AI systems engineering with security, evaluation, and speech intelligence into one coherent research direction.

---

## `// OPERATING_PRINCIPLES`

```text
QUESTION
   ↓
HYPOTHESIS
   ↓
EXPERIMENTAL PROTOCOL
   ↓
IMPLEMENTATION
   ↓
EVALUATION
   ↓
FAILURE ANALYSIS
   ↓
REPRODUCIBLE EVIDENCE
```

I care not only about whether a system works, but whether the result is **reproducible**, the protocol is **well-defined**, failures are **recorded**, and conclusions can survive **independent review**.

---

## `// TOOLCHAIN`

<div align="center">

[![My Skills](https://skillicons.dev/icons?i=python,cpp,pytorch,git,github,linux,vscode)](https://skillicons.dev)

`Python` · `C++` · `PyTorch` · `Git` · `GitHub` · `LLM APIs` · `MCP` · `Speech / Audio Evaluation`

</div>

---

## `// TELEMETRY`

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=XuWenboooo&show_icons=true&hide_border=true&rank_icon=github&theme=tokyonight&bg_color=00000000" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=XuWenboooo&layout=compact&hide_border=true&theme=tokyonight&bg_color=00000000" />

</div>

---

## `// CURRENT_PROCESS`

- `ACTIVE` 🔬 Long-form TTS evaluation
- `EXPLORE` 🛡️ AI Security and synthetic speech forensics
- `STUDY` 🧠 LLM evaluation and reliable AI systems
- `BUILD` 🔧 Testing, CI, reproducibility and research-grade engineering

---

<div align="center">

### `RESEARCH // BUILD // EVALUATE // AUDIT // UNDERSTAND`

<sub>signal acquired · experiment running · evidence matters</sub>

</div>
