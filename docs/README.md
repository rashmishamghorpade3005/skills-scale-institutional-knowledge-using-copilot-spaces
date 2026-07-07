# OctoAcme Project Management Docs

This repository contains OctoAcme's project management process documents. This README serves as a single landing page summarizing our approach and linking to each process document.

## OctoAcme Project Management Overview

OctoAcme follows a structured, five-phase project lifecycle designed to deliver customer value through iterative, data-informed execution. The process begins with **Initiation**, where new ideas are validated through a lightweight Project One-pager that confirms business need, identifies stakeholders, and establishes success metrics. Once approved, projects move into **Planning**, where work is broken into shippable increments with clear acceptance criteria, dependencies are mapped, and a prioritized backlog is created. The core **Execution & Tracking** phase emphasizes daily standups, weekly delivery syncs, and a GitHub Projects workflow with standardized PR practices (≤400 lines, automated testing, and peer review requirements). Finally, **Release & Deployment** and **Retrospective & Continuous Improvement** phases ensure quality releases with documented rollback plans and systematic capture of learnings to drive ongoing optimization.

The organization operates with clearly defined roles that balance strategic and tactical responsibilities. **Product Managers** own the vision, prioritize the backlog, and define success metrics; **Project Managers** coordinate schedules, manage risks, and drive stakeholder communication; **Developers** implement features while maintaining test coverage and identifying technical risks; and **QA/Testing** roles validate quality and acceptance criteria. This structure ensures clear ownership and accountability, with weekly PM-PdM syncs and twice-weekly team standups maintaining alignment across engineering, product, and stakeholder groups.

Quality and risk management are embedded throughout the execution lifecycle rather than treated as afterthoughts. OctoAcme mandates unit tests, integration tests, and end-to-end smoke tests before release, along with security scanning in CI. A formal Risk Register tracks identified threats by impact and likelihood, with weekly review during delivery syncs and escalation paths that move from team-level triage through PM, Product Lead, and Sponsor levels. Communication is intentionally structured through weekly status templates, monthly stakeholder updates, and ad-hoc incident playbooks, ensuring transparency across all stakeholders while maintaining psychological safety for honest feedback and continuous improvement.

---

## Process Documents

### Quick Reference

- **Initiation**: Capture the problem, goals, stakeholders, and success metrics in a Project One-pager.
- **Planning**: Break work into shippable increments, estimate, identify dependencies, and document a release plan.
- **Execution & Tracking**: Use a project board, small PRs, CI checks, daily standups, and weekly syncs to track progress.
- **Release & Deployment**: Follow pre-release checks, smoke tests, and rollback plans with post-deploy verification.
- **Retrospective & Continuous Improvement**: Run retrospectives, create action items, and track improvements.
- **Risk & Communication**: Maintain a risk register, escalate blockers, and follow stakeholder communication templates.

### Full Documentation

| Document | Purpose |
|----------|---------|
| [Project Management Overview](./octoacme-project-management-overview.md) | Concise introduction to roles, principles, and lifecycle. |
| [Project Initiation Guide](./octoacme-project-initiation.md) | One-pager template, initiation checklist, and decision gate. |
| [Project Planning](./octoacme-project-planning.md) | Backlog templates, sprint planning, and risk management. |
| [Execution & Tracking](./octoacme-execution-and-tracking.md) | Team rhythm, workflows, CI/PR guidance, and blocker escalation. |
| [Risks & Communication](./octoacme-risks-and-communication.md) | Risk register, communication templates, and escalation paths. |
| [Release & Deployment](./octoacme-release-and-deployment.md) | Deployment checklist, rollback playbook, and release notes. |
| [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Retrospective structure and tracking improvements. |
| [Roles & Personas](./octoacme-roles-and-personas.md) | Role descriptions and responsibilities. |

---

## Adding or Updating Docs

To propose a new process document or update an existing one, use the repository's issue template **"Add Content to Project Management Process Docs"** located in `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml`.

When creating an issue:
1. Select the document you want to update (or leave blank for a new document)
2. Provide a summary of the new content or updates
3. Explain why the update is needed
4. Optionally include suggested content
5. Verify acceptance criteria are met

---

## How to Use These Docs

- **New team members**: Start with the [Project Management Overview](./octoacme-project-management-overview.md) and [Roles & Personas](./octoacme-roles-and-personas.md) to understand the framework and key roles.
- **Project leads**: Reference the [Initiation Guide](./octoacme-project-initiation.md) and [Planning](./octoacme-project-planning.md) docs when starting a new project.
- **Delivery teams**: Use [Execution & Tracking](./octoacme-execution-and-tracking.md) for day-to-day guidance.
- **Release managers**: Follow the [Release & Deployment](./octoacme-release-and-deployment.md) checklist before going live.
- **Retrospectives**: Use [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) to capture learnings.

---

## Questions or Feedback?

If you have questions about these processes or would like to suggest improvements, please open an issue using the issue template referenced above.
