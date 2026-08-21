<div align="center">

# DAX
### AI & Agent Development
**Local AI • Automation • Computer Agents • Developer Tools**

[![GitHub followers](https://img.shields.io/github/followers/dax0056?label=Followers&style=flat-square&color=238636)](https://github.com/dax0056)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/Python-3.9%20%7C%203.10%20%7C%203.11%20%7C%203.12-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![Status](https://img.shields.io/badge/Status-Active%20Building-success?style=flat-square)]()

</div>

---

## 🎯 About

I design and build **local-first AI agents**, **autonomous coding tools**, and **sandboxed desktop automation systems**. 

My engineering focus centers on:
- **Local Inference Architecture**: Building deterministic agent runtimes powered by local models (Ollama, vLLM, LM Studio) with transparent fallback layers.
- **Deterministic Tooling & Verification**: Replacing fuzzy LLM code generation with AST validation, atomic unified diff patching, and explicit approval gates.
- **Sandboxed Execution & Safety**: Enforcing bounded operating system confines, application allowlists, and immutable SHA-256 audit logs for computer agents.

---

## 🚀 Featured Projects

| Project | Description | Tech Stack | Status |
| :--- | :--- | :--- | :--- |
| [**nexus-agent**](https://github.com/dax0056/nexus-agent) | Modular local-first AI agent reference architecture with multi-backend model routing, episodic memory, and sandboxed workspace tools. | Python, Ollama, Pytest, JSON Schema | `v0.1.0` • Public |
| [**micro-coding-agent**](https://github.com/dax0056/micro-coding-agent) | Lightweight autonomous coding engine featuring AST syntax parsing, unified diff generation, atomic patching, and human-in-the-loop approval. | Python, AST, Unified Diff, Pytest | `v0.1.0` • Public |
| [**desktop-action-agent**](https://github.com/dax0056/desktop-action-agent) | Safe local computer agent reference architecture with window detection, application allowlists, bounded actions, and SHA-256 audit logging. | Python, OS Abstractions, SHA-256 | `v0.1.0` • Public |

---

## 🛠️ Architecture & What I'm Building

### 1. Local AI Agent Runtimes
Decoupled multi-backend orchestrators that prioritize user data privacy by executing reasoning loops entirely on local silicon.

```
User Goal ──► Nexus Agent ──► Task Planner ──► Model Router (Ollama/vLLM) ──► Sandboxed Tools ──► Verification
```

### 2. Autonomous Coding & Patch Engines
Deterministic patch formulation where every proposed edit is dry-run tested, diff-inspected, and AST syntax-verified before touching disk.

```
Task ──► Plan Chunks ──► Dry-Run Diff ──► Approval Gate ──► Atomic Write ──► AST Verification
```

### 3. Sandboxed Desktop Automation
OS-level computer interaction bound by strict execution policies, permission barriers, and cryptographically verified JSONL audit logs.

```
Action Request ──► Policy Sandbox ──► Allowlist Verification ──► Bounded Execution ──► SHA-256 Audit Trail
```

---

## 💻 Tech Stack & Tooling

- **Languages**: Python, Bash, SQL, YAML
- **AI & Agent Engineering**: Model Routing, Function Calling, Prompt Structuring, JSON Schema Validation, Local Inference (Ollama / vLLM / LM Studio)
- **Code Intelligence & Parsing**: Abstract Syntax Trees (Python `ast`), Unified Diff Engines (`difflib`)
- **System Automation & Security**: Sandboxing, Process Isolation, Cryptographic Audit Logging (SHA-256), Subprocess Management
- **Quality & CI/CD**: Pytest, Automated CI Workflows (GitHub Actions), Linting & Typing (`ruff`, `mypy`)

---

## 🛡️ Security & Open Source Principles

- **Zero-Secret Commitment**: Strict public isolation firewalls and pre-commit secret scanners prevent credential leakage.
- **Deterministic Safety**: No unvetted commands or arbitrary shell executions without explicit policy validation.
- **Reproducible Testing**: Every open-source repository includes full automated test suites running across multiple Python versions on GitHub Actions.

---

## 📬 Connect & Links

- **GitHub Profile**: [@dax0056](https://github.com/dax0056)
- **Inquiries & Vulnerability Reporting**: `dax0056@users.noreply.github.com`
- **Location**: Remote / Global
