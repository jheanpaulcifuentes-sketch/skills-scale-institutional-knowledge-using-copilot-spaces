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

## Technical Leads

### Role Summary
Technical Leads guide the architectural direction of a project and help the team turn product goals into technically sound implementation decisions.

### Responsibilities
- Define technical approach, standards, and architecture for the project
- Mentor developers and support technical decision-making
- Review design trade-offs and identify technical risks early
- Coordinate technical dependencies across teams and systems
- Align implementation choices with delivery goals and quality expectations

### Goals
- Improve technical clarity and execution quality
- Reduce rework caused by unclear design decisions
- Keep delivery aligned with architecture and performance goals

### Typical Communication
- Architecture discussions and technical design reviews
- Dependency planning with PMs and other engineering leads
- Escalation of major risks or design blockers to stakeholders

### Interaction with Existing Roles
- Works closely with Developers to translate requirements into implementation plans
- Partners with Product Managers to validate feasibility and trade-offs
- Coordinates with Project Managers on sequencing, dependencies, and delivery risks
- Escalates architecture or staffing concerns that may affect scope or timeline

---

## Engineering Managers

### Role Summary
Engineering Managers support delivery health by aligning people, capacity, and team-level execution with project goals.

### Responsibilities
- Plan and balance team capacity and resourcing
- Support hiring, onboarding, and team development needs
- Remove delivery obstacles and coordinate cross-team dependencies
- Monitor team health, workload, and execution risks
- Partner with leaders on prioritization and staffing decisions

### Goals
- Maintain sustainable delivery and healthy team performance
- Reduce bottlenecks and talent-related blockers
- Improve accountability and support across engineering teams

### Typical Communication
- Team capacity reviews and staffing discussions
- Engineering health check-ins and escalation conversations
- Collaboration with PMs and technical leads on planning and resourcing

### Interaction with Existing Roles
- Works with Project Managers to align timelines, staffing, and risks
- Supports Technical Leads by removing impediments to implementation
- Helps Developers maintain focus and clarity through capacity planning
- Coordinates with Product Managers on trade-offs between delivery scope and team readiness

---

## Release / Platform Engineers

### Role Summary
Release and Platform Engineers make sure software can be built, deployed, and verified reliably in a repeatable way.

### Responsibilities
- Maintain CI/CD pipelines, release automation, and deployment tooling
- Define and document deployment procedures and rollback plans
- Ensure environments are configured and monitored for release readiness
- Coordinate release windows and post-deploy validations
- Support incident recovery and operations continuity for production changes

### Goals
- Reduce release risk and deployment friction
- Improve observability and operational readiness
- Enable dependable, repeatable delivery across environments

### Typical Communication
- Release readiness and deployment sign-offs
- Change and incident coordination with engineering and support teams
- Platform reliability updates and environment health reporting

### Interaction with Existing Roles
- Works with Developers to validate that changes are releasable and testable
- Coordinates with Project Managers on launch timing and communication
- Supports Product Managers and Stakeholders with deployment readiness and release messaging
- Collaborates with SRE/On-call Engineers during incident response and post-deploy checks

---

## UX Researchers / Designers

### Role Summary
UX Researchers and Designers ensure that solutions are usable, accessible, and aligned to customer needs before and during delivery.

### Responsibilities
- Conduct user research, usability testing, and design validation
- Define user flows, interfaces, and design patterns
- Translate customer insights into actionable requirements and acceptance criteria
- Partner with engineering to ensure design feasibility and quality
- Advocate for accessibility, usability, and customer clarity

### Goals
- Improve customer experience and usability outcomes
- Reduce ambiguity between product intent and implementation
- Increase confidence that delivered work meets real user needs

### Typical Communication
- User research findings, design reviews, and prototype feedback
- Product and engineering alignment sessions
- Story-level design clarifications and usability acceptance criteria

### Interaction with Existing Roles
- Works with Product Managers to define customer outcomes and desirable experience
- Provides specifications and feedback to Developers during implementation
- Supports QA by clarifying expected user interactions and acceptance criteria
- Helps Project Managers communicate scope trade-offs tied to design and usability

---

## Data Analysts / Measurement Leads

