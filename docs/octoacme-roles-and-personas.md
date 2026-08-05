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

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Additional suggested personas (new)
Below are recommended additions to the personas document. Each entry includes responsibilities and how they interact with existing roles. Add these as separate sections under "Additional suggested personas" (or integrate into the main persona list as appropriate).

### Release Coordinator
- Responsibilities:
  - Plan and coordinate releases for minor/major/patch release types.
  - Maintain and enforce the release checklist and timeline.
  - Schedule deployment windows and coordinate rollback plans.
  - Draft and publish release notes; communicate release status to stakeholders.
- Interactions:
  - Works with PM and PdM to align scope and release timing.
  - Coordinates Developers, QA, SRE, and Support during deployment.
  - Notifies Stakeholders and Customer Support about release impacts.

### Security Champion
- Responsibilities:
  - Identify security risks in backlog items and features.
  - Perform threat modeling for relevant features and capture mitigations.
  - Ensure security scans (SAST/DAST/dependency) are addressed and tracked.
  - Coordinate with the central Security team for escalations and compliance reviews.
- Interactions:
  - Embedded with Developers and PM for early-stage design/scope discussions.
  - Helps PdM add security acceptance criteria to backlog items.
  - Escalates critical findings to Security on-call and PM.

### Observability Owner
- Responsibilities:
  - Define monitoring, metrics, and alerting expectations for delivered features.
  - Ensure logs/traces/metrics are instrumented and dashboards are in place.
  - Validate SLOs/SLIs for features and own observability-related acceptance checks.
- Interactions:
  - Works with Developers and SRE to implement instrumentation.
  - Collaborates with QA on observability-driven tests.
  - Informs PM and Stakeholders about operational readiness.

### Business Analyst (BA)
- Responsibilities:
  - Translate stakeholder needs into clear, testable requirements.
  - Define and maintain acceptance criteria and user scenarios.
  - Support backlog grooming and clarify scope for engineering.
- Interactions:
  - Works closely with PdM and PM to prioritize and refine requirements.
  - Clarifies requirements for Developers and QA.
  - Helps prioritize non-functional and reporting requirements.

### UX Researcher / Designer
- Responsibilities:
  - Conduct user research and usability testing.
  - Define user journeys, wireframes, and design artifacts.
  - Validate designs with users and translate findings into acceptance criteria.
- Interactions:
  - Partners with PdM on product decisions and trade-offs.
  - Hands off designs to Developers and supports QA on usability checks.
  - Provides assets and guidance for documentation and release announcements.

### Site Reliability Engineer (SRE)
- Responsibilities:
  - Define operational requirements and capacity planning.
  - Create and maintain runbooks for operational incidents.
  - Participate in post-incident reviews and reliability improvements.
- Interactions:
  - Collaborates with Developers on architecture and operational changes.
  - Alerts PM on operational risks affecting delivery.
  - Works with Observability Owner to set SLOs and alerting.

### Data Analyst
- Responsibilities:
  - Define measurement plans and instrument analytics/events.
  - Analyze outcomes against success metrics and provide recommendations.
  - Support A/B testing and rollout analysis.
- Interactions:
  - Works with PdM to define success metrics.
  - Provides data for retrospectives and product decisions.
  - Assists in monitoring post-release outcomes.

### Release/Feature Owner (for large initiatives)
- Responsibilities:
  - Own end-to-end delivery for a large feature or cross-team program.
  - Track cross-team dependencies, timelines, and milestones.
  - Coordinate communication and issue resolution across teams.
- Interactions:
  - Acts as single point of contact to PM, PdM, Engineering Managers, and Stakeholders.
  - Coordinates with Release Coordinator and Project Manager to ensure on-time delivery.

### Legal / Compliance Liaison
- Responsibilities:
  - Identify regulatory and compliance constraints relevant to the project.
  - Review deliverables for legal risk and required contractual language.
  - Coordinate required sign-offs and documentation for compliance.
- Interactions:
  - Engages early with PM and PdM during planning.
  - Escalates blockers to Sponsor or Product Lead where needed.

---

## Guidance for adding new personas
- For each new persona, include:
  - Role summary
  - Responsibilities
  - Who they interact with and when
  - Example deliverables or artifacts they own
- Link persona sections from the Project One-pager and the Project README so role expectations are visible to contributors.
