# OctoAcme — Definition of Ready & Definition of Done

## Purpose
Establish clear, shared criteria that determine when a work item is ready to be pulled into a sprint (Definition of Ready) and when it is truly complete (Definition of Done). Using these checklists consistently reduces rework, improves predictability, and keeps quality high.

For role ownership of DoR/DoD, see the [RACI Matrix](./octoacme-raci-matrix.md).

---

## Definition of Ready (DoR)

A backlog item is **Ready** to be pulled into a sprint only when all of the following are true:

### Story / Requirement
- [ ] User story or task is written in agreed format (e.g., "As a [role], I want [action] so that [outcome]")
- [ ] Acceptance criteria are clear, specific, and testable
- [ ] Business value or rationale is documented
- [ ] Item is estimated (story points or T-shirt size)

### Design & UX
- [ ] UI/UX mockups or wireframes are available and linked (if UI work is involved)
- [ ] Design has been reviewed and approved by the UX/UI Designer

### Dependencies
- [ ] All external dependencies are identified and resolved or have an agreed plan
- [ ] Related items (blockers, related stories) are linked in the project board

### Technical Readiness
- [ ] Technical approach is understood; any spikes are complete
- [ ] No known blockers that would prevent the developer from starting

### QA Readiness
- [ ] Test scenarios are outlined or agreed upon with the QA Lead
- [ ] Test environment is available or scheduled

> **Tip:** The Product Manager and Business Analyst own ensuring stories meet DoR before sprint planning. The QA Lead confirms test readiness.

---

## Definition of Done (DoD)

A work item is **Done** when all of the following are true:

### Development
- [ ] All acceptance criteria are met
- [ ] Code is merged to the main/target branch via an approved PR
- [ ] PR includes a link to the related issue and a clear description of changes

### Quality & Testing
- [ ] Unit tests written and passing for new logic
- [ ] Integration tests passing (where applicable)
- [ ] End-to-end or smoke tests passing for critical flows
- [ ] Manual QA sign-off obtained from the QA Lead (for feature work)
- [ ] No P1/P2 defects outstanding

### Code Quality
- [ ] CI pipeline (lint, tests, security scan) is green
- [ ] Code reviewed and approved by at least one peer
- [ ] No commented-out code or debug artifacts left in

### Documentation
- [ ] Inline code documentation updated (if relevant)
- [ ] User-facing docs or release notes updated (if applicable)
- [ ] API or interface changes documented

### Operational Readiness (for release-bound items)
- [ ] Feature flags or rollout configuration reviewed with DevOps Engineer
- [ ] Monitoring/alerting updated if new signals are introduced
- [ ] Rollback plan documented if the change is high risk

> **Tip:** The QA Lead confirms DoD is met before marking an item Done. The Project Manager verifies DoD compliance before sprint closure.

---

## Using DoR and DoD in Practice

| Checkpoint | Who checks | When |
|---|---|---|
| DoR review | Product Manager, QA Lead, Business Analyst | Sprint planning / backlog refinement |
| DoD review | QA Lead, Developer | Before moving item to "Done" column |
| DoD audit | Project Manager | Sprint review / closure |

---

## Related Docs
- [Project Planning](./octoacme-project-planning.md) — backlog and sprint planning activities
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — quality and PR workflow
- [RACI Matrix](./octoacme-raci-matrix.md) — ownership of DoR/DoD across roles
- [Roles & Personas](./octoacme-roles-and-personas.md) — role responsibilities
