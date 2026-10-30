# Documentation steward instructions

This documentation area holds project reference material. It describes intended outcomes and records the decisions that support them. It may share a repository with delivery work or live separately. Do not infer current implementation behaviour from a plan; inspect the actual delivered artifact and its evidence.

## Read first

1. Read [README.md](README.md), `context/README.md`, and `docs/README.md`.
2. Read the relevant roadmap epic and follow its links to requirement IDs, source files, accepted decisions, and open questions.
3. Read the nearest `AGENTS.md` before editing a directory. Its local rules add to this file.
4. For delivery planning, begin with the specific approved handoff in `plans/approved/`. Read only the linked context needed for the task.
5. For Product Steward work, read `agents/product-steward.md` as role orientation. This file remains the governing instruction.

## Authority and uncertainty

Use this default order until the project owner tailors it: accepted decisions that explicitly resolve a conflict; approved canonical requirements; preserved source material; approved workflow and schema descriptions; roadmap and traceability views; triaged requests and draft plans; untriaged inbox items and reference designs. A newer document is not automatically more authoritative. If two sources disagree, identify the conflict and its effect; do not silently choose one.

An inbox item, proposal, mockup, draft decision, or draft handoff is evidence or a suggested option, not approved behaviour. An approved handoff bounds delivery planning but cannot override a canonical requirement or accepted decision without an explicit recorded change.

## Change discipline

- Preserve stable IDs and the original source archive. Add a versioned replacement or an accepted decision instead of rewriting supplied originals.
- Record who approved a decision, the date, alternatives considered, consequences, and what it changes or supersedes.
- When a change is incorporated, update affected requirements, workflows, schema notes, roadmap gates, handoffs, and traceability together. Leave links from the request to its outcome.
- Separate confirmed facts, proposals, assumptions, hard prerequisites, and optional sequencing preferences.
- Keep privacy, security, accessibility, audit, historical reproducibility, and operational effects visible when relevant to the project.
- Return unresolved questions with their stable IDs and blocking point. Do not settle them through a diagram, test fixture, interface choice, or implementation convenience.

## Working with delivery teams

Give a delivery agent one approved, bounded handoff and its linked decisions. Ask it to record deviations and bring new product questions back to `inbox/new/`. Actual delivery artifacts and their evidence establish what currently exists; this documentation establishes intended behaviour. This boundary applies whether the artifacts live in the same repository or another one. Do not claim a feature is deployed or accepted from a plan or a local check alone.

## File practices

Use repository-relative links. Prefer one file per coherent capability or decision, not one file per sentence or one giant file for the entire project. Keep headings and filenames stable after others begin linking to them. Run link, ID, status, and diff checks before committing. Do not include credentials or personal data in examples. Do not commit generated previews unless the project explicitly governs them.

