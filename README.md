# Franzabner Proof Stack

Status: `scaffolded` locally after Phase 1 patch  
Purpose: master proof index and claim-control spine for Francisco Abner Rivera's public engineering surface

## Proof Model

Every public claim must map to:

- a repository or artifact;
- an approved status label;
- an artifact class;
- a public/private/sealed boundary;
- a validation method;
- an evidence state;
- a human review state;
- a next review action.

This repository is a control layer. It does not release products, create umbrella repositories, approve GitHub metadata changes, approve Hugging Face metadata changes, authorize publication, or make Codex an architectural authority.

## Reading Order

| Step | File | Purpose |
| ---: | --- | --- |
| 1 | `README.md` | Proof model, 17-repo architecture, status vocabulary, boundaries, and review rules. |
| 2 | `proof-matrix.md` | Repo-by-repo claim routing with artifact, status, validation, boundary, and next action. |
| 3 | `claim-register.md` | Allowed claim patterns, evidence requirements, and forbidden public claims. |
| 4 | `artifact-status.md` | Artifact availability, public state, release state, and review needs. |
| 5 | `boundary-register.md` | Boundary classes for the 17 final repo roles and existing supporting repo categories. |
| 6 | `review-log.md` | Human review history and pending decisions. |
| 7 | `templates/proof-entry.md` | Required format for future proof rows. |

## 17-Repo Architecture

The approved production architecture contains two existing control/navigation repositories and 15 planned umbrella repositories.

| Repo | Category | Phase 1 status |
| --- | --- | --- |
| `Franzabner` | Control/navigation | `scaffolded` locally after Phase 1 patch; publication requires human review and push approval. |
| `franzabner-proof-stack` | Control/navigation | `scaffolded` locally after Phase 1 patch; publication requires human review and push approval. |
| `modular-infrastructure-studies` | Modular infrastructure | `planned`; do not create in Phase 1. |
| `cad-mechanical-design-lab` | Mechanical CAD | `planned`; do not create in Phase 1. |
| `electrical-controls-architecture` | Electrical controls | `planned`; do not create in Phase 1. |
| `embedded-hardware-lab` | Embedded hardware | `planned`; do not create in Phase 1. |
| `engineering-simulation-lab` | Simulation and validation | `planned`; do not create in Phase 1. |
| `data-model-infrastructure` | Data/model infrastructure | `planned`; do not create in Phase 1. |
| `infrastructure-energy-studies` | Energy studies | `planned`; do not create in Phase 1. |
| `civic-infrastructure-production-systems` | Civic production systems | `planned`; do not create in Phase 1. |
| `engineering-standards-and-validation` | Standards and validation | `planned`; do not create in Phase 1. |
| `engineering-security-boundary` | Security boundary | `planned`; do not create in Phase 1. |
| `engineering-deliverables-template` | Deliverables | `planned`; do not create in Phase 1. |
| `application-development-systems` | Application systems | `planned`; do not create in Phase 1. |
| `immersive-access-systems` | Immersive access | `planned`; do not create in Phase 1. |
| `automated-engineering-systems` | Automated engineering systems | `planned`; do not create in Phase 1. |
| `agentic-engineering-workforce` | Agentic engineering workforce | `planned`; do not create in Phase 1. |

## Repo Categories

| Category | Proof direction | Current Phase 1 rule |
| --- | --- | --- |
| Control/navigation | Identity, navigation, proof control, status language, and boundary routing. | Patch only `Franzabner` and `franzabner-proof-stack`. |
| Modular infrastructure | Rack-scale systems, power/cooling assumptions, serviceability, and deployment constraints. | `planned`; no repo creation. |
| Mechanical CAD | Fusion 360, enclosure, rack geometry, ducting, mounting, serviceability, and manufacturing assumptions. | `planned`; no repo creation. |
| Electrical controls | Field-grade power, sensing, actuation, control narratives, and commissioning logic. | `planned`; no repo creation. |
| Embedded hardware | PCB, firmware, MCU, breadboard, management-bus, and validation patterns. | `planned`; no repo creation. |
| Simulation and validation | Assumptions, models, outputs, limits, reports, and validation paths. | `planned`; no repo creation. |
| Data/model infrastructure | Source capture, schemas, vector indexes, datasets, fine-tuning, evals, model/dataset cards, and DGX boundaries. | `planned`; no repo creation. |
| Energy studies | Water-current-to-electricity, solar-to-hydrogen, storage, conversion, control, and safety boundaries. | `planned`; no repo creation. |
| Civic production systems | Foundation-adjacent production studies without speaking as the Foundation. | `planned`; no repo creation. |
| Standards and validation | Safety, commissioning, acceptance criteria, risk registers, and standard-aware templates. | `planned`; no repo creation. |
| Security boundary | Secrets, repo visibility, client/Foundation/model boundaries, and agent permissions. | `planned`; no repo creation. |
| Deliverables | Engineering templates, reports, BOMs, control narratives, commissioning plans, cards, and handoff checklists. | `planned`; no repo creation. |
| Application systems | Next.js, TypeScript, product-boundary, review workflows, deployment assumptions, and validation. | `planned`; no repo creation. |
| Immersive access | Spatial dashboards, digital twins, HMI, controlled access, CAD-to-USD pipeline, and public-safe renders. | `planned`; no repo creation. |
| Automated engineering systems | Obsidian, Forgejo, n8n, source/provenance, operator dashboards, and mirror boundaries. | `planned`; no repo creation. |
| Agentic engineering workforce | Codex-style execution, role cards, review gates, tool permissions, logs, and human approvals. | `planned`; no repo creation. |

