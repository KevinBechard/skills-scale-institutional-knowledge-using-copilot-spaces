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

## QA / Testing

### Role Summary
QA and Testing validate that implemented features meet acceptance criteria and quality standards before release.

### Responsibilities
- Design and run test plans (unit, integration, E2E) for features
- Maintain test environments and test data
- Verify acceptance criteria and file reproducible bugs
- Participate in release verification and smoke tests

### Typical Communication
- Work closely with Developers to reproduce and verify fixes
- Coordinate with Project Manager and Release Manager for test sign-offs

---

## Additional Cross-functional Personas (new)

Below are suggested personas to add to improve clarity of ownership for common delivery activities.

### Release Manager

Role summary: Coordinates and owns the release process to production, including scheduling, verification, and rollback readiness.

Key responsibilities:
- Maintain release checklist, schedule, and cross-team sign-offs
- Coordinate pre-release and post-release verifications (smoke tests)
- Ensure rollback and mitigation plans are in place and tested
- Communicate release windows and impacts to stakeholders and support

Primary interactions:
- Project Manager: aligns release dates with project plan
- Developers / Platform: executes deployment steps
- QA: verifies smoke tests and acceptance in staging
- Support / Customer Success: share release notes and known impacts

Example scenarios:
- Owning the pre-release checklist for a minor/major release
- Coordinating an urgent patch release with Platform and Support

---

### Technical Writer / Documentation Specialist

Role summary: Produces and maintains user-facing documentation, runbooks, and release notes.

Key responsibilities:
- Draft and maintain release notes, user docs, and runbooks
- Update API docs and in-repo process documentation
- Ensure documentation is reviewed before release

Primary interactions:
- Product Manager: feature descriptions and acceptance criteria
- Developers: technical accuracy and examples
- Release Manager: final release notes and rollout guidance

---

### UX Researcher / Designer Liaison

Role summary: Validates user assumptions and provides design artifacts to inform acceptance criteria.

Key responsibilities:
- Run user research and usability tests
- Produce design mockups, flows, and acceptance criteria for UX
- Provide UX-related success criteria and measurement suggestions

Primary interactions:
- Product Manager: user needs and prioritization
- Developers: implementation feasibility and handoff
- QA: usability acceptance tests and criteria

---

### Data Analyst / Measurement Lead

Role summary: Defines measurement approach, instruments events, and produces dashboards to evaluate success metrics.

Key responsibilities:
- Define and maintain success metrics and dashboards
- Coordinate event instrumentation and validate telemetry
- Provide analysis and interpretation after releases

Primary interactions:
- Product Manager: define success metrics and KPIs
- Developers: implement instrumentation
- PM/Stakeholders: post-release impact analysis

---

### Security Liaison / Security Engineer

Role summary: Ensures security reviews are completed and that remediation and checks are in place.

Key responsibilities:
- Conduct security reviews for design and release
- Run/validate automated security scans and remediate findings
- Provide guidance on compliance and threat models

Primary interactions:
- Developers: remediation and guidance
- CI/Platform owners: scan integration
- PM: timeline impacts when security issues arise

---

### Support / Customer Success Liaison

Role summary: Bridges customer-facing teams and engineering to surface issues and coordinate communications.

Key responsibilities:
- Surface recurring customer issues and impact
- Prepare support guidance and triage steps for known issues
- Coordinate external communications for significant changes or incidents

Primary interactions:
- Product Manager: prioritization and impact
- Release Manager: release impact communication
- QA: provide steps to reproduce customer issues

---

### Platform / DevOps Engineer

Role summary: Maintains deployment pipelines, infra reliability, and observability.

Key responsibilities:
- Maintain CI/CD pipelines and deployment automation
- Ensure platform reliability, monitoring, and rollback tooling
- Support performance and capacity planning

Primary interactions:
- Developers: deployment support
- Release Manager: coordinate runs and rollbacks
- PM: surface platform-level constraints and outages

---

## How these personas are used in the exercise

- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
