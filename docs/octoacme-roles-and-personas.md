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
QA ensures delivered work meets acceptance criteria and quality expectations.

### Responsibilities
- Validate acceptance criteria and run test plans
- Execute manual exploratory and acceptance testing when needed
- Maintain or drive automated test coverage and test pipelines
- Triage and verify fixes

### Typical Communication
- Test results in PRs and CI
- Coordination with Developers and Project Managers for release readiness

---

## New / Additional Personas (proposed additions)

### UX Designer
- Role Summary: Designs user flows, prototypes, and user interfaces in close collaboration with Product Managers and Developers.
- Responsibilities:
  - Conduct user research, usability testing, and synthesize findings
  - Produce wireframes, mockups, and interactive prototypes
  - Define and communicate UI/UX acceptance criteria
  - Participate in design reviews and integrate stakeholder feedback
  - Support implementation with clear specs and assets; validate UI during QA
- Interactions:
  - Syncs with Product Managers to define user goals and success metrics
  - Works with Developers on implementation details and QA to verify UX acceptance
  - Contributes to demo/release notes for user-facing changes

### DevOps Engineer
- Role Summary: Builds and maintains the deployment pipeline, automation, and observability tools to enhance stability and delivery velocity.
- Responsibilities:
  - Maintain and improve CI/CD pipelines and infrastructure-as-code
  - Manage staging/production environments and runbooks
  - Implement monitoring, alerts, and security scanning
  - Support release automation, rollbacks, and incident mitigation
- Interactions:
  - Coordinates with Developers and QA for release cutover and staging verification
  - Works with Project Managers to schedule deployments that have operational impact
  - Notifies Product/Project leads of operational risks and system health

### Technical Writer / Documentation Specialist
- Role Summary: Ensures project and product documentation is clear, discoverable, and kept up-to-date.
- Responsibilities:
  - Create and maintain process docs, user guides, release notes, and onboarding material
  - Ensure documentation templates and content standards are followed
  - Gather feedback from teams and customers to improve docs
  - Help translate technical decisions into accessible content for stakeholders
- Interactions:
  - Works with Product Managers for user-facing docs and acceptance criteria summaries
  - Syncs with Developers and QA to ensure technical accuracy
  - Partners with Project Managers to keep project READMEs, risk registers, and status notes current

---

## How to use these persona definitions
- Use these persona definitions to frame scenarios, assignment of ownership on backlog items, and to guide handoffs.
- Add named owners for role-specific responsibilities (e.g., staging owner, design owner) in the project one-pager and backlog items to increase accountability.
