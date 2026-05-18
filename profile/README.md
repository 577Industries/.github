<div align="center">

# 577 Industries

**Dual-use commercial and defense AI systems engineering.**
577 Industries Incorporated  ·  Columbus, Ohio

</div>

577 Industries builds **calibrated, provenance-tracked decision systems** for environments where being wrong is expensive — space-weather and GNSS for civilian and defense missions, secure-messaging-application assessment for the U.S. Department of Defense, and the agent infrastructure that runs underneath them.

Every public artifact ships with a license, a CI badge, and citable evidence. Every internal artifact is gated by a documented IP boundary. The list below is the entry point.

[![License: Apache 2.0](https://img.shields.io/badge/license-Apache_2.0-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0)
[![SBIR](https://img.shields.io/badge/SBIR-NASA_Phase_I_submitted-0b3d91)](https://github.com/577Industries/helios-program)
[![Patents](https://img.shields.io/badge/patents-5_described_(2025--2026)-7c3aed)](#forge-os--agent-infrastructure-apache-20)
[![npm](https://img.shields.io/badge/npm-@577--industries-cb3837)](https://www.npmjs.com/search?q=%40577-industries)

---

## Programs

Each program is a discrete SBIR / contract-research thread with its own repos, release cadence, and evidence trail. New SBIRs land here as separate cards.

### HELIOS — Calibrated Heliophysics Fusion

![status](https://img.shields.io/badge/status-NASA_SBIR_Phase_I_submitted_2026--05--18-0b3d91) ![phase-ii](https://img.shields.io/badge/Phase_II-ready-009688)

Calibrated, provenance-tracked fusion of space-weather model outputs across two vertical slices: NASA SRAG mission-operations radiation risk and U.S. precision-agriculture GNSS. Subtopic SPWX.1.S26A.

> [!NOTE]
> Headline result: **1,302 station-hours of U.S. row-crop GNSS pushed past the 2.5 cm tolerance** during the May 2024 Gannon G5 superstorm — the first citable quantification of solar-storm impact on U.S. agriculture (climatological v1; real-SPP v2 in progress).

| Repo | What it is |
|---|---|
| [`helios-program`](https://github.com/577Industries/helios-program) | Umbrella meta-repo, master plan, companion document, 4 submodules |
| [`helios-provenance-spec`](https://github.com/577Industries/helios-provenance-spec) | JSON Schema 2020-12 + W3C PROV-JSON RFC for feature-level lineage |
| [`helios-spaceweather-connectors`](https://github.com/577Industries/helios-spaceweather-connectors) | 6 production adapters (DONKI, SEP A/B/C, SWPC, GOES, DSCOVR, CDDIS GIMs) |
| [`helios-fusion-engine`](https://github.com/577Industries/helios-fusion-engine) | BMA + isotonic + Mondrian conformal calibration + arXiv preprint draft |
| [`gannon-storm-rtk-analysis`](https://github.com/577Industries/gannon-storm-rtk-analysis) | May 2024 Gannon G5 retrospective on NGS CORS network |

**Public companion document:** [577industries.github.io/helios-program](https://577industries.github.io/helios-program/)

---

### AEGIS — DARPA ASEMA application-layer assessment

![status](https://img.shields.io/badge/status-DARPA_evaluation-grey)

Graph-based application-layer assessment evidence platform for Secure Messaging Applications. DARPA contract HR0011SB20254-12, Tier 3 research, currently under evaluation.

| Repo | What it is |
|---|---|
| [`aegisgraph`](https://github.com/577Industries/aegisgraph) | Feasibility artifact — URL frozen during evaluation |

> [!IMPORTANT]
> Program materials and evaluation evidence are intentionally limited during the DARPA evaluation window. Additional artifacts will land in this org post-evaluation.

---

### ASEMA — DARPA secure-messaging assessment (founder account)

![status](https://img.shields.io/badge/status-DARPA_evaluation-grey)

DARPA ASEMA feasibility artifacts are currently hosted on the founder's personal account during the evaluation window. Will consolidate to the `577Industries` org post-evaluation.

| Repo | What it is |
|---|---|
| [`577-Industries/asema-feasibility-artifacts`](https://github.com/577-Industries/asema-feasibility-artifacts) | Feasibility artifacts (founder account, transitional) |

---

## FORGE OS — Agent infrastructure (Apache 2.0)

Reusable TypeScript libraries for AI-agent applications. Each library implements an algorithm described in a 2025–2026 patent. npm packages publish under `@577-industries/*` today; an `@577industries/forge-*` rebrand is on the roadmap (as of 2026-05).

| Library | Purpose | Patent (described) |
|---|---|---|
| [`forge-agent-memory`](https://github.com/577Industries/forge-agent-memory) | Persistent memory: log-reinforcement, exponential decay, composite recall | Autonomous Memory Evolution — Dec 2025 |
| [`forge-model-router`](https://github.com/577Industries/forge-model-router) | Multi-provider routing: 6 strategies, sovereign profiles, cost ceiling | Adaptive Model Routing — Feb 2026 |
| [`forge-tool-guardrails`](https://github.com/577Industries/forge-tool-guardrails) | 4-level middleware (none/log/pause/block) + HITL approval | Governed Autonomy Framework — Jan 2026 |
| [`forge-workflow-dag`](https://github.com/577Industries/forge-workflow-dag) | YAML → DAG compiler (Kahn topological sort, cycle detection) | Workflow DAG Compiler — Mar 2026 |
| [`forge-hashchain-audit`](https://github.com/577Industries/forge-hashchain-audit) | Tamper-evident audit (SHA-256 chaining + Ed25519 + Merkle anchoring) | Hash-Chained Audit Ledger — Mar 2026 |

---

## Recent

- **2026-05-18** — HELIOS NASA SBIR Phase I proposal submitted; Phase II evidence in assembly.
- **2026-03** — `forge-workflow-dag` and `forge-hashchain-audit` patents described.
- **2026-02** — `forge-model-router` patent described.
- **2025-12** — `forge-agent-memory` patent described; first FORGE OS library shipped to npm.

---

<INFO@577INDUSTRIES.COM>

---

<div align="center">
<sub>© 2025–2026 577 Industries Incorporated · Columbus, Ohio · Apache 2.0 except where noted</sub>
</div>
