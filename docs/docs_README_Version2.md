```markdown
# OctoAcme Project Management Docs — README

This README is the entry point for OctoAcme’s program management processes. It summarizes OctoAcme’s project management approach and links to detailed process documents to help teams and new contributors quickly understand core workflows, responsibilities, and quality practices.

## Overview: OctoAcme Project Management Processes

OctoAcme uses an iterative, artifact-driven approach designed for predictable delivery and continuous improvement. Work starts with lightweight initiation (Project One‑pager, stakeholder identification, and a go/no‑go decision), moves into planning to break down scope into shippable increments with acceptance criteria and a Definition of Done, and proceeds to disciplined execution and release. Execution is tracked via a visible project board (Backlog → Ready → In Progress → In Review → QA → Done) and small, reviewable pull requests that include issue links and acceptance criteria.

Key workflows, roles, and communication patterns:
- Workflows: Project boards for status, small PRs with CI, defined DoD and acceptance criteria, and release checklists including rollback plans.
- Roles/Personas: Product Manager (outcomes & prioritization), Project Manager (schedules, risks, communications), Developers (implementation & tests), QA (validation), and Stakeholders (inputs & approvals).
- Communication: Daily standups for blockers, weekly delivery syncs and PM+PdM alignment, and monthly stakeholder updates; risks tracked in a risk register with clear escalation paths (Team → PM → Product Lead → Sponsor).
- Quality Assurance: Automated unit/integration tests and CI security scans, E2E smoke tests for critical flows, manual QA when needed, and action items captured from retrospectives.

## Key Documents

- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](./octoacme-roles-and-personas.md)

## How to use these docs

- Keep the Project One‑pager and project README updated as the single source of truth for each project.
- Use the issue template "Add Content to Project Management Process Docs" (`.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml`) to propose doc changes.
- Add process-specific templates or guidance into `.copilot/` if you want Copilot Spaces to use them as additional context.

```