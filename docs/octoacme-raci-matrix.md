# OctoAcme — RACI & Role Interaction Matrix

## Purpose
Provide a quick-reference ownership matrix so every team member knows exactly who is **R**esponsible, **A**ccountable, **C**onsulted, and **I**nformed for each key activity across the project lifecycle.

> **Key:** R = Responsible (does the work) · A = Accountable (owns the outcome) · C = Consulted (input required) · I = Informed (kept in the loop)

---

## Matrix

| Activity | Project Manager | Product Manager | Developer | Scrum Master | UX Designer | DevOps Engineer | Data Analyst | QA / Testing |
|---|---|---|---|---|---|---|---|---|
| **Initiation** | | | | | | | | |
| Problem statement & success metrics | C | A/R | I | I | C | I | C | I |
| Stakeholder identification & alignment | A/R | C | I | I | I | I | I | I |
| Initial risk list | A/R | C | C | C | I | C | I | I |
| Go / no-go decision | C | A | I | I | I | I | C | I |
| **Planning** | | | | | | | | |
| Backlog creation & prioritization | C | A/R | C | C | C | C | C | C |
| Sprint / iteration planning | C | C | R | A/R | C | C | I | C |
| Release plan & milestone map | A/R | C | C | C | I | C | I | I |
| Definition of Done | C | C | A/R | R | C | C | I | C |
| Design specification & wireframes | I | C | C | I | A/R | I | I | C |
| Environment & infrastructure plan | I | I | C | I | I | A/R | I | I |
| **Execution** | | | | | | | | |
| Feature implementation | I | I | A/R | I | C | C | I | C |
| Design implementation review | I | I | R | I | A | I | I | I |
| CI/CD pipeline & build health | I | I | C | I | I | A/R | I | I |
| Daily standup facilitation | I | I | C | A/R | I | I | I | C |
| Blocker escalation (team level) | C | C | R | A/R | I | C | I | I |
| Blocker escalation (PM+ level) | A/R | C | I | C | I | C | I | I |
| **Release** | | | | | | | | |
| Pre-release sign-off checklist | A/R | C | C | C | C | C | I | C |
| Deployment execution | I | I | C | I | I | A/R | I | I |
| Post-deploy verification | C | I | R | I | I | R | I | A/R |
| Release announcement | C | A/R | I | I | I | I | I | I |
| **Retrospective** | | | | | | | | |
| Retrospective facilitation | C | I | C | A/R | I | I | I | C |
| Metrics & outcome review | C | C | I | I | I | I | A/R | I |
| Action item ownership & tracking | A/R | C | C | C | C | C | C | C |
| **Risk & Escalation** | | | | | | | | |
| Risk register maintenance | A/R | C | C | C | I | C | C | I |
| Incident response | C | I | C | I | I | A/R | I | C |
| Security incident escalation | A/R | I | C | I | I | C | I | I |

---

## Notes
- A single cell can hold both A and R when one person both owns and performs the activity.
- Where a role is not listed in the matrix it has no standing involvement; they may still be looped in ad-hoc.
- This matrix is a guide, not a rigid rule. Teams should adapt it to their specific context at kickoff.

---

## Related Documents
- [Roles & Personas](./octoacme-roles-and-personas.md) — full descriptions of each role
- [Project Kickoff & Handoff Checklist](./octoacme-kickoff-and-handoff-checklist.md) — accountability checkpoints across phases
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
