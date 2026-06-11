# OctoAcme Project Management Docs

Welcome to the OctoAcme project management documentation hub! This README gives a concise overview of our processes and links directly to process documents below.

## Overview of Project Management Processes

OctoAcme project delivery is guided by an iterative, customer-first approach with clearly defined roles, artifacts, and routines:

**Core Approach and Lifecycle:** OctoAcme follows a structured, iterative project lifecycle designed to balance customer value with operational clarity. The approach spans five key phases: **Initiation** (problem validation and stakeholder alignment), **Planning** (scope definition and backlog creation), **Execution** (build and iterate), **Release** (deploy and verify), and **Close & Retrospective** (capture learnings). At each stage, the process emphasizes clear ownership, measurable success metrics, and data-informed decision-making. Projects begin with a lightweight One-pager that confirms business need and success criteria before committing resources, ensuring alignment between stakeholders and the delivery team before moving into detailed planning.

**Roles, Communication, and Governance:** OctoAcme operates with clearly defined personas: **Product Managers** (who define what to build and prioritize the backlog), **Project Managers** (who coordinate delivery, manage risk, and ensure stakeholder alignment), **Developers** (who implement features and maintain quality), and **QA/Testing** (who validate acceptance criteria). Communication follows a disciplined cadence—daily standups focus on progress and blockers, weekly syncs between PM and Product Lead drive coordination, and monthly stakeholder updates maintain visibility. The team uses a project board workflow with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done) and requires pull requests to be small (≤400 lines), linked to issues, and approved before merge. Risk management is embedded throughout: a Risk Register tracks issues by impact, likelihood, and mitigation, with escalation paths from team-level triage → PM → Product Lead → Sponsor for business-critical blockers.

**Quality, Release, and Continuous Improvement:** Quality assurance is baked into execution through unit tests for new logic, integration tests where applicable, and end-to-end smoke tests before release. Releases are standardized using semantic versioning (Patch, Minor, Major) with pre-release checklists that ensure CI/security scans pass, smoke tests run on staging, and rollback plans are documented. Post-release, the team conducts retrospectives after each sprint or milestone to capture what went well, what could improve, and convert findings into tracked action items. This continuous improvement cycle—combined with weekly risk monitoring, velocity tracking, and success metrics dashboards—enables OctoAcme teams to deliver iteratively while maintaining transparency, predictability, and psychological safety across the organization.

## Process Documents

- [Project Management Overview](octoacme-project-management-overview.md) — Concise introduction to how OctoAcme runs projects, roles, key artifacts, and lifecycle overview.
- [Project Initiation Guide](octoacme-project-initiation.md) — Initial steps to validate and authorize work, align stakeholders, and create a lightweight plan.
- [Project Planning](octoacme-project-planning.md) — Turn an approved initiative into an actionable plan and backlog for delivery.
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Guidance for managing day-to-day execution and tracking progress toward project milestones.
- [Risk Management & Communication](octoacme-risks-and-communication.md) — How to identify, manage, and communicate risks and dependencies.
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — Standardize how OctoAcme releases features to production to reduce risk and improve observability.
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and convert them into actionable improvements.
- [Roles & Personas](octoacme-roles-and-personas.md) — Define typical roles and responsibilities used in OctoAcme project docs and exercises.

## Getting Started

- **New to OctoAcme?** Start with [Project Management Overview](octoacme-project-management-overview.md) to understand our principles and core roles.
- **Starting a new project?** Follow the [Project Initiation Guide](octoacme-project-initiation.md) and [Project Planning](octoacme-project-planning.md) documents in sequence.
- **Managing day-to-day work?** Reference [Execution & Tracking](octoacme-execution-and-tracking.md) and [Risk Management & Communication](octoacme-risks-and-communication.md).
- **Preparing a release?** See [Release & Deployment Guide](octoacme-release-and-deployment.md).
- **Wrapping up a project or sprint?** Use [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) to capture learnings.

## Keeping Docs Up-to-Date

These documents evolve as our processes improve. To propose updates or add new content:
- Use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template.
- Submit a PR with changes and tag relevant stakeholders for review.
- Keep this README current as new processes are documented or workflows evolve.
