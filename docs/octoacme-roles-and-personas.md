# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. For a full view of how these roles map to project activities, see the [RACI Matrix](./octoacme-raci-matrix.md).

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

### Interactions
- **Product Managers**: receive acceptance criteria and feature specs; flag scope or feasibility concerns.
- **Project Managers**: report progress in standups; escalate blockers for risk tracking.
- **QA Lead**: collaborate on test coverage, resolve defects, and confirm the [Definition of Done](./octoacme-definition-of-ready-and-done.md).
- **UX/UI Designer**: consume design specs and mockups; provide feedback on technical constraints.
- **DevOps Engineer**: align on CI/CD pipeline requirements, branching strategy, and deployment steps.
- **Business Analyst**: clarify requirement details and refine user stories before sprint start.

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

### Interactions
- **Project Managers**: align on timelines, milestones, and risk trade-offs.
- **Developers**: provide clear acceptance criteria; validate delivered features against success metrics.
- **QA Lead**: review test plans to ensure they cover stated acceptance criteria.
- **UX/UI Designer**: co-create user flows and validate designs against product goals.
- **Business Analyst**: receive refined requirements and user story details.
- **Customer Support/Success**: gather user feedback and bug reports to inform backlog priorities.

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

### Interactions
- **Product Managers**: align scope and priority; co-own escalations to sponsors.
- **Developers**: track progress, surface blockers, and update the risk register.
- **QA Lead**: ensure QA timelines are reflected in the project plan.
- **DevOps Engineer**: coordinate deployment windows and rollback planning.
- **Business Analyst**: rely on BA to surface scope clarifications and stakeholder requirements.
- **Customer Support/Success**: include in release communications and stakeholder updates.

---

## QA Lead

### Role Summary
The QA Lead owns the test strategy, ensures quality standards are met across all phases, and acts as the final quality gate before release.

### Responsibilities
- Define and maintain the test plan and quality standards
- Coordinate functional, regression, and exploratory testing
- Review acceptance criteria to ensure testability
- Approve releases from a quality perspective
- Track and triage defects; escalate blockers to the Project Manager

### Goals
- Prevent defects from reaching production
- Ensure the [Definition of Done](./octoacme-definition-of-ready-and-done.md) includes meaningful quality criteria
- Continuously improve test coverage and automation

### Typical Communication
- Daily standups and sprint review participation
- Test plan and defect reports shared with PM and Developers
- Release readiness sign-off communicated to the Project Manager

### Interactions
- **Developers**: collaborate on unit/integration test coverage; review PRs for testability.
- **Product Managers**: validate that acceptance criteria are complete and testable.
- **Project Managers**: report QA status and escalate blocking defects.
- **DevOps Engineer**: align on test automation in the CI/CD pipeline.
- **UX/UI Designer**: coordinate usability and accessibility testing.
- **Customer Support/Success**: review known issues and customer-reported bugs before release.

---

## UX/UI Designer

### Role Summary
The UX/UI Designer champions user-centered design, translating requirements into mockups, interaction flows, and design specifications that guide development.

### Responsibilities
- Deliver wireframes, prototypes, and high-fidelity design specs
- Conduct and incorporate user research findings
- Advocate for accessibility and usability best practices
- Participate in design reviews and handoff sessions with Developers
- Ensure visual consistency with product design guidelines

### Goals
- Reduce friction and improve user satisfaction
- Deliver clear, implementation-ready designs before sprint start
- Ensure designs are accessible and meet relevant standards

### Typical Communication
- Design review sessions with Product Managers and Developers
- Annotated mockups and design assets shared via design tool links
- Participation in sprint planning to confirm design readiness

### Interactions
- **Product Managers**: translate product requirements into user flows and validate designs against goals.
- **Developers**: hand off design specs; clarify design intent during implementation.
- **QA Lead**: support usability testing and review UI against design specs during QA.
- **Business Analyst**: incorporate user research insights and business requirements into designs.
- **Customer Support/Success**: review user-reported pain points to inform design iterations.

---

## DevOps Engineer

### Role Summary
The DevOps Engineer owns the CI/CD pipeline, automates deployments, and ensures the reliability and observability of production systems.

### Responsibilities
- Build and maintain CI/CD pipelines and infrastructure as code
- Automate deployments and environment provisioning
- Monitor system health, alerts, and incident response tooling
- Coordinate deployment windows with the Project Manager
- Support rollback and incident remediation procedures

### Goals
- Reduce deployment risk and mean time to recovery (MTTR)
- Improve pipeline reliability and deployment frequency
- Maintain clear observability of production environments

### Typical Communication
- Deployment schedule coordination with Project Managers
- Incident status updates during outages
- Pipeline and infrastructure documentation maintained in the repo

### Interactions
- **Developers**: review pipeline configurations; support debugging of CI failures.
- **QA Lead**: integrate automated tests into the pipeline; coordinate test environment provisioning.
- **Project Managers**: communicate deployment windows, risks, and rollback plans.
- **Product Managers**: provide release timing constraints and post-deploy health signals.
- **Customer Support/Success**: notify of deployments that may affect users; provide incident status updates.

---

## Business Analyst

### Role Summary
The Business Analyst bridges business stakeholders and the delivery team by analyzing needs, clarifying requirements, and translating them into actionable user stories.

### Responsibilities
- Facilitate requirement-gathering sessions with stakeholders
- Author and refine user stories and acceptance criteria
- Validate that delivered features meet business objectives
- Maintain traceability between business needs and backlog items
- Identify process gaps and surface improvement opportunities

### Goals
- Ensure requirements are clear, complete, and agreed upon before work begins
- Reduce rework caused by misunderstood requirements
- Support stakeholders with clear documentation and decision support

### Typical Communication
- Requirement workshops and stakeholder interviews
- User story write-ups and acceptance criteria shared with the team
- Participation in sprint planning and backlog refinement

### Interactions
- **Product Managers**: co-author user stories; surface stakeholder-driven priorities.
- **Developers**: clarify ambiguous requirements before and during development.
- **Project Managers**: flag scope changes and dependencies uncovered during analysis.
- **UX/UI Designer**: provide user research context and business requirements to inform design.
- **QA Lead**: review acceptance criteria together to ensure testability.
- **Customer Support/Success**: synthesize customer feedback into structured requirements.

---

## Customer Support/Success

### Role Summary
Customer Support/Success represents the voice of the customer within the team. They relay user feedback, assist with release communications, and help prioritize improvements based on real-world impact.

### Responsibilities
- Communicate bug reports and feature requests from users to the team
- Assist in drafting user-facing release notes and announcements
- Participate in release readiness reviews to flag known user-impacting issues
- Advocate for user needs during backlog prioritization
- Support post-release monitoring by tracking user-reported issues

### Goals
- Ensure the team understands customer pain points and impact
- Reduce time-to-resolution for user-impacting issues
- Improve communication quality around releases and incidents

### Typical Communication
- Participation in release readiness reviews and stakeholder updates
- Bug and feedback summaries shared with Product Managers and QA Lead
- Post-release customer communication coordinated with Project Managers

### Interactions
- **Product Managers**: provide customer-driven input for backlog prioritization.
- **Project Managers**: coordinate customer communication during releases and incidents.
- **Developers**: escalate high-priority user-reported bugs for triage.
- **QA Lead**: share known issues from user reports before release sign-off.
- **DevOps Engineer**: receive incident status updates to communicate to affected customers.
- **Business Analyst**: contribute customer feedback to requirement-gathering sessions.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See the [RACI Matrix](./octoacme-raci-matrix.md) to understand accountability across project phases.

