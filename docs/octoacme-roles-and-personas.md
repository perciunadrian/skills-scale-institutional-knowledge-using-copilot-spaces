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

### Interactions with Other Roles
- Work with Product Managers to clarify requirements and trade-offs.
- Coordinate with Project Managers on estimates, dependencies, and delivery risks.
- Partner with QA/Testing on testability and acceptance evidence.

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

### Interactions with Other Roles
- Align with Project Managers on scope, priority, timing, and dependencies.
- Work with Developers and UX/Design Leads on feasible, usable solutions.
- Use Data Analysts and customer/support feedback to validate outcomes.

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

### Interactions with Other Roles
- Coordinate priorities and trade-offs with Product Managers.
- Work with Delivery Facilitators to remove team-level impediments.
- Align Developers, QA, Release Managers, and Support on plans and readiness.

---

## Delivery Facilitator / Scrum Master

### Role Summary
The Delivery Facilitator helps the team improve flow, remove impediments, and maintain healthy delivery practices. This role complements, rather than replaces, the Project Manager.

### Responsibilities
- Facilitate planning, standups, reviews, and retrospectives
- Identify systemic blockers and drive them to resolution
- Coach the team on backlog refinement and delivery practices
- Monitor flow signals and escalation needs

### Goals
- Improve delivery predictability and team effectiveness
- Reduce avoidable delays and process waste
- Strengthen psychological safety and continuous improvement

### Typical Communication
- Daily standups and sprint ceremonies
- Impediment logs and team improvement actions
- Flow reviews with the Project Manager

### Interactions with Other Roles
- Partners with Project Managers on impediment removal and team-level coordination.
- Works with Developers and QA/Testing to improve flow and definition-of-ready/done practices.
- Escalates cross-team blockers to Product Managers and stakeholders when needed.

---

## Release Manager

### Role Summary
The Release Manager coordinates release readiness, deployment, verification, and rollback planning across involved teams.

### Responsibilities
- Maintain release plans, criteria, and communication schedules
- Coordinate deployment windows and change approvals
- Confirm CI, security checks, smoke tests, and rollback plans
- Facilitate release announcements and post-deployment verification

### Goals
- Deliver releases safely and predictably
- Reduce failed deployments and recovery time
- Provide clear release accountability

### Typical Communication
- Release readiness reviews
- Deployment checklists and release notes
- Post-deployment status updates

### Interactions with Other Roles
- Coordinates Product Managers, Developers, QA/Testing, Security, Operations/SRE, and Support.
- Works with Project Managers on release milestones and stakeholder communications.
- Escalates readiness or rollback risks to Sponsors or incident leadership as appropriate.

---

## Security Lead

### Role Summary
The Security Lead provides security expertise and ensures security, privacy, and compliance considerations are addressed throughout delivery.

### Responsibilities
- Define applicable security and compliance requirements
- Review threat models and security-sensitive designs
- Coordinate security scans, assessments, and remediation
- Lead or support security incident escalation

### Goals
- Reduce security and compliance risk
- Make security risks visible and actionable
- Improve secure engineering practices

### Typical Communication
- Security reviews and risk assessments
- Vulnerability and remediation updates
- Security incident coordination

### Interactions with Other Roles
- Advises Product Managers and Developers on requirements, threats, and trade-offs.
- Works with QA/Testing on security validation and with Operations/SRE on incident response.
- Reports material risks to Project Managers and stakeholders and follows the security escalation runbook.

---

## DevOps / Site Reliability Engineer

### Role Summary
DevOps and Site Reliability Engineers improve delivery automation, deployment safety, reliability, and operational observability.

### Responsibilities
- Build and maintain CI/CD pipelines and deployment automation
- Define and monitor reliability indicators
- Improve observability, alerting, capacity, and recovery capabilities
- Participate in incident response and operational readiness

### Goals
- Increase deployment frequency and reduce failure rates
- Improve service availability and recovery time
- Make operational risks measurable and manageable

### Typical Communication
- Reliability and capacity reviews
- CI/CD and operational dashboards
- Incident updates and post-incident actions

### Interactions with Other Roles
- Partner with Developers on testability, deployment, and observability.
- Coordinate with Release Managers on rollout and rollback capabilities.
- Provide operational evidence to Product Managers and Project Managers and support QA/Testing in pre-release validation.

---

## UX / Design Lead

### Role Summary
The UX/Design Lead represents customer and usability needs throughout discovery and delivery.

### Responsibilities
- Research user needs and clarify usability requirements
- Create and test user flows, prototypes, and design specifications
- Establish interaction and accessibility patterns
- Review delivered work for design and usability quality

### Goals
- Improve usability, accessibility, and customer satisfaction
- Reduce costly rework from unclear or untested designs
- Create consistent customer experiences

### Typical Communication
- Discovery workshops and design reviews
- Prototypes and design specifications
- Usability test reports

### Interactions with Other Roles
- Collaborates with Product Managers on problem framing and success criteria.
- Works with Developers to make designs feasible and with QA/Testing to define usability acceptance checks.
- Shares customer insights with Project Managers and stakeholders.

---

## Data Analyst

### Role Summary
The Data Analyst helps teams define, collect, interpret, and communicate evidence used to measure outcomes.

### Responsibilities
- Refine success metrics and reporting requirements
- Define measurement approaches and validate data quality
- Analyze experiments, adoption, and performance
- Communicate findings and recommendations

### Goals
- Improve decision quality through reliable evidence
- Make project outcomes measurable
- Surface risks and opportunities early

### Typical Communication
- Metric definitions and dashboards
- Experiment and adoption analysis
- Findings shared in stakeholder updates and retrospectives

### Interactions with Other Roles
- Works with Product Managers to translate outcomes into metrics and acceptance signals.
- Provides delivery and outcome evidence to Project Managers and stakeholders.
- Helps Developers and Operations/SRE instrument required data and alerts.

---

## Customer Success / Support Representative

### Role Summary
The Customer Success or Support Representative represents customer needs and operational support readiness.

### Responsibilities
- Communicate customer feedback and recurring pain points
- Identify support impacts and training needs
- Prepare support teams for releases and incidents
- Coordinate issue intake and customer communications

### Goals
- Improve customer outcomes and satisfaction
- Reduce support disruption during releases
- Ensure feedback reaches delivery and product decisions

### Typical Communication
- Customer feedback summaries and support trend reports
- Release readiness and support handoff meetings
- Incident and stakeholder communications

### Interactions with Other Roles
- Provides feedback to Product Managers and UX/Design Leads for prioritization and discovery.
- Works with Release Managers and Technical Writers on release notes and support readiness.
- Shares support impacts with Project Managers and stakeholders and coordinates incident updates with Operations/SRE.

---

## Technical Writer

### Role Summary
The Technical Writer creates accurate, accessible documentation for users and delivery teams.

### Responsibilities
- Maintain user, operational, and release documentation
- Draft migration instructions and known-issue communications
- Coordinate documentation review and publication
- Align documentation with acceptance and release readiness

### Goals
- Improve documentation accuracy and discoverability
- Reduce support effort and implementation risk
- Keep documentation synchronized with delivered behavior

### Typical Communication
- Documentation plans and review requests
- Release notes and migration guides
- Documentation issues and publishing updates

### Interactions with Other Roles
- Works with Product Managers and UX/Design Leads on customer-facing information.
- Partners with Developers and QA/Testing to validate technical accuracy and acceptance coverage.
- Coordinates with Release Managers and Support for launch materials, known issues, and migration guidance.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Teams should assign only the personas relevant to a project and define a named owner or shared accountability for every material delivery activity.
