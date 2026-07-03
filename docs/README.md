# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation hub. This collection of guides helps teams consistently execute projects with clear ownership, data-informed decisions, and continuous improvement.

## Quick Start

New to OctoAcme? Start with the [Project Management Overview](./octoacme-project-management-overview.md) for a concise introduction to our approach, roles, and key artifacts.

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named PM and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## OctoAcme Project Management Approach

OctoAcme follows a structured, lifecycle-based approach to project management built on clear ownership and data-driven execution. The organization defines three key roles—Project Manager (PM), Product Manager (PdM), and the delivery team (Developers, QA/Testing, and Stakeholders)—each with distinct responsibilities that enable coordinated execution.

### Project Lifecycle Overview

Projects flow through five phases: **Initiation** (validating business need and stakeholder alignment), **Planning** (breaking work into shippable increments), **Execution** (building and testing), **Release** (deploying to production), and **Close & Retrospective** (capturing learnings). This lifecycle ensures that every initiative has clear success metrics, defined deliverables, and documented rationale before work begins.

Execution and delivery are managed through a rigorous workflow and communication cadence. Teams use GitHub Projects with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done) and follow small PR practices with automated CI/CD checks, linting, and security scanning before human review. Quality is maintained through unit tests, integration tests, end-to-end smoke tests, and manual QA when needed.

Risk management and stakeholder communication are embedded throughout the project lifecycle. OctoAcme maintains a Risk Register reviewed at weekly syncs and communicates proactively with stakeholders through status updates, milestone notifications, and blameless retrospectives. This enables teams to deliver customer value reliably while building organizational learning and reducing single-person dependency risk.

## Documentation Index

### Overview & Strategy

- [Project Management Overview](./octoacme-project-management-overview.md) — Introduction to OctoAcme's approach, roles, key artifacts, and communication cadence

### Project Lifecycle Phases

1. [Project Initiation](./octoacme-project-initiation.md) — Validate ideas, align stakeholders, create lightweight plans, and decide go/no-go for planning
2. [Project Planning](./octoacme-project-planning.md) — Turn approved initiatives into actionable plans, backlogs, and release timelines
3. [Execution & Tracking](./octoacme-execution-and-tracking.md) — Manage day-to-day execution, track progress, and handle blockers
4. [Release & Deployment](./octoacme-release-and-deployment.md) — Standardize releases to production with safety checks and rollback plans
5. [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and drive actionable improvements

### Cross-cutting Guidance

- [Roles & Personas](./octoacme-roles-and-personas.md) — Define typical roles (Developers, Product Managers, Project Managers) and responsibilities
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — Identify, manage, and communicate risks and dependencies

## Key Artifacts

Common documents you'll create and maintain across the project lifecycle:

- **Project Charter / One-pager** — Problem statement, goals, success metrics, stakeholders
- **Roadmap and Release Plan** — High-level timeline and milestones
- **Sprint/Iteration Backlog** — Prioritized work items with acceptance criteria
- **Risk Register** — Tracked risks, mitigation plans, and status
- **Definition of Done** — Team's quality and acceptance standards
- **Retrospective Notes** — Learnings and action items from completed phases

## Communication Cadence

- **Daily**: 15-minute standups (focus on progress, blockers, dependencies)
- **Weekly**: PM + PdM sync; delivery team standups; risk register review
- **Sprint/Milestone**: Planning, demo/review, and retrospective
- **Monthly**: Stakeholder updates
- **Ad-hoc**: Escalations and incident communication

## Getting Started with a New Project

Follow these steps to establish a new project using OctoAcme's approach:

1. **Initiation** → Complete a Project One-pager and get stakeholder alignment
2. **Planning** → Create prioritized backlog, estimate scope, define Definition of Done
3. **Execution** → Execute sprints, track progress, manage risks and blockers
4. **Release** → Prepare release notes, run smoke tests, deploy to production
5. **Retrospective** → Capture learnings and schedule improvements

For detailed guidance at each phase, refer to the documentation index above.

## Contributing to These Docs

To update or add content to the OctoAcme process documentation:

1. Open a [Process Doc Update issue](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)
2. Describe the content you want to add or update
3. Explain the rationale (gap closure, clarity improvement, best practice alignment)
4. Submit for team review and validation

See [add-update-content-to-process-docs.yml](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) for the template.

---

**Last Updated**: June 2026  
**Maintained by**: OctoAcme Team
