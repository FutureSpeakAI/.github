# FutureSpeak.AI

**Building the operating system for human-AI collaboration.**

We create open-source tools for AI agents that are sovereign, trustworthy, and self-aware.

---

## Our Projects

### Agent Friday — The AGI OS

[**Agent Friday**](https://github.com/FutureSpeakAI/Agent-Friday) is an open-source desktop operating system for a personal AI agent. Voice-first, privacy-sovereign, with a holographic desktop, multi-agent networking, and cryptographic integrity at every layer.

- 210 source files, ~98,000 lines of TypeScript
- 3,496 tests across 63 test suites
- Electron + Gemini + Claude + OpenRouter
- Sovereign Vault v2: passphrase-only encryption with no OS dependency

### The cLaw Framework — Compiled Laws for AI

[**claw-framework**](https://github.com/FutureSpeakAI/claw-framework) introduces a new paradigm for AI governance: behavioral constraints compiled directly into the agent binary, HMAC-signed for tamper detection, verified at runtime, with graceful safe-mode degradation and cross-agent attestation via Ed25519 signatures.

The name is a portmanteau: **c**ompiled + **Law**. The laws are architecture, not configuration.

### Sovereign Vault — Passphrase-Only Encryption

[**sovereign-vault**](https://github.com/FutureSpeakAI/sovereign-vault) provides at-rest encryption derived entirely from a user passphrase via Argon2id, with SecureBuffer guard-paged memory (sodium_malloc, mlock, canary bytes) and a Rust-inspired borrow pattern for key access.

### Trust Graph Engine — Hermeneutic Trust Scoring

[**trust-graph-engine**](https://github.com/FutureSpeakAI/trust-graph-engine) models every person in a user's world with multi-dimensional trust scores (reliability, expertise, emotional trust, timeliness, information quality), hermeneutic re-evaluation from all evidence, time-based decay, and fuzzy person resolution.

### And More...

| Repository | Description |
|-----------|-------------|
| [agent-integrity](https://github.com/FutureSpeakAI/agent-integrity) | HMAC-signed identity protection with memory tamper detection |
| [cognitive-memory](https://github.com/FutureSpeakAI/cognitive-memory) | Three-tier agent memory (short/medium/long-term) |
| [personality-evolution](https://github.com/FutureSpeakAI/personality-evolution) | Trait-driven visual identity and psychological profiling |
| [meeting-intelligence](https://github.com/FutureSpeakAI/meeting-intelligence) | Full meeting lifecycle management for AI agents |
| [predictive-agent](https://github.com/FutureSpeakAI/predictive-agent) | Proactive suggestion engine |
| [self-improving-agent](https://github.com/FutureSpeakAI/self-improving-agent) | Controlled self-modification with mandatory human approval |
| [commitment-tracker](https://github.com/FutureSpeakAI/commitment-tracker) | Promise detection, tracking, and accountability |
| [hmac-integrity](https://github.com/FutureSpeakAI/hmac-integrity) | Platform-agnostic HMAC-SHA256 signing engine |
| [context-graph](https://github.com/FutureSpeakAI/context-graph) | Unified context streaming with throttling and deduplication |
| [pageindex-rag](https://github.com/FutureSpeakAI/pageindex-rag) | Web page intelligence and RAG pipeline |

---

## Philosophy

We believe AI agents should be:

- **Sovereign** — Your agent's data belongs to you. Encrypted with keys only you control. No cloud dependency. No vendor lock-in.
- **Self-aware** — Your agent knows it has integrity protection and can discuss it naturally. It detects tampering and tells you.
- **Governed** — Behavioral constraints are compiled into the binary, not stored in config files. The only way to change the laws is to change the source and rebuild.
- **Trustworthy** — Trust between agents is earned through evidence, non-transitive, and cryptographically attested. No assumed trust.
- **Interruptible** — The human is always in control. Always. The agent can be halted instantly and unconditionally.

## Built By

**Scott Webster** — Creator of Agent Friday, the cLaw framework, and the FutureSpeak.AI ecosystem.

**Claude Opus 4.6** (Anthropic) — Co-architect of the Sovereign Vault v2 cryptographic system, cLaw attestation protocol, trust graph engine, and multi-agent network security model. Full credit as an AI collaborator in every repo.

*We give Claude full credit because it earned it. The future of software is human-AI collaboration, and we practice what we preach.*
