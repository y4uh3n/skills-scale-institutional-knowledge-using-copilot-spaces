# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation! This repository contains comprehensive guidance for running projects using the OctoAcme approach.

## What is OctoAcme?

OctoAcme is a lightweight, iterative project management framework designed for cross-functional teams delivering product features, services, and integrations. Our approach prioritizes customer value, clear ownership, psychological safety, and data-driven decision-making.

## Project Lifecycle

1. **Initiation** - Validate business need, align stakeholders, define success criteria
2. **Planning** - Break work into increments, identify risks, create release timeline
3. **Execution** - Build, test, review, and iterate with daily standups and weekly syncs
4. **Release** - Deploy to production with comprehensive verification and communication
5. **Close & Retrospective** - Capture learnings and drive continuous improvement

## Documentation

### Core Guides
- [Project Management Overview](./octoacme-project-management-overview.md) - Start here for principles, roles, and high-level lifecycle
- [Roles & Personas](./octoacme-roles-and-personas.md) - Understand key roles and responsibilities

### By Project Phase
- [Project Initiation Guide](./octoacme-project-initiation.md) - How to start a new project
- [Project Planning](./octoacme-project-planning.md) - Creating actionable plans and backlogs
- [Execution & Tracking](./octoacme-execution-and-tracking.md) - Day-to-day delivery and progress tracking
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) - Standardized release process
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) - Capturing learnings

### Cross-functional Topics
- [Risk Management & Communication](./octoacme-risks-and-communication.md) - Risk registers, escalation paths, and stakeholder updates

## OctoAcme Project Management Processes Summary

OctoAcme provides structured guidance across six key project phases:

### Initiation & Planning
Teams validate business needs, identify stakeholders, and define success metrics in a Project One-pager. Planning breaks work into shippable increments with clear acceptance criteria, estimates, dependencies, and a release timeline.

### Execution & Delivery
Day-to-day work follows established team rhythms: daily standups (15 min), weekly delivery syncs, and end-of-sprint demos. Teams use project boards with standard columns (Backlog, Ready, In Progress, In Review, QA, Done) and enforce small pull requests (≤400 lines) with automated CI/CD checks.

### Quality & Testing
Quality is built into every step with unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, and security scanning in CI. Manual QA validates feature acceptance when needed.

### Risk Management & Communication
Teams maintain a risk register tracking ID, description, impact, likelihood, owner, and mitigation plan. Risks are reviewed weekly, escalated through clear paths (Team → PM → Product Lead → Sponsor), and communicated transparently to stakeholders.

### Release & Deployment
Releases follow a standardized process ensuring all acceptance criteria are met, CI/CD passes, release notes are prepared, and rollback plans are documented. Deployments include smoke tests in staging, post-deploy verification, and stakeholder announcement.

### Retrospectives & Continuous Improvement
After each sprint or release, teams conduct 45–75 minute retrospectives focused on what went well, what could improve, and 2–3 prioritized action items. Action items are tracked and reviewed in weekly PM syncs to drive incremental improvements.

## Key Principles
- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named PM and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## How to Use These Docs
- Use as a reference during project planning and execution
- Adapt templates and checklists to your team's needs
- Keep project documentation synchronized with these guidelines
- Contribute improvements back to this repository

## Core Roles

- **Project Manager (PM)**: Coordinates delivery, schedules, risks, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, and measures success
- **Developers**: Implement features, collaborate on design and testability
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs and approvals

## Communication Cadence
- Weekly sync between PM + PdM
- Twice-weekly standups for delivery team (or as agreed)
- Monthly stakeholder updates
- Ad-hoc escalations as needed
