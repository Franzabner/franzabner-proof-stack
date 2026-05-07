# Boundary Map

Status: Scaffolded. Human Review Required before publication.

## Purpose

This file summarizes the public, private, and sealed boundaries for the proof stack. It is a staging review aid and does not move any private artifact into public scope.

## Boundary Matrix

| Area | Public-safe material | Private or sealed exclusions | Review trigger |
| --- | --- | --- | --- |
| GitHub proof | Status-labeled READMEs, checklists, templates, synthetic examples, and reviewed public artifacts. | Private source, unreleased implementation, customer-sensitive material, sealed company IP, or unsupported claims. | Any repo link or proof claim. |
| Mechanical / Fusion 360 | Synthetic screenshots, simplified diagrams, reviewed documentation patterns. | Production CAD, exact dimensions, product geometry, source files, manufacturing packages, private screenshots. | Any real asset, screenshot, export, dimension, or geometry. |
| Electrical / KiCad / PCB | Synthetic review packets, checklist rows, public-safe report templates. | Production schematics, routing, BOMs, Gerbers, exact pin maps, private libraries, board source, firmware integration details. | Any real board, file, net, pin, library, or manufacturing artifact. |
| Embedded / Pico / RP2350 | Generic interface notes and reviewed reference patterns. | Production firmware, exact interface maps, credentials, private protocols, rack/RIB integration, customer wiring, site details. | Any firmware, pinout, protocol, wiring, or deployment reference. |
| Agents / harnesses | Abstract harness diagrams, review gates, synthetic memory/task examples. | Private prompts, tool contracts, logs, endpoints, corpora, memory, YAi/YOSO-YAi internals, customer data. | Any real prompt, tool, model route, endpoint, log, memory, or corpus. |
| DGX / NVIDIA / fine-tuning | Public-safe workflow shapes, synthetic runbooks, template lab notes. | Rack topology, hostnames, ports, credentials, private corpora, private weights, adapters, endpoints, NIM routing, run logs. | Any infrastructure, model, dataset, result, endpoint, or log detail. |
| Hugging Face / EPI | Templates, release checklists, planned/scaffolded status rows. | Fake weights, fake datasets, fake Spaces, private corpora, unreleased results, unsupported benchmarks. | Any artifact status above planned/scaffolded. |
| Omniverse / USD / 3D worlds | Synthetic scene plans, asset manifests, pipeline templates. | Production USD scenes, private CAD, product geometry, facility layout, customer scenes, proprietary textures. | Any real scene, asset, dimension, facility, or product reference. |
| Upwork / monetization | Draft proof routing and reviewed proof links only. | Live offer copy, pricing, timelines, guarantees, client outcomes, Foundation marketing proof, sealed company IP. | Any external profile, proposal, offer, service page, or buyer-facing text. |

## Refusal Rule

Do not publish, summarize outward, or convert an item into proof when its evidence depends on private implementation, sealed source, customer or employer material, credentials, private infrastructure, unreleased models, unreleased datasets, production CAD/KiCad/USD assets, or Foundation private operations.
