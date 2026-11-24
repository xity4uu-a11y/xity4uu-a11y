<div align="center">
  <img src="assets/profile-banner.svg" alt="xity4uu-a11y Open-Source Engineering Portfolio" width="100%" />
</div>

<div align="center">
  <br />
  <img src="https://img.shields.io/badge/Focus-Local--First%20AI%20%26%20SaaS%20Killers-111318?style=flat" alt="Focus" />
  <img src="https://img.shields.io/badge/Protocol-MCP%20Native-1D4ED8?style=flat" alt="MCP Native" />
  <img src="https://img.shields.io/badge/Cloud%20Lock--In-Zero-15803D?style=flat" alt="Zero Cloud Lock-In" />
  <img src="https://img.shields.io/badge/License-MIT-374151?style=flat" alt="MIT License" />
</div>

<br />

Building **local-first, zero-lock-in, open-source developer & AI platforms** that replace recurring cloud SaaS subscriptions with fast, auditable, single-binary and 1-command software you actually own.

---

## Featured Flagships (The SaaS-Killer Lineup)

### 1. [dewrapper](https://github.com/xity4uu-a11y/dewrapper) — The AI Wrapper Killer (`v1.0.0`)
> **Stop paying `$30/mo` for Jasper, Copy.ai, and Resume.io. Own your AI.**
- **Rust (Tauri v2) + React 19 + Ollama** single-binary offline desktop app replacing `$220+/mo` of thin AI SaaS wrappers with zero cloud calls.
- Built-in ATS Resume Forge (print-ready HTML/PDF + JD keyword match ring), SEO Article Studio (Flesch-Kincaid & keyword density), Clarity Rewriter (word-level LCS diff), Local Document Synthesizer, Cold Email Writer, and a **25-line JSON community plugin system**.

### 2. [whisperflow](https://github.com/xity4uu-a11y/whisperflow) — The Meeting Bot Killer (`v1.0.0`)
> **Stop paying `$19/mo` for Otter.ai and Fireflies. Transcribe meetings locally and privately.**
- **Rust Audio DSP/VAD Core + Python Whisper-large-v3 + Virtual Audio Cable (BlackHole / VB-Cable / PipeWire) + SQLite WAL/FTS5** with Desktop GUI & CLI.
- Captures Zoom/Teams/Meet audio silently with zero bots joining your call, indexes every word in local SQLite FTS5, summarizes offline via Ollama or built-in extractive NLP, and supports community JSON meeting plugins.

### 3. [shipzero](https://github.com/xity4uu-a11y/shipzero) — The Boilerplate Seller Killer (`v1.0.0`)
> **Stop paying `$200` for SaaS boilerplates. Generate a production-ready app in 30 seconds for free.**
- Zero-runtime-dependency Node/TypeScript CLI (`npx create-shipzero`) scaffolding a complete **Next.js 14 App Router + Local Supabase Docker (Postgres + RLS + GoTrue + PostgREST + Mailpit) + Stripe Test Mode / Offline Webhook Simulator** SaaS app.
- Ships with 5 injectable community plugins (`mdx-blog`, `waitlist`, `admin-console`, `transactional-emails`, `api-rate-limiter`) via `shipzero add <plugin>`.

### 4. [docubot-local](https://github.com/xity4uu-a11y/docubot-local) — The Chatbot SaaS Killer (`v1.0.0`)
> **Stop paying `$50/mo` for Intercom Fin and CustomGPT. Run an AI chatbot on your site for `$0` API costs.**
- **WebAssembly (`cosine.wasm` 287B kernel) + WebLLM / WebGPU + `sqlite-vec` (`vec0`) + Zero-Dependency Shadow DOM Widget (`60.5 KB` single `<script>`)** executing 100% inside the visitor's browser with zero outbound API calls.
- Includes a zero-dep docs indexer CLI (`docubot-local build`), hybrid BM25 + Wasm RRF retrieval, instant zero-GPU extractive fallback with `[1]` citations, and 5 validated JSON community plugins (including Luhn/PII input redaction).

