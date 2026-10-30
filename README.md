# Project documentation template

This is a reusable home for product and project reference material. It separates incoming evidence from approved requirements and decisions, then turns approved intent into bounded handoffs for delivery. It assumes no programming language, framework, hosting platform, database, or repository layout. It can live beside implementation work or in a separate documentation repository.

## Start a project

1. Copy this directory into the new project's repository or documentation area. Keep original source files in `docs/source/` and record their origin, version, and date in its README.
2. Replace the guidance in `context/` with a short overview, vocabulary, constraints, and unresolved questions. Do not invent answers to fill gaps.
3. Choose stable ID prefixes for requirements, changes, decisions, epics, and features. Record the convention in `docs/traceability/README.md` before issuing IDs.
4. Tailor the authority order in [AGENTS.md](AGENTS.md) to the project and name the people or roles who can approve changes, decisions, designs, and handoffs.
5. Add canonical requirements and workflow descriptions only after checking them against source material. Put new suggestions in `inbox/new/` first.
6. Build a roadmap from the accepted scope. Draft a feature handoff in `plans/drafted/`; promote it to `plans/approved/` only after the named approvals and blocking decisions are recorded.

## Directory map

| Directory | Purpose | Why it is separate |
| --- | --- | --- |
| [context/](context/README.md) | Short orientation, vocabulary, invariants, open questions | Lets a new reader find the right source without loading the whole corpus |
| [docs/](docs/README.md) | Source archive, canonical requirements, workflows, schema, roadmap, traceability | Keeps obligations and derived planning views distinct |
| [decisions/](decisions/README.md) | Dated cross-cutting decisions and their consequences | Preserves why a choice was made and what it superseded |
| [inbox/](inbox/README.md) | New requests, triage, and incorporation outcomes | Stops an unreviewed suggestion from becoming a requirement by accident |
| [design/](design/README.md) | Interface evidence, proposals, shared patterns, approved contracts | Separates a visual option from an approved implementation input |
| [plans/](plans/README.md) | Feature handoffs and review records | Gives delivery teams a bounded, traceable scope |
| [agents/](agents/README.md) | Restart prompts for documentation roles | Restores role context without duplicating governing rules |

## Typical flow

```text
source or incoming change -> triage -> decision -> canonical docs + traceability
                                         -> roadmap -> draft handoff
                                         -> approved handoff -> delivery plan
                                         -> review and implementation record
```

Read [AGENTS.md](AGENTS.md) before asking an agent to edit this repository. For a fresh Product Steward session, use the [role prompt](agents/product-steward.md). Every directory has a README describing what belongs there. Templates are examples to copy and adapt; they are not approved project content.

