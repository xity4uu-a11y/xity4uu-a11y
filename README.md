<div align="center">
  <img src="assets/profile-banner.svg" alt="xity4uu-a11y" width="100%" />
</div>

<br />

I build small, self-hosted tools and single-binary apps in **Rust, Go, TypeScript, and Python**—mostly scratching my own itch whenever a simple workflow turns into a bloated cloud subscription or forces my data onto someone else's server.

Everything here is MIT-licensed, runs offline or on your own box, and avoids unnecessary cloud dependencies.

---

### Things I'm most proud of lately

- **[sovereign-memory](https://github.com/xity4uu-a11y/sovereign-memory)** — Encrypted, 100% local digital memory in Rust + Tauri v2 + SQLite FTS5/`sqlite-vec` + local Ollama: captures & deduplicates screen OCR (`dHash`), indexes docs/git/bookmarks/terminal/transcripts, scrubs PII & skips Incognito/password managers, and seals everything at rest with Argon2id + AES-256-GCM.
- **[morph-os](https://github.com/xity4uu-a11y/morph-os)** — Runtime stream, API, and DOM mutator in Rust + WASM + Tauri v2 + local Ollama/WebLLM: wraps unstructured legacy CLI stdout into strict JSON, translates XML/v1 API payloads over a loopback proxy with a circuit breaker, and runs a 575-byte `.wasm` DOM transformer locally.
- **[localpdf](https://github.com/xity4uu-a11y/localpdf)** ([Live Web App](https://xity4uu-a11y.github.io/localpdf/)) — Got tired of editing a PDF online only to hit a `$20` paywall at the Download button. Built a browser-only editor (PDF.js + `pdf-lib`) that auto-matches fonts, swaps logos, adds signatures, and merges pages without uploading a single byte.
- **[ghostmetrics](https://github.com/xity4uu-a11y/ghostmetrics)** — A `2.44 MB` Rust binary for cookie-free web analytics (`826 B` tracker, local columnar partitions, optional ClickHouse sync, Alpine.js UI).
- **[omni-coder](https://github.com/xity4uu-a11y/omni-coder)** — Local coding assistant wired straight to Ollama and WebLLM, with a Rust repo indexer and atomic diff preview so source code stays on `127.0.0.1`.
- **[folklore-crm](https://github.com/xity4uu-a11y/folklore-crm)** — Plain-text CRM stored as `contacts/*.md` files inside a regular Git repo, with a Tauri v2 Kanban app that updates whenever you save a file in VS Code.
- **[db-vanguard](https://github.com/xity4uu-a11y/db-vanguard)** — Pure-Rust + Tauri SQL client built to stream 50k-row CSV/NDJSON exports in flat memory instead of freezing like Electron database tools.
- **[bastion](https://github.com/xity4uu-a11y/bastion)** — Pre-release security gate combining secret scanning, adversarial diff review, build hardening, and Ed25519 release certificates.

---

### Full Index (50 Open-Source Repos)

#### Everyday & Creator Tools
| Repo | What it does | Stack |
| --- | --- | --- |
| **[sovereign-memory](https://github.com/xity4uu-a11y/sovereign-memory)** | Encrypted local digital memory (Argon2id + AES-256-GCM) with dHash screen OCR, git/doc/terminal ingestors, FTS5/`sqlite-vec` & Ollama Q&A | Rust · Tauri v2 · AES-GCM · Ollama |
| **[localpdf](https://github.com/xity4uu-a11y/localpdf)** | Browser-only PDF editor with font auto-matching, logo swapping, signatures & page merge — zero uploads | React · TypeScript · PDF.js · `pdf-lib` |
| **[dewrapper](https://github.com/xity4uu-a11y/dewrapper)** | Offline Tauri + Ollama desktop workspace for resumes, SEO drafts, and inline-diff rewrites | Rust · Tauri v2 · React · Ollama |
| **[whisperflow](https://github.com/xity4uu-a11y/whisperflow)** | Records local system audio via virtual cable, transcribes with Whisper-large-v3, and searches in SQLite FTS5 | Rust · Python · Whisper · SQLite |
| **[linkforge](https://github.com/xity4uu-a11y/linkforge)** | Turns a single `links.md` file into a `<12 KB` bio-link page with live SSE/HTMX reload and local analytics | Go · HTMX 2.0 · SQLite · Markdown |
| **[folklore-crm](https://github.com/xity4uu-a11y/folklore-crm)** | Plain-text Markdown CRM backed by Git with a Tauri desktop Kanban board and CLI | Rust · Git · Markdown · Tauri v2 |
| **[billzero](https://github.com/xity4uu-a11y/billzero)** | Single-binary freelance invoicing app with ~1.5ms pure-Go PDF 1.4 rendering and Stripe payment links | Go · SQLite · Native PDF |
| **[docubot-local](https://github.com/xity4uu-a11y/docubot-local)** | Drop-in `60 KB` docs Q&A widget running a 287-byte WebAssembly cosine kernel and optional WebGPU right in the browser | WebAssembly · WebLLM · `sqlite-vec` |
| **[seo-local](https://github.com/xity4uu-a11y/seo-local)** | Offline Python SERP keyword gap checker, Ollama long-form Markdown drafter, and AI-cliche scrubber | Python · Ollama · Markdown |
| **[autopilot-social](https://github.com/xity4uu-a11y/autopilot-social)** | Personal social post scheduler using local cron, Ollama Llama-3 editing, and Playwright | Python · Playwright · Ollama · SQLite |
| **[inboxzero-agent](https://github.com/xity4uu-a11y/inboxzero-agent)** | Self-hosted Python IMAP/SMTP outreach workflow with Ollama drafting and automatic opt-out suppression | Python · IMAP/SMTP · Ollama · SQLite |
| **[watchtower](https://github.com/xity4uu-a11y/watchtower)** | Go + Rod webpage change monitor that filters out timestamp noise and pings Slack/Discord on real copy or price diffs | Go · Rod · Ollama · SQLite |

#### Web, Data & Developer Infrastructure
| Repo | What it does | Stack |
| --- | --- | --- |
| **[morph-os](https://github.com/xity4uu-a11y/morph-os)** | Local runtime stream, HTTP reverse-proxy & WASM DOM mutator with circuit-broken Ollama/WebLLM pipeline & Tauri UI | Rust · WASM · Tauri v2 · Ollama |
| **[omni-coder](https://github.com/xity4uu-a11y/omni-coder)** | Local coding assistant with Rust repo indexing, safe atomic diff patches, and Ollama/WebLLM inference | Rust · Tauri v2 · React · WebLLM |
| **[ghostmetrics](https://github.com/xity4uu-a11y/ghostmetrics)** | Single-binary cookie-free web analytics (`826 B` tracker, local columnar store, optional ClickHouse sync) | Rust · Axum · ClickHouse · Alpine.js |
| **[zero-metrics](https://github.com/xity4uu-a11y/zero-metrics)** | High-throughput Go product event ingestion (funnels, cohort retention, MAU) with a SvelteKit UI | Go · ClickHouse · SvelteKit |
| **[rag-forge](https://github.com/xity4uu-a11y/rag-forge)** | C++17 HNSW/int8 vector search core with Python bindings and `sqlite-vec` hybrid retrieval | C++17 · Python · `sqlite-vec` |
| **[auth-zero](https://github.com/xity4uu-a11y/auth-zero)** | Zero-dependency Node 24 auth server (scrypt, Ed25519 JWT/JWKS, TOTP MFA, OIDC PKCE) + React UI | TypeScript · Node 24 · SQLite · React |
| **[log-terminator](https://github.com/xity4uu-a11y/log-terminator)** | Rust log shipper and 5-format parser with sub-ms local search, optional Meilisearch sync, and Next.js explorer | Rust · Axum · Meilisearch · Next.js |
| **[flag-zero](https://github.com/xity4uu-a11y/flag-zero)** | Go feature flag server with an embedded Redis RESP2 store, SSE updates, and a Vue 3 UI | Go · RESP2 · SSE · Vue 3 |
| **[hook-sniper](https://github.com/xity4uu-a11y/hook-sniper)** | Untruncated local webhook capture, HMAC verification, diffing, and replay proxy in Rust + HTMX 2.0 | Rust · Axum · Tauri v2 · HTMX |
| **[db-vanguard](https://github.com/xity4uu-a11y/db-vanguard)** | Native Rust + Tauri SQL studio with Postgres v3 wire driver, SQL safety linter, and constant-memory exports | Rust · Tauri v2 · React |
| **[pipeline-forge](https://github.com/xity4uu-a11y/pipeline-forge)** | Runs GitHub Actions YAML workflows locally in parallel via Go and the Docker Engine API | Go · Docker API · React |
| **[mail-forge](https://github.com/xity4uu-a11y/mail-forge)** | Local SMTP (`:1025`) and IMAP (`:1143`) dev mail catcher in Rust with automatic OTP & magic-link extraction | Rust · Axum · SMTP/IMAP · React |
| **[formforge](https://github.com/xity4uu-a11y/formforge)** | Next.js form builder that encrypts submissions client-side with `libsodium` before they reach SQLite | Next.js 15 · `libsodium` · SQLite |
| **[form-vault](https://github.com/xity4uu-a11y/form-vault)** | Zero-dep Node form endpoint backed by SQLite with honeypot, Naive Bayes spam filtering, and Tailwind templates | TypeScript · Node 24 · SQLite · Tailwind |
| **[mockmaster](https://github.com/xity4uu-a11y/mockmaster)** | Turns any OpenAPI 3.0/3.1 spec into a stateful Fastify mock server seeded with relational Faker data | TypeScript · Fastify · Faker.js |
| **[shipzero](https://github.com/xity4uu-a11y/shipzero)** | Zero-dep CLI scaffolding Next.js 14, local Docker Supabase, and an offline Stripe webhook simulator | TypeScript · Next.js 14 · Supabase |
| **[cron-terminator](https://github.com/xity4uu-a11y/cron-terminator)** | Tiny (`< 5 MB` RAM) Rust scheduler daemon for local shell & HTTP jobs with overlap locks, retries, and DLQ | Rust · Tokio · WAL/SQLite |
| **[pixel-forge](https://github.com/xity4uu-a11y/pixel-forge)** | Self-hosted Rust image resizer and WebP transcoder with SHA-256 disk cache, HMAC URL signing & Next.js UI | Rust · Axum · WebP · Next.js |
| **[ghost-test](https://github.com/xity4uu-a11y/ghost-test)** | Self-hosted flaky-test & stack-cluster dashboard for Playwright, Vitest, Cypress & JUnit backed by SQLite | TypeScript · Node 24 · SQLite · React |
| **[vault-zero](https://github.com/xity4uu-a11y/vault-zero)** | Go Argon2id + AES-256-GCM secret vault that injects env vars straight into child processes without `.env` files | Go · Argon2id · AES-GCM · Tauri v2 |

#### AI Agent Tooling, Testing & Security
| Repo | What it does | Stack |
| --- | --- | --- |
| **[nexus-agent-os](https://github.com/xity4uu-a11y/nexus-agent-os)** | Visual multi-agent DAG studio, SQLite replay checkpoints, 28-tool MCP server, and eval arena | Python · FastAPI · Next.js · MCP |
| **[bastion](https://github.com/xity4uu-a11y/bastion)** | 3-stage pre-release security gate with secret quarantine, adversarial diff audit, and Ed25519 certificates | Python · FastAPI · Next.js |
| **[prompt-firewall](https://github.com/xity4uu-a11y/prompt-firewall)** | Reverse proxy for OpenAI/Anthropic/Ollama that scores prompt injections and tokenizes PII locally | Python · FastAPI · Next.js |
| **[mcp-forge](https://github.com/xity4uu-a11y/mcp-forge)** | JSON-RPC 2.0 traffic inspector, stdio proxy, and SHA-256 lockfile auditor for MCP servers | TypeScript · Node (0 deps) |
| **[agent-replay](https://github.com/xity4uu-a11y/agent-replay)** | Signed `.replay` trajectory bundles, diff viewer, and `pass@k` regression harness for agents | Python · FastAPI · Typer |
| **[rag-xray](https://github.com/xity4uu-a11y/rag-xray)** | Compares chunking strategies across BM25, dense SVD, and hybrid RRF to see why RAG queries miss | Python · NumPy · FastAPI |
| **[local-eval-arena](https://github.com/xity4uu-a11y/local-eval-arena)** | Local LLM prompt regression runner with deterministic graders, bootstrap CIs, and Elo scores | Python · FastAPI · Typer |
| **[dep-detective](https://github.com/xity4uu-a11y/dep-detective)** | Audits npm, Python, Cargo, and Go lockfiles for typosquats and risky hooks; exports CycloneDX SBOMs | Python · FastAPI · SARIF |
| **[api-drift](https://github.com/xity4uu-a11y/api-drift)** | Cross-checks OpenAPI specs, AST source routes, and HAR traffic to find shadow endpoints and missing auth | Python · AST · FastAPI |
| **[cert-watch](https://github.com/xity4uu-a11y/cert-watch)** | X.509 chain auditor, live TLS probe, and SSH/JWT posture checker with signed snapshots | Python · cryptography · FastAPI |
| **[log-sleuth](https://github.com/xity4uu-a11y/log-sleuth)** | Streaming log forensics engine across JSONL, Nginx, Syslog, GitHub Audit, and CloudTrail | Python · FastAPI · Typer |
| **[sandbox-runner](https://github.com/xity4uu-a11y/sandbox-runner)** | Copy-on-run local execution harness with Merkle filesystem diffs and scrubbed env vars | Python · SQLite · FastAPI |
| **[sql-pulse](https://github.com/xity4uu-a11y/sql-pulse)** | Lints risky Postgres/SQLite migrations, visualizes `EXPLAIN` plans, and spots ORM N+1 queries | Python · FastAPI · Next.js |
| **[code-topo](https://github.com/xity4uu-a11y/code-topo)** | AST import graph across Python, TS/JS, Go, and Rust for finding circular dependencies and dead exports | Python · AST · SVG |
| **[webhook-lab](https://github.com/xity4uu-a11y/webhook-lab)** | Local webhook capture studio and chaos testbench for Stripe, GitHub, and Slack HMAC handlers | TypeScript · Node (0 deps) |
| **[diff-lens](https://github.com/xity4uu-a11y/diff-lens)** | AST-level Git diff analyzer flagging breaking symbol changes, blast radius, and changelogs | Python · AST · Typer |
| **[wire-mock-studio](https://github.com/xity4uu-a11y/wire-mock-studio)** | Records HTTP and WebSocket traffic into PII-scrubbed cassettes for deterministic replay testing | TypeScript · Node (0 deps) |
| **[privacy-lab-auditor](https://github.com/xity4uu-a11y/privacy-lab-auditor)** | Educational Go + Docker + Next.js self-audit lab for testing your own browser/VPN against DNS, WebRTC & IPv6 leaks | Go · Docker · Next.js |

---

*Note: All projects include automated test suites, MIT licenses, and are scanned with TruffleHog before tagging releases. Issues and PRs are always welcome.*
