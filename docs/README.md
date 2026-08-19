# OctoAcme Project Management Documentation

Welcome to OctoAcme's project management process library. This README is the central entry point for our approach to running cross-functional projects — from initiation through delivery and retrospectives — and links to the detailed process docs in this folder.

Our approach prioritizes customer value, iterative delivery, clear ownership, data-informed decisions, and psychological safety. Work moves through a lightweight lifecycle: Initiation (validate the problem and align stakeholders), Planning (break work into shippable increments, define success metrics, and identify risks), Execution (build, test, and iterate with standing rhythms and CI), Release (deploy with checks, rollback plans, and stakeholder communications), and Close & Retrospective (capture learnings and drive improvements).

Key workflows include a project board (Backlog → Ready → In Progress → In Review → QA → Done), a PR workflow that requires linked issues, acceptance criteria, automated CI checks, and reviews before merging, and a Risk Register + escalation paths for blockers. Quality assurance is layered: unit and integration tests, security scanning in CI, end-to-end smoke tests for critical flows, and manual QA when needed. Retrospectives and measurable action items ensure continuous improvement.

Documentation index
- Foundations
  - [Project Management Overview](./octoacme-project-management-overview.md)
  - [Roles & Personas](./octoacme-roles-and-personas.md)
- Phase-by-Phase Guides
  - [Project Initiation Guide](./octoacme-project-initiation.md)
  - [Project Planning](./octoacme-project-planning.md)
  - [Execution & Tracking](./octoacme-execution-and-tracking.md)
  - [Release & Deployment Guide](./octoacme-release-and-deployment.md)
  - [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- Cross-cutting
  - [Risk Management & Communication](./octoacme-risks-and-communication.md)

Quick start by role
- Project Manager: start with Project Management Overview, then Initiation and Planning.
- Product Manager: review Initiation for success metrics and the Overview for artifacts.
- Developers: see Execution & Tracking for workflow and quality expectations; check Release & Deployment for deployment steps.
- QA/Testing: reference Execution & Tracking and Release & Deployment for verification and smoke test guidance.

Contributing updates
To propose additions or changes:
1. Open an issue using the Add Content to Project Management Process Docs template: .github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml
2. Include the affected doc, proposed change, and rationale.
3. Discuss with the team and iterate before merging.
