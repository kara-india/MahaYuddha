# MahaYuddha — ASTRA: Rise of the Legendary Warriors

A mobile-first, high-fidelity Mahabharata-inspired action game concept. The initial product direction is a cinematic third-person story campaign that teaches combat and unlocks abilities, feeding into fair 1v1 PvP. The roadmap can expand to 2v2 and a compact survival/battle-royale mode only after the core loop proves fun and commercially viable.

## Current status

This repository was empty when initialized. It currently contains the product/research brief and execution workflows, not an existing Unity game build or source project. Unity assets, licensed/commissioned art, audio, and gameplay implementation must be added as they are created.

## Product constraints

- Mobile-first; free-to-play with optional in-app purchases, not a paid download.
- Hindi and English story presentation.
- Third-person solo missions; mission rewards unlock powers, weaponry, and progression for 1v1.
- Competitive PvP should be skill-forward; progression must not create pay-to-win advantages.
- Prototype spending target: under ₹10 lakh.
- Working title: **ASTRA: Rise of the Legendary Warriors** (clear trademarks and title rights before public launch).
- Proposed engine: Unity 6 LTS with URP, subject to a short device-performance validation spike.

## Repository guide

- `research/`: market, product, prototype scope, and validation hypotheses.
- `workflows/`: repeatable research, implementation, QA, and release process.
- `.github/workflows/`: lightweight repository CI and documentation checks.
- `game/`: reserved for the Unity project once actual source files are available.

## First milestone

Validate a vertical slice: one polished third-person mission, two playable heroes, one boss encounter, a small progression loop, Hindi/English presentation, and a technical online 1v1 feasibility spike. Do not start battle-royale production before this slice validates retention, combat feel, performance, and unit economics.

See [research/product-brief.md](research/product-brief.md), [research/market-validation.md](research/market-validation.md), and [workflows/DEVELOPMENT_WORKFLOW.md](workflows/DEVELOPMENT_WORKFLOW.md).
