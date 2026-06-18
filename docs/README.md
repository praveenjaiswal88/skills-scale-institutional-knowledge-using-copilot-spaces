# OctoAcme Project Management Docs

Welcome to OctoAcme's project management process documentation. This folder contains comprehensive guides for how we run cross-functional projects, from initiation through retrospectives and continuous improvement.

## Quick Overview

OctoAcme operates a structured, lifecycle-based project management approach that emphasizes customer value, iterative delivery, and clear ownership. Our methodology follows five distinct phases—**Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**—each with defined artifacts and decision gates.

Projects begin with a lightweight One-pager that validates business need, identifies stakeholders, and confirms success metrics before advancing to detailed planning. This gated approach ensures that only well-aligned initiatives move forward, reducing wasted effort and maintaining strategic focus.

**Key Principles:**
- **Customer-first:** Prioritize customer value and usability
- **Iterative delivery:** Deliver small, testable increments
- **Clear ownership:** Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions:** Measure impact and iterate based on evidence
- **Psychological safety:** Encourage feedback and learning

## Core Roles & Responsibilities

Our projects succeed through well-defined roles and regular communication cadences:

- **Project Manager:** Owns schedules, risks, blockers, and stakeholder communications
- **Product Manager:** Defines outcomes, prioritizes the backlog, and measures success
- **Developers:** Implement features with quality in mind, collaborate on design and testability
- **QA/Testing:** Validate acceptance criteria and quality standards

For detailed role definitions and personas, see [**Roles & Personas**](#roles--personas).

## Key Workflows & Quality Practices

**Execution & Quality Standards:**
- Use GitHub Projects with standardized columns: Backlog → Ready → In Progress → In Review → QA → Done
- Small PRs (≤400 lines when possible) with issue links and acceptance criteria
- Unit tests, integration tests, and end-to-end smoke tests
- Security scanning in CI pipelines
- Require at least one approval before merging

**Risk Management & Communication:**
- Maintain a Risk Register tracking likelihood, impact, and mitigation
- Weekly syncs between PM and Product Manager
- Twice-weekly standups for delivery teams
- Monthly stakeholder updates
- Escalation paths: Team-level → PM → Product Lead → Sponsor

**Release & Deployment:**
- Pre-release checklist (passing CI, security scans, rollback plans)
- Staged deployment to production with post-deploy verification
- Release notes documenting changes and migration steps

**Continuous Improvement:**
- Retrospectives held after each sprint or milestone
- Action items tracked and reviewed in weekly syncs
- Celebrate wins and maintain team morale

## Process Documents

Navigate to the guide that matches your current project phase or role:

| Document | Purpose | Best For |
|----------|---------|----------|
| [**OctoAcme Project Management Overview**](octoacme-project-management-overview.md) | Concise introduction to our approach, roles, and key artifacts | New team members, project setup |
| [**Project Initiation Guide**](octoacme-project-initiation.md) | Initial steps to validate business need and authorize work | Starting a new project or feature proposal |
| [**Project Planning**](octoacme-project-planning.md) | Turn an approved initiative into an actionable backlog and plan | Planning phase, sprint setup |
| [**Execution & Tracking**](octoacme-execution-and-tracking.md) | Manage day-to-day execution and track progress toward milestones | Active delivery, sprint execution |
| [**Risk Management & Communication**](octoacme-risks-and-communication.md) | Identify, manage, and communicate risks and dependencies | Risk tracking, stakeholder updates |
| [**Release & Deployment Guide**](octoacme-release-and-deployment.md) | Standardize releases to production and incident response | Pre-release checklist, deployment |
| [**Retrospective & Continuous Improvement**](octoacme-retrospective-and-continuous-improvement.md) | Capture learnings and convert them into improvements | Sprint close-out, post-incident reviews |
| [**Roles & Personas**](octoacme-roles-and-personas.md) | Detailed definitions of typical roles and responsibilities | Understanding team structure |

## Getting Started

1. **For Project Leads:** Start with [Project Initiation Guide](octoacme-project-initiation.md) and create a One-pager
2. **For Delivery Teams:** Review [Execution & Tracking](octoacme-execution-and-tracking.md) for workflow standards
3. **For New Team Members:** Read [Project Management Overview](octoacme-project-management-overview.md) for context
4. **For Risk or Blocker Escalation:** Consult [Risk Management & Communication](octoacme-risks-and-communication.md)

## Contributing & Updating These Docs

To propose updates or add new content to OctoAcme's process documentation, please open an issue using the **[Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)** template.

---

**Questions or feedback?** Open an issue or reach out to your Product Lead.
