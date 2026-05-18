# 577 Industries

Dual-use space-weather + GNSS decision intelligence. NASA SBIR, DARPA, and FORGE OS platform engineering.

577 Industries Inc., Columbus OH. Founded by [Thomas Waweru](https://github.com/577-Industries).

---

## Active Programs

### HELIOS — Calibrated Heliophysics Fusion

NASA SBIR Phase I (submitted; Phase II re-pitch in development). Subtopic SPWX.1.S26A. Calibrated, provenance-tracked fusion of space-weather model outputs for NASA mission operations (SRAG radiation risk) and U.S. precision-agriculture GNSS.

[**helios-program**](https://github.com/577Industries/helios-program) — meta-repo, companion document, master plan, and 4 public artifacts as submodules. Visit the [companion site](https://577industries.github.io/helios-program/) for the public-facing proposal mirror.

| Artifact | What it is | Latest |
|---|---|---|
| [helios-program](https://github.com/577Industries/helios-program) | Umbrella meta-repo + 4 submodules | ![](https://img.shields.io/github/v/release/577Industries/helios-program) |
| [helios-provenance-spec](https://github.com/577Industries/helios-provenance-spec) | JSON Schema + W3C PROV-JSON RFC for feature-level lineage | ![](https://img.shields.io/github/v/release/577Industries/helios-provenance-spec) |
| [helios-spaceweather-connectors](https://github.com/577Industries/helios-spaceweather-connectors) | 6 production adapters: DONKI, SEP Scoreboards A/B/C, SWPC, GOES, DSCOVR, CDDIS GIMs | ![](https://img.shields.io/github/v/release/577Industries/helios-spaceweather-connectors) |
| [helios-fusion-engine](https://github.com/577Industries/helios-fusion-engine) | BMA + isotonic + Mondrian conformal framework + arXiv preprint draft | ![](https://img.shields.io/github/v/release/577Industries/helios-fusion-engine) |
| [gannon-storm-rtk-analysis](https://github.com/577Industries/gannon-storm-rtk-analysis) | First citable quantification of solar-storm impact on U.S. row-crop GNSS — **1,302 station-hours over 2.5 cm** during the May 2024 Gannon G5 superstorm (climatological v1; real-SPP v2 pending TFT-TEC track) | ![](https://img.shields.io/github/v/release/577Industries/gannon-storm-rtk-analysis) |

---

### AEGIS — (DARPA, in evaluation)

[**aegisgraph**](https://github.com/577Industries/aegisgraph) — feasibility artifact (URL frozen during DARPA evaluation).

### ASEMA — (DARPA, in evaluation)

[**asema-feasibility-artifacts**](https://github.com/577-Industries/asema-feasibility-artifacts) on the founder's personal account during DARPA evaluation. Will consolidate to the `577Industries` org post-evaluation.

---

## FORGE OS — Open-source agent infrastructure

Reusable TypeScript libraries for AI-agent applications. Apache 2.0.

| Library | Purpose |
|---|---|
| [forge-agent-memory](https://github.com/577Industries/forge-agent-memory) | Bio-inspired persistent memory for LLM agents (logarithmic reinforcement, exponential decay) |
| [forge-model-router](https://github.com/577Industries/forge-model-router) | Multi-provider model routing with 6 strategies, sovereign profiles, cost-ceiling enforcement |
| [forge-tool-guardrails](https://github.com/577Industries/forge-tool-guardrails) | 4-level guardrail middleware (none/log/pause/block) with human-in-the-loop approval workflow |
| [forge-hashchain-audit](https://github.com/577Industries/forge-hashchain-audit) | Tamper-evident audit trail (SHA-256 hash chaining + Ed25519 + Merkle anchoring) |
| [forge-workflow-dag](https://github.com/577Industries/forge-workflow-dag) | YAML-to-DAG workflow compiler (Kahn's topological sort, cycle detection, parallel groups) |

**Note**: npm packages currently publish under the `@577-industries/<name>` scope. A separate npm rebrand to `@577industries/forge-<name>` is on the operator's roadmap; until then, repo URLs and npm names intentionally diverge.

---

## Internal

| Repo | Visibility | Purpose |
|---|---|---|
| [577i-unified](https://github.com/577Industries/577i-unified) | private | FORGE OS platform monorepo |
| [helios-fusion-internal](https://github.com/577Industries/helios-fusion-internal) | private | HELIOS trained weights, BMA priors, equipment transfer functions (IP-gated) |

---

## Contact

Engineering: <engineering@577industries.com>
PI / Founder: Thomas Waweru — <gitongaw@gmail.com>

Patent disclosure and SBIR data-rights inquiries: contact engineering@.
