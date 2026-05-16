# Wave Plan

Status: Public scaffold. Release status: scaffolded. License pending human review.

## Purpose

This file records the staged rollout order for the Franzabner public technical surface. Completed waves identify public navigation or merged scaffold alignment only. They do not create release, deployment, client, manufacturing, certification, model, dataset, Space, benchmark, eval-result, or hosted-artifact claims.

## Waves

| Wave | Focus | Repos | Current state | Gate |
|---|---|---|---|---|
| 1 | Navigation and proof control | `Franzabner`, `franzabner-proof-stack` | Live profile and proof-control scaffold. | Identity, status, boundary, and license-path review. |
| 2 | First clean public proof stack | `public-pcb-review-checklist`, `engineering-agent-review-gates`, `hf-card-templates`, `technical-readme-lab` | Live public scaffolds except `hf-card-templates`, now an archived-legacy candidate superseded by umbrella template and claim-gate repos. | Claim, license, artifact, and external-reference review. No Hugging Face model, dataset, Space, card, release, metadata, or publication claim. |
| 3 | First safe old-repo alignment | `electrical-panel-dressing`, `field-to-architect`, `mission-critical-discipline`, `pico2-pio-i2c-reference` | Alignment branches merged to `main`. | Rendered README/status review before stronger public use. |
| 4 | EPI spine alignment | `energy-per-intelligence`, `epi-bench`, `epi-meter` | `energy-per-intelligence` and `epi-bench` are archived-legacy candidates; public-safe EPI taxonomy, benchmark-scaffold boundaries, no-result language, synthetic fields, and energy framing migrated to umbrella repos. | No result, benchmark, dataset, model, Space, production hardware, certification, deployment, Hugging Face release, metadata, publication, production-readiness, customer outcome, or proof-completion claim. |
| 5 | Paper-specific EPI cleanup | `attention-head-surgery-epi`, `mixed-quant-epi`, `expert-pruning-epi` | Archived-legacy candidates; public-safe EPI taxonomy and claim gates migrated to `data-model-infrastructure`, `engineering-simulation-lab`, and `engineering-standards-and-validation`. | No model, dataset, Space, Hugging Face, benchmark, result, proof-completion, release, deployment, validated method, private harness, or proven result claim. |
| 6 | RIB breadboard boundary cleanup | `rib-breadboard` | Cleanup PR merged to `main`. | Public breadboard/reference scaffold only; production RIB implementation remains sealed. No production board files, firmware internals, BOMs, Gerbers, pin maps, routing, manufacturing approval, certification, sign-off, or production-ready claim. |
| 7 | First derivative public boundary repo | `local-ai-lab-boundary` | Live public scaffold. | Synthetic-only local AI lab boundary model. No real topology, endpoints, credentials, tokens, private corpora, private weights, private prompts, private agent harnesses, or sealed YOSO-YAi IP. |
| 8 | Second derivative public DGX/workstation notes repo | `dgx-ai-workstation-notes` | Live public scaffold. | Public-safe DGX/NVIDIA/workstation workflow notes. Synthetic-only examples. No real topology, hostnames, IPs, endpoints, credentials, tokens, Tailscale, SSH, Forgejo, n8n, LiteLLM, NIM details, private corpora, private weights, private prompts, private agent harnesses, sealed YOSO-YAi IP, model, dataset, Space, training run, model output, or hosted artifact claim. |
| 9 | Third derivative fine-tuning lab notes repo | `fine-tuning-lab-notes` | Archived-legacy candidate; public-safe note structure, dataset-boundary fields, no-result language, and release gates migrated to umbrella repos. | Retained only for archive-decision tracking. No private corpora, private weights, adapters, training logs, eval results, model, dataset, Space, hosted artifact, real training run, model output, HF action, release, metadata, publication, or proof-completion claim. |
| 10 | Evidence-boundary simulation repo | `field-propulsion-observatory` | Live public scaffold. | Public-safe engineering documentation and lightweight simulation scaffold for anomalous-motion evidence frameworks, sensor metadata schemas, trajectory/uncertainty reasoning, and hypothesis-boundary mapping. Synthetic examples only. No exotic propulsion claim, real case claim, Hugging Face artifact, or Upwork listing. |
| 11 | S2H-G control ledger proof surface | `s2h-g-control-ledger` | Live public proof surface. | Controlled solar hydrogen logic, simulated before silicon. Implementation withheld under a proprietary boundary. All rights reserved. No public simulator implementation, public reuse license, or generation-guide claim. |
| 12 | Risky old-repo boundary review | rack, agent, Fusion, KiCad production, production RIB, infrastructure, private-harness-adjacent repos, and real-case analysis lanes | Held or derivative-only. | Boundary review before any edit, link, PR, proof routing, real case analysis, or stronger propulsion language. |
| 13 | Monetization routing | proof entries, `technical-readme-lab`, `local-ai-lab-boundary`, `dgx-ai-workstation-notes`, umbrella EPI/release-readiness repos, `field-propulsion-observatory`, `s2h-g-control-ledger`, draft Upwork maps | Draft only. `fine-tuning-lab-notes`, `hf-card-templates`, `energy-per-intelligence`, and `epi-bench` are archived-legacy candidates only. | Human review of exact external wording. |

## Current Navigation Priority

The public account should now point to:

1. proof navigation;
2. first clean public scaffolds;
3. merged mechanical/electrical/embedded discipline repos;
4. umbrella EPI/release-readiness repos, with `energy-per-intelligence`, `epi-bench`, `hf-card-templates`, and `fine-tuning-lab-notes` retained only as archived-legacy candidates;
5. archived-legacy candidate status for paper-specific EPI repos, with public-safe EPI material routed through `data-model-infrastructure`, `engineering-simulation-lab`, and `engineering-standards-and-validation`;
6. merged RIB breadboard reference scaffold;
7. live local AI lab boundary scaffold;
8. live DGX/NVIDIA workstation notes scaffold;
9. migrated fine-tuning lab-note template controls in umbrella repos;
10. live field propulsion observatory evidence-boundary simulation scaffold;
11. live S2H-G control ledger proof surface;
12. held status for risky production-adjacent, real-case analysis, and remaining derivative-only repos.

## Non-Authorization

This wave plan does not authorize additional GitHub repo creation, repository pinning, Hugging Face repo/card/model/dataset/Space creation, Upwork external use, license selection, release claims, or use of private implementation artifacts.