### 5. [nexus-agent-os](https://github.com/xity4uu-a11y/nexus-agent-os) — Local-First Multi-Agent OS & Visual Studio (`v1.0.0`)
> Open-source local alternative to **LangSmith**, **CrewAI Enterprise**, **Dify Cloud**, and **Zapier AI**.
- Visual Next.js 15 DAG Studio (8 node types), durable SQLite WAL checkpointing + HITL approvals + time-travel replay, **28-Tool Native MCP Server & `SKILL.md`**, Universal MCP Hub with SHA-256 rug-pull defense, Hybrid FTS5+Vector Memory Graph, Fernet Vault, and Statistical Eval Arena.

### 6. [bastion](https://github.com/xity4uu-a11y/bastion) — 3-Stage Pre-Ship Security & Anti-REA Release Gate (`v2.1.0`)
> Automated local DevSecOps web app, CLI, and AGPL-clean `Dockerfile.cli`.
- **Gate 1:** Pluggable TruffleHog / MIT Gitleaks secret quarantine · **Gate 2:** Cloudflare 6-phase Hunter vs. Verifier audit with git-diff scoping & budget caps · **Gate 3:** BLA Anti-REA build hardening + Post-BLA smoke verification + **Ed25519 Signed Release Certificates**.

---

## Complete Open-Source Engineering Suite (21 Repositories)

