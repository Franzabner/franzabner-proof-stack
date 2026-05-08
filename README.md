# Franzabner Proof Stack

Status: Public scaffold. Release status: scaffolded. License pending human review.

## Purpose

This repository is the public scaffold proof-control layer for Francisco Abner Rivera's `Franzabner` public technical surface. It is not a generic index. It is the master map that keeps public claims tied to evidence, status, boundary review, and human approval before they appear in GitHub navigation, Hugging Face context, or draft Upwork proof routing.

The repo proves that the public surface is being treated as an engineering system: every repo, artifact, card, checklist, synthetic example, and future service route has to carry a status label and a public/private/sealed boundary note.

## Proof Model

| Control | Purpose |
| --- | --- |
| `proof-matrix.md` | Maps planned proof lanes to repos, artifacts, status, and review needs. |
| `claim-register.md` | Records allowed, draft, and forbidden claims. |
| `CLAIMS.md` | Claim-review summary of allowed, review-required, and forbidden claim classes. |
| `artifact-status.md` | Tracks Planned, Scaffolded, Draft, and Human Review Required labels without implying release. |
| `review-log.md` | Records human review decisions before public use. |
| `REVIEW_CHECKLIST.md` | Gate before the proof stack is used for external proof references. |
| `REPO_MAP.md` | Maps planned Franzabner repos by proof lane and review gate. |
| `WAVE_PLAN.md` | Shows the staged rollout order across navigation, hardware, agents, AI, Omniverse, and monetization routing. |
| `HUGGINGFACE_MAP.md` | Keeps Hugging Face as a planned release surface only. |
| `UPWORK_MAP.md` | Keeps Upwork language as draft proof routing only. |
| `MONETIZATION_MAP.md` | Records monetization-readiness boundaries without live offers, pricing, or client claims. |
| `BOUNDARY_MAP.md` | Summarizes public, private, and sealed exclusions by technical lane. |
| `templates/proof-entry.md` | Standard proof entry shape for future rows. |
| `LICENSE_DECISION.md` | Records that license selection is still pending human review. |

## Technical Surface Covered

| Lane | Proof role |
| --- | --- |
| Mechanical / Fusion 360 | Tracks reviewed or synthetic mechanical proof without exposing production CAD, geometry, dimensions, or manufacturing packages. |
| Electrical / KiCad / PCB | Tracks KiCad-adjacent and PCB review proof, with `public-pcb-review-checklist` as the first concrete engineering proof candidate, without exposing production schematics, routing, BOMs, Gerbers, pin maps, or customer files. |
| Embedded / Pico / RP2350 | Tracks embedded reference proof without exposing production firmware, protocols, device credentials, or exact integration maps. |
| Agents / harnesses | Tracks public-safe agent architecture, memory, task contracts, and review gates without exposing private YAi/YOSO-YAi internals. |
| AI-assisted engineering | Tracks workflow discipline across engineering tasks with human authority upstream of AI output. |
| DGX / NVIDIA / fine-tuning | Tracks workstation, runbook, evaluation, and lab-note proof without exposing topology, credentials, private corpora, private weights, or run logs. |
| Hugging Face / EPI | Tracks templates, roadmaps, cards, and release gates without fake weights, datasets, Spaces, benchmark results, or released status. |
| Omniverse / USD / 3D | Tracks synthetic scene and USD pipeline proof without exposing private CAD, product geometry, facility layout, or production scenes. |
| Upwork proof | Routes evidence to draft service lanes without live offer copy, pricing, turnaround promises, or client outcomes. |
| Public/private/sealed boundaries | Records what is public-safe, private, sealed, planned, draft, or human-review gated. |

## Proof Routing

GitHub is the portfolio proof surface. Hugging Face is a release surface only. Upwork language remains draft proof routing until human review approves external wording. This stack sits between those surfaces so a public claim cannot move forward just because a scaffold exists.

## Early Concrete Proof Route

`public-pcb-review-checklist` is the first concrete engineering proof route in this public batch because it can show PCB review discipline, KiCad-adjacent documentation judgment, severity framing, and public-safe report structure without publishing real board source or manufacturing artifacts.

## Operating Rule

No claim is clean public proof until it has:

- an evidence row;
- an artifact status;
- a public/private/sealed boundary note;
- a review requirement;
- a refusal rule for unsupported or unsafe claims.

## Scope Limits

This scaffold does not authorize additional GitHub repo creation, Hugging Face artifact creation, live Upwork copy, license selection, release claims, or edits to existing cloned Franzabner repos.
