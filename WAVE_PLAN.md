# Wave Plan

Status: Public scaffold. Release status: scaffolded. License pending human review.

## Purpose

This file records the staged rollout order for the Franzabner public technical surface. Completed waves identify public navigation or merged scaffold alignment only. They do not create release, deployment, client, manufacturing, certification, model, dataset, Space, benchmark, eval-result, or hosted-artifact claims.

## Waves

| Wave | Focus | Repos | Current state | Gate |
|---|---|---|---|---|
| 1 | Navigation and proof control | `Franzabner`, `franzabner-proof-stack` | Live profile and proof-control scaffold. | Identity, status, boundary, and license-path review. |
| 2 | First clean public proof stack | `public-pcb-review-checklist`, `engineering-agent-review-gates`, `hf-card-templates`, `technical-readme-lab` | Live public scaffolds. | Claim, license, artifact, and external-reference review. |
| 3 | First safe old-repo alignment | `electrical-panel-dressing`, `field-to-architect`, `mission-critical-discipline`, `pico2-pio-i2c-reference` | Alignment branches merged to `main`. | Rendered README/status review before stronger public use. |
| 4 | EPI spine alignment | `energy-per-intelligence`, `epi-bench`, `epi-meter` | Alignment branches merged to `main`. | No result, benchmark, dataset, model, Space, production hardware, certification, or deployment claims. |
| 5 | Paper-specific EPI cleanup | `attention-head-surgery-epi`, `mixed-quant-epi`, `expert-pruning-epi` | Alignment PRs merged to `main`. | No released method, benchmark, dataset, model, Space, eval result, deployment, validated method, private harness, or proven result claim. |
| 6 | RIB breadboard boundary cleanup | `rib-breadboard` | Cleanup PR merged to `main`. | Public breadboard/reference scaffold only; production RIB implementation remains sealed. No production board files, firmware internals, BOMs, Gerbers, pin maps, routing, manufacturing approval, certification, sign-off, or production-ready claim. |
| 7 | First derivative public boundary repo | `local-ai-lab-boundary` | Live public scaffold. | Synthetic-only local AI lab boundary model. No real topology, endpoints, credentials, tokens, private corpora, private weights, private prompts, private agent harnesses, or sealed YOSO-YAi IP. |
| 8 | Second derivative public DGX/workstation notes repo | `dgx-ai-workstation-notes` | Live public scaffold. | Public-safe DGX/NVIDIA/workstation workflow notes. Synthetic-only examples. No real topology, hostnames, IPs, endpoints, credentials, tokens, Tailscale, SSH, Forgejo, n8n, LiteLLM, NIM details, private corpora, private weights, private prompts, private agent harnesses, sealed YOSO-YAi IP, model, dataset, Space, training run, model output, or hosted artifact claim. |
| 9 | Third derivative fine-tuning lab notes repo | `fine-tuning-lab-notes` | Live public scaffold. | Public-safe fine-tuning lab-note scaffold. Synthetic-only examples. Dataset prep boundary, model release gate, evaluation note template, and Hugging Face planned/template-only routing. No private corpora, private weights, training logs, eval results, model, dataset, Space, hosted artifact, real training run, model output, or HF action claim. |
| 10 | Evidence-boundary simulation repo | `field-propulsion-observatory` | Live public scaffold. | Public-safe engineering documentation and lightweight simulation scaffold for anomalous-motion evidence frameworks, sensor metadata schemas, trajectory/uncertainty reasoning, and hypothesis-boundary mapping. Synthetic examples only. No exotic propulsion claim, real case claim, Hugging Face artifact, or Upwork listing. |
| 11 | Risky old-repo boundary review | rack, agent, Fusion, KiCad production, production RIB, infrastructure, private-harness-adjacent repos, and real-case analysis lanes | Held or derivative-only. | Boundary review before any edit, link, PR, proof routing, real case analysis, or stronger propulsion language. |
| 12 | Monetization routing | proof entries, `technical-readme-lab`, `local-ai-lab-boundary`, `dgx-ai-workstation-notes`, `fine-tuning-lab-notes`, `field-propulsion-observatory`, draft Upwork maps | Draft only. | Human review of exact external wording. |

## Current Navigation Priority

The public account should now point to:

1. proof navigation;
2. first clean public scaffolds;
3. merged mechanical/electrical/embedded discipline repos;
4. merged EPI spine scaffolds;
5. merged paper-specific EPI scaffolds;
6. merged RIB breadboard reference scaffold;
7. live local AI lab boundary scaffold;
8. live DGX/NVIDIA workstation notes scaffold;
9. live fine-tuning lab-note scaffold;
10. live field propulsion observatory evidence-boundary simulation scaffold;
11. held status for risky production-adjacent, real-case analysis, and remaining derivative-only repos.

## Non-Authorization

This wave plan does not authorize additional GitHub repo creation, repository pinning, Hugging Face repo/card/model/dataset/Space creation, Upwork external use, license selection, release claims, or use of private implementation artifacts.
