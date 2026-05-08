# Hugging Face Map

Status: Public scaffold. Release status: scaffolded. License pending human review.

## Purpose

This file records how `franzabner-proof-stack` may reference Hugging Face. Hugging Face is a release surface only. It is not the canonical home for private model development, sealed datasets, private corpora, unreleased results, DGX workflows, or development artifacts.

## HF Routing

| Repo or lane | HF role | Current status | Allowed public wording | Review gate |
|---|---|---|---|---|
| `franzabner-proof-stack` | Tracks HF proof entries and release status. | Public scaffold | Planned or scaffolded release-readiness tracking only. | Artifact evidence row required. |
| `hf-card-templates` | Provides model, dataset, report, and Space card templates. | Live public scaffold | Template language only. No artifact exists because this repo exists. | Template and status review. |
| `engineering-agent-review-gates` | Supports release-gate discipline for AI-assisted engineering workflows. | Live public scaffold | Review-gate language only. | No private prompt, memory, tool, endpoint, corpus, or model route. |
| `local-ai-lab-boundary` | Process and boundary reference only. | Live public scaffold | No HF artifact exists because this repo exists. It may be referenced only as a boundary model for public-safe lab documentation. | No model, dataset, Space, benchmark, eval result, hosted artifact, endpoint, private corpus, private weight, private prompt, or private harness claim. |
| `dgx-ai-workstation-notes` | Process and workstation workflow reference only. | Live public scaffold | No HF artifact exists because this repo exists. It may be referenced only as public-safe DGX/NVIDIA/workstation documentation. | No model, dataset, Space, benchmark, eval result, hosted artifact, endpoint, private corpus, private weight, private prompt, private harness, training run, model output, or real topology claim. |
| `technical-readme-lab` | Supports release-readiness documentation patterns. | Live public scaffold | Documentation scaffold only. | No fake external references or service claims. |
| EPI spine | `energy-per-intelligence`, `epi-bench`, `epi-meter` | Merged scaffolds | Research, tooling, and measurement readiness only. | No benchmark, eval result, dataset, model, Space, hosted artifact, or release claim. |
| Paper-specific EPI repos | `attention-head-surgery-epi`, `mixed-quant-epi`, `expert-pruning-epi` | Merged paper/research scaffolds | GitHub paper-scaffold links only. No HF artifact exists because these repos exist. | No benchmark, eval result, dataset, model, Space, hosted artifact, or release claim. |
| Fine-tuning derivative repos | Future public-safe workflow patterns. | Held / planned | Process reference only after review. `local-ai-lab-boundary` and `dgx-ai-workstation-notes` are live boundary/workflow scaffolds, not HF artifact sources. | No topology, credentials, private corpora, weights, endpoints, results, benchmarks, logs, training runs, model outputs, models, datasets, Spaces, or hosted artifacts. |

## Forbidden HF Claims

- No released model, dataset, Space, report, benchmark, eval result, endpoint, hosted model, or hosted dataset claim without public evidence and human approval.
- No fake weights, datasets, Spaces, metrics, or demo artifacts.
- No private corpora, adapters, traces, model outputs, training logs, DGX topology, endpoints, or infrastructure details.
- No Foundation artifact under the Franzabner personal proof surface.

## Review Requirement

Any future HF row must name the artifact class, status, evidence, limitations, provenance, private exclusions, review requirement, and review date before external use.
