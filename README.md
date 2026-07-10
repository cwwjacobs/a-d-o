# Terminus Protocol

**Applied AI systems, local-first tools, agent observability, deterministic evaluation, and security-aware workflows.**

I build working technical systems from ambiguous requirements, then package the result with tests, receipts, claim boundaries, and reproducible proof.

## Selected work

### Agent Flight Recorder
Local-first evidence recorder for tool-using AI agent runs. Captures model calls, tool calls, tool results, state snapshots, checkpoints, errors, and replay requests. Exports portable run bundles and regression-case material.

- Repository: https://github.com/cwwjacobs/agent-flight-recorder
- Proof surface: CI, Docker quickstart, CLI, SDK, API, replay boundaries, regression-case generator

### Card Forge
Reusable workflow Cards, Stacks, Decks, Runs, and Receipts for AI-assisted work. Includes schemas, templates, validation, edge-runtime packets, and a GitHub Actions validator.

- Repository: https://github.com/cwwjacobs/Card-Forge
- Proof surface: public validator, starter deck, 32k edge-runtime packet demo

### Constellation
A local-first operator console that projects manifests, capabilities, project maps, planned work, and drift receipts into a spatial visual interface.

- Repository: https://github.com/cwwjacobs/ixc-constellation
- Proof surface: local Observatory UI, Project Cartographer, Proposal Mapper, Drift Receipt demo

### DIF Defense
Behavioral prompt-injection detection prototype for bounded agent workflows. Compares observable traces against a frozen Kernel and emits clean, warn, or compromised verdicts with explicit claim boundaries.

- Repository: https://github.com/cwwjacobs/dif-defense
- Proof surface: runnable clean-versus-injected demo, structured result, containment primitives

### LocalParse
Static, browser-only JSON and JSONL inspector. No backend, account, telemetry, or upload path.

- Repository: https://github.com/cwwjacobs/LocalParse
- Proof surface: dependency-free static app, local file inspection, JSON and JSONL export

### Receipt Fixer
Local Windows utility that converts receipt images and PDFs into a verified CSV, flags low-confidence fields, and writes an audit log beside the output.

- Repository: https://github.com/cwwjacobs/receipt-fixer
- Proof surface: local OCR pipeline, tests, verification receipt, packaged-product path

## External delivery proof

### Memanto SkillChain bridge
Designed and implemented a reviewer-safe Claude Code Skills + Memanto memory bridge with deterministic local validation and an optional live integration path.

- Contribution: https://github.com/moorcheh-ai/memanto/pull/717
- Reproducible demo: https://github.com/cwwjacobs/mdemo

## Services

### Agent-ready repository hardening
I turn an AI-built or partially built repository into a bounded, maintainable delivery surface.

Typical deliverables:
- repository map and source-of-truth identification
- focused bug fixes and integration repair
- tests, smoke commands, and CI rails
- `AGENTS.md` or implementation handoff instructions
- claim-boundary and security documentation
- release receipt and remaining-risk report

### Evaluation harness and benchmark implementation
I build deterministic or hybrid evaluation workflows for structured AI tasks.

Typical deliverables:
- case schema and frozen evaluation pack
- model transport integration
- structured output validation
- expected-versus-predicted comparison
- reproducible receipts, hashes, latency, and usage records
- local or API-backed runner

### Local-first AI utility or workflow prototype
I build compact tools that keep sensitive data on the customer device whenever the workflow allows it.

Typical deliverables:
- browser-only HTML utility, Python CLI, Tauri shell, or local API
- explicit data-flow and privacy boundary
- import, export, and verification paths
- demo fixture and packaged handoff

### AI security and prompt-injection test harness
I build bounded test rigs for agent behavior, untrusted-content handling, canary leakage, tool-output poisoning, and observable trace comparison.

Typical deliverables:
- threat hypothesis and scope guard
- clean and adversarial fixtures
- repeatability measurement
- structured evidence receipts
- mitigation notes and regression cases

## Working style

- Evidence before adjectives
- Smallest coherent patch
- Tests before victory laps
- Local-first when practical
- Explicit claim boundaries
- Receipts that survive the demo

## Contact

- GitHub: https://github.com/cwwjacobs
- Contra: https://contra.com/TerminusProtocol
