# OctoAcme — RACI Responsibility Matrix

## Purpose
Provide a lightweight RACI (Responsible, Accountable, Consulted, Informed) reference so every team member knows who owns each key activity or artifact across the project lifecycle.

**Key:**
- **R** — Responsible: does the work
- **A** — Accountable: final decision-maker / sign-off owner (one per row)
- **C** — Consulted: provides input before the activity is complete
- **I** — Informed: notified of outcomes

For role definitions, see [Roles & Personas](./octoacme-roles-and-personas.md).

---

## RACI Matrix

| Activity / Artifact | Project Manager | Product Manager | Developer | QA Lead | UX/UI Designer | DevOps Engineer | Business Analyst | Customer Support/Success | Stakeholder/Sponsor |
|---|---|---|---|---|---|---|---|---|---|
| **Initiation** | | | | | | | | | |
| One-pager / Charter | R | A | C | — | — | — | C | — | I |
| Stakeholder alignment & sign-off | R | C | — | — | — | — | C | — | A |
| Initial risk list | A | C | C | — | — | C | C | — | I |
| **Planning** | | | | | | | | | |
| Backlog & acceptance criteria | C | A | C | C | C | — | R | C | I |
| Definition of Ready / Definition of Done | A | C | R | R | C | C | C | — | — |
| Test plan / QA approach | C | C | C | A | — | C | — | I | — |
| Release plan & milestones | A | C | C | C | — | C | — | — | I |
| **Execution & Tracking** | | | | | | | | | |
| Sprint / iteration execution | I | C | R | C | R | C | C | — | — |
| PR reviews & code quality | I | — | A | C | — | C | — | — | — |
| Risk register updates | A | C | C | C | — | C | C | — | I |
| Stakeholder status updates | R | C | — | — | — | — | — | C | A |
| **Release & Deployment** | | | | | | | | | |
| Release notes | R | C | C | C | — | — | — | C | I |
| Release readiness sign-off | A | C | C | R | — | C | — | C | I |
| Deployment execution | I | — | C | C | — | R | — | — | I |
| Incident / rollback decision | A | C | C | C | — | R | — | I | I |
| **Retrospective** | | | | | | | | | |
| Retro facilitation | R | C | C | C | C | C | C | C | — |
| Action item ownership assignment | A | C | R | R | R | R | R | R | — |
| Action item tracking & follow-up | R | C | C | C | C | C | C | C | I |

---

## Notes
- A single role holds **A** (Accountable) per row. When multiple roles share **R**, they collaborate on execution.
- Stakeholder/Sponsor participation should be confirmed during [Project Initiation](./octoacme-project-initiation.md).
- Update this matrix at the start of each project if the team composition differs from the defaults above.

## Related Docs
- [Roles & Personas](./octoacme-roles-and-personas.md)
- [Project Initiation](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Release & Deployment](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
