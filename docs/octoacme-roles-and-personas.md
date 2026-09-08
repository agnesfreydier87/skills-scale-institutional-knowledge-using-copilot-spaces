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

## Program Managers or Portfolio Leads

### Role Summary
Program Managers or Portfolio Leads coordinate related projects across a portfolio. They align project-level plans with strategic priorities, shared milestones, and cross-team dependencies.

### Responsibilities
- Maintain portfolio-level roadmaps, dependency maps, and delivery health views
- Identify shared risks, sequencing constraints, and resource conflicts across projects
- Facilitate trade-off discussions when portfolio priorities or timelines conflict
- Escalate decisions that exceed a single project's scope, budget, or authority

### Goals
- Keep related initiatives aligned to business and customer outcomes
- Reduce cross-project surprises and duplicated work
- Ensure portfolio-level risks and decisions have clear owners

### Interactions with existing roles
- Partner with Project Managers on milestones, dependency handoffs, status reporting, and escalation paths; Project Managers retain ownership of project execution.
- Work with Product Managers on roadmap trade-offs, sequencing, and outcome measures; Product Managers retain product priority and customer-value decisions.
- Coordinate with Developers through Engineering Leads or Project Managers when portfolio dependencies affect implementation timing or technical sequencing.
- Participate in initiation, planning, release readiness, and retrospective reviews for related projects, especially when decisions affect multiple teams.

---

## Engineering Leads or Technical Leads

### Role Summary
Engineering Leads or Technical Leads guide technical direction for delivery teams. They clarify architecture, implementation approach, technical risks, and engineering readiness.

### Responsibilities
- Define technical approach, architecture decisions, and implementation standards
- Validate estimates, dependencies, and feasibility during planning
- Identify technical risks, quality concerns, and mitigation options
- Coordinate code review expectations, technical handoffs, and release readiness inputs

### Goals
- Ensure solutions are feasible, maintainable, secure, and observable
- Help Developers deliver consistently against acceptance criteria and Definition of Done
- Surface technical blockers early enough for project and product trade-offs

### Interactions with existing roles
- Support Developers with technical guidance and decision-making while Developers retain ownership for implementation and tests.
- Advise Product Managers on feasibility, technical trade-offs, and scope options; Product Managers retain product priority decisions.
- Inform Project Managers of technical risks, dependencies, delivery confidence, and readiness gates; Project Managers retain schedule and coordination ownership.
- Escalate unresolved architecture, quality, security, or operational risks before they affect release commitments.

---

## UX/UI or Product Designers

### Role Summary
UX/UI or Product Designers shape user workflows, interaction design, and usability validation. They help ensure delivered solutions solve customer problems clearly and accessibly.

### Responsibilities
- Conduct or synthesize user research and workflow analysis
- Create design artifacts such as journeys, wireframes, prototypes, and usability findings
- Collaborate on acceptance criteria for user experience and accessibility expectations
- Provide design handoffs and feedback during implementation and validation

### Goals
- Improve usability, accessibility, and customer satisfaction
- Reduce rework by clarifying experience requirements before build
- Validate that released experiences match intended customer outcomes

### Interactions with existing roles
- Partner with Product Managers on customer problems, desired outcomes, and scope boundaries; Product Managers retain prioritization and product decisions.
- Handoff designs, specifications, and usability feedback to Developers, then clarify behavior during implementation without taking ownership of code delivery.
- Keep Project Managers informed about research, design review, and validation timing so those activities are reflected in plans and risks.
- Escalate usability, accessibility, or customer-impact concerns when proposed scope changes would compromise the intended experience.

---

## Technical Writers or Documentation Owners

### Role Summary
Technical Writers or Documentation Owners maintain clear user-facing, operational, and internal documentation. They ensure release notes and readiness content match delivered behavior.

### Responsibilities
- Plan and update documentation for features, workflows, operations, and releases
- Gather source material from product specs, implementation notes, and support feedback
- Validate documentation accuracy before launch and after production changes
- Maintain documentation handoffs for support, operations, and future project teams

### Goals
- Help users and internal teams understand changes and operate them safely
- Reduce support burden caused by unclear or outdated documentation
- Keep documentation aligned with accepted scope and release timing

### Interactions with existing roles
- Work with Product Managers to understand audience, value, positioning, and release messaging; Product Managers retain product narrative and priority decisions.
- Work with Developers to verify technical accuracy, configuration steps, and known limitations; Developers retain implementation ownership.
- Coordinate with Project Managers on documentation milestones, review owners, launch readiness, and escalation when documentation blocks release.
- Participate in planning, release readiness, and retrospectives when documentation quality affects adoption or support outcomes.

