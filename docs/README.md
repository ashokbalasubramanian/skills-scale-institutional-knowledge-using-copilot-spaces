# OctoAcme Project Management Docs

This folder contains OctoAcme's project management process documentation. These documents capture how we start, plan, build, verify, release, and continuously improve cross-functional projects at OctoAcme. They are intended to centralize knowledge, speed onboarding, and make our processes discoverable and repeatable.

Overview
OctoAcme follows a lifecycle from Initiation → Planning → Execution → Release → Retrospective. We emphasize clear ownership (a named Project Manager and Product Lead per initiative), iterative delivery in small increments, and data-informed decisions. Communication is cadence-driven (standups, weekly delivery syncs, PM+PdM alignment, milestone demos) and risks/dependencies are tracked in a simple Risk Register with defined escalation paths.

Key workflows include a project board flow (Backlog → Ready → In Progress → In Review → QA → Done), a disciplined pull request and CI process (small PRs, issue links, CI tests, security scans, and required approvals), and a release checklist that includes staging verification, smoke tests, and rollback plans. Quality assurance is layered — unit/integration tests, end-to-end smoke tests for critical flows, automated security scanning in CI, and manual QA where needed — with QA activities tied to the pipeline and release gate checklist.

Contents
- octoacme-project-management-overview.md — high-level roles, principles, and lifecycle
- octoacme-project-initiation.md — one-pager and initiation checklist
- octoacme-project-planning.md — backlog templates, planning cadence, DoD
- octoacme-execution-and-tracking.md — team rhythm, PR workflow, tracking
- octoacme-release-and-deployment.md — release types, pre-release gates, rollback
- octoacme-retrospective-and-continuous-improvement.md — running retrospectives and tracking actions
- octoacme-risks-and-communication.md — risk register and communication templates
- octoacme-roles-and-personas.md — personas and responsibilities

How to use
- Keep the one-pager and README up to date as the single source of truth for project status and links.
- Add any project-specific artifacts and runbooks to the project repo and reference them here.
- If you find gaps or have improvements, open an issue and propose a change — we use retrospective action items and backlog issues to evolve these docs.

Acceptance criteria
- Content aligns with existing process docs in this folder.
- README provides clear navigation and a concise summary of OctoAcme processes.
- README is reviewed and approved by stakeholders as needed.
