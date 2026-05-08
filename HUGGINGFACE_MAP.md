# Hugging Face Map

Status: Public scaffold. Release status: scaffolded. License pending human review.

## Purpose

This file records how `franzabner-proof-stack` may reference Hugging Face in future proof entries. Hugging Face is a release surface only. It is not the canonical home for private model development, sealed datasets, private corpora, unreleased results, DGX workflows, or development artifacts.

## HF Routing

| Repo or lane | HF role | Current status | Allowed public wording | Review gate |
| --- | --- | --- | --- | --- |
| `franzabner-proof-stack` | Tracks HF proof entries and release status. | Scaffolded | Planned or scaffolded release-readiness tracking only. | Artifact evidence row required. |
| `hf-card-templates` | Provides future model, dataset, report, and Space card templates. | Planned / Scaffolded | Template language only. | Template and status review. |
| `model-release-boundary-template` | Defines release decision packet before any artifact status changes. | Planned / Scaffolded | Release-readiness gate only. | Human approval before release status. |
| EPI roadmap and evaluation repos | May support future report or dataset cards. | Planned | Research/evaluation roadmap only. | Provenance, limitations, evidence, and review. |
| DGX / NVIDIA / fine-tuning repos | May document public-safe workflow patterns. | Planned | Process reference only. | No topology, credentials, private corpora, weights, endpoints, or logs. |
| Omniverse / USD repos | May support synthetic scene or report cards later. | Planned | Synthetic asset metadata only. | Asset and scene review. |

## Forbidden HF Claims

- No released model, dataset, Space, report, benchmark, or endpoint claim without public evidence and human approval.
- No fake weights, datasets, Spaces, metrics, or demo artifacts.
- No private corpora, adapters, traces, model outputs, training logs, DGX topology, endpoints, or infrastructure details.
- No Foundation artifact under the Franzabner personal proof surface.

## Review Requirement

Any future HF row must name the artifact class, status, evidence, limitations, provenance, private exclusions, review requirement, and review date before external use.
