# Repo Map

Status: Public scaffold. Release status: scaffolded. License pending human review.

## Purpose

This file maps `franzabner-proof-stack` to the current Franzabner public technical repo system. It is a navigation and proof-control map only. It does not authorize additional GitHub repo creation, Hugging Face artifacts, Upwork listings, release claims, or unsupported external references.

## Current Public Repo Lanes

| Lane | Repos | Proof role | Current status | Review gate |
|---|---|---|---|---|
| Navigation | `Franzabner`, `franzabner-proof-stack` | Account front door and claim-control layer. | Live public scaffold. | Identity, status-language, and boundary review. |
| Electrical / KiCad / PCB | `public-pcb-review-checklist`, `electrical-panel-dressing` | Electrical review discipline, panel documentation posture, and public-safe checklist structure. | Live / merged scaffold. | Board-source, routing, BOM, Gerber, pin-map, certification, and sign-off review. |
| Field / mission-critical discipline | `field-to-architect`, `mission-critical-discipline` | Field-to-architecture translation and mission-critical documentation discipline. | Merged scaffold. | No deployment, client, customer, revenue, or production claim without review. |
| Embedded / Pico / RP2350 | `pico2-pio-i2c-reference` | Embedded reference workflow and interface documentation proof. | Merged scaffold. | Firmware, protocol, pin-map, and production integration review. |
| Hardware breadboard / RIB boundary | `rib-breadboard` | Public breadboard/reference scaffold and hardware boundary discipline. | Merged scaffold. | Production RIB implementation remains sealed; no production board files, firmware internals, BOMs, Gerbers, pin maps, routing, manufacturing approval, certification, sign-off, or production-ready claim. |
| Agents / review gates | `engineering-agent-review-gates` | AI-assisted engineering review gates and human authority discipline. | Live public scaffold. | No private prompt, memory, tool, endpoint, corpus, or harness exposure. |
| Local AI lab boundary | `local-ai-lab-boundary` | First derivative public boundary repo for documenting local AI lab, AI workstation, and agent-workflow concepts without exposing real infrastructure. | Live public scaffold. | Synthetic-only examples; no real topology, endpoints, credentials, tokens, private corpora, private weights, private prompts, private agent harnesses, or sealed YOSO-YAi IP. |
| DGX / NVIDIA workstation notes | `dgx-ai-workstation-notes` | Second derivative public repo for DGX/NVIDIA/workstation workflow documentation without exposing real infrastructure. | Live public scaffold. | Synthetic-only examples; no real topology, hostnames, IPs, endpoints, credentials, tokens, Tailscale, SSH, Forgejo, n8n, LiteLLM, NIM details, private corpora, private weights, private prompts, private agent harnesses, sealed YOSO-YAi IP, model, dataset, Space, training run, model output, or hosted artifact claim. |
| Fine-tuning lab notes | `fine-tuning-lab-notes` | Legacy fine-tuning lab-note scaffold. Public-safe note structure, dataset-boundary fields, no-result language, and release gates migrated to `data-model-infrastructure`, `engineering-deliverables-template`, and `engineering-standards-and-validation`. | Archived-legacy candidate; retained only for archive-decision tracking. | No private corpora, private weights, adapters, training logs, eval results, model, dataset, Space, hosted artifact, real training run, model output, private endpoint, private prompt, private harness, HF action, release, metadata, publication, or proof-completion claim. |
| Energy systems / control ledger / simulation-first engineering | `s2h-g-control-ledger` | Public proof surface for a proprietary simulation-first energy-control project: solar-energy accounting, water-quality gating, electrolyzer-cell model boundaries, MCU-style fault shutdown doctrine, and daily generation ledger structure. | Live public proof surface. Implementation withheld. All rights reserved. | No public simulator implementation, no public reuse license, no generation-guide claim, and no claim that private implementation details are public. |
| Evidence-boundary simulation / anomalous-motion framework | `field-propulsion-observatory` | Public-safe engineering documentation and lightweight simulation repo for anomalous-motion evidence frameworks, sensor metadata schemas, trajectory/uncertainty reasoning, and hypothesis-boundary mapping. | Live public scaffold. | Synthetic examples only; no exotic propulsion claim, real case claim, Hugging Face artifact, Upwork listing, released dataset, model, Space, benchmark, eval result, deployment, or verified propulsion claim. |
| README/productization proof | `technical-readme-lab` | Synthetic README quality and repo-polish proof. | Live public scaffold. | Example, status, and claim review. |
| Hugging Face readiness | `hf-card-templates` | Legacy model-card, dataset-card, Space-card, report, and release-checklist template scaffold. Public-safe template structure and release gates migrated to `data-model-infrastructure`, `engineering-deliverables-template`, and `engineering-standards-and-validation`. | Archived-legacy candidate; retained only for archive-decision tracking. | No Hugging Face model, dataset, Space, card, release, metadata, publication, benchmark, eval result, hosted artifact, or proof-completion claim. |
| Batch 6 EPI spine | `energy-per-intelligence`, `epi-bench` | Legacy EPI research and benchmark scaffolds. Public-safe taxonomy, benchmark-scaffold boundaries, no-result language, synthetic field names, and generic energy framing migrated to `data-model-infrastructure`, `engineering-simulation-lab`, `engineering-standards-and-validation`, and `infrastructure-energy-studies`. | Archived-legacy candidates; retained only for archive-decision tracking. | No benchmark validity, measured result, dataset, model, Space, Hugging Face, release, deployment, production-readiness, customer outcome, or proof-completion claim. |
| Paper-specific EPI archived-legacy candidates | `attention-head-surgery-epi`, `mixed-quant-epi`, `expert-pruning-epi` | Legacy paper/research scaffolds for attention-head intervention, mixed quantization, and expert pruning EPI directions. Public-safe EPI taxonomy and claim gates have migrated to `data-model-infrastructure`, `engineering-simulation-lab`, and `engineering-standards-and-validation`. | Archived-legacy candidates; superseded by umbrella repos and retained only for archive-decision tracking. | No model, dataset, Space, Hugging Face, benchmark, result, proof-completion, release, deployment, private harness, or proven result claim. |

