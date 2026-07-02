# OctoAcme Project Management Docs

This repository contains OctoAcme's project management process documents. This README serves as a single landing page summarizing our approach and linking to each process document.

## OctoAcme Project Management Overview

OctoAcme follows a structured five-phase project lifecycle that emphasizes iterative delivery, clear ownership, and data-informed decision-making. The process begins with **Initiation**, where new projects are validated through a lightweight Project One-pager that establishes the business need, success metrics, stakeholder alignment, and resource requirements. Once approved, the project moves into **Planning**, where work is broken down into shippable increments with prioritized backlogs, acceptance criteria, and a release plan. The core **Execution & Tracking** phase leverages daily standups, weekly delivery syncs, and GitHub Projects boards (with columns: Backlog, Ready, In Progress, In Review, QA, Done) to manage day-to-day progress. Pull requests are kept small (≤400 lines when possible), require CI validation and at least one approval before merging, and are tracked against acceptance criteria. After delivery, projects move through **Release & Deployment** with pre-release checklists, smoke testing, and rollback plans, followed by **Retrospectives & Continuous Improvement** to capture learnings and convert them into actionable improvements.

### Roles and Organization

The organization defines clear roles and responsibilities across four core personas. **Product Managers** own the product vision, prioritize the backlog, and measure outcomes through success metrics. **Project Managers** coordinate delivery activities, manage schedules, risks, and communications to ensure projects stay on track and stakeholders remain aligned. **Developers** implement features, write tests, participate in code reviews, and help identify technical risks. **QA/Testing** validates quality and acceptance criteria. This distributed ownership model is reinforced through a consistent communication cadence: daily standups (15 minutes) focused on progress and blockers, weekly PM and PdM syncs, twice-weekly team standups, and monthly stakeholder updates.

### Quality Assurance and Risk Management

Risk and quality management are embedded throughout the lifecycle. Teams maintain a Risk Register capturing ID, description, impact, likelihood, owner, and mitigation plans, reviewed weekly during syncs. Escalation follows a three-level path: team-level triage → PM escalation to Product Lead and dependent teams → sponsor-level escalation for business-impacting issues. Quality assurance practices include unit tests for new logic, integration tests where applicable, end-to-end smoke tests before release, CI-based security scanning, and manual QA for feature acceptance. Success is tracked through velocity, burndown charts, and dashboards monitoring key signals (errors, latency, usage) identified in the Project One-pager. This comprehensive approach balances speed with rigor, ensuring OctoAcme delivers reliable, measurable value while maintaining transparency and psychological safety across teams.

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

- **New team members**: Start with the [Project Management Overview](./octoacme-project-management-overview.md) and [Roles & Personas](./octoacme-roles-and-personas.md) to understand the framework.
- **Project leads**: Reference the [Initiation Guide](./octoacme-project-initiation.md) and [Planning](./octoacme-project-planning.md) docs when starting a new project.
- **Delivery teams**: Use [Execution & Tracking](./octoacme-execution-and-tracking.md) for day-to-day guidance.
- **Release managers**: Follow the [Release & Deployment](./octoacme-release-and-deployment.md) checklist before going live.
- **Retrospectives**: Use [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) to capture learnings.

---

## Questions or Feedback?

If you have questions about these processes or would like to suggest improvements, please open an issue using the issue template referenced above.
