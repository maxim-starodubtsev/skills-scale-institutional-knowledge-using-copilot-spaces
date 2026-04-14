# OctoAcme Project Management Docs — README

Welcome to OctoAcme's project management documentation. This README provides a concise entry point to our processes and direct links to the detailed process docs in the docs/ folder.

## Brief overview of our approach
OctoAcme follows a lightweight, iterative lifecycle that starts with a focused Initiation and moves through Planning, Execution, Release, and Continuous Improvement. Initiation captures the problem, SMART goals, stakeholders, and measurable success metrics; a clear go/no‑go decision moves work into Planning. Planning breaks approved initiatives into shippable increments, prioritizes a backlog with acceptance criteria, estimates scope, documents a Definition of Done, and records dependencies and risks.

Execution relies on a steady team rhythm (daily standups, weekly delivery syncs, timeboxed planning and demos), a project board workflow (Backlog → Ready → In Progress → In Review → QA → Done), and PR/CI quality gates (small PRs, linked acceptance criteria, automated tests and security scans, and required reviews). Releases follow checklist-driven pipelines with staging smoke tests, release notes, rollback plans, and post-deploy verification. After milestones and incidents we run blameless retrospectives and convert action items into tracked backlog work to continuously improve.

## Templates and checklists
To standardize delivery and QA, this repo includes templates:
- docs/templates/release-checklist.md
- docs/templates/qa-checklist.md

Use these templates as starting points during planning, sprint sign-off, and release preparation. Copy or adapt them per-project and add owner names and dates.

## Docs index
- [Project Management Overview](docs/octoacme-project-management-overview.md)
- [Project Initiation Guide](docs/octoacme-project-initiation.md)
- [Project Planning](docs/octoacme-project-planning.md)
- [Execution & Tracking](docs/octoacme-execution-and-tracking.md)
- [Risk Management & Communication](docs/octoacme-risks-and-communication.md)
- [Release & Deployment Guide](docs/octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](docs/octoacme-roles-and-personas.md)
- [Templates: release & qa](docs/templates/release-checklist.md) — (new)
- [Templates: qa checklist](docs/templates/qa-checklist.md) — (new)

## How to use this repo
- Use the project one‑pager and templates in the docs to kick off new work.
- Keep the project README and risk register updated as the single source of truth.
- Add process-specific docs into `.copilot/` when you want Copilot Spaces to use them as context.