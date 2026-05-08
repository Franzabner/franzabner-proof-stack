# Proof Matrix

Status: Public scaffold. Release status: scaffolded. License pending human review.

## Matrix

| Lane | Proof source | Artifact type | Current status | Boundary note | Review need |
|---|---|---|---|---|---|
| Navigation | `Franzabner`, `franzabner-proof-stack` | Profile README and proof index | Live public scaffold | Identity, links, and status require review. | approve profile language |
| PCB review | `public-pcb-review-checklist` | checklist, synthetic reports, boundary rules | Live public scaffold | No production schematics, routing, BOMs, Gerbers, pin maps, board source, firmware integration, or customer files. | asset and certification-language review |
| AI review gates | `engineering-agent-review-gates` | review checklists and gate templates | Live public scaffold | No private prompts, tools, memory, corpora, endpoints, logs, or private harness internals. | human-authority review |
| HF readiness | `hf-card-templates` | model card, dataset card, Space card, eval-report templates | Live public scaffold | No released model, dataset, Space, benchmark, eval result, hosted model, or hosted dataset claim. | release-readiness review |
| README/productization | `technical-readme-lab` | synthetic README frameworks and examples | Live public scaffold | No client, deployment, revenue, or live service claim. | example and claim review |
| Electrical discipline | `electrical-panel-dressing` | public-safe electrical documentation | Merged scaffold | No customer, deployment, production, certification, or sign-off claim. | rendered README review |
| Field discipline | `field-to-architect` | field-to-architecture documentation | Merged scaffold | No employer/customer-sensitive material or production claim. | rendered README review |
| Mission-critical discipline | `mission-critical-discipline` | operating-discipline documentation | Merged scaffold | No client, deployment, revenue, or production-readiness claim. | rendered README review |
| Embedded / Pico / RP2350 | `pico2-pio-i2c-reference` | embedded reference workflow | Merged scaffold | No production firmware, exact pin map, protocol secret, or rack integration. | firmware and interface review |
| Breadboard / RIB boundary | `rib-breadboard` | public breadboard/reference scaffold | Merged scaffold | Production RIB implementation remains sealed. No production board files, firmware internals, BOMs, Gerbers, pin maps, routing, manufacturing approval, certification, sign-off, deployment, client, customer, revenue, or production-ready claim. | rendered README, boundary, and license-posture review |
| EPI framing | `energy-per-intelligence` | research scaffold | Merged scaffold | No released benchmark, dataset, model, Space, eval result, or hosted artifact claim. | research-status review |
| EPI tooling | `epi-bench` | tooling scaffold | Merged scaffold | No benchmark validity, released result, hosted artifact, or deployment claim. | prototype boundary review |
| EPI measurement | `epi-meter` | hardware measurement scaffold | Merged scaffold | No manufacturing approval, certification, sign-off, production-ready status, approved BOM, or Gerber claim. | hardware boundary review |
| Paper-specific EPI | `attention-head-surgery-epi`, `mixed-quant-epi`, `expert-pruning-epi` | paper/research scaffolds | Merged scaffold | No released method, validated benchmark, dataset, model, Space, eval result, deployed agent, private harness, or proven result claim. | rendered README and license-posture review |
| Risky production-adjacent repos | rack, DGX, agent, Fusion, KiCad production, production RIB, infrastructure lanes | mixed artifacts | Held or derivative-only | May contain private implementation, topology, routing, BOMs, Gerbers, firmware internals, private corpora, weights, or endpoints. | boundary review before edit |

## Evidence Standard

Each future proof row should include artifact location, status, evidence summary, excluded private material, review requirement, and review date.

## Pin Priority

The public profile pin set should favor navigation, concrete electrical proof, agent review discipline, EPI framing, embedded reference workflow, and README/productization proof.
