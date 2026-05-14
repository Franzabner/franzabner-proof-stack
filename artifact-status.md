# Artifact Status

Status: `scaffolded` locally after Phase 1 patch  
Purpose: artifact availability and release-state control

## Status Vocabulary

Use only these approved top-level labels: `planned`, `scaffolded`, `published`, `released`, `paused`, `deprecated`, and `private/not-public`.

Artifact presence may be described as present or absent, but the status field must stay within the approved vocabulary.

## Phase 1 Artifact Table

| Repo or artifact | Artifact presence | Status | Public/release state | Review need |
| --- | --- | --- | --- | --- |
| `Franzabner` profile file set | Present locally after Phase 1 patch. | `scaffolded` | Local patch only; not pushed or newly published by Phase 1. | Human review before push or public routing update. |
| `franzabner-proof-stack` file set | Present locally after Phase 1 patch. | `scaffolded` | Local patch only; not pushed or newly published by Phase 1. | Human review before push or public routing update. |
| [`modular-infrastructure-studies`](https://github.com/Franzabner/modular-infrastructure-studies) | Public scaffold repo present; first artifact at [`studies/modular-serviceability-study.md`](https://github.com/Franzabner/modular-infrastructure-studies/blob/main/studies/modular-serviceability-study.md). | `scaffolded` | Public scaffold only; not released, deployed, certified, product-ready, or proof-complete. | Human review before profile routing, proof promotion, release language, pinning, or metadata changes. |
| [`cad-mechanical-design-lab`](https://github.com/Franzabner/cad-mechanical-design-lab) | Public scaffold repo present; first artifact at [`design-studies/synthetic-enclosure-study.md`](https://github.com/Franzabner/cad-mechanical-design-lab/blob/main/design-studies/synthetic-enclosure-study.md). | `scaffolded` | Public scaffold only; not released, no production CAD, no CAD export approval, and no deployment/certification/product-readiness claim. | Human CAD-boundary review before profile routing, proof promotion, screenshots, exports, renders, pinning, or metadata changes. |
| `electrical-controls-architecture` | Absent in Phase 1. | `planned` | No public repo or release claim from this patch. | Human approval before creation. |
| `embedded-hardware-lab` | Absent in Phase 1. | `planned` | No public repo or release claim from this patch. | Human approval before creation. |
| `engineering-simulation-lab` | Absent in Phase 1. | `planned` | No public repo or release claim from this patch. | Human approval before creation. |
| `data-model-infrastructure` | Absent in Phase 1. | `planned` | No public repo or release claim from this patch. | Human approval before creation. |
| `infrastructure-energy-studies` | Absent in Phase 1. | `planned` | No public repo or release claim from this patch. | Human approval before creation. |
| `civic-infrastructure-production-systems` | Absent in Phase 1. | `planned` | No public repo or release claim from this patch. | Human approval and Foundation-boundary review before creation. |
| `engineering-standards-and-validation` | Absent in Phase 1. | `planned` | No public repo or release claim from this patch. | Human approval before creation. |
| `engineering-security-boundary` | Absent in Phase 1. | `planned` | No public repo or release claim from this patch. | Human approval before creation. |
| `engineering-deliverables-template` | Absent in Phase 1. | `planned` | No public repo or release claim from this patch. | Human approval before creation. |
| `application-development-systems` | Absent in Phase 1. | `planned` | No public repo or release claim from this patch. | Human approval before creation. |
| `immersive-access-systems` | Absent in Phase 1. | `planned` | No public repo or release claim from this patch. | Human approval before creation. |
| `automated-engineering-systems` | Absent in Phase 1. | `planned` | No public repo or release claim from this patch. | Human approval before creation. |
| `agentic-engineering-workforce` | Absent in Phase 1. | `planned` | No public repo or release claim from this patch. | Human approval before creation. |
| Existing supporting narrow repos | Not changed by Phase 1. | `private/not-public` unless a separate repo review confirms `planned`, `scaffolded`, `published`, `released`, `paused`, or `deprecated`. | No upgrade, publication, archive, transfer, rename, or visibility change from this patch. | Separate repo-by-repo status, claim, and boundary review. |
| Hugging Face models, datasets, Spaces, cards, collections, or profile metadata | Not changed by Phase 1. | `private/not-public` unless separate release-surface review confirms `planned`, `scaffolded`, `published`, or `released`. | No metadata change, release, hosted artifact, benchmark, eval result, model output, or Space claim. | Separate release-surface review. |

## Release Rule

`released` requires a reviewed public artifact with evidence, limitations, companion links, and approval. Phase 1 does not release any product, model, dataset, Space, benchmark, eval result, report, deployment, service, or hardware artifact.

## Publication Rule

This file may describe scaffolded public files. It does not release artifacts, update GitHub metadata, update Hugging Face metadata, approve profile routing, approve proof completion, or authorize stronger public claims.
