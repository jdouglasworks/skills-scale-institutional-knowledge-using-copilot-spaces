# OctoAcme Project Management — Documentation Hub

Welcome to the OctoAcme project management documentation. This folder is the single source of truth for how OctoAcme plans, executes, and continuously improves its projects. Whether you are a new team member or a returning contributor, start here to orient yourself before diving into the detailed process documents.

---

## Table of Contents

- [Overview](#overview)
- [Key Roles & Responsibilities](#key-roles--responsibilities)
- [Team Rhythm & Communication Cadence](#team-rhythm--communication-cadence)
- [Process Documents](#process-documents)

---

## Overview

OctoAcme follows a structured, lifecycle-based project management approach designed to maximize customer value while maintaining transparency and team ownership. The framework encompasses five core phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Retrospective**. During Initiation, teams validate business needs and align stakeholders around a lightweight Project One-pager that defines the problem, objectives, success metrics, and resource requirements. This decision-gate approach ensures projects move forward only when success criteria are clear and stakeholder buy-in is confirmed. The Planning phase then transforms the approved initiative into actionable increments, with teams breaking work into backlog items with acceptance criteria, estimating scope, identifying dependencies, and establishing a clear Definition of Done. This deliberate front-loading of planning reduces downstream surprises and rework.

Execution is managed through iterative delivery cycles with a structured team rhythm: daily standups (15 minutes, focused on progress and blockers), weekly delivery syncs to review progress and flag risks, and demos at sprint or milestone endpoints. The team uses GitHub Projects to visualize workflow stages (Backlog → Ready → In Progress → In Review → QA → Done) and maintains quality through unit tests, integration tests, end-to-end smoke tests, and security scanning in CI. Pull requests are kept small (≤ 400 lines when possible) and require at least one approval before merging, with automated testing and linting enforced before review. Risk management is continuous, with a Risk Register tracking identified issues and mitigation plans that are reviewed weekly and escalated through defined levels: team triage → PM to Product Lead → sponsor-level escalation for business-impacting issues.

Clear role definition underpins OctoAcme's success. **Project Managers** coordinate delivery, manage schedules, risks, and communications; **Product Managers** define outcomes, prioritize backlogs, and measure success; **Developers** implement features collaboratively and write tests and documentation; and **QA/Testing** validates quality against acceptance criteria. Before Release, teams verify all acceptance criteria are met, CI and security scans pass, release notes are drafted, and rollback plans are documented. Finally, Retrospectives after each sprint, release, or incident capture learnings and convert them into actionable improvements tracked with clear ownership and due dates, embedding continuous improvement into the team's culture and reinforcing psychological safety and shared accountability.

---

## Key Roles & Responsibilities

| Role | Primary Responsibilities |
|---|---|
| **Project Manager (PM)** | Coordinates delivery, manages schedules, tracks risks, and facilitates communication |
| **Product Manager (PdM)** | Defines outcomes, prioritizes the backlog, and measures success against goals |
| **Developers** | Implement features, collaborate on design and testability, write tests and documentation |
| **QA / Testing** | Validate quality and acceptance criteria before release |
| **Stakeholders** | Provide inputs, approvals, and business context |

For a deeper look at each persona, see [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md).

---

## Team Rhythm & Communication Cadence

| Cadence | Participants | Purpose |
|---|---|---|
| Daily standup (15 min) | Delivery team | Share progress, surface blockers |
| Weekly delivery sync | PM + Developers + QA | Review progress, flag risks, adjust plan |
| Weekly PM + PdM alignment | PM, PdM | Roadmap and priority alignment |
| Sprint / milestone demo | Delivery team + Stakeholders | Showcase completed work, gather feedback |
| Monthly stakeholder update | PM, PdM, Stakeholders | Broader status update and roadmap review |
| Ad-hoc escalation | As needed | Address urgent risks or blockers |

---

## Process Documents

The following documents provide detailed guidance for each phase and practice area:

| Document | Description |
|---|---|
| [octoacme-project-management-overview.md](./octoacme-project-management-overview.md) | High-level principles, core roles, key artifacts, and lifecycle summary |
| [octoacme-project-initiation.md](./octoacme-project-initiation.md) | Initiation phase: problem validation, stakeholder alignment, and the Project One-pager |
| [octoacme-project-planning.md](./octoacme-project-planning.md) | Planning phase: backlog creation, estimation, dependencies, and Definition of Done |
| [octoacme-execution-and-tracking.md](./octoacme-execution-and-tracking.md) | Execution phase: team rhythm, GitHub Projects workflow, and quality assurance practices |
| [octoacme-risks-and-communication.md](./octoacme-risks-and-communication.md) | Risk Register management, escalation paths, and communication strategies |
| [octoacme-release-and-deployment.md](./octoacme-release-and-deployment.md) | Release phase: deployment checklist, release notes, and rollback planning |
| [octoacme-retrospective-and-continuous-improvement.md](./octoacme-retrospective-and-continuous-improvement.md) | Retrospective practices, action item tracking, and continuous improvement loops |
| [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md) | Detailed breakdown of each role, responsibilities, and collaboration patterns |

---

> **New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md), then read the [Initiation](./octoacme-project-initiation.md) and [Planning](./octoacme-project-planning.md) docs to understand how projects get started. From there, the [Execution & Tracking](./octoacme-execution-and-tracking.md) guide will walk you through daily team practices.
