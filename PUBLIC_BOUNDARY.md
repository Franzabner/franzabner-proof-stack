# Public Boundary

Status: Public scaffold. Release status: scaffolded. License pending human review.

## Boundary Rules

| Area | Rule |
| --- | --- |
| Claims | Claims must map to evidence, status, boundary notes, and human review. |
| Mechanical/Fusion | Public rows may describe synthetic or reviewed proof only; production CAD, source geometry, exact dimensions, and manufacturing packages stay sealed. |
| Electrical/KiCad/PCB | Public rows may describe synthetic or reviewed proof only; production schematics, routing, BOMs, Gerbers, pin maps, board source, and customer files stay sealed. |
| Embedded/Pico/RP2350 | Public rows may describe generic references only; production firmware, protocols, credentials, and integration maps stay sealed. |
| Agents/harnesses | Public rows may describe control patterns only; private prompts, tools, corpora, logs, memory, endpoints, and YAi/YOSO-YAi internals stay sealed. |
| DGX/NVIDIA/fine-tuning | Public rows may describe release-safe workflow shapes only; topology, hostnames, credentials, private corpora, private weights, adapters, and training logs stay sealed. |
| Omniverse/USD/3D | Public rows may describe synthetic scene and pipeline proof only; production scenes, private CAD, product geometry, facility layout, and customer assets stay sealed. |
| Hugging Face | Treat as release surface only; no fake weights, datasets, Spaces, reports, benchmarks, endpoints, or released status. |
| Upwork | Draft proof routing only; no live service language, pricing, turnaround promises, guarantees, or client outcomes. |
| Foundation/company boundary | Foundation material is not personal marketing proof; sealed YOSO-YAi LLC source is not public evidence. |

## Review Trigger

Any row that references a real artifact, existing repo, public profile, Hugging Face item, Upwork route, CAD/KiCad/USD asset, DGX/NVIDIA workflow, model, dataset, report, client example, Foundation context, or company context needs human review before release claims or external references.
