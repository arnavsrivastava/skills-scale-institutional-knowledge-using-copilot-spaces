# OctoAcme Project Management — Overview

OctoAcme follows a lightweight, iterative project lifecycle: initiate with a concise one-pager to validate the problem, goals, and success metrics; plan by creating a prioritized backlog and release map; execute in small, shippable increments using a project board and PR-driven development; and finish with a gated release and a retrospective to capture improvements.

Key workflows include a standard project board (Backlog → Ready → In Progress → In Review → QA → Done), a Pull Request process that encourages small changes, linked issues and acceptance criteria, CI and lint gating, and at least one reviewer approval before merging. Planning artifacts use a consistent backlog-item template and Definition of Done, and the release process includes pre-release checks, staging smoke tests, automated deployment pipelines, and documented rollback steps.

Roles are clearly defined: Product Managers set outcomes and prioritize work; Project Managers coordinate delivery, risks, and communications; Developers implement, test, and document; QA validates acceptance criteria; and stakeholders review and approve at decision gates. Communication cadence includes daily standups, weekly delivery syncs, PM/PdM alignment meetings, and periodic stakeholder updates. Risks are tracked in a risk register and escalated along defined paths (team → PM → Product Lead → Sponsor).

Quality assurance is embedded throughout the lifecycle: unit and integration tests for code quality, end-to-end smoke tests for critical flows, security scans in CI, and manual QA for feature acceptance when needed. Releases follow a checklist (acceptance criteria met, passing CI, smoke tests, release notes, rollback plan) and retrospectives convert learnings into tracked, owner-assigned action items.

## Docs

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Risks & Communication](octoacme-risks-and-communication.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)
