# Hugging Face Map

Status: Public scaffold. Release status: scaffolded. License pending human review.

## Purpose

This file records how `franzabner-proof-stack` may reference Hugging Face. Hugging Face is a release surface only. It is not the canonical home for private model development, sealed datasets, private corpora, unreleased results, DGX workflows, or development artifacts.

## HF Routing

| Repo or lane | HF role | Current status | Allowed public wording | Review gate |
|---|---|---|---|---|
| `franzabner-proof-stack` | Tracks HF proof entries and release status. | Public scaffold | Planned or scaffolded release-readiness tracking only. | Artifact evidence row required. |
| `hf-card-templates` | Legacy model, dataset, report, and Space card template scaffold. | Archived-legacy candidate; superseded by `data-model-infrastructure`, `engineering-deliverables-template`, and `engineering-standards-and-validation`. | Public-safe template structure, no-result language, and release gates migrated to umbrella repos. Legacy name retained only for archive-decision tracking. | No Hugging Face model, dataset, Space, card, release, metadata, publication, hosted artifact, benchmark, result, or proof-completion claim. |
| `engineering-agent-review-gates` | Supports release-gate discipline for AI-assisted engineering workflows. | Live public scaffold | Review-gate language only. | No private prompt, memory, tool, endpoint, corpus, or model route. |
| `local-ai-lab-boundary` | Process and boundary reference only. | Live public scaffold | No HF artifact exists because this repo exists. It may be referenced only as a boundary model for public-safe lab documentation. | No model, dataset, Space, benchmark, eval result, hosted artifact, endpoint, private corpus, private weight, private prompt, or private harness claim. |
| `dgx-ai-workstation-notes` | Process and workstation workflow reference only. | Live public scaffold | No HF artifact exists because this repo exists. It may be referenced only as public-safe DGX/NVIDIA/workstation documentation. | No model, dataset, Space, benchmark, eval result, hosted artifact, endpoint, private corpus, private weight, private prompt, private harness, training run, model output, or real topology claim. |
| `fine-tuning-lab-notes` | Legacy fine-tuning note and release-gate scaffold. | Archived-legacy candidate; superseded by `data-model-infrastructure`, `engineering-deliverables-template`, and `engineering-standards-and-validation`. | Public-safe fine-tuning note structure, dataset-boundary fields, no-result language, and release gates migrated to umbrella repos. Legacy name retained only for archive-decision tracking. | No private corpus, private weight, adapter, training log, eval result, accuracy, benchmark, model, dataset, Space, hosted artifact, real training run, model output, endpoint, private prompt, private harness, HF action, release, metadata, or publication claim. |
| `field-propulsion-observatory` | Evidence-boundary documentation and synthetic simulation reference only. | Live public scaffold | No HF artifact exists because this repo exists. It may be referenced only as public-safe documentation for sensor metadata schemas, trajectory/uncertainty simulation, and hypothesis-boundary mapping. | No model, dataset, Space, benchmark, eval result, hosted artifact, real case claim, exotic propulsion claim, zero-point propulsion proof, anti-gravity proof, recovered craft claim, or HF action claim. Franzabner HF token/auth is still required before any HF action. |
| `s2h-g-control-ledger` | Energy-control ledger documentation reference only. | Live public proof surface | No HF artifact exists because this repo exists. It may be referenced only as public proof-surface documentation for simulation-first energy-control accounting and ledger structure. | No model, dataset, Space, benchmark, eval result, hosted artifact, public simulator implementation, public reuse license, or HF action claim. Franzabner HF token/auth is still required before any HF action. |
| `technical-readme-lab` | Supports release-readiness documentation patterns. | Live public scaffold | Documentation scaffold only. | No fake external references or service claims. |
| Batch 6 EPI archived-legacy candidates | `energy-per-intelligence`, `epi-bench` | Archived-legacy candidates; superseded by `data-model-infrastructure`, `engineering-simulation-lab`, `engineering-standards-and-validation`, and `infrastructure-energy-studies`. | Public-safe taxonomy, benchmark-scaffold boundaries, no-result language, synthetic field names, and energy framing migrated to umbrella repos. Legacy names retained only for archive-decision tracking. | No Hugging Face model, dataset, Space, card, release, metadata, publication, benchmark, measured result, deployment, production-readiness, customer outcome, or proof-completion claim. |
| Paper-specific EPI archived-legacy candidates | `attention-head-surgery-epi`, `mixed-quant-epi`, `expert-pruning-epi` | Archived-legacy candidates; superseded by `data-model-infrastructure`, `engineering-simulation-lab`, and `engineering-standards-and-validation`. | Public-safe EPI taxonomy and claim gates migrated to umbrella repos. Legacy repo names are retained only for archive-decision tracking. | No model, dataset, Space, Hugging Face, benchmark, result, proof-completion, or release claim. |
| Remaining fine-tuning derivative candidates | Future public-safe workflow patterns beyond archived-legacy `fine-tuning-lab-notes`. | Held / planned | Process reference only after review. `local-ai-lab-boundary` and `dgx-ai-workstation-notes` remain boundary/workflow scaffolds; `fine-tuning-lab-notes` is retained only for archive-decision tracking. | No topology, credentials, private corpora, weights, endpoints, results, benchmarks, logs, training runs, model outputs, models, datasets, Spaces, hosted artifacts, or HF action. |

## Forbidden HF Claims

- No released model, dataset, Space, report, benchmark, eval result, endpoint, hosted model, or hosted dataset claim without public evidence and human approval.
- No fake weights, datasets, Spaces, metrics, or demo artifacts.
- No private corpora, adapters, traces, model outputs, training logs, DGX topology, endpoints, or infrastructure details.
- No Foundation artifact under the Franzabner personal proof surface.
- No Franzabner Hugging Face action until Franzabner HF token/auth is configured and human-approved.

## Review Requirement

Any future HF row must name the artifact class, status, evidence, limitations, provenance, private exclusions, review requirement, and review date before external use.
