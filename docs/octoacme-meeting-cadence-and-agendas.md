# OctoAcme — Meeting Cadence & Agendas

## Purpose
Describe the recommended meeting cadence for OctoAcme projects and provide standard agendas so facilitators and attendees can prepare efficiently and keep meetings focused.

For role-specific responsibilities in facilitation, see the [RACI Matrix](./octoacme-raci-matrix.md) and [Roles & Personas](./octoacme-roles-and-personas.md).

---

## Recommended Cadence Summary

| Meeting | Frequency | Duration | Facilitator |
|---|---|---|---|
| Project Kickoff | Once (start of project) | 60–90 min | Project Manager |
| Sprint Planning | Every sprint | 1–2 hours | Project Manager |
| Daily Standup | Daily (Mon–Fri) | 15 min | Project Manager / Team rotation |
| Weekly Status Sync | Weekly | 30–45 min | Project Manager |
| Release Readiness Review | Before each release | 45–60 min | Project Manager |
| Retrospective | End of each sprint / milestone | 45–75 min | Project Manager |

---

## Project Kickoff

**Purpose:** Align the full team and key stakeholders on project goals, scope, roles, and ways of working before execution begins.

**Attendees:** Project Manager, Product Manager, Developers, QA Lead, UX/UI Designer, DevOps Engineer, Business Analyst, Customer Support/Success (as relevant), Stakeholder/Sponsor.

**Agenda:**
1. Welcome & introductions (5 min)
2. Project One-pager review — goals, success metrics, timeline (10 min)
3. Scope & out-of-scope clarification (10 min)
4. Roles & responsibilities walkthrough — reference [Roles & Personas](./octoacme-roles-and-personas.md) (10 min)
5. Key milestones and dependencies overview (10 min)
6. Risk identification and initial register review (10 min)
7. Ways of working — tools, branching, PR process, meeting cadence (10 min)
8. Q&A and open discussion (5–15 min)
9. Next steps and owners assigned (5 min)

**Outputs:**
- Updated Project One-pager / Charter
- Confirmed team roster and RACI (see [RACI Matrix](./octoacme-raci-matrix.md))
- Initial Risk Register populated
- Project board set up with backlog skeleton

---

## Sprint Planning

**Purpose:** Select and commit to backlog items for the upcoming sprint, confirm readiness, and assign ownership.

**Attendees:** Project Manager, Product Manager, Developers, QA Lead, UX/UI Designer (as needed), Business Analyst.

**Agenda:**
1. Review sprint goal and capacity (5 min)
2. Product Manager presents top-priority backlog items (10 min)
3. Definition of Ready check on candidate items — reference [DoR & DoD](./octoacme-definition-of-ready-and-done.md) (15 min)
4. Estimation and commitment (20–40 min)
5. Assignment of owners per item (5 min)
6. Risk and dependency check for the sprint (5 min)
7. Confirm sprint board is updated (5 min)

**Outputs:**
- Sprint backlog committed and visible on the project board
- Item owners assigned
- Flagged risks or blockers documented

---

## Daily Standup

**Purpose:** Short daily sync to surface progress, blockers, and coordination needs.

**Attendees:** Developers, QA Lead, DevOps Engineer, Project Manager, UX/UI Designer (as needed).

**Format (each participant answers):**
1. What did I complete since the last standup?
2. What am I working on today?
3. Are there any blockers or dependencies I need help with?

**Guidelines:**
- Timebox strictly to 15 minutes.
- Park detailed discussions for after standup.
- Project Manager captures blockers for follow-up and risk register updates.

---

## Weekly Status Sync

**Purpose:** Provide stakeholders and the full team with a progress update, surface risks, and make decisions needed to keep the project on track.

**Attendees:** Project Manager, Product Manager, key Developers, QA Lead, Stakeholder/Sponsor (or delegate).

**Agenda:**
1. Progress update against milestones (10 min)
2. Risk register review — new, changed, or closed risks (10 min)
3. Blockers and escalations (5–10 min)
4. Upcoming decisions and asks (5 min)
5. Next week's focus areas (5 min)

**Outputs:**
- Updated risk register
- Decisions documented
- Weekly status update sent to stakeholders (use template in [Risk Management & Communication](./octoacme-risks-and-communication.md))

---

## Release Readiness Review

**Purpose:** Confirm that all criteria are met for a safe release before deployment begins.

**Attendees:** Project Manager, Product Manager, QA Lead, DevOps Engineer, Customer Support/Success, Developers (as needed).

**Agenda:**
1. Release scope recap — features, fixes, and known exclusions (5 min)
2. QA sign-off — test results, outstanding defects, QA Lead confirmation (15 min)
3. Deployment plan review — steps, rollback procedure (DevOps Engineer) (10 min)
4. Release notes review — accuracy and completeness (5 min)
5. Customer/support readiness — Customer Support/Success confirms readiness to handle queries (5 min)
6. Go / No-Go decision (5 min)
7. Deployment window and communication plan confirmed (5 min)

**Outputs:**
- Go / No-Go decision recorded
- Deployment checklist completed (see [Release & Deployment](./octoacme-release-and-deployment.md))
- Release notes approved
- Stakeholder communication scheduled

---

## Retrospective

**Purpose:** Reflect on what went well and what can be improved; generate concrete action items.

**Attendees:** Project Manager, Product Manager, Developers, QA Lead, UX/UI Designer, DevOps Engineer, Business Analyst, Customer Support/Success (all active team members).

**Agenda:**
1. Welcome and recap of the sprint/milestone (5 min)
2. What went well — gather and group ideas (10–15 min)
3. What could be improved — gather and group ideas (10–15 min)
4. Dot voting to prioritize top areas (5 min)
5. Action item definition — owner, due date, success criteria (10–15 min)
6. Follow-up on previous retro action items (5–10 min)
7. Wrap-up and appreciation (5 min)

**Outputs:**
- Retrospective notes documented and shared
- 2–3 prioritized action items with owners and due dates
- Action items added to the backlog or issues (see [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md))

---

## Related Docs
- [Roles & Personas](./octoacme-roles-and-personas.md) — attendee role definitions
- [RACI Matrix](./octoacme-raci-matrix.md) — meeting facilitation accountability
- [Definition of Ready & Done](./octoacme-definition-of-ready-and-done.md) — used in sprint planning
- [Project Initiation](./octoacme-project-initiation.md) — kickoff prerequisites
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — daily and weekly rhythm
- [Release & Deployment](./octoacme-release-and-deployment.md) — release readiness checklist
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — retro structure and action items
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — weekly status template
