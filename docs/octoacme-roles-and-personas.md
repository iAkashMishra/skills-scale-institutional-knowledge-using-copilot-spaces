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

## QA / Testing Lead

### Role Summary
QA / Testing Lead defines the quality strategy for a project and ensures that work meets acceptance criteria before release. They help protect end-user trust by identifying gaps early and validating readiness across releases.

### Responsibilities
- Define quality plans, test strategy, and release readiness criteria
- Create and maintain manual and automated test coverage for critical flows
- Review acceptance criteria with Product Managers and Developers
- Coordinate regression testing and issue triage before release
- Track quality metrics and escalate risk when delivery confidence is low

### Goals
- Reduce defects reaching production
- Improve release confidence and customer experience
- Ensure quality is built into delivery rather than checked at the end

### Typical Communication
- Daily standups and sprint planning
- QA sign-off reviews and defect triage
- Release readiness check-ins with PMs and stakeholders

### How they interact with existing roles
- Works with Developers to validate functionality, reproduce bugs, and confirm fixes
- Partners with Product Managers to ensure that acceptance criteria are measurable and testable
- Coordinates with Project Managers on release timing, risk signals, and issue prioritization

---

## Technical Architect

### Role Summary
Technical Architect sets the direction for the system design and ensures technical decisions support long-term maintainability, scalability, and reliability. They help balance short-term delivery needs with architectural health.

### Responsibilities
- Review technical designs and architecture decisions for major features
- Define standards for integration patterns, performance, scalability, and maintainability
- Identify technical debt and recommend mitigation approaches
- Support Developers with design guidance and decision-making frameworks
- Align engineering choices with product goals and operational constraints

### Goals
- Maintain a coherent and scalable technical foundation
- Reduce avoidable rework and architecture drift
- Support sustainable delivery as the system grows

### Typical Communication
- Architecture review meetings and design discussions
- Technical decision records and design docs
- Cross-team planning sessions involving engineering leads and stakeholders

### How they interact with existing roles
- Collaborates with Developers to guide design trade-offs and implementation decisions
- Helps Product Managers understand technical feasibility, delivery risk, and roadmap implications
- Works with Project Managers and PMs to flag dependencies, delivery constraints, and risk areas that affect milestones

---

## DevOps / Infrastructure Engineer

### Role Summary
DevOps / Infrastructure Engineer owns the delivery pipeline, infrastructure, monitoring, and production reliability needed to support software releases. They enable fast, repeatable, and observable deployment practices.

### Responsibilities
- Maintain CI/CD pipelines and deployment automation
- Manage infrastructure configuration, environments, and production health
- Configure monitoring, logging, and alerting for applications and services
- Support incident response and rollback readiness for production changes
- Improve deployment safety, throughput, and operational resilience

### Goals
- Enable reliable and frequent releases
- Reduce operational risk and unplanned downtime
- Improve observability and recovery time for incidents

### Typical Communication
- Release planning and deployment reviews
- Incident response and postmortem sessions
- Infrastructure and reliability updates with engineering leads

### How they interact with existing roles
- Works with Developers to support environment readiness, build pipelines, and deployment validation
- Coordinates with Project Managers and stakeholders on release windows, rollback plans, and operational risks
- Supports Product Managers by helping assess whether delivery commitments are realistic given operational constraints

---

## Security / Compliance Officer

### Role Summary
Security / Compliance Officer helps ensure that projects meet security standards, privacy expectations, and required regulatory obligations. They provide a risk lens across planning, development, and release activities.

### Responsibilities
- Review application and system designs for security and compliance risks
- Define security requirements, controls, and review checkpoints
- Support vulnerability management, remediation tracking, and access controls
- Work with teams on incident response and post-incident follow-up
- Validate that work complies with internal policies and relevant standards

### Goals
- Reduce security risk and exposure to the organization
- Ensure compliance is considered early in the lifecycle
- Build secure-by-default delivery habits across teams

### Typical Communication
- Security review gates and compliance checkpoints
- Risk register updates and incident communications
- Partnerships with engineering and project leadership during planning and release

### How they interact with existing roles
- Advises Developers on secure design patterns, threat models, and safe implementation practices
- Works with Product Managers to align security requirements with feature scope and release timelines
- Partners with Project Managers on risk assessment, escalation paths, and mitigation planning

---

## UX / Design Lead

### Role Summary
UX / Design Lead shapes the user experience and ensures that product decisions are usable, accessible, and aligned with customer needs. They translate user needs and business goals into clear design direction.

### Responsibilities
- Conduct user research, interviews, and usability analysis
- Create design concepts, flows, wireframes, and high-fidelity mockups
- Define design standards, accessibility expectations, and user experience goals
- Partner with Product Managers on roadmap and feature prioritization
- Work with Developers to ensure implementation matches intended experience

### Goals
- Deliver intuitive and accessible experiences
- Improve adoption, satisfaction, and customer retention
- Align product design with user and business value

### Typical Communication
- Design reviews and product discovery sessions
- User research synthesis and prototype feedback loops
- Collaboration with engineering on feature design and validation

### How they interact with existing roles
- Helps Product Managers refine requirements and validate problem statements with user evidence
- Collaborates with Developers to clarify UI decisions, edge cases, and implementation constraints
- Supports Project Managers in clarifying scope, dependencies, and delivery sequencing for design-heavy work

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Master / Agile Coach helps the team improve delivery flow, remove obstacles, and strengthen agile practices. They support continuous improvement while protecting the team from unnecessary disruption.

### Responsibilities
- Facilitate sprint planning, daily standups, reviews, and retrospectives
- Help the team identify blockers and improve ways of working
- Coach teams on agile practices, collaboration habits, and flow efficiency
- Support alignment between Product Managers, Developers, and Project Managers
- Encourage a healthy, transparent, and psychologically safe team environment

### Goals
- Improve team effectiveness and delivery predictability
- Reduce friction and improve collaboration across roles
- Help the team learn and adjust continuously

### Typical Communication
- Agile ceremonies and retrospective sessions
- One-on-ones with team members and informal coaching conversations
- Cross-functional coordination on work flow and improvement opportunities

### How they interact with existing roles
- Works with Product Managers to support backlog clarity, prioritization, and feedback loops
- Helps Developers improve delivery habits, collaboration, and planning quality
- Partners with Project Managers to resolve schedule conflicts, dependencies, and communication gaps

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Together, these roles create a clearer model of accountability and collaboration across the full project lifecycle.
