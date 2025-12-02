# OctoAcme Project Management Docs

## Purpose
This folder centralizes OctoAcme's project management processes, templates, and checklists. It provides a single place for new and existing team members to find project lifecycle guidance, supports onboarding, and makes process artifacts discoverable for Copilot Spaces ingestion.

## How to use these docs
- Start with this README to locate the right process document for your need.
- Project-specific artifacts (one-pagers, risk registers, release notes) should live in the project repo's docs/ or .copilot/ so Copilot Spaces can use them as context.
- Keep each document concise, focused, and link to concrete templates or examples where possible.
- To propose edits, use the ".github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml" issue template.

## Brief overview of OctoAcme project management processes
OctoAcme follows a customer-first, iterative delivery model with clear ownership and a focus on small, testable increments. The following concise summary reflects the process documents in this repository:

- Initiation: validate the problem, create a Project One-pager with measurable success metrics, identify stakeholders and initial risks, and decide to proceed to planning.
- Planning: run a kickoff, produce a prioritized backlog with acceptance criteria, estimate scope, define a Definition of Done, identify dependencies and populate the risk register, and produce a release/milestone plan.
- Execution & Tracking: deliver in small increments using PRs, CI, automated tests, and the project board. Maintain a team rhythm of standups, weekly delivery syncs, and demos; update the risk register and report velocity/metrics.
- Release & Deployment: follow the release checklist (pre-release checks, staging smoke tests, automated pipeline where possible), document rollback/incident playbooks, and announce releases to stakeholders.
- Retrospective & Continuous Improvement: run retros after sprints/releases/incidents, convert action items into backlog issues, measure impact of improvements, and iterate on processes.

Core practices used across these stages:
- Named PM and Product Lead for each initiative
- Small, reviewable pull requests with CI gating and automated tests
- Weekly status updates and regular risk register reviews
- Retrospectives that produce tracked action items
- Single source of truth per project (project README / one-pager)

## Documents in this folder
- [Project Management Overview](./octoacme-project-management-overview.md) — high level principles, roles, artifacts.
- [Project Initiation Guide](./octoacme-project-initiation.md) — one-pager template and decision gate.
- [Project Planning](./octoacme-project-planning.md) — backlog, estimates, DoD, and planning checklist.
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — team rhythm, workflows, quality, and reporting.
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — risk register, templates, and escalation paths.
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) — pre-release checklist, deployment, and rollback playbook.
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — running retros, tracking action items.
- [Roles and Personas](./octoacme-roles-and-personas.md) — role summaries and responsibilities.

## Templates and Checklists
- [Change Management Checklist](./change-management-checklist.md) — standardized checklist for managing change requests.
- [Communications Plan Template](./communications-plan-template.md) — template for project communications planning.
- [Quality Acceptance Checklist](./quality-acceptance-checklist.md) — checklist for validating deliverable quality.
- [Stakeholder Engagement Log](./stakeholder-engagement-log.md) — log for tracking stakeholder interactions and feedback.

## Acceptance criteria
- [ ] Links point to the correct documents in this folder
- [ ] Content aligns with existing process docs and doesn't introduce conflicting guidance
- [ ] Stakeholders (PM/Product Lead) have reviewed content where applicable

## Contribution guidance
- Propose changes with the repository's process-doc issue template: .github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml
- Small edits: open a branch (e.g., docs/add-octoacme-readme), update this file, and create a pull request referencing the originating issue (e.g., #2).
- Larger changes: discuss in a quick sync or comment on issue #2 before drafting edits.
