# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## QA / Testers

### Role Summary
QA Testers ensure product quality and compliance with acceptance criteria through comprehensive test planning, execution, and documentation. They collaborate closely with Developers and Product Managers to validate stories, catch defects early, and reduce release risk.

### Responsibilities
- Develop and maintain test plans and test cases aligned with acceptance criteria
- Execute functional, integration, and regression testing
- Document test results and defects with clarity and reproducibility
- Collaborate with developers on bug reproduction and validation
- Participate in sprint planning to understand testability requirements
- Conduct release sign-off and smoke testing
- Identify and report quality risks and test coverage gaps

### Goals
- Ensure consistent, high-quality releases
- Catch defects early in the development cycle
- Build confidence in feature acceptance and readiness
- Improve test automation and reduce manual testing burden

### Typical Communication
- Sprint planning and backlog refinement sessions
- Test case reviews with product and development teams
- Defect reports with detailed reproduction steps
- Quality metrics and risk assessments in weekly syncs
- Release readiness reports and sign-off

### Interaction with Other Roles
- **Developers**: Collaborate on bug fixes, test case clarification, and automation strategy
- **Product Managers**: Validate acceptance criteria and feature requirements
- **Project Managers**: Report quality metrics and escalate blockers
- **UX Designers**: Review user workflows for testability and usability concerns

---

## UX / Product Designers

### Role Summary
UX Designers own the user experience and translate product requirements into intuitive, user-centric solutions. They create wireframes, user flows, and design systems while supporting usability testing and design reviews.

### Responsibilities
- Conduct user research and translate findings into design requirements
- Create wireframes, prototypes, and user flow documentation
- Develop and maintain design systems and component libraries
- Collaborate with Product Managers to align design with product strategy
- Facilitate design reviews with stakeholders and developers
- Support usability testing and iterate based on user feedback
- Document design specifications and rationale for development handoff

### Goals
- Maximize user adoption and satisfaction through intuitive design
- Reduce friction in user workflows and decision-making
- Ensure consistent, accessible user experiences across features
- Enable developers to implement features efficiently with clear design specs

### Typical Communication
- Design reviews during backlog grooming and sprint planning
- Design documentation and component specs in design systems
- Usability testing reports and user feedback synthesis
- Weekly alignment with Product Managers on design strategy
- Collaboration on accessibility and performance considerations

### Interaction with Other Roles
- **Product Managers**: Align on user needs and product roadmap
- **Developers**: Provide design specifications and support implementation questions
- **QA Testers**: Validate user experience acceptance criteria and usability
- **Project Managers**: Communicate design timelines and design-related risks

---

## Business Analysts

### Role Summary
Business Analysts bridge the gap between business stakeholders and the technical team. They clarify requirements, document process flows, and ensure alignment on scope and success criteria throughout the project lifecycle.

### Responsibilities
- Gather and document business requirements from stakeholders
- Analyze current processes and identify improvement opportunities
- Create process flow diagrams and requirement specifications
- Support Product Managers in defining acceptance criteria
- Identify and document dependencies and integration points
- Validate that solutions align with business objectives
- Support change management and stakeholder communication

### Goals
- Ensure clear understanding of business needs across all team members
- Reduce scope ambiguity and rework due to misaligned requirements
- Enable informed trade-off decisions between technical and business constraints
- Improve time-to-value by optimizing processes

### Typical Communication
- Requirement gathering sessions and stakeholder interviews
- Process documentation and flow diagrams
- Acceptance criteria and scope definition documents
- Risk and dependency identification in planning meetings
- Change impact analysis and stakeholder communications

### Interaction with Other Roles
- **Product Managers**: Collaborate on requirements definition and prioritization
- **Project Managers**: Support timeline planning and dependency identification
- **Developers**: Clarify technical feasibility and scope questions
- **Stakeholders**: Communicate requirements and gather business needs

---

## Support Engineers

### Role Summary
Support Engineers serve as the primary contact for operational and user-facing issues in production. They gather user feedback, triage incidents, and facilitate communication between customers and the development team to resolve issues quickly and improve product reliability.

### Responsibilities
- Triage and escalate critical production incidents
- Gather detailed user feedback and support tickets
- Identify patterns in user issues and feature requests
- Collaborate with developers on bug fixes and workarounds
- Maintain support documentation and runbooks
- Communicate status and resolution timelines to users
- Participate in retrospectives for high-impact incidents

### Goals
- Minimize customer impact and incident resolution time
- Gather user insights to inform product improvements
- Reduce repeat issues through documentation and knowledge sharing
- Build customer trust through transparent, timely communication

### Typical Communication
- Incident alerts and escalation to development team
- Post-incident retrospectives and root cause analysis
- Support ticket summaries and recurring issue reports
- User feedback synthesis for product team
- Runbook and knowledge base documentation

### Interaction with Other Roles
- **Developers**: Collaborate on hotfix prioritization and root cause analysis
- **Product Managers**: Report user feedback and improvement opportunities
- **QA Testers**: Validate fixes and regression test critical paths
- **Project Managers**: Escalate business-impacting issues

---

## Release Managers

### Role Summary
Release Managers plan, coordinate, and execute production releases to ensure smooth, low-risk deployments. They communicate release status to stakeholders and manage rollback procedures when needed.

### Responsibilities
- Create and maintain release plans and deployment schedules
- Coordinate with development, QA, and operations teams on release readiness
- Verify all prerequisites are met before deployment (tests, security scans, documentation)
- Communicate release status, timelines, and risks to stakeholders
- Execute deployment procedures and monitor for issues
- Coordinate rollback procedures if critical issues arise
- Document lessons learned and drive continuous improvement in release processes

### Goals
- Deliver releases on schedule with zero or minimal production impact
- Reduce deployment risk through clear planning and coordination
- Ensure transparent communication with all stakeholders
- Minimize mean time to recovery (MTTR) for production incidents

### Typical Communication
- Release readiness checklists and sign-off gates
- Deployment schedules and stakeholder notifications
- Release notes and deployment instructions
- Incident response coordination during and post-deployment
- Post-release retrospectives and process improvements

### Interaction with Other Roles
- **Developers**: Coordinate code freeze, version tagging, and hotfix procedures
- **QA Testers**: Verify release readiness and smoke test results
- **Product Managers**: Communicate release content and timelines
- **Project Managers**: Track release dependencies and milestone progress
- **Support Engineers**: Brief on new features and potential support implications

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to interaction points to understand cross-functional collaboration and handoff patterns.