---

## Security, Privacy, or Compliance Leads

### Role Summary
Security, Privacy, or Compliance Leads identify governance requirements and delivery risks related to security, privacy, regulatory, and compliance obligations.

### Responsibilities
- Define required controls, reviews, evidence, and approval checkpoints
- Assess security, privacy, and compliance risks during planning and release readiness
- Advise teams on mitigation options, incident preparation, and required remediation
- Maintain escalation paths for security incidents, privacy issues, or compliance blockers

### Goals
- Reduce security, privacy, and compliance risk before release
- Ensure required evidence and approvals are available at decision gates
- Support safe delivery without duplicating product or engineering ownership

### Interactions with existing roles
- Advise Developers and Engineering Leads on controls, secure design, remediation, and verification evidence; Developers retain implementation ownership.
- Work with Product Managers to clarify customer, data, and regulatory requirements that influence scope and acceptance criteria.
- Work with Project Managers to place review gates, risk owners, and escalation steps in project plans and risk registers.
- Escalate unresolved critical findings, missing approvals, incidents, or policy exceptions to the Project Manager, Product Manager, and Sponsor as appropriate.

---

## Operations, SRE, or Platform Owners

### Role Summary
Operations, SRE, or Platform Owners prepare and operate the environments, deployment paths, reliability practices, and platform services needed for successful delivery.

### Responsibilities
- Confirm deployment, monitoring, alerting, capacity, backup, and rollback readiness
- Identify operational dependencies, service-level risks, and support requirements
- Coordinate production changes, post-deploy verification, and incident response inputs
- Provide platform constraints and operational acceptance criteria during planning

### Goals
- Improve reliability, observability, and recovery readiness
- Reduce release and production support risk
- Ensure operational requirements are visible before deployment

### Interactions with existing roles
- Coordinate with Developers on deployability, observability, runbooks, and operational handoffs; Developers retain code and test ownership.
- Inform Product Managers about reliability, performance, and operational trade-offs that may affect customer outcomes.
- Work with Project Managers on deployment windows, readiness checklists, incident communications, and post-release verification.
- Escalate capacity, reliability, rollback, or incident risks when they threaten release success or service commitments.

---

## Customer Support or Service Owners

### Role Summary
Customer Support or Service Owners represent support readiness and customer-impact feedback. They prepare service teams for launch and feed production learnings back into future work.

### Responsibilities
- Identify support implications, known issues, and customer communication needs
- Prepare support playbooks, triage guidance, and escalation contacts
- Share customer-impact signals during planning, launch, and post-release review
- Route recurring issues or high-impact feedback into the backlog

### Goals
- Ensure support teams can help customers effectively at release
- Reduce customer confusion and time to resolution
- Improve future project outcomes with production and support insights

### Interactions with existing roles
- Partner with Product Managers on customer impact, messaging, adoption risks, and backlog feedback; Product Managers retain product prioritization.
- Work with Developers to understand expected behavior, limitations, diagnostics, and fixes without taking ownership of implementation.
- Coordinate with Project Managers on launch readiness, support handoffs, stakeholder communications, and escalation timing.
- Escalate severe customer-impact issues, recurring incidents, or unclear ownership through the Project Manager and Product Manager.

---

## Business or Executive Sponsors

### Role Summary
Business or Executive Sponsors provide strategic sponsorship and decision authority for major outcomes, investments, and escalations. They ensure projects remain aligned with the business case.

### Responsibilities
- Confirm strategic goals, funding expectations, and success measures
- Resolve high-impact scope, timing, investment, or organizational trade-offs
- Support stakeholder alignment and remove executive-level blockers
- Review outcomes at major decision gates and retrospectives

### Goals
- Keep project outcomes aligned with business priorities
- Provide timely decisions when escalation exceeds team authority
- Ensure sponsorship remains visible throughout the lifecycle

### Interactions with existing roles
- Work with Product Managers on business outcomes, customer value, and priority trade-offs; Product Managers retain day-to-day product decisions.
- Work with Project Managers on decision gates, escalations, status expectations, and major risk responses; Project Managers retain delivery coordination.
- Engage Developers through demos, readiness reviews, or escalation forums when technical constraints affect business commitments.
- Participate in initiation, major planning checkpoints, release decisions, and retrospectives where sponsorship decisions or escalations are required.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
