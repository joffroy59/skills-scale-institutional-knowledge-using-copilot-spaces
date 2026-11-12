# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

Role assignments are flexible: a project may combine roles or share them across people, but it should name an accountable owner for each area. These personas are guidance, not required staffing for every project. When a decision crosses areas, consult the affected owners, record the decision, and ask the Project Manager to coordinate escalation if the team cannot resolve it.

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

## UX/Design Lead

### Role Summary
The UX/Design Lead represents user needs in the solution and guides research, interaction design, usability, and accessibility.

### Decision Ownership
- Owns the design approach and usability/accessibility validation within the agreed product goals and constraints.
- Partners with the Product Manager on user needs and scope; the Product Manager owns backlog priority and product outcomes.

### Responsibilities
- Plan or conduct user research and turn findings into design recommendations
- Create and maintain user flows, interaction designs, and design guidance
- Identify usability and accessibility risks and agree on validation with QA/Testing
- Review implemented experiences with Developers and provide actionable feedback

### Lifecycle Touchpoints & Interactions
- During initiation and planning, works with the Product Manager and stakeholders to validate users, needs, and success measures.
- During execution, collaborates with Developers and QA/Testing on design details, acceptance criteria, and usability checks.
- Shares feedback and lessons from user validation in reviews and retrospectives; raises scope or schedule impacts with the Product Manager and Project Manager.
- Typical deliverables: research findings, user flows or prototypes, and usability/accessibility findings.

---

## Technical Lead/Architect

### Role Summary
The Technical Lead/Architect guides technical design and architecture so the solution is maintainable, secure, and operable.

### Decision Ownership
- Owns technical design and architecture decisions within agreed product, security, and operational constraints.
- Escalates decisions that materially change scope, cost, risk, or cross-team dependencies to the Product Manager and Project Manager.

### Responsibilities
- Define and communicate architecture and technical design guidance
- Identify technical risks, integration points, and dependencies
- Support Developers with implementation choices, reviews, and estimation
- Coordinate technical mitigations with Security/Privacy and DevOps/SRE or Release Manager

### Lifecycle Touchpoints & Interactions
- During initiation and planning, advises the Product Manager and Project Manager on feasibility, dependencies, and sequencing.
- During execution, supports Developers and collaborates with QA/Test Lead on testability and with Security/Privacy on mitigations.
- Before release, works with DevOps/SRE or Release Manager on operability and readiness; records significant decisions for the team.
- Typical deliverables: technical design notes, architecture decisions, and technical risk/dependency updates.

---

## QA/Test Lead

### Role Summary
The QA/Test Lead (the QA/Testing function in the project overview) guides the team's test strategy and makes quality risks visible throughout delivery.

### Decision Ownership
- Owns the test approach and communicates quality evidence, open defects, and readiness risks.
- The Product Manager owns product acceptance criteria; Developers own the quality of their changes and collaborate on test coverage.

### Responsibilities
- Define test coverage and validation methods for functional, integration, and regression risks
- Work with the Product Manager to make acceptance criteria verifiable
- Collaborate with Developers on testability, automation, and defect investigation
- Track quality gaps and report their impact and release implications

### Lifecycle Touchpoints & Interactions
- During planning, aligns the test approach with the Product Manager, Developers, and Project Manager.
- During execution, coordinates validation with Developers and reports defects and risks to the delivery team.
- Before release, shares test results and outstanding risks with the Project Manager, Product Manager, and DevOps/SRE or Release Manager; the accountable product and delivery owners make any scope or timing trade-offs.
- Typical deliverables: test strategy, test results, and a visible defect/quality-risk list.

---

## DevOps/SRE or Release Manager

### Role Summary
This role coordinates operational readiness and release execution so changes can be deployed, observed, and recovered safely. Depending on project size, these responsibilities may be held by a DevOps/SRE specialist, a Release Manager, or shared owners.

### Decision Ownership
- Owns operational readiness recommendations and deployment, monitoring, and rollback procedures within the agreed release plan.
- Raises reliability or readiness concerns early; the Project Manager coordinates schedule changes and the Product Manager decides product scope trade-offs with relevant stakeholders.

### Responsibilities
- Define deployment, monitoring, and rollback needs
- Confirm that operational checks and required runbooks are prepared
- Coordinate deployment verification and communicate operational incidents
- Work with Developers and QA/Test Lead to resolve release blockers

### Lifecycle Touchpoints & Interactions
- During planning, identifies environment, reliability, and release dependencies with the Technical Lead/Architect and Project Manager.
- During execution, helps Developers make changes observable and deployable and aligns release checks with QA/Test Lead.
- Before and during release, coordinates readiness, deployment, verification, and rollback with the Project Manager and delivery team.
- After release, shares operational findings with the Product Manager and Project Manager for follow-up and retrospectives.
- Typical deliverables: release checklist, runbooks, monitoring/rollback plan, and deployment status.

---

## Security/Privacy Lead

### Role Summary
The Security/Privacy Lead helps the team identify and address security, privacy, and compliance risks throughout the project.

### Decision Ownership
- Owns security and privacy assessments and identifies required controls or reviews; provides or coordinates required specialist approval where applicable.
- Partners with the Product Manager on risk-informed scope trade-offs and with the Technical Lead/Architect on technical mitigations.

### Responsibilities
- Identify relevant threat, data protection, and compliance considerations
- Advise on secure design, data handling, and privacy controls
- Review mitigations and coordinate required security or privacy assessments
- Communicate unresolved risks and required actions to accountable project owners

### Lifecycle Touchpoints & Interactions
- During initiation and planning, works with the Product Manager and Technical Lead/Architect to identify risks and required reviews.
- During execution, advises Developers and the Technical Lead/Architect on mitigations and verifies agreed controls.
- Before release, communicates outstanding risks and any required approval to the Project Manager and Product Manager for resolution or escalation.
- Typical deliverables: security/privacy risk findings, control recommendations, and review outcomes.

---

## Customer Support/Operations Representative

### Role Summary
The Customer Support/Operations Representative brings customer-facing and service-operational needs into planning and helps prepare teams to support a release.

### Decision Ownership
- Owns recommendations for support readiness, customer-facing guidance, and operational feedback.
- The Product Manager owns product priorities and outcome decisions; the Project Manager coordinates readiness work and stakeholder communication.

### Responsibilities
- Surface recurring customer issues, support needs, and operational constraints
- Identify support documentation, training, and escalation-path requirements
- Prepare the support team for expected changes and known issues
- Gather post-release feedback and incidents for product and process follow-up

### Lifecycle Touchpoints & Interactions
- During initiation and planning, shares customer and service needs with the Product Manager and Project Manager.
- During execution, reviews support impacts and coordinates customer-facing guidance with the Product Manager.
- Before release, works with the Project Manager and DevOps/SRE or Release Manager on support readiness, known issues, and escalation paths.
- After release, routes customer feedback and operational issues to the Product Manager and Project Manager for prioritization and follow-up.
- Typical deliverables: support notes, customer guidance, and post-release feedback summaries.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Assign only the roles needed for the project, while making ownership and handoffs explicit across initiation, planning, execution, release, and retrospectives.