### Local-First SaaS Killers & AI Agent Infrastructure
| Project | Description | Stack | Release |
| --- | --- | --- | --- |
| **[dewrapper](https://github.com/xity4uu-a11y/dewrapper)** | Offline AI Wrapper Killer replacing Jasper, Copy.ai, Resume.io & Grammarly via Ollama + JSON plugins | Rust · Tauri v2 · React 19 · Ollama | `v1.0.0` |
| **[whisperflow](https://github.com/xity4uu-a11y/whisperflow)** | Zero-bot local meeting transcriber (Whisper-large-v3, Virtual Audio Cable, Rust VAD/DSP, SQLite FTS5) | Rust · Python · FastAPI · SQLite FTS5 | `v1.0.0` |
| **[shipzero](https://github.com/xity4uu-a11y/shipzero)** | Zero-dep `npx create-shipzero` CLI scaffolding Next.js 14 + Local Supabase Docker + Stripe Test Mode | TypeScript · Next.js 14 · Supabase · Stripe | `v1.0.0` |
| **[docubot-local](https://github.com/xity4uu-a11y/docubot-local)** | In-browser AI docs chatbot with native Wasm cosine kernel, WebLLM/WebGPU, `sqlite-vec` & `60.5 KB` Shadow DOM widget | WebAssembly · WebLLM · WebGPU · `sqlite-vec` | `v1.0.0` |
| **[nexus-agent-os](https://github.com/xity4uu-a11y/nexus-agent-os)** | Multi-Agent OS, Visual DAG Studio, 28-Tool MCP Server, Universal MCP Hub, Hybrid Memory Graph & Eval Arena | Python · FastAPI · Next.js 15 · MCP | `v1.0.0` |
| **[prompt-firewall](https://github.com/xity4uu-a11y/prompt-firewall)** | OpenAI/Anthropic/Ollama reverse proxy with prompt-injection scoring, reversible Fernet PII vault & YAML tool policies | Python · FastAPI · Next.js 15 | `v1.0.0` |
| **[mcp-forge](https://github.com/xity4uu-a11y/mcp-forge)** | Universal MCP JSON-RPC 2.0 inspector, stdio proxy, SHA-256 lockfile rug-pull auditor & schema boundary fuzzer | TypeScript · Node.js 22 (0 deps) | `v1.0.0` |
| **[agent-replay](https://github.com/xity4uu-a11y/agent-replay)** | Deterministic time-travel debugger, SHA-256 `.replay` bundle SDK, trajectory differ & `pass@k`/`pass^k` CI harness | Python · FastAPI · Typer | `v1.0.0` |
| **[rag-xray](https://github.com/xity4uu-a11y/rag-xray)** | Offline RAG forensic debugger comparing chunkers x BM25/Dense SVD/Hybrid RRF with Recall@K, MRR & blind-spot diagnosis | Python · NumPy · FastAPI · Next.js 15 | `v1.0.0` |
| **[local-eval-arena](https://github.com/xity4uu-a11y/local-eval-arena)** | Local LLM benchmark & prompt regression suite with 7 deterministic graders, 95% bootstrap CIs & Bradley-Terry Elo | Python · FastAPI · Typer | `v1.0.0` |

### Security, Forensics & Supply-Chain Defense
| Project | Description | Stack | Release |
| --- | --- | --- | --- |
| **[bastion](https://github.com/xity4uu-a11y/bastion)** | 3-Stage Pre-Ship Security & Anti-REA Release Gate with Fernet vault, Ed25519 certificates & AGPL-clean `Dockerfile.cli` | Python · FastAPI · Next.js 15 | `v2.1.0` |
| **[dep-detective](https://github.com/xity4uu-a11y/dep-detective)** | Multi-ecosystem lockfile supply-chain hunter (`npm`, `Python`, `Cargo`, `Go`) with typosquatting, CycloneDX 1.5 SBOM & SARIF | Python · FastAPI · Typer | `v1.0.0` |
| **[api-drift](https://github.com/xity4uu-a11y/api-drift)** | 3-way OpenAPI 3.0/3.1 vs. AST routes (FastAPI, Express, Next.js) vs. HAR 1.2 traffic shadow-endpoint & auth-guard auditor | Python · AST · FastAPI · SARIF | `v1.0.0` |
| **[cert-watch](https://github.com/xity4uu-a11y/cert-watch)** | X.509 PEM/DER chain auditor, live TLS handshake probe, OpenSSH & JWT posture inspector with Ed25519 signed snapshots | Python · cryptography · FastAPI | `v1.0.0` |
| **[log-sleuth](https://github.com/xity4uu-a11y/log-sleuth)** | Streaming 5-format log forensics engine (JSONL, Nginx, Syslog, GitHub Audit, CloudTrail) with anomaly correlation & timelines | Python · FastAPI · Typer | `v1.0.0` |
| **[sandbox-runner](https://github.com/xity4uu-a11y/sandbox-runner)** | Zero-trust local script execution harness with Merkle filesystem diffing, ambient env scrubbing & Ed25519 attestations | Python · cryptography · SQLite · FastAPI | `v1.0.0` |

### Systems, Databases & Developer Tools
| Project | Description | Stack | Release |
| --- | --- | --- | --- |
| **[sql-pulse](https://github.com/xity4uu-a11y/sql-pulse)** | PostgreSQL & SQLite migration safety linter with zero-downtime rewrites, dual `EXPLAIN` flame-plan analyzer & ORM N+1 hunter | Python · FastAPI · Next.js 15 | `v1.0.0` |
| **[code-topo](https://github.com/xity4uu-a11y/code-topo)** | Multi-language AST architecture cartographer (Python, TS/JS, Go, Rust), Tarjan SCC cycle detector & YAML boundary enforcer | Python · AST · FastAPI · SVG | `v1.0.0` |
| **[webhook-lab](https://github.com/xity4uu-a11y/webhook-lab)** | Local webhook capture & SSE studio, constant-time HMAC-SHA256 signer/verifier (Stripe, GitHub, Slack) & chaos testbench | TypeScript · Node.js 22 (0 deps) | `v1.0.0` |
| **[diff-lens](https://github.com/xity4uu-a11y/diff-lens)** | Semantic Git PR & release risk analyzer combining AST symbol breaking-change detection, blast radius & changelogs | Python · AST · FastAPI · Typer | `v1.0.0` |
| **[wire-mock-studio](https://github.com/xity4uu-a11y/wire-mock-studio)** | Record-and-replay HTTP & pure RFC 6455 WebSocket contract simulator, automatic PII cassette sanitizer & chaos proxy | TypeScript · Node.js 22 (0 deps) | `v1.0.0` |

---

### Core Engineering Principles
- **Own Your Software:** Zero mandatory cloud accounts, zero per-minute transcription caps, zero `$200` boilerplate paywalls, zero `$50/mo` chatbot API fees.
- **Community-Extensible by Design:** Declarative JSON plugin/skill schemas (`CONTRIBUTING.md` + automated validators) across DeWrapper, WhisperFlow, ShipZero, DocuBot Local, and Nexus Agent OS.
- **Cryptographically Verifiable:** Ed25519 release/execution attestations, SHA-256 content-addressed lockfiles, CycloneDX 1.5 SBOMs, and SARIF v2.1.0 outputs.
