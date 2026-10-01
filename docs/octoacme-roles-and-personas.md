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
The QA / Testing Lead owns quality assurance strategy, test planning, and release readiness. They ensure features meet acceptance criteria and quality standards before being considered done.

### Responsibilities
- Define and maintain test plans aligned to user stories and acceptance criteria
- Execute manual and automated testing, including regression and smoke coverage
- Identify, triage, and track defects with development teams
- Validate that work meets the Definition of Done before release
- Partner with Release Manager on pre-deploy verification and go-live checks

### Goals
- Catch defects early and reduce production risk
- Improve confidence in delivery quality
- Minimize rework and post-release firefighting

### Typical Communication
- Daily standups and sprint planning
- Test plan reviews with Product Managers and Developers
- Defect triage and quality dashboards
- Release readiness check-ins with Project Managers and Release Managers

### Interaction with Existing Roles
- Works closely with Developers to confirm testability and resolve defects.
- Aligns with Product Managers on acceptance criteria and customer-facing quality expectations.
- Keeps Project Managers informed of delivery quality and release risk.
- Coordinates with Release Managers to verify staging, rollback readiness, and deployment confidence.

---

## Stakeholder / Sponsor

### Role Summary
The Stakeholder / Sponsor is the business decision-maker or executive sponsor who approves scope, priorities, and strategic direction. They provide context for why the work matters and help unblock decisions at key milestones.

### Responsibilities
- Approve the project charter, business goals, and resource commitments
- Participate in go/no-go decisions at milestone gates
- Provide business priorities, trade-offs, and strategic alignment
- Review major risks, dependencies, and releases with leadership context
- Escalate or resolve cross-functional issues that require executive sponsorship

### Goals
- Ensure the project delivers measurable business value
- Maintain alignment between delivery teams and organizational priorities
- Enable timely decisions to reduce project delays

### Typical Communication
- Milestone reviews and steering meetings
- Weekly or monthly stakeholder updates
- Escalation and risk alerts when business impact is material

### Interaction with Existing Roles
- Works with Product Managers to validate outcomes and prioritize trade-offs.
- Provides direction to Project Managers on scope and timeline commitments.
- Relies on QA and Release Managers to understand delivery risk before major approvals.
- Interfaces with Developers and Architects when business priorities affect technical feasibility or sequencing.

---

## Technical Lead / Architect

### Role Summary
The Technical Lead / Architect provides technical direction, reviews design decisions, and helps the team navigate complex implementation challenges. They ensure the solution remains scalable, maintainable, and aligned with the broader technical strategy.

### Responsibilities
- Review technical design and architecture choices for risk and feasibility
- Guide engineering trade-offs and technical standards
- Identify architecture risks, dependencies, and technical debt
- Mentor developers and ensure maintainability of implementation decisions
- Support Definition of Done with technical quality expectations

### Goals
- Preserve system reliability and performance
- Reduce unnecessary complexity and technical debt
- Enable the team to make confident, well-scoped technical decisions

### Typical Communication
- Design reviews and architecture discussions
- Code review collaboration and technical risk reviews
- Planning sessions for dependencies and feasibility analysis

### Interaction with Existing Roles
- Partners with Developers on implementation quality and technical standards.
- Works with Product Managers and Stakeholders when roadmap changes affect technical feasibility.
- Supports Project Managers in identifying dependencies, delivery constraints, and risk mitigation.
- Coordinates with Security and Release functions to ensure production-readiness and safe deployment patterns.

---

## Release Manager

### Role Summary
The Release Manager coordinates deployment, communication, and post-release verification. They reduce release risk by managing sequencing, readiness, and rollout stability.

### Responsibilities
- Plan release windows, staging, and production deployment steps
- Coordinate with QA on smoke testing and release verification
- Manage release notes, stakeholder communication, and rollback planning
- Monitor post-deployment health and respond to early release issues
- Support incident learning and continuous improvement after each deployment

### Goals
- Deliver predictable, low-risk releases
- Minimize downtime and user disruption
- Maintain clear communication across support, stakeholders, and delivery teams

### Typical Communication
- Release planning and deployment windows
- Release notes and stakeholder announcements
- Incident response and post-deployment reviews

### Interaction with Existing Roles
- Collaborates with QA / Testing Lead on acceptance validation and release readiness.
- Works with Project Managers to align release timing with milestones and dependencies.
- Partners with Developers and Technical Leads on rollback readiness and production impact risk.
- Keeps Stakeholders informed of release status and business impact or risk.

---

## Security / Compliance Officer

### Role Summary
The Security / Compliance Officer ensures the project meets security, privacy, and regulatory requirements. They identify risks early and help the team build safeguards into the delivery process.

### Responsibilities
- Review security and privacy implications of planned work
- Participate in threat assessments, secure design reviews, and compliance checks
- Validate conformance with security policies and regulatory requirements
- Support incident response and post-incident remediation when security events occur
- Guide teams on secure coding, data handling, and risk mitigation practices

### Goals
- Prevent security breaches and data loss
- Ensure compliance with required controls and standards
- Build trust through secure and responsible delivery practices

### Typical Communication
- Security review gates during planning and release readiness
- Risk register updates and compliance checkpoints
- Incident response coordination with engineering and leadership

### Interaction with Existing Roles
- Works with Developers and Architects to assess design and implementation risks.
- Partners with Product Managers and Stakeholders on decision points that affect compliance or customer trust.
- Provides Project Managers with security risk visibility and escalation paths.
- Coordinates with Release Managers to ensure production deployments meet security and rollback expectations.

---

## UX / Design Lead

### Role Summary
The UX / Design Lead shapes the user experience, visual design, and usability standards for the product. They ensure the work is useful, understandable, and aligned to user needs.

### Responsibilities
- Gather user research, user needs, and usability insights
- Create prototypes, interface flows, and design specs
- Collaborate with Product Managers on prioritization and customer value
- Review implementation against design intent and quality standards
- Capture user feedback and identify improvement opportunities after release

### Goals
- Create intuitive, accessible, and high-value experiences
- Reduce friction and support burden for users
- Ensure features are easy to learn and use

### Typical Communication
- Design reviews and usability sessions
- Product backlog refinement and acceptance-criteria alignment
- Post-release feedback reviews and iteration planning

### Interaction with Existing Roles
- Works with Product Managers to translate business goals into user-centered requirements.
- Collaborates with Developers and Technical Leads to validate design feasibility and implementation quality.
- Supports QA by defining usability acceptance criteria and edge-case scenarios.
- Helps Project Managers communicate user impact and adoption considerations during milestone reviews.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Together, these roles clarify ownership, communication, and accountability across the full project lifecycle.
