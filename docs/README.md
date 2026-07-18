# OctoAcme Project Management Docs

Welcome to OctoAcme's project management processes documentation. This directory contains guidance for running projects at OctoAcme—from initial concept through execution, release, and continuous improvement.

## Overview of OctoAcme Project Management Processes

OctoAcme operates on a structured lifecycle approach that moves projects through five distinct phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. The process begins with rigorous initiation, where new ideas are validated through a lightweight One-pager that confirms business need, identifies stakeholders, and establishes success metrics before proceeding. Once approved, projects transition to detailed planning where work is broken into shippable increments with clear acceptance criteria, dependencies are mapped, and a prioritized backlog is created. This foundation enables the team to execute with confidence, using a consistent pull request workflow with automated testing and peer review to maintain quality throughout development.

The organization emphasizes clear ownership through three primary roles: **Project Managers** coordinate delivery timelines and risk management, **Product Managers** define outcomes and prioritize the backlog, and **Developers** implement features while maintaining high quality standards. This role clarity is reinforced through consistent communication rhythms—daily standups focus on progress and blockers, weekly syncs align the PM and Product Manager, and monthly stakeholder updates maintain transparency. Risk management is woven throughout the entire lifecycle, with a Risk Register tracking issues by impact and likelihood, and escalation paths that move from team-level triage through PM channels to sponsor-level interventions for business-critical issues.

Quality assurance and continuous improvement are embedded in OctoAcme's DNA. The execution phase requires unit tests for new logic, integration testing where applicable, and end-to-end smoke tests before release, complemented by security scanning in CI pipelines. Deployment follows strict pre-release requirements including passing CI checks, drafted release notes, and documented rollback plans to minimize production risk. Finally, each sprint and release concludes with retrospectives that capture learnings and convert them into actionable improvements, tracked through the project backlog with clear owners and timelines to ensure the organization continually refines its processes and capabilities.

## Quick Navigation

| Document | Purpose |
|----------|---------|
| [**octoacme-project-management-overview.md**](./octoacme-project-management-overview.md) | High-level overview of how OctoAcme runs projects, core roles, lifecycle stages, and key artifacts. Start here for context. |
| [**octoacme-project-initiation.md**](./octoacme-project-initiation.md) | Steps and minimum deliverables to validate and authorize new projects: one-pager, stakeholder alignment, decision gate. |
| [**octoacme-project-planning.md**](./octoacme-project-planning.md) | Guidance for turning approved initiatives into actionable plans: backlog creation, estimation, release planning, and Definition of Done. |
| [**octoacme-execution-and-tracking.md**](./octoacme-execution-and-tracking.md) | Day-to-day execution rhythms, team standups, PR workflow, quality assurance, reporting, and blocker escalation. |
| [**octoacme-release-and-deployment.md**](./octoacme-release-and-deployment.md) | Release types, pre-release requirements, deployment checklist, rollback and incident playbook, and release notes template. |
| [**octoacme-retrospective-and-continuous-improvement.md**](./octoacme-retrospective-and-continuous-improvement.md) | Retrospective structure, action-item tracking, and continuous improvement practices. |
| [**octoacme-risks-and-communication.md**](./octoacme-risks-and-communication.md) | Risk register guidance, stakeholder communication templates, and escalation paths. |
| [**octoacme-roles-and-personas.md**](./octoacme-roles-and-personas.md) | Role summaries and responsibilities for Developers, Product Managers, and Project Managers. |

## How to Use These Docs

1. **New to OctoAcme?** Start with [octoacme-project-management-overview.md](./octoacme-project-management-overview.md) for context, then explore specific guides based on your current phase.

2. **Starting a new project?** Follow the sequence:
   - [Project Initiation](./octoacme-project-initiation.md) — Validate the idea
   - [Project Planning](./octoacme-project-planning.md) — Create an actionable plan
   - [Execution & Tracking](./octoacme-execution-and-tracking.md) — Build and deliver
   - [Release & Deployment](./octoacme-release-and-deployment.md) — Ship to production
   - [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Learn and improve

3. **Managing risks or communicating status?** Refer to [octoacme-risks-and-communication.md](./octoacme-risks-and-communication.md).

4. **Looking for role definitions?** See [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md).

## Key Project Artifacts

- **Project Charter / One-pager** — Problem, goal, success metrics, stakeholders, timeline, risks, resources
- **Roadmap and Release Plan** — High-level features, milestones, dependencies
- **Sprint / Iteration Backlog** — Prioritized work with acceptance criteria and estimates
- **Risk Register** — Tracked issues with impact, likelihood, owner, and mitigation
- **Retrospective Notes** — Learnings and action items for continuous improvement

## Communication Cadence

- **Daily standups** — Progress, blockers, dependencies (15 min)
- **Weekly PM + PdM sync** — Planning and prioritization
- **Twice-weekly team standups** — Delivery coordination (as needed)
- **Monthly stakeholder updates** — Status, risks, asks
- **Ad-hoc escalations** — Critical issues via escalation path (Team → PM → Product Lead → Sponsor)

## How to Propose Changes

To propose changes to any process document, open a new issue using the **"Add Content to Project Management Process Docs"** template (found in [.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)).

In your issue:
- Select the target document (or `<new document>` for a new guide)
- Provide a summary of the new content or update
- Explain why the change is needed
- Optionally include suggested copy

This approach ensures process improvements are captured, discussed, and versioned as part of the project repository.

## Maintainers

These process docs are maintained collaboratively by OctoAcme's Project Managers, Product Managers, and team leads. For questions or feedback, reach out to the team or open an issue.

---

**Last Updated:** 2026-07-18  
**Version:** 1.0
