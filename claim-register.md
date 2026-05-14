# Claim Register

Status: `scaffolded` locally after Phase 1 patch  
Purpose: allowed claims, evidence requirements, and forbidden public claims

## Allowed Claim Patterns

| Claim pattern | Allowed status | Evidence requirement | Boundary note |
| --- | --- | --- | --- |
| Francisco Abner Rivera is Founder of YOSO-YAi and Systems Architect building intelligent infrastructure from power to autonomy. | `scaffolded` | Profile README and boundary files. | Personal identity line; not a product, deployment, client, or Foundation outcome claim. |
| `Franzabner` is a personal public engineering profile and navigation surface. | `scaffolded` | `Franzabner` README, `PROOF_INDEX.md`, `PUBLIC_SURFACE.md`, `BOUNDARIES.md`, `STATUS.md`. | Not the official company, product, Foundation, client, or release authority. |
| `franzabner-proof-stack` is a proof-control layer for public claims. | `scaffolded` | This README, `proof-matrix.md`, `claim-register.md`, `artifact-status.md`, `boundary-register.md`, `review-log.md`, and `templates/proof-entry.md`. | Claim control only; does not approve publication or release. |
| The approved public architecture contains 17 final repo roles. | `planned` for the 15 umbrella repos; `scaffolded` for the two control repos after local patch. | Approved architecture docs and this proof matrix. | The 15 umbrella repos are not created in Phase 1. |
| GitHub is a public mirror, deployment source, portfolio surface, or open-source surface depending on repository classification. | `scaffolded` | Boundary register and profile boundary file. | GitHub is not canonical for private or sealed source. |
| Forgejo is canonical private source where private or sealed source applies. | `scaffolded` | Boundary register and profile boundary file. | Do not expose Forgejo internals. |
| Hugging Face is a model/dataset/Space release surface only. | `scaffolded` | Boundary register and artifact status. | No model, dataset, Space, card, eval result, or benchmark is released by Phase 1. |
| Codex and other agents may assist execution under human authority. | `scaffolded` | Boundary register and review requirements. | AI tools are not architectural authority and do not approve publication. |

## Claims Requiring Evidence Before Use

| Claim | Required evidence before use |
| --- | --- |
| A repo is `published`. | Public URL verification, reviewed README status, boundary language, and human approval to use the public link as proof. |
| A repo or artifact is `released`. | Public artifact link, release notes or card, limitations, provenance posture, companion links, validation evidence, and human release approval. |
| A model, dataset, Space, eval result, benchmark, hosted artifact, or report exists. | Public Hugging Face or artifact link, card/README, safety or limitations note, review state, and companion proof-stack row. |
| A mechanical, CAD, KiCad, electrical, firmware, hardware, or USD asset is public-safe. | Asset review, redaction or synthetic-source review, boundary note, and proof matrix row. |
| A simulation result or energy result is validated. | Assumptions, inputs, model, outputs, limits, validation path, review state, and explicit statement of what the study does not prove. |
| A product, deployment, service, certification, manufacturing-ready design, production-ready design, or client outcome exists. | Reviewed public artifact, owner approval, claim review, boundary review, and evidence appropriate to the claim. |
| Foundation-adjacent work can be cited. | Foundation-boundary review, entity-separated language, no donor/student/volunteer/private-operation exposure, and Foundation review where required. |

## Forbidden Claims

Do not claim or imply:

- active products, deployed infrastructure, public services, client outcomes, revenue, manufacturing approval, certified design status, production-ready status, or code-compliance approval without reviewed evidence;
- released models, datasets, Hugging Face Spaces, benchmarks, eval results, hosted models, hosted datasets, adapters, weights, training runs, or model outputs without reviewed public artifacts;
- production CAD, KiCad, PCB, firmware, USD, DGX, RAG, Forgejo, n8n, topology, prompt, corpus, weight, endpoint, credential, or operational source exposure;
- Foundation endorsement, Foundation operations, Foundation outcomes, donor data, student data, volunteer data, or Foundation-private records as personal or company marketing proof;
- YOSO-YAi LLC sealed IP, product internals, private source, or customer obligations as public proof;
- YOSOR as a separate legal entity or Foundation product;
- client-owned applications as Franzabner personal products, YOSOR, or Foundation programs;
- autonomous production agents, uncontrolled autonomy, or AI output as architectural authority.

## Refusal Rule

If a proposed public claim lacks evidence, status, boundary, validation, or human review state, keep it `planned`, `scaffolded`, or `private/not-public` as appropriate and route it back to human review.
