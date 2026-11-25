<div align="center">
  <img src="assets/profile-banner.svg" alt="xity4uu-a11y" width="100%" />
</div>

<br />

I build local-first, privacy-respecting tools in **Rust, Go, TypeScript, and Python**—focused on software that runs on your own hardware without cloud lock-in, telemetry, or surprise subscription paywalls.

Right now my primary focus is **[sovereign-memory](https://github.com/xity4uu-a11y/sovereign-memory)** (an encrypted, offline digital memory engine) and **[localpdf](https://xity4uu-a11y.github.io/localpdf/)** (a zero-upload browser PDF editor).

---

### Flagship Projects

| Project | What it does | Stack | Latest |
| --- | --- | --- | --- |
| **[sovereign-memory](https://github.com/xity4uu-a11y/sovereign-memory)** | Encrypted local digital memory (Argon2id + AES-256-GCM) with `dHash` screen OCR, Git/doc/PDF/terminal ingestors, SQLite FTS5/`sqlite-vec`, and loopback Ollama Q&A | Rust · Tauri v2 · AES-GCM · Ollama | `v1.1.0` |
| **[localpdf](https://github.com/xity4uu-a11y/localpdf)** ([Live App](https://xity4uu-a11y.github.io/localpdf/)) | Browser-only PDF editor with automatic font matching, inline text replacement, logo swapping, signatures, and page merging — zero server uploads | React · TypeScript · PDF.js · `pdf-lib` | `v1.0.0` |
| **[morph-os](https://github.com/xity4uu-a11y/morph-os)** | Local runtime stream, loopback HTTP reverse-proxy, and 575-byte `.wasm` DOM mutator with circuit-broken Ollama/WebLLM fallback and Tauri control panel | Rust · WebAssembly · Tauri v2 · Axum | `v1.0.0` |
| **[ghostmetrics](https://github.com/xity4uu-a11y/ghostmetrics)** | Single-binary (`2.44 MB`) cookie-free web analytics with an `826 B` tracker, local columnar partitions, optional ClickHouse sync, and Alpine.js UI | Rust · Axum · ClickHouse · Alpine.js | `v1.0.0` |
| **[folklore-crm](https://github.com/xity4uu-a11y/folklore-crm)** | Plain-text Markdown CRM stored in a standard local Git repository with a Tauri v2 Kanban app and standalone Rust CLI | Rust · Git · Markdown · Tauri v2 | `v1.0.0` |
| **[db-vanguard](https://github.com/xity4uu-a11y/db-vanguard)** | Native Rust + Tauri SQL client with a pure-Rust Postgres v3 wire driver, SQL safety linter, and constant-memory streaming exports (`1.4M rows/sec`) | Rust · Tauri v2 · React 19 | `v1.0.0` |
| **[billzero](https://github.com/xity4uu-a11y/billzero)** | Offline-first single-binary freelance invoicing app in Go with SQLite WAL, `~1.5ms` pure-Go PDF 1.4 rendering, and optional Stripe payment links | Go · SQLite · Native PDF | `v1.0.0` |
| **[bastion](https://github.com/xity4uu-a11y/bastion)** | Three-stage pre-release security gate combining secret scanning, adversarial diff review, build hardening, and Ed25519 signed release certificates | Python · FastAPI · Next.js 15 | `v2.1.0` |

---

### Want to Collaborate?
- Check open roadmap items and `good first issue` tickets on **[sovereign-memory/issues](https://github.com/xity4uu-a11y/sovereign-memory/issues)** or join **[Discussions](https://github.com/xity4uu-a11y/sovereign-memory/discussions)**.
- Security researchers interested in reviewing our Argon2id + AES-256-GCM vault format can start at **[sovereign-memory/SECURITY.md](https://github.com/xity4uu-a11y/sovereign-memory/blob/main/SECURITY.md)**.
