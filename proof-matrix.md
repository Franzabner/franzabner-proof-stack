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
| Local AI lab boundary | `local-ai-lab-boundary` | derivative public boundary scaffold | Live public scaffold | Synthetic-only examples. No real topology, endpoints, credentials, tokens, private corpora, private weights, private prompts, private agent harnesses, or sealed YOSO-YAi IP. No Hugging Face artifact or live service claim. | boundary, license-posture, profile, and proof-stack routing review |
| DGX / NVIDIA workstation notes | `dgx-ai-workstation-notes` | derivative public workflow-notes scaffold | Live public scaffold | Synthetic-only examples. No real topology, hostnames, IPs, endpoints, credentials, tokens, Tailscale, SSH, Forgejo, n8n, LiteLLM, NIM details, private corpora, private weights, private prompts, private agent harnesses, sealed YOSO-YAi IP, model, dataset, Space, training run, model output, hosted artifact, or live service claim. | boundary, license-posture, profile, proof-stack routing, and HF no-artifact review |
| Fine-tuning lab notes | `fine-tuning-lab-notes` | derivative public fine-tuning documentation scaffold | Live public scaffold | Synthetic-only examples. Dataset prep boundary, model release gate, evaluation note template, and Hugging Face planned/template-only routing. No private corpora, private weights, training logs, eval results, model, dataset, Space, hosted artifact, real training run, model output, private endpoint, private prompt, private harness, HF action, or live service claim. | boundary, license-posture, profile, proof-stack routing, and HF no-artifact review |
| Evidence-boundary simulation | `field-propulsion-observatory` | public-safe documentation and lightweight simulation scaffold | Live public scaffold | Synthetic-only examples. Sensor metadata schemas, trajectory/uncertainty simulation, and hypothesis-boundary mapping only. No exotic propulsion claim, real case claim, Hugging Face artifact, Upwork listing, released dataset, model, Space, benchmark, eval result, deployment, client, customer, revenue, or verified propulsion claim. | boundary, license-posture, profile, proof-stack routing, and HF no-artifact review |
| EPI framing | `energy-per-intelligence` | research scaffold | Merged scaffold | No released benchmark, dataset, model, Space, eval result, or hosted artifact claim. | research-status review |
| EPI tooling | `epi-bench` | tooling scaffold | Merged scaffold | No benchmark validity, released result, hosted artifact, or deployment claim. | prototype boundary review |
| EPI measurement | `epi-meter` | hardware measurement scaffold | Merged scaffold | No manufacturing approval, certification, sign-off, production-ready status, approved BOM, or Gerber claim. | hardware boundary review |
| Paper-specific EPI | `attention-head-surgery-epi`, `mixed-quant-epi`, `expert-pruning-epi` | paper/research scaffolds | Merged scaffold | No released method, validated benchmark, dataset, model, Space, eval result, deployed agent, private harness, or proven result claim. | rendered README and license-posture review |
| Risky production-adjacent and real-case analysis lanes | rack, agent, Fusion, KiCad production, production RIB, infrastructure lanes, and real anomalous-motion case analysis | mixed artifacts | Held or derivative-only | May contain private implementation, topology, routing, BOMs, Gerbers, firmware internals, private corpora, weights, prompts, harnesses, endpoints, real case claims, or disputed-event narratives. `local-ai-lab-boundary`, `dgx-ai-workstation-notes`, `fine-tuning-lab-notes`, and `field-propulsion-observatory` are public boundary/workflow/documentation scaffolds, not clearance for real infrastructure, model, dataset, fine-tuning, or propulsion-claim exposure. | boundary review before edit |

## Evidence Standard

Each future proof row should include artifact location, status, evidence summary, excluded private material, review requirement, and review date.

## Pin Priority

The public profile pin set should favor navigation, concrete electrical proof, agent review discipline, EPI framing, embedded reference workflow, and README/productization proof.
