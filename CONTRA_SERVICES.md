# Contra Service Listings

These are written as bounded offers for a solo operator. Prices are launch recommendations, not market claims. Adjust after the first three paid projects.

---

## Service 1: I will rescue and harden your AI-built repository

### One-line description
I turn a fragile, confusing, or partially working AI-built codebase into a tested repository another developer can understand and continue.

### Best for
- AI-generated apps that almost work
- abandoned prototypes with unclear structure
- repos that break during setup or deployment
- founders preparing a technical handoff
- teams that need a reliable source of truth before adding features

### What I deliver
- source-of-truth and repository map
- setup and runtime diagnosis
- focused repair of the agreed blocker
- targeted tests or smoke checks
- cleaned setup instructions
- `AGENTS.md` or developer handoff guidance when useful
- final change report with files changed, tests run, remaining risks, and exact next steps

### Process
1. Inspect the repository and reproduce the blocker.
2. Freeze the task boundary and identify the smallest coherent repair.
3. Implement and verify the repair.
4. Package the result for a human or coding agent to continue safely.

### Starting package
**Repository Rescue Sprint**

- one repository
- one primary blocker or tightly related blocker cluster
- up to 10 changed files unless agreed otherwise
- targeted tests and final receipt
- delivery target: 2 to 4 business days
- recommended launch price: **$350**

### Add-ons
- CI workflow: +$125
- deployment repair: +$175
- additional blocker cluster: +$150
- architecture and technical-debt map: +$175

### Public proof
- Agent Flight Recorder: https://github.com/cwwjacobs/agent-flight-recorder
- Memanto SkillChain contribution: https://github.com/moorcheh-ai/memanto/pull/717
- Reproducible demo: https://github.com/cwwjacobs/mdemo

### Client requirements
- repository access or a source archive
- the expected working behavior
- known setup commands, credentials boundary, and deployment target if applicable

### Boundary
This service is a bounded implementation and hardening sprint. It is not an unlimited rewrite, ongoing maintenance contract, penetration test, or guarantee that every defect in the repository has been found.

---

## Service 2: I will build an evaluation harness for your AI workflow

### One-line description
I build a reproducible evaluation path that tests whether your AI feature still behaves correctly after prompt, model, data, or workflow changes.

### Best for
- structured classification or extraction workflows
- teams switching models or providers
- prompt and RAG regression testing
- JSON or schema-constrained outputs
- internal AI features that need evidence before release

### What I deliver
- evaluation case schema
- starter case pack from client-provided examples
- model or application transport integration
- structured output parser and validator
- expected-versus-predicted result view
- run receipts with configuration, hashes, latency, and usage when available
- command-line or local API run path
- final replay instructions and limitations

### Process
1. Define the exact behavior that must be preserved.
2. Convert representative examples into a frozen case format.
3. Connect the target model, API, or workflow.
4. Run, validate, and package reproducible receipts.

### Starting package
**AI Regression Harness Starter**

- one target workflow or endpoint
- up to 25 client-provided cases
- one structured validator
- one model or application transport
- local CLI or API run path
- delivery target: 3 to 5 business days
- recommended launch price: **$500**

### Add-ons
- second model or provider transport: +$150
- additional 50 cases: +$125
- comparison report: +$150
- simple browser results console: +$250

### Public proof
- Agent Flight Recorder: https://github.com/cwwjacobs/agent-flight-recorder
- Card Forge: https://github.com/cwwjacobs/Card-Forge
- Eval-oriented workflow and receipt patterns are available in public repositories; private benchmark demonstrations are available on request.

### Client requirements
- representative inputs
- expected outputs or an explicit scoring rule
- target API, model endpoint, or callable workflow
- permission to test the supplied system

### Boundary
The harness measures the supplied cases and validator. It does not prove universal model quality, production safety, regulatory compliance, or correctness outside the tested behavior.

---

## Service 3: I will build a local-first AI or data utility

### One-line description
I build a compact browser, Python, or desktop utility that keeps customer data local whenever the workflow allows it.

### Best for
- private JSON, JSONL, CSV, document, or image workflows
- internal tools that do not need a cloud account system
- repeatable file transformation and verification
- local model or API-assisted utilities
- founders who need a focused MVP instead of a large platform

### What I deliver
- one bounded local workflow
- clear import and export path
- browser-only HTML, Python CLI, local API, or small desktop shell
- validation and failure states
- sample files and smoke test
- privacy and data-flow boundary
- setup instructions and packaged handoff

### Process
1. Freeze one user journey and its input/output contract.
2. Select the lightest runtime that fits the job.
3. Build the working path and visible failure states.
4. Test with fixtures and package the handoff.

### Starting package
**Local Utility MVP**

- one primary workflow
- one input format and one output format
- simple interface or CLI
- sample fixture and smoke test
- delivery target: 4 to 7 business days
- recommended launch price: **$650**

### Add-ons
- second file format: +$125
- local model integration: +$200
- signed Windows packaging: quoted separately
- polished visual interface: +$250

### Public proof
- LocalParse: https://github.com/cwwjacobs/LocalParse
- Receipt Fixer: https://github.com/cwwjacobs/receipt-fixer
- Constellation: https://github.com/cwwjacobs/ixc-constellation

### Client requirements
- representative sample files with sensitive values removed
- expected output examples
- target operating system and distribution requirements

### Boundary
Local-first means the delivered workflow is designed to process data locally. Operating-system compromise, external dependencies, optional remote model calls, and client modifications can change that boundary.

---

# Suggested Contra profile headline

**Applied AI Systems Builder | Agent Observability, Eval Harnesses, Local-First Tools**

# Suggested profile summary

I turn ambiguous AI and software problems into bounded, testable systems. My work focuses on agent observability, deterministic evaluation, local-first utilities, security-aware workflows, and repository rescue.

I am strongest in the hard middle between an attractive prototype and something another person can actually run: tracing the source of truth, repairing integrations, adding tests, constraining claims, producing receipts, and packaging a clean handoff.

Public work includes Agent Flight Recorder, Card Forge, Constellation, DIF Defense, LocalParse, and Receipt Fixer. I have also shipped a reviewer-safe SkillChain memory integration for the Memanto project with a reproducible no-credential proof path.

Bring me the repository, workflow, or prototype that is close but not trustworthy yet.

# Suggested skills/tags

- AI Development
- Python
- JavaScript
- API Integration
- AI Agents
- LLM Evaluation
- Developer Tools
- Cybersecurity
- Automation
- Technical Documentation
- GitHub Actions
- Local-First Software
