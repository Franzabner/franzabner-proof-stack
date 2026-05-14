# Boundary Register

Status: `scaffolded` locally after Phase 1 patch  
Purpose: boundary classes for final repo roles and supporting repo categories

## Final Repo Boundary Classes

| Repo | Boundary class | Public-safe content | Private/sealed exclusions |
| --- | --- | --- | --- |
| `Franzabner` | Personal public proof surface. | Identity, navigation, status labels, proof routing, boundary notes, reviewed links. | Company source, Foundation-private operations, client data, product internals, private topology, model/data secrets. |
| `franzabner-proof-stack` | Public proof-control layer. | Claim register, proof matrix, artifact status, boundary register, review log, templates. | Private evidence, sealed source excerpts, internal agent logs, private topology, private corpora, customer artifacts. |
| `modular-infrastructure-studies` | Public-safe infrastructure study boundary. | Synthetic system diagrams, assumption tables, serviceability studies, simplified deployment constraints. | Production rack topology, real facility layouts, customer infrastructure, private thermal measurements, sensitive site data. |
| `cad-mechanical-design-lab` | Public-safe mechanical CAD boundary. | Redacted screenshots, synthetic assemblies, reviewed exports, service-access diagrams. | Production F3D, exact dimensions, manufacturing package, product geometry, private rack models, sealed design lineage. |
| `electrical-controls-architecture` | Public-safe electrical/control boundary. | Simplified schematics, control narratives, sensor/actuator tables, commissioning logic, calculation notes. | Production schematics, panel identifiers, customer wiring, exact private pin maps, production BOMs, live control logic, certification claims. |
| `embedded-hardware-lab` | Public-safe embedded hardware boundary. | Simplified schematics, generic pin maps, synthetic firmware examples, test scripts, breadboard diagrams, validation notes. | Production board source, routing, BOM, Gerbers, exact pin maps, private firmware, manufacturing details, customer hardware, certified-design claims. |
| `engineering-simulation-lab` | Public-safe simulation boundary. | Notebooks, scripts, assumptions, plots, reports, synthetic fixtures, model-limit notes. | Private traces, customer data, unreleased benchmark results, private measurements, production thermal data, private workloads, unsupported result claims. |
| `data-model-infrastructure` | Public-safe data/model infrastructure boundary. | Synthetic schemas, capture/OCR workflow, metadata templates, dataset/model card templates, eval report templates, DGX workflow boundaries. | Private corpora, customer data, Foundation-private data, private weights, adapters, training logs, endpoints, topology, credentials, unreleased metrics. |
| `infrastructure-energy-studies` | Public-safe energy study boundary. | Assumption tables, diagrams, simulation notebooks, control states, validation plans, non-certified safety notes. | Deployment claims, commercial-readiness claims, proven-output claims, private measurements, sealed designs. |
| `civic-infrastructure-production-systems` | Foundation-adjacent public-safe engineering boundary. | Synthetic process diagrams, 3D-print workflow notes, QA checklists, public-safe renders, schema examples, dashboard mockups. | Donor data, student data, volunteer data, Foundation-private operations, school-sensitive details, vendor details, deployment claims without reviewed evidence. |
| `engineering-standards-and-validation` | Standards-aware validation boundary. | Checklists, acceptance criteria, failure-mode tables, test plans, commissioning templates, calibration procedures. | Formal certification claims, stamped-engineering implication, customer procedures, private incident reports, code-compliance approval claims. |
| `engineering-security-boundary` | Security and publication-decision boundary. | Policies, synthetic examples, redaction rules, checklists, permission matrices, decision trees. | Credentials, private URLs, production secrets, customer data, Foundation-private data, sealed design files, private model artifacts, sensitive infrastructure details. |
| `engineering-deliverables-template` | Public-safe deliverables boundary. | README, status, claims, public boundary, BOM, control narrative, commissioning, simulation report, model/dataset card, handoff templates. | Stamped document implication, client deliverables, customer data, sealed product excerpts, active service, pricing, turnaround claims. |
| `application-development-systems` | Public-safe app architecture boundary. | Architecture diagrams, component examples, synthetic UI screenshots, review checklists, deployment assumptions, validation notes. | Client source, credentials, unreleased product internals, engineering super-app sealed details, customer data, production secrets, ownership confusion. |
| `immersive-access-systems` | Public-safe immersive access boundary. | Dashboard wireframes, USD scene notes, CAD-to-USD diagrams, rendered stills, browser-streamed architecture notes, HMI checklists. | Production USD scenes, private CAD, real facility layout, private rack topology, operator credentials, security-sensitive controls, customer assets, Foundation private operations. |
| `automated-engineering-systems` | Public-safe engineering operating-system boundary. | Synthetic workflow diagrams, sanitized run-log templates, mirror policy, dashboard concepts, automation checklists. | Real topology, hostnames, endpoints, ports, credentials, private vaults, production logs, internal workflows, customer operations, live automation exports. |
| `agentic-engineering-workforce` | Public-safe agent workflow boundary. | Role cards, task templates, tool permissions, review gates, audit fields, run-log templates, refusal rules. | Sealed specialist-agent workflows, internal prompts, private harnesses, private tools, customer operations, uncontrolled autonomy, autonomous production-agent claims. |

## Supporting Repo Categories

| Supporting category | Phase 1 treatment | Boundary rule |
| --- | --- | --- |
| Existing electrical/control repos | Source context only. | Do not upgrade status, patch files, or claim certification, production wiring, customer work, or deployment readiness in Phase 1. |
| Existing embedded/PCB/breadboard repos | Source context only. | Do not expose production board source, BOMs, Gerbers, exact pin maps, private firmware, or manufacturing posture. |
| Existing EPI/model/eval repos | Source context only. | Do not claim released benchmarks, eval results, models, datasets, Spaces, private harnesses, or hosted artifacts. |
| Existing AI/DGX/fine-tuning/local-lab repos | Source context only. | Do not expose topology, endpoints, tokens, private corpora, weights, prompts, logs, or sealed YOSO-YAi IP. |
| Existing CAD/rack/enclosure/Fusion/KiCad library repos | Source context only. | Treat production geometry, dimensions, libraries, footprints, thermal assumptions, and manufacturing details as sealed unless reviewed derivative material exists. |
| Existing Foundation-adjacent repos | Hold for entity review. | Do not use Foundation work as personal or company marketing proof. |
| Existing studio/fleet/dotfiles/private-ops repos | Hold or private/not-public. | Do not expose topology, credentials, location, mesh, endpoints, internal workflows, or live operations. |

## Entity Boundary

| Entity or surface | Rule |
| --- | --- |
| YOSO-YAi LLC | Company entity responsible for company source, products, customer obligations, sealed IP, and company public surfaces. |
| YOSOR | Product of YOSO-YAi LLC; not a separate legal entity and not a Foundation product. |
| 218 Network Foundation | Co-equal but legally and operationally distinct Foundation; not a CSR project, company marketing arm, YOSO-YAi sub-brand, or product line. |
| Forgejo | Canonical private source where private or sealed source applies. |
| GitHub | Public mirror, deployment source, portfolio surface, or open-source surface depending on repository classification. |
| Hugging Face | Model/dataset/Space release surface only; not canonical sealed model-development home. |
| Codex | Build lane only; not architectural authority. |
