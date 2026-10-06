# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation. This folder contains comprehensive guides and best practices for running projects at OctoAcme, from initiation through retrospectives and continuous improvement.

## Overview of OctoAcme's Project Management Approach

OctoAcme operates a structured yet flexible project management framework built on five core principles: **customer-first delivery**, **iterative increments**, **clear ownership**, **data-informed decisions**, and **psychological safety**. 

The organization employs a customer-centric approach where the **Project Manager (PM)** coordinates delivery, timelines, and communications, while the **Product Manager (PdM)** defines desired outcomes and prioritizes the backlog. Developers implement features with quality ownership, QA/Testing validates acceptance criteria, and Stakeholders provide governance and approvals.

Communication at OctoAcme follows a disciplined cadence: weekly syncs between PM and PdM, twice-weekly standups with the delivery team, and monthly stakeholder updates. All project documentation is maintained in a central repository, with critical processes optionally added to `.copilot/` folders for Copilot Spaces context. The organization uses project boards with standardized workflows and Pull Requests follow strict conventions to ensure code quality.

Risk management and escalation are proactive throughout OctoAcme's processes. A centralized Risk Register tracks risks with weekly review cycles, escalation follows a clear hierarchy (team → PM → Product Lead → Sponsor), and a blameless retrospective culture holds after each sprint, release, or incident to capture learnings and drive continuous improvement.

Quality assurance is comprehensive and distributed: unit tests and integration tests accompany feature development, end-to-end smoke tests validate critical flows before release, security scanning runs in CI, and success metrics are tracked alongside retrospective action items. This combination ensures OctoAcme delivers reliable software while maintaining team cohesion and continuous improvement.

---

## Project Management Process Documents

### 1. [Project Initiation Guide](./octoacme-project-initiation.md)
Defines the initial steps to validate and authorize work, align stakeholders, and create a lightweight plan. Use this guide when a new project idea or feature proposal is ready to be explored. Covers problem statements, success metrics, stakeholder identification, and the go/no-go decision gate for moving into planning.

### 2. [Project Planning](./octoacme-project-planning.md)
Turns an approved initiative into an actionable plan and backlog for delivery. Includes guidance on breaking work into shippable increments, identifying dependencies and risks, creating prioritized backlogs with acceptance criteria, defining Definition of Done, and creating release plans and milestone maps.

### 3. [Execution & Tracking](./octoacme-execution-and-tracking.md)
Provides guidance for managing day-to-day execution and tracking progress toward project milestones. Covers team rhythm (standups, syncs, demos), workflow practices (project boards, PR conventions), quality and testing approaches, reporting metrics, and blocker escalation procedures.

### 4. [Risk Management & Communication](./octoacme-risks-and-communication.md)
Explains how to identify, manage, and communicate risks and dependencies. Details the Risk Register structure and lifecycle, stakeholder communication strategies, weekly status templates, incident communication procedures, and escalation paths to ensure transparency and quick resolution.

### 5. [Release & Deployment Guide](./octoacme-release-and-deployment.md)
Standardizes how OctoAcme releases features to production to reduce risk and improve observability. Covers release types (patch, minor, major), pre-release requirements, deployment checklists, rollback and incident playbooks, and release notes templates.

### 6. [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
Captures learnings and converts them into actionable improvements. Held after each sprint, release, or important milestone, this guide provides structure for retrospectives, action item tracking, and a continuous improvement culture that celebrates progress and drives iterative evolution.

### 7. [Roles and Personas](./octoacme-roles-and-personas.md)
Defines typical roles and responsibilities used in OctoAcme project docs and exercises. Describes Developers, Product Managers, and Project Managers—their role summaries, responsibilities, goals, and typical communication patterns—providing clarity on expectations and collaboration across the organization.

### 8. [Project Management Overview](./octoacme-project-management-overview.md)
Provides a concise, shareable introduction to how OctoAcme runs projects. Covers core principles, roles, key artifacts, the five-phase lifecycle, communication cadence, and how to use these documents in practice, serving as a quick reference for new team members.

---

## Quick Start

- **New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md) for a high-level introduction.
- **Launching a new project?** Follow the [Project Initiation Guide](./octoacme-project-initiation.md).
- **Planning your first sprint?** Use the [Project Planning](./octoacme-project-planning.md) guide.
- **Need to understand roles?** Review the [Roles and Personas](./octoacme-roles-and-personas.md) document.
- **Managing risks or communicating updates?** Consult [Risk Management & Communication](./octoacme-risks-and-communication.md).
- **Deploying to production?** Follow the [Release & Deployment Guide](./octoacme-release-and-deployment.md).
- **Closing out a project?** Hold a retrospective using [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md).

---

## Using These Docs with Copilot Spaces

To use these process documents as context in Copilot Spaces, add relevant files to your project's `.copilot/` directory. This enables Copilot to provide role-specific guidance and process-aligned recommendations for your team.

For questions or updates to these processes, please reach out to your Project Manager or Product Lead.