## Held Repo Lanes

| Lane | Held repos or examples | Hold reason |
|---|---|---|
| Mechanical / Fusion 360 | Fusion and enclosure portfolio candidates | Asset, geometry, dimensions, export, and manufacturing review required. |
| KiCad / PCB production | KiCad libraries, production board candidates, production RIB materials | Board-source, routing, BOM, Gerber, pin map, manufacturing, and certification review required. |
| Fine-tuning / evaluation candidates beyond archived-legacy `fine-tuning-lab-notes` | future evaluation, model-release, and lab-note candidates | `fine-tuning-lab-notes` is no longer an active proof surface. Additional candidates still require corpus, private weights, endpoint, log, benchmark, model output, and result review. |
| Agents / harnesses | private harness, memory schema, autonomous engineering candidates | Private prompt, tool, memory, corpus, endpoint, and sealed YOSO-YAi boundary review required. |
| Omniverse / USD / 3D worlds | USD scene, worldbuilding, and 3D engineering candidates | Scene, private CAD, product geometry, facility, and asset review required. |
| Real anomalous-motion case analysis | real public case analysis, disputed-event narratives, propulsion conclusions | `field-propulsion-observatory` is live only as a synthetic evidence-boundary and simulation scaffold. Real case analysis, external accusations, or stronger propulsion language require separate human review. |
| S2H-G private implementation | future private company/org implementation repo | `s2h-g-control-ledger` is the public proof surface only. Full implementation remains private and proprietary unless separately authorized. |

## Review Notes

- Live links do not imply released products.
- Public-surface alignment does not imply customer use, deployment, revenue, manufacturing approval, certification, sign-off, model release, dataset release, Space release, benchmark validity, eval result, or hosted artifact status.
- Public evidence must be synthetic, reviewed, or already approved for public use.
