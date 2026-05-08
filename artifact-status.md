# Artifact Status

Status: Public scaffold. Release status: scaffolded. License pending human review.

## Current Status Vocabulary

| Status | Meaning |
|---|---|
| Live public scaffold | Public repo exists and can be linked as a scaffold/proof surface. |
| Merged scaffold | Public-surface alignment has been merged to `main`; this still does not imply release status. |
| Planned | Repo or artifact is planned only and should not imply public availability. |
| Draft | Service routing or example language is internal draft material only. |
| Held | Existing repo or lane requires human review before edit, link, PR, merge, or proof routing. |
| Human Review Required | Human approval is required before release claims, license changes, or external references. |

Future labels such as released require separate evidence and approval. They are not current labels for this public scaffold.

## Current Public Artifacts

| Artifact | Public reference | Status | Notes |
|---|---|---|---|
| `Franzabner` profile | `https://github.com/Franzabner` | Live public scaffold | Public front door. |
| `franzabner-proof-stack` | `https://github.com/Franzabner/franzabner-proof-stack` | Live public scaffold | Evidence control layer. |
| `public-pcb-review-checklist` | `https://github.com/Franzabner/public-pcb-review-checklist` | Live public scaffold | Electrical / PCB review proof surface. |
| `engineering-agent-review-gates` | `https://github.com/Franzabner/engineering-agent-review-gates` | Live public scaffold | AI-assisted engineering review gates. |
| `hf-card-templates` | `https://github.com/Franzabner/hf-card-templates` | Live public scaffold | Template-only HF release-readiness surface. |
| `technical-readme-lab` | `https://github.com/Franzabner/technical-readme-lab` | Live public scaffold | README/productization proof surface. |
| `electrical-panel-dressing` | `https://github.com/Franzabner/electrical-panel-dressing` | Merged scaffold | Old-repo alignment merged. |
| `field-to-architect` | `https://github.com/Franzabner/field-to-architect` | Merged scaffold | Old-repo alignment merged. |
| `mission-critical-discipline` | `https://github.com/Franzabner/mission-critical-discipline` | Merged scaffold | Old-repo alignment merged. |
| `pico2-pio-i2c-reference` | `https://github.com/Franzabner/pico2-pio-i2c-reference` | Merged scaffold | Old-repo alignment merged. |
| `rib-breadboard` | `https://github.com/Franzabner/rib-breadboard` | Merged breadboard/reference scaffold | Public-boundary cleanup merged. Production RIB implementation remains sealed. No production board files, firmware internals, BOMs, Gerbers, pin maps, routing, manufacturing approval, certification, sign-off, deployment, client, customer, revenue, or production-ready claim. |
| `local-ai-lab-boundary` | `https://github.com/Franzabner/local-ai-lab-boundary` | Live public scaffold | First derivative public boundary repo. Public-safe local AI lab boundary model with synthetic-only examples. No real topology, endpoints, credentials, tokens, private corpora, private weights, private prompts, private agent harnesses, sealed YOSO-YAi IP, Hugging Face artifact, or live service claim. |
| `energy-per-intelligence` | `https://github.com/Franzabner/energy-per-intelligence` | Merged research scaffold | EPI spine alignment merged. |
| `epi-bench` | `https://github.com/Franzabner/epi-bench` | Merged tooling scaffold | EPI spine alignment merged. |
| `epi-meter` | `https://github.com/Franzabner/epi-meter` | Merged hardware measurement scaffold | EPI spine alignment merged. |
| `attention-head-surgery-epi` | `https://github.com/Franzabner/attention-head-surgery-epi` | Merged paper/research scaffold | Paper-specific EPI cleanup merged. No released method, validated benchmark, model, dataset, Space, eval result, or proven result claim. |
| `mixed-quant-epi` | `https://github.com/Franzabner/mixed-quant-epi` | Merged paper/research scaffold | Paper-specific EPI cleanup merged. No released quantization recipe, production benchmark, evaluated model, dataset, Space, or eval result claim. |
| `expert-pruning-epi` | `https://github.com/Franzabner/expert-pruning-epi` | Merged paper/research scaffold | Paper-specific EPI cleanup merged. No released pruning workflow, deployed agent, private harness, model, dataset, Space, or eval result claim. |

## Held Artifacts

| Artifact or lane | Status | Reason |
|---|---|---|
| Rack / DGX / agent / Fusion / KiCad production / production RIB / infrastructure repos | Held or derivative-only | Boundary review required before public proof routing. DGX/NVIDIA and fine-tuning derivative repos remain future candidates. |

## Hugging Face Status Rule

Existing or planned HF references remain Planned, Scaffolded, or Template-only unless a public artifact exists with evidence, limitations, review, and approval. No model, dataset, Space, benchmark, eval result, hosted model, or hosted dataset claim is made here.
