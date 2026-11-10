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

## UX/Design Leads

### Role Summary
UX/Design Leads shape the user experience and ensure that proposed solutions are usable, accessible, and grounded in user needs.

### Responsibilities
- Plan or conduct user research and synthesize findings
- Create and maintain user flows, interaction designs, and prototypes
- Document usability and accessibility considerations
- Validate designs with users and incorporate feedback

### Collaboration with Existing Roles
- Partner with Product Managers to connect user needs, product outcomes, and acceptance criteria
- Work with Developers and Technical Leads to assess feasibility and resolve implementation questions
- Coordinate with QA/Testing to make usability and accessibility expectations testable
- Align with Project Managers on design milestones, dependencies, and reviews

### Goals
- Deliver clear, inclusive, and consistent user experiences
- Reduce rework by validating assumptions before implementation

### Typical Communication
- Research findings, design reviews, prototypes, and usability feedback

---

## Technical Leads/Architects

### Role Summary
Technical Leads/Architects guide technical direction and help the team make maintainable, secure, and interoperable implementation decisions.

### Responsibilities
- Facilitate architecture and technical design decisions
- Identify integration points, technical dependencies, and constraints
- Promote engineering standards, testability, and maintainability
- Surface technical risks and recommend mitigations

### Collaboration with Existing Roles
- Coordinate with Developers on implementation choices, reviews, and technical trade-offs
- Work with Product Managers to explain technical options and scope implications
- Partner with Project Managers to sequence dependencies and track delivery risks
- Align with QA/Testing and Operations/SRE on testability and operational readiness

### Goals
- Enable a coherent and supportable technical solution
- Make technical decisions and trade-offs visible to the team

### Typical Communication
- Architecture notes, design reviews, dependency discussions, and technical risk updates

---

## Security/Privacy Leads

### Role Summary
Security/Privacy Leads help teams identify and address security, privacy, and applicable compliance requirements throughout delivery.

### Responsibilities
- Identify security and privacy requirements, data-handling constraints, and review needs
- Facilitate threat and privacy risk assessments appropriate to the project
- Recommend safeguards and coordinate remediation of identified gaps
- Document residual risks and required approvals or escalations

### Collaboration with Existing Roles
- Work with Product Managers to clarify user, data, and policy impacts
- Partner with Technical Leads and Developers to incorporate safeguards into designs and implementation
- Coordinate with QA/Testing to validate security and privacy requirements
- Work with Project Managers to record risks, owners, mitigations, and escalation paths

### Goals
- Address security and privacy risks early and transparently
- Ensure required safeguards and reviews are part of delivery planning

### Typical Communication
- Risk assessments, review findings, remediation tracking, and incident escalation

---

## Data/Analytics Leads

### Role Summary
Data/Analytics Leads define how project outcomes will be measured and help ensure that useful, trustworthy data is available for decision-making.

### Responsibilities
- Translate success metrics into measurement and instrumentation requirements
- Define event, data-quality, and reporting expectations
- Validate that measurements support product and operational decisions
- Document metric definitions, assumptions, and limitations

### Collaboration with Existing Roles
- Align with Product Managers on success metrics and interpretation
- Coordinate with Developers on instrumentation and data access
- Work with QA/Testing to verify measurement behavior and data quality
- Partner with Project Managers to report progress and outcomes against agreed metrics

### Goals
- Make project impact measurable and understandable
- Support evidence-based prioritization and continuous improvement

### Typical Communication
- Metric definitions, instrumentation plans, dashboards, and outcome reviews

---

## Operations/SRE Leads

### Role Summary
Operations/SRE Leads help ensure that services and releases are reliable, observable, and ready to operate in production.

### Responsibilities
- Define operational readiness, monitoring, and reliability expectations
- Coordinate deployment, rollback, and service handoff plans
- Identify operational risks and capacity or resilience needs
- Support incident response and communicate operational learnings

### Collaboration with Existing Roles
- Coordinate with Developers and Technical Leads on reliability, deployment, and observability requirements
- Work with QA/Testing to plan release verification and smoke tests
- Align with Project Managers on readiness criteria, release dependencies, and escalations
- Partner with Security/Privacy Leads on operational controls and incident coordination where needed

### Goals
- Reduce avoidable production risk and improve service reliability
- Make ownership and response paths clear after release

### Typical Communication
- Readiness reviews, deployment plans, monitoring dashboards, and incident updates

---

## Customer Support/Enablement Leads

### Role Summary
Customer Support/Enablement Leads prepare customer-facing teams to support a change and bring customer feedback back to the project team.

### Responsibilities
- Prepare support guidance, knowledge-base updates, and enablement materials
- Identify customer communication and training needs
- Share recurring customer questions, issues, and feedback with the project team
- Coordinate support readiness for known issues and launch escalations

### Collaboration with Existing Roles
- Work with Product Managers to understand user impact, feature behavior, and customer messaging
- Coordinate with Project Managers on release timing and stakeholder communications
- Partner with Developers and Operations/SRE to document known issues, troubleshooting steps, and escalation routes
- Share support feedback with QA/Testing to help identify gaps in acceptance or release verification

### Goals
- Enable consistent, timely customer support during and after releases
- Ensure customer feedback informs future product decisions

### Typical Communication
- Support playbooks, FAQs, training sessions, release notes, and customer feedback summaries

---

## Using These Personas
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Assign an accountable owner for each responsibility; on smaller projects, one person may cover multiple personas if ownership and handoffs remain clear.
