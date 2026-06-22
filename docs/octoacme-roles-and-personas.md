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

## Additional Personas (new)
Below are additional specialized personas commonly involved in cross-functional projects. Each entry includes responsibilities and key interactions with existing roles.

- Release Manager
  - Responsibilities: Coordinate release windows, manage deployment checklists, validate rollback plans, and own release communications.
  - Interactions: Works with Project Manager for scheduling, Developers and QA for readiness, Observability/SRE for monitoring, and Support for post-release follow-up.

- Technical Program Manager (TPM)
  - Responsibilities: Drive cross-team technical dependencies, manage program-level timelines, and facilitate engineering coordination.
  - Interactions: Works with Product Manager and Project Manager for prioritization and timelines; coordinates with Solution Architect and leads across engineering teams.

- Solution Architect
  - Responsibilities: Define system-level architecture, review designs for scalability, reliability, and maintainability; surface technical trade-offs and constraints.
  - Interactions: Collaborates with Developers, TPM, and Product Manager to align architecture with product goals and non-functional requirements.

- UX Researcher / Designer
  - Responsibilities: Lead user research, define UX acceptance criteria, produce design assets and interaction specs; validate usability.
  - Interactions: Partners with Product Manager on requirements, Developers on implementation, and QA on UX acceptance tests.

- Security Engineer
  - Responsibilities: Perform threat modeling, security reviews, and ensure compliance with security standards and scans; advise on mitigations.
  - Interactions: Works with Developers and CI owners for secure builds, and with Project Manager for risk communication and escalation.

- Data Analyst / Data Engineer
  - Responsibilities: Define measurement plans, implement instrumentation, produce dashboards/reports, and validate success metrics.
  - Interactions: Collaborates with Product Manager on metrics, Developers on instrumentation, and Project Manager for reporting cadence.

- Observability Engineer / SRE
  - Responsibilities: Define monitoring and alerting, create runbooks, support post-deploy verification, and participate in incident response.
  - Interactions: Works with Developers, Release Manager, and Support to ensure operational readiness and fast recovery.

- Support Lead / Customer Success Representative
  - Responsibilities: Capture customer issues, provide triage context, maintain knowledge base, and surface recurring problems.
  - Interactions: Communicates with Product Manager and Project Manager for prioritization and with Developers/QA for reproducible bug fixes.

- Business Analyst
  - Responsibilities: Translate stakeholder requirements into clear acceptance criteria, maintain business-rule documentation, and validate compliance to business needs.
  - Interactions: Works closely with Product Manager and Project Manager to ensure alignment between business needs and delivered functionality.

How this improves outcomes:
- Clarifies ownership for cross-cutting concerns (security, releases, observability, UX, data).
- Reduces ambiguity in handoffs, speeding resolution and decreasing rework.
- Improves risk identification and escalation paths by assigning clear owners.
- Ensures success metrics and instrumentation are owned and measurable.

Suggested placement: Add this "Additional Personas" section to docs/octoacme-roles-and-personas.md (as above). Keep descriptions concise (1–3 bullets each) and include a short line on interactions with existing roles.
