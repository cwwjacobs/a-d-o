# Business Portfolio Launch Checklist

## GitHub pin order

Pin these six repositories in this order:

1. `agent-flight-recorder`
2. `Card-Forge`
3. `ixc-constellation`
4. `dif-defense`
5. `LocalParse`
6. `receipt-fixer`

### Why this order

- **Agent Flight Recorder** is the strongest technical anchor: CI, SDK, API, CLI, Docker, documentation, replay boundaries, and regression-case generation.
- **Card Forge** shows reusable workflow architecture, schemas, validation, and edge-runtime thinking.
- **Constellation** provides the visual product surface and planned-versus-actual drift story.
- **DIF Defense** establishes the AI security and prompt-injection research lane.
- **LocalParse** proves the ability to ship a small, immediately understandable static product.
- **Receipt Fixer** proves practical utility, local processing, verification behavior, and a paid-product path.

## Do not pin yet

### `eval-foundry`
Keep private until the public console, sanitized demo receipt, and product README are ready.

### `Archivist`
The implementation is substantial, but the undocumented browser/backend API path needs one current live validation and a refreshed README before business-facing promotion.

### `Agent-Control-Tower`
The current public README is too thin. Promote after it has screenshots, a quickstart, and a concrete working demo.

### `llm-capability-runner`
The current README points to Edge Light and creates source-of-truth confusion. Repair or archive before promotion.

### `edge-lite`
Strong private build evidence, but it should not be promoted publicly until the product boundary, upstream attribution, screenshots, and on-device proof are packaged.

### `omega-harness`
Impressive architecture, but the current first-cathedral framing is broader than the strongest verified runtime proof. Keep as an internal or secondary case study until a short working demo exists.

### `memanto`
Use as external contribution proof, not as a pinned owned product. Link the upstream PR and the `mdemo` proof repository.

## Enable the portfolio site

Repository:

`https://github.com/cwwjacobs/a-d-o`

The repository now contains:

- `index.html`
- `README.md`
- `CONTRA_SERVICES.md`
- `.github/workflows/pages.yml`
- `.nojekyll`

Manual GitHub steps:

1. Open repository **Settings**.
2. Open **Pages**.
3. Under **Build and deployment**, choose **GitHub Actions** as the source.
4. Open the **Actions** tab and run **Deploy portfolio to GitHub Pages** if the push-triggered run did not start automatically.

Expected site URL after deployment:

`https://cwwjacobs.github.io/a-d-o/`

## GitHub profile copy

### Name

Corey Jacobs | Terminus Protocol

### Bio

Applied AI systems builder focused on agent observability, evaluation harnesses, local-first tools, and security-aware workflows.

### Website

Use the GitHub Pages URL after deployment, or the existing Terminus Protocol site if it has the stronger current business page.

## Contra launch order

Publish these three services first:

1. **I will rescue and harden your AI-built repository**
2. **I will build an evaluation harness for your AI workflow**
3. **I will build a local-first AI or data utility**

The full listing copy is in `CONTRA_SERVICES.md`.

Do not publish a generic “I build any AI app” service. The bounded services are more credible, easier to scope, and better supported by public proof.

## Case studies to add next

### Memanto SkillChain bridge
- upstream contribution PR
- reviewer-safe no-key demo
- describe the problem, implementation, validation, and external reward accurately

### Security bounty placement
- identify the exact bounty page and result record
- capture the placement, task, patch, and outcome
- do not publish the second-place claim without linking the exact proof

### EvalFoundry trace mismatch
- sanitize the demo receipt
- show expected label, predicted label, and deterministic rubric mismatch
- explain that the engine passed while the tested model failed validation

### Archivist
- run current API/browser validation
- capture one successful archive export
- refresh screenshots and setup text

## Immediate definition of done

The business-facing portfolio is launched when:

- the six recommended repositories are pinned
- GitHub Pages is enabled and the portfolio URL loads
- the three Contra services are published
- the portfolio URL is added to GitHub and Contra
- the Memanto contribution is added as a project or case study

Everything after that is optimization, not permission to launch.