### Role Summary
Data Analysts and Measurement Leads define how success will be measured and how product outcomes are tracked over time.

### Responsibilities
- Define metrics, instrumentation needs, and dashboard requirements
- Analyze usage, performance, and quality trends related to project goals
- Validate whether delivered work is producing expected impact
- Support evidence-based decision-making and iteration planning
- Ensure telemetry and reporting align with stakeholder expectations

### Goals
- Improve visibility into product and operational outcomes
- Support decisions with data rather than assumptions
- Help teams learn from results and adapt quickly

### Typical Communication
- KPI reviews and measurement strategy discussions
- Reporting on adoption, performance, and business impact
- Collaboration with product and engineering leaders on success criteria

### Interaction with Existing Roles
- Partners with Product Managers on objective success metrics and outcome tracking
- Helps Developers and QA define the measurements needed to verify product health
- Provides PMs with evidence to communicate progress and risks to stakeholders
- Supports release reviews with post-launch findings and impact signals

---

## Support / Customer Success Representatives

### Role Summary
Support and Customer Success roles connect the project to customer reality by surfacing issues, needs, and operational feedback from real users.

### Responsibilities
- Track customer pain points, service quality issues, and recurring support themes
- Coordinate support readiness and knowledge sharing before and after launch
- Surface customer impact and escalation needs to project teams
- Help validate whether a solution is solving the intended problem
- Maintain communication with stakeholders about user experience and support readiness

### Goals
- Improve customer satisfaction and issue response quality
- Reduce friction between product delivery and customer support operations
- Ensure the project remains grounded in lived user experiences

### Typical Communication
- Issue and feedback loops with product and engineering teams
- Customer readiness and release communication updates
- Support handoff notes and operational readiness reviews

### Interaction with Existing Roles
- Provides Product Managers with real-world feedback and customer impact signals
- Helps Project Managers identify operational risks and communication needs
- Supports Developers by clarifying recurring issues and usability problems
- Coordinates with Release/Platform Engineers on deployment communications and support readiness

---

## Security / Compliance Advocates

### Role Summary
Security and Compliance Advocates ensure that project work meets required safeguards, standards, and risk expectations.

### Responsibilities
- Review project plans for security, privacy, and compliance implications
- Define required controls, guardrails, and review checkpoints
- Assess risks associated with dependencies, data handling, and release readiness
- Partner with engineering teams on remediation and continuous improvement
- Help maintain alignment with organizational policies and external requirements

### Goals
- Reduce security and compliance risk across delivery work
- Improve confidence in safe, responsible project execution
- Support secure release practices and operational governance

### Typical Communication
- Security reviews, risk assessments, and remediation planning
- Dependency and compliance discussions during planning and release
- Escalation of high-risk issues affecting product or stakeholder trust

### Interaction with Existing Roles
- Works with Developers to review implementation risk and control requirements
- Helps Project Managers include security checkpoints in planning and release readiness
- Supports Product Managers in balancing business goals with security and compliance needs
- Collaborates with Release/Platform Engineers on secure deployment and rollback considerations

---

## SRE / On-call Engineers

### Role Summary
SRE and On-call Engineers focus on service reliability, monitoring, and rapid response to production issues that can impact business outcomes.

### Responsibilities
- Define monitoring, alerting, and service health practices
- Own runbooks and escalation steps for incidents and outages
- Support production readiness and operational resilience for releases
- Participate in post-incident reviews and continuous reliability improvements
- Help prevent outages by identifying system-risk patterns early

### Goals
- Protect service reliability and customer trust
- Reduce mean time to detect and recover from incidents
- Improve operational visibility and resilience over time

### Typical Communication
- Incident response coordination and operational alerts
- Release health checks and post-deploy validation discussions
- Reliability reviews and improvement planning

### Interaction with Existing Roles
- Works with Release/Platform Engineers to validate monitoring and rollout safety
- Supports Project Managers in assessing business-impacting incidents and communication needs
- Helps Developers prioritize resilience and observability work within feature delivery
- Collaborates with Product Managers and Stakeholders during incident communications and recovery planning

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Together, these roles help clarify accountability, dependencies, and communication paths across project lifecycles.