## Status Vocabulary

Use only these approved top-level labels:

| Status | Meaning in this proof stack |
| --- | --- |
| `planned` | Name, purpose, and review path are documented; no public artifact is claimed. |
| `scaffolded` | Public-safe structure exists with README files, docs, templates, or placeholders but no release claim. |
| `published` | A public repo or public document is reachable and intended for public review. |
| `released` | A reviewed public artifact exists with evidence, limitations, companion links, and approval. |
| `paused` | Visible work is intentionally on hold. |
| `deprecated` | Visible work remains only with archival, replacement, or sunset context. |
| `private/not-public` | Private, sealed, donor-sensitive, student-sensitive, customer-sensitive, model-sensitive, or security-sensitive work must not be linked as public proof. |

`released` must not be used for Phase 1 control-layer scaffolds unless a separate human-approved release artifact exists.

## Boundary Rules

| Boundary | Rule |
| --- | --- |
| Public-safe artifacts only | Examples, screenshots, diagrams, model cards, dataset cards, reports, logs, outputs, and demos require synthetic or reviewed public-safe inputs. |
| Private and sealed exclusions | Production CAD, KiCad source, BOMs, Gerbers, pin maps, firmware, topology, credentials, private corpora, weights, customer data, Foundation-private data, and operational logs stay non-public unless explicitly reviewed and transformed. |
| Foundation independence | 218 Network Foundation is co-equal but legally and operationally distinct. Foundation material must not become personal or company marketing proof. |
| Company/product/client separation | YOSO-YAi LLC is the company; YOSOR is a YOSO-YAi LLC product; client-owned apps are not Franzabner personal products, YOSOR, or Foundation programs. |
| Forgejo/GitHub source role | Forgejo is canonical private source where private or sealed source applies. GitHub is public mirror, deployment source, portfolio surface, or open-source surface depending on classification. |
| Hugging Face release-only rule | Hugging Face is a model/dataset/Space release surface only and not the canonical sealed model-development home. |
| AI build lane | Codex and other agents are build lanes, not architectural authority or publication approval. |

## Review Requirements

| Review | Required before |
| --- | --- |
| Claim review | Stronger public language, profile routing, portfolio use, or proof promotion. |
| Boundary review | Any screenshot, generated output, CAD/KiCad/firmware example, model/data artifact, Foundation-adjacent material, client material, or operational example. |
| Evidence review | Any `published` or `released` status change, benchmark, eval result, artifact claim, physical validation claim, product claim, or deployment claim. |
| Validation review | Any repo promoted beyond `planned` or `scaffolded`. |
| Human approval | Any publication, pinning, metadata change, release, archive, transfer, rename, visibility change, or Hugging Face action. |

## Next Build Step

Phase 1 is limited to patching:

- `Franzabner`: `README.md`, `PROOF_INDEX.md`, `PUBLIC_SURFACE.md`, `BOUNDARIES.md`, `STATUS.md`;
- `franzabner-proof-stack`: `README.md`, `proof-matrix.md`, `claim-register.md`, `artifact-status.md`, `boundary-register.md`, `review-log.md`, `templates/proof-entry.md`.

The next human review should decide whether these two control repositories are safe to keep at `scaffolded` status and whether a separate Phase 2 plan may start for the first umbrella repositories.
