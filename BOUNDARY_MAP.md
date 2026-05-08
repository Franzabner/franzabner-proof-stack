# Boundary Map

Status: Public scaffold. Release status: scaffolded. License pending human review.

## Purpose

This file summarizes public, private, and sealed boundaries for the proof stack. It is a public scaffold review aid and does not move any private artifact into public scope.

## Boundary Matrix

| Area | Public-safe material | Private or sealed exclusions | Review trigger |
|---|---|---|---|
| GitHub proof | Status-labeled READMEs, checklists, templates, synthetic examples, and reviewed public artifacts. | Private source, unreleased implementation, customer-sensitive material, sealed company IP, or unsupported claims. | Any repo link or proof claim. |
| Mechanical / Fusion 360 | Synthetic screenshots, simplified diagrams, reviewed documentation patterns. | Production CAD, exact dimensions, product geometry, source files, manufacturing packages, private screenshots. | Any real asset, screenshot, export, dimension, or geometry. |
| Electrical / KiCad / PCB | Synthetic review packets, checklist rows, public-safe report templates, aligned electrical documentation repos. | Production schematics, routing, BOMs, Gerbers, exact pin maps, private libraries, board source, firmware integration details. | Any real board, file, net, pin, library, or manufacturing artifact. |
| Embedded / Pico / RP2350 | Generic interface notes and reviewed reference patterns. | Production firmware, exact interface maps, credentials, private protocols, rack/RIB integration, customer wiring, site details. | Any firmware, pinout, protocol, wiring, or deployment reference. |
| Breadboard / RIB reference | Public breadboard/reference scaffold, public-safe hardware documentation patterns, status labels, and boundary notes. | Production RIB implementation, production board files, production firmware internals, routing, BOMs, Gerbers, exact pin maps, manufacturing packages, certification, sign-off, production-ready claims, and private YOSO-YAi implementation. | Any real hardware photo, diagram, code, component list, measurement, interface note, manufacturing claim, certification claim, or production reference. |
| Agents / harnesses | Abstract review gates, task checks, and human-authority rules. | Private prompts, tool contracts, logs, endpoints, corpora, memory, YAi/YOSO-YAi internals, customer data. | Any real prompt, tool, model route, endpoint, log, memory, or corpus. |
| Local AI lab boundary | Public-safe boundary model, synthetic-only examples, text-only disclosure policies, and public/private/sealed review checklists. | Real topology, endpoints, credentials, tokens, Tailscale, SSH, Forgejo, n8n, LiteLLM, NIM, private corpora, private weights, private prompts, private agent harnesses, and sealed YOSO-YAi IP. | Any real infrastructure, endpoint, credential, topology, prompt, corpus, weight, harness, or service-route detail. |
| DGX / NVIDIA workstation notes | Public-safe DGX/NVIDIA/workstation workflow notes, synthetic runbooks, artifact-status tables, and review checklists. | Real topology, hostnames, IPs, ports, endpoints, credentials, tokens, Tailscale, SSH, Forgejo, n8n, LiteLLM, NIM details, private corpora, private weights, private prompts, private agent harnesses, training logs, training runs, model outputs, and sealed YOSO-YAi IP. | Any real infrastructure, topology, endpoint, credential, model, dataset, result, log, model output, or service-route detail. |
| Fine-tuning | Future template lab notes and release-readiness gates only. | Private corpora, private weights, adapters, endpoints, training logs, training runs, model outputs, benchmarks, eval results, hosted artifacts, and private model workflows. | Any model, dataset, corpus, result, endpoint, hosted artifact, or log detail. |
| Hugging Face / EPI | Templates, release checklists, planned/scaffolded status rows, EPI research scaffolds, and paper-specific EPI scaffolds. | Fake weights, fake datasets, fake Spaces, private corpora, unreleased results, unsupported benchmarks, hosted artifact claims, private harnesses, and private model workflows. | Any artifact status above planned/scaffolded. |
| EPI measurement hardware | Public-safe measurement-instrument scaffold and safety boundary language. | Manufacturing-ready files, approved BOMs, approved Gerbers, certification, sign-off, production firmware, calibration claims. | Any build, calibration, accuracy, manufacturing, certification, or release claim. |
| Omniverse / USD / 3D worlds | Synthetic scene plans, asset manifests, pipeline templates. | Production USD scenes, private CAD, product geometry, facility layout, customer scenes, proprietary textures. | Any real scene, asset, dimension, facility, or product reference. |
| Upwork / monetization | Draft proof routing and reviewed proof links only. | Live offer copy, pricing, timelines, guarantees, client outcomes, Foundation marketing proof, sealed company IP. | Any external profile, proposal, offer, service page, or buyer-facing text. |

## Held Repo Rule

Risky rack, agent, Fusion, KiCad production, production RIB, and infrastructure repos remain held until a human-approved boundary review scopes their public updates or derivative-only replacement. `local-ai-lab-boundary` is live as a public boundary model, and `dgx-ai-workstation-notes` is live as public DGX/NVIDIA workstation workflow documentation, but neither makes the real studio, lab, DGX, agent, or infrastructure topology public.

## Refusal Rule

Do not publish, summarize outward, or convert an item into proof when its evidence depends on private implementation, sealed source, customer or employer material, credentials, private infrastructure, unreleased models, unreleased datasets, production CAD/KiCad/USD assets, or Foundation private operations.
