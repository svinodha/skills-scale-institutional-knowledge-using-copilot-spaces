# OctoAcme Project Management Docs

## Overview

This README provides a map of OctoAcme's project/program management processes and links to all process documents in the `docs/` folder. It serves as the entry point for onboarding, reference, and continuous improvement.

---

## Project Management Processes Summary

OctoAcme follows a structured, lifecycle-based approach to project management centered on customer value, iterative delivery, and clear ownership. The organization applies five core principles—customer-first thinking, iterative delivery, clear ownership, data-informed decisions, and psychological safety—across all cross-functional projects. Projects flow through five phases: Initiation (validating business need and stakeholder alignment), Planning (breaking work into shippable increments with clear acceptance criteria), Execution (daily delivery with regular demos and reviews), Release (standardized deployment with rollback plans), and Close & Retrospective (capturing learnings for continuous improvement). Each project is owned by a Project Manager (PM) who coordinates delivery and a Product Manager (PdM) who defines outcomes and measures success, ensuring clear accountability and alignment at every stage.

### Communication & Team Rhythm

The communication cadence and team rhythm form the backbone of execution. OctoAcme maintains multiple touchpoints: daily standups (15 minutes, focused on progress and blockers), weekly syncs between PM and PdM, twice-weekly delivery team standups, and monthly stakeholder updates. Weekly delivery syncs and sprint reviews showcase progress and flag risks, while formal retrospectives (held after sprints, releases, or milestones) capture improvements. Risk management is continuous—teams maintain a risk register tracking ID, description, impact, likelihood, owner, and mitigation plan, with escalation paths flowing from team-level triage to PM to Product Lead to Sponsor. This structured communication ensures transparency and enables rapid issue resolution at the appropriate level.

### Quality & Testing

Quality and testing are embedded throughout the execution workflow rather than treated as afterthoughts. Teams use small pull requests (≤400 lines), automated CI/CD for testing and linting, and require at least one approval before merging. Quality gates include unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows before release, security scanning in CI, and manual QA for feature acceptance when needed. The project board (e.g., GitHub Projects) tracks work through columns—Backlog, Ready, In Progress, In Review, QA, Done—making progress visible and dependencies clear. Pre-release requirements are rigorous: all acceptance criteria must be met, CI and security scans must pass, release notes must be drafted, and rollback/mitigation plans documented. This combination of continuous quality assurance, clear acceptance criteria, and data-driven metrics (velocity, burndown, success metrics from the Project One-pager) ensures OctoAcme delivers reliable, measurable value consistently.

---

## Core Roles

OctoAcme's structured approach relies on clearly defined roles and responsibilities:

- **Project Manager (PM):** Coordinates delivery, manages schedules, risks, and communications
- **Product Manager (PdM):** Defines outcomes, prioritizes backlog, and measures success
- **Developers:** Implement features, collaborate on design and testability
- **QA/Testing:** Validate quality and acceptance criteria
- **Stakeholders:** Provide inputs and approvals

For detailed persona definitions and responsibilities, see [Roles & Personas](./octoacme-roles-and-personas.md).

---

## Process Documentation

The following documents provide detailed guidance for each phase of the project lifecycle:

1. **[Project Management Overview](./octoacme-project-management-overview.md)**
   - Introduction to OctoAcme's approach, principles, and key artifacts
   - High-level lifecycle overview
   - Communication cadence

2. **[Project Initiation Guide](./octoacme-project-initiation.md)**
   - Validating business need and stakeholder alignment
   - Project One-pager template
   - Go/no-go decision criteria

3. **[Project Planning](./octoacme-project-planning.md)**
   - Breaking work into shippable increments
   - Backlog item template and prioritization
   - Definition of Done and risk/dependency management

4. **[Execution & Tracking](./octoacme-execution-and-tracking.md)**
   - Day-to-day delivery and team rhythm
   - Pull Request workflow and quality gates
   - Reporting, metrics, and blocker escalation

5. **[Risk Management & Communication](./octoacme-risks-and-communication.md)**
   - Risk Register template and lifecycle
   - Stakeholder communication strategies
   - Escalation paths and incident communication

6. **[Release & Deployment Guide](./octoacme-release-and-deployment.md)**
   - Release types and pre-release requirements
   - Deployment checklist and verification steps
   - Rollback and incident playbook

7. **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)**
   - Retrospective structure and facilitation
   - Tracking improvements and action items
   - Building a culture of continuous learning

8. **[Roles & Personas](./octoacme-roles-and-personas.md)**
   - Detailed role definitions and responsibilities
   - Communication patterns and goals
   - How personas are used in exercises and scenarios

---

## How to Use These Docs

- **New to OctoAcme?** Start with [Project Management Overview](./octoacme-project-management-overview.md) for the big picture
- **Starting a new project?** Follow the sequence: Initiation → Planning → Execution → Release → Retrospective
- **Need specific guidance?** Use the links above to jump to the relevant phase
- **Keeping Copilot Spaces in sync?** Add process-specific docs to `.copilot/` to ground Copilot in your project context

---

## Continuous Improvement

These documents are living artifacts. If you identify gaps, improvements, or best practices worth capturing, create an issue using the [Process Doc Update template](./.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) to propose changes.
