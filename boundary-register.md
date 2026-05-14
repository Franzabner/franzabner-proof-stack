# Boundary Register

Status: `scaffolded` locally after Phase 1 patch  
Purpose: boundary classes for final repo roles and supporting repo categories

## Final Repo Boundary Classes

| Repo | Boundary class | Public-safe content | Private/sealed exclusions |
| --- | --- | --- | --- |
| `Franzabner` | Personal public proof surface. | Identity, navigation, status labels, proof routing, boundary notes, reviewed links. | Company source, Foundation-private operations, client data, product internals, private topology, model/data secrets. |
| `franzabner-proof-stack` | Public proof-control layer. | Claim register, proof matrix, artifact status, boundary register, review log, templates. | Private evidence, sealed source excerpts, internal agent logs, private topology, private corpora, customer artifacts. |
| [`modular-infrastructure-studies`](https://github.com/Franzabner/modular-infrastructure-studies) | Public-safe infrastructure study boundary. | Synthetic system diagrams, assumption tables, serviceability studies, validation notes, and public scaffold documentation. | Production rack topology, real facility layouts, production CAD, customer infrastructure, private thermal measurements, private measurements, sensitive site data, sealed geometry. |
| [`cad-mechanical-design-lab`](https://github.com/Franzabner/cad-mechanical-design-lab) | Public-safe mechanical CAD boundary. | Synthetic enclosure studies, CAD-boundary rules, export policy, qualitative constraints, service-access diagrams, and public scaffold documentation. | Production F3D, production CAD, exact dimensions, manufacturing package, product geometry, customer parts, private rack models, sealed design lineage, sealed geometry. |
| [`electrical-controls-architecture`](https://github.com/Franzabner/electrical-controls-architecture) | Public-safe electrical/control boundary. | Synthetic control narratives, sensor/actuator category tables, commissioning questions, public-safe control-flow diagrams, calculation notes, and validation review scaffolds. | Production schematics, production board or panel source, BOMs, Gerbers, exact pin maps, customer wiring, live control logic, private firmware, manufacturing-ready files, internal product names, deployment claims, certification claims, release claims. |
| [`embedded-hardware-lab`](https://github.com/Franzabner/embedded-hardware-lab) | Public-safe embedded hardware boundary. | Synthetic MCU/management-bus patterns, firmware-boundary notes, generic role-based pin-map patterns, public-safe test harness concepts, breadboard notes, diagrams, and validation review scaffolds. | Production board source, production schematics, routing, BOMs, Gerbers, exact pin maps, private firmware, customer hardware, customer wiring, manufacturing-ready files, internal product names, deployment claims, certification claims, release claims, manufacturing claims. |
| [`engineering-simulation-lab`](https://github.com/Franzabner/engineering-simulation-lab) | Public-safe simulation boundary. | Synthetic simulation studies, assumptions, model boundaries, synthetic inputs, synthetic outputs, generated report plans, validation questions, proof-limit notes, and Mermaid validation diagrams. | Private traces, customer data, Foundation-private data, unreleased benchmark results, private measurements, production thermal data, production airflow data, production power data, production simulation data, private workloads, endpoints, topology, credentials, unsupported result claims, benchmark claims, physical-validation claims, deployment claims, certification claims, release claims. |
| [`data-model-infrastructure`](https://github.com/Franzabner/data-model-infrastructure) | Public-safe data/model infrastructure boundary. | Synthetic schemas, source-capture/OCR workflow, metadata templates, normalization/deduplication/chunking/quality rubrics, vector-index notes, dataset/model card templates, eval templates, DGX workflow boundaries, and release-surface discipline. | Private corpora, copyrighted material without rights, customer data, Foundation-private data, private weights, adapters, private training logs, endpoints, topology, credentials, unreleased metrics, private prompts, private eval outputs, model releases, dataset releases, Space releases, fine-tuned model availability claims, Hugging Face metadata changes. |
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
