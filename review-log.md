# Review Log

Status: `scaffolded` locally after Phase 1 patch  
Purpose: human review history and pending review queue

## Review Entries

| Date | Item | Decision | Review requirement | Notes |
| --- | --- | --- | --- | --- |
| 2026-05-07 | Initial public proof-stack scaffold | `scaffolded` | Human review required | Earlier scaffold prepared claim routing, status control, and boundary review before broader public proof use. |
| 2026-05-13 | Phase 1 profile/proof-stack execution plan | `planned` | Human review required | Plan authorized only the two control repositories: `Franzabner` and `franzabner-proof-stack`. No umbrella repo creation, supporting repo patch, push, publication, GitHub metadata change, or Hugging Face metadata change. |
| 2026-05-13 | Phase 1 local proof-stack patch | `scaffolded` | Human review required before push or public use | Rebuilt this repo around the approved 17-repo architecture, status vocabulary, claim register, artifact status, boundary register, review log, and proof-entry template. |
| 2026-05-13 | Phase 2 modular/CAD public scaffold repos | `scaffolded` | Human review required before profile routing or proof promotion | `modular-infrastructure-studies` and `cad-mechanical-design-lab` are public scaffold repos with validation scripts and first synthetic artifacts. They are not released, deployed, certified, product-ready, or proof-complete. |
| 2026-05-14 | Phase 3 electrical/embedded public scaffold repos | `scaffolded` | Human review required before proof promotion | `electrical-controls-architecture` and `embedded-hardware-lab` are public scaffold repos with validation scripts and first synthetic artifacts. They are not released, deployed, certified, manufacturing-ready, product-ready, or proof-complete. |

## Required Future Reviews

| Review | Required before |
| --- | --- |
| Profile language review | Pushing or publicly relying on the patched `Franzabner` profile files or Phase 2/3 scaffold links. |
| Proof matrix review | Pushing or publicly relying on this proof stack as the control layer for Phase 2/3 scaffold routes. |
| Status vocabulary review | Any status change beyond `planned` or `scaffolded`. |
| Boundary review | Any supporting repo promotion, generated output, screenshot, CAD, KiCad, firmware, model/data artifact, Foundation-adjacent material, or client-related material. |
| Evidence review | Any `published` or `released` claim, artifact release, model/dataset/Space claim, benchmark, eval result, product claim, deployment claim, service claim, or certification claim. |
| Metadata review | Any GitHub profile bio, pin, repo description, topic, homepage, visibility, archive, or Hugging Face metadata change. |
| Umbrella repo creation review | Creating any of the 11 remaining planned umbrella repositories. |
| Supporting repo patch review | Editing any existing narrow supporting repository. |

## Open Decisions

| Decision | Current state |
| --- | --- |
| Are `Franzabner` and `franzabner-proof-stack` safe to push as `scaffolded` Phase 1 control repos? | Pending human review. |
| Are `modular-infrastructure-studies` and `cad-mechanical-design-lab` safe to route from `Franzabner` as scaffolded public proof surfaces? | Pending human review of this routing patch. |
| Are `electrical-controls-architecture` and `embedded-hardware-lab` safe to route from `Franzabner` as scaffolded public proof surfaces? | Pending human review of this routing patch. |
| Should any supporting narrow repo be rewritten, merged, replaced, archived, transferred, or made private/not-public? | Pending separate repo-by-repo review. |
| Should any GitHub or Hugging Face metadata change? | Not authorized by Phase 1. |
