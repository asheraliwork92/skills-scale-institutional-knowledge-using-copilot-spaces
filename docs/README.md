# OctoAcme Project Management Docs

Welcome! This README provides an overview and easy access to OctoAcme's program/project management process documents.

## Process Overview

OctoAcme uses a structured approach based on iterative planning, strong stakeholder alignment, clear roles, pragmatic risk management, and continuous improvement.

### Key Principles
- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

### Five-Phase Lifecycle

**1. Initiation** — Verify business need through a lightweight Project One-pager that captures problem statement, success metrics, stakeholder alignment, and initial timeline. Move to planning when success metrics are clear, stakeholders agree on priority, and team availability is confirmed.

**2. Planning** — Break work into shippable increments with prioritized backlogs, clear acceptance criteria, and a Definition of Done. Identify dependencies and risks, then create release plan and milestone map. Planning includes a kickoff meeting, estimation, and test strategy.

**3. Execution & Tracking** — Day-to-day progress management with daily standups (15 min), weekly delivery syncs, and regular demos. Teams use GitHub Projects board (Backlog → Ready → In Progress → In Review → QA → Done) with small PRs (≤400 lines), automated testing/linting in CI, and at least one approval before merging. Quality includes unit tests, integration tests, end-to-end smoke tests, security scanning, and manual QA for feature acceptance.

**4. Release & Deployment** — Checklist-driven safe launches with pre-deployment verification (acceptance criteria met, security scans passed, smoke tests ready), documented rollback/incident playbook, and post-deploy verifications. Release notes and communication to stakeholders complete the phase.

**5. Retrospective & Continuous Improvement** — After each sprint, release, or milestone, teams conduct 45–75 minute retrospectives to capture learnings, prioritize 2–3 action items with clear owners and due dates, and measure impact of improvements.

### Risk & Communication

Risk management maintains a Risk Register (ID, Description, Impact, Likelihood, Owner, Mitigation, Status) reviewed weekly at syncs. Escalation follows a three-level path: team-level → PM → Product Lead → Sponsor. Stakeholder communication uses a single source of truth (project README or release doc) with weekly status updates covering progress, next steps, risks/blockers, and decisions needed.

### Core Roles

- **Project Manager (PM)**: Coordinates delivery, manages schedules, risk, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, measures success
- **Developers**: Implement features, collaborate on design and testability
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs and approvals

## Available Process Docs

- **[Project Management Overview](octoacme-project-management-overview.md)** — Introduction to OctoAcme's approach, roles, and key artifacts
- **[Project Initiation Guide](octoacme-project-initiation.md)** — Steps to validate business need, align stakeholders, and create initial plan
- **[Project Planning](octoacme-project-planning.md)** — Breaking work into shippable increments, estimation, Definition of Done, and risk management
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Day-to-day execution, team rhythm, PR workflow, quality assurance, and blocker escalation
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Risk register, lifecycle, stakeholder communication, and escalation paths
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Release types, pre-release requirements, deployment checklist, and rollback playbook
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Retrospective structure, running meetings, tracking improvements, and building continuous improvement culture
- **[Roles and Personas](octoacme-roles-and-personas.md)** — Detailed role summaries, responsibilities, and goals for Developers, Product Managers, and Project Managers

## How to Use These Docs

1. **New to OctoAcme?** Start with [Project Management Overview](octoacme-project-management-overview.md) for a high-level introduction.
2. **Starting a new project?** Follow the [Project Initiation Guide](octoacme-project-initiation.md) → [Project Planning](octoacme-project-planning.md) → [Execution & Tracking](octoacme-execution-and-tracking.md) sequence.
3. **Managing risks or communications?** Reference [Risk Management & Communication](octoacme-risks-and-communication.md).
4. **Preparing for release?** Use [Release & Deployment Guide](octoacme-release-and-deployment.md).
5. **Learning from a project?** Follow [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md).
6. **Understanding roles?** See [Roles and Personas](octoacme-roles-and-personas.md).

## Communication Cadence

- **Daily**: Team standups (focus on progress, blockers, dependencies)
- **Weekly**: PM + PdM sync, twice-weekly delivery team standups
- **Milestone-based**: Demo/Review at end of each sprint or milestone
- **Monthly**: Stakeholder updates
- **As-needed**: Ad-hoc escalations and incident communication

## Questions?

Refer to the specific process doc for your phase or role. For process improvements or gaps, please create an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.
