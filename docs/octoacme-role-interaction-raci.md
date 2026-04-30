# OctoAcme Role Interaction & RACI-lite Reference

This document provides a quick-reference view of how OctoAcme roles interact across the project lifecycle, and a lightweight checklist for key role handoffs. Use this alongside the full role definitions in [Roles & Personas](octoacme-roles-and-personas.md).

---

## Role Interaction Matrix (RACI-lite)

**Key:** R = Responsible (does the work) · A = Accountable (final say) · C = Consulted (provides input) · I = Informed (kept in the loop)

| Activity | PM (Project Mgr) | PdM (Product Mgr) | Developer | UX Designer | Scrum Master | Business Analyst | QA / Testing | Technical Writer | Customer / End User |
|---|---|---|---|---|---|---|---|---|---|
| Project Initiation & Charter | A/R | C | I | I | I | C | I | I | I |
| Requirements Elicitation | C | A | C | C | I | R | C | I | C |
| Backlog Grooming & Prioritization | C | A/R | C | C | C | R | C | I | I |
| Sprint Planning & Scheduling | A/R | C | C | C | R | C | I | I | I |
| UX Research & Design | I | C | C | A/R | I | C | I | I | C |
| Design Handoff to Dev | I | C | R | A | I | I | I | I | I |
| Feature Development | C | I | A/R | C | C | C | I | I | I |
| Code Review & PR Merge | I | I | A/R | I | I | I | C | I | I |
| QA & Acceptance Testing | C | C | C | C | I | C | A/R | C | C |
| User Acceptance Testing (UAT) | C | A | C | C | I | C | R | I | R |
| Documentation Updates | C | C | C | I | I | I | C | A/R | I |
| Weekly Status Update | A/R | C | I | I | I | I | I | I | I |
| Risk Identification & Escalation | A/R | C | C | C | C | C | C | I | I |
| Standup Facilitation | I | I | R | R | A/R | I | R | I | I |
| Sprint Retrospective | C | C | R | R | A/R | C | R | I | I |
| Release Readiness Checklist | A/R | C | R | C | C | C | R | R | I |
| Release Notes | C | A | C | I | I | I | C | R | I |
| Post-Deploy Validation | C | C | R | I | I | I | A/R | I | I |
| Continuous Improvement Actions | R | C | C | C | A/R | C | C | I | I |

---

## Lifecycle Phase: Who Owns What

### 1. Initiation
- **PM** creates the project charter and identifies stakeholders.
- **PdM** defines the problem statement, goals, and success metrics.
- **Business Analyst** supports stakeholder interviews and initial requirements gathering.
- **Scrum Master** ensures agile ceremonies are set up for the delivery team.

### 2. Planning
- **PM** owns the project plan, milestones, and risk register.
- **PdM** finalizes the prioritized backlog and roadmap.
- **Business Analyst** decomposes requirements into user stories with acceptance criteria.
- **UX Designer** produces initial wireframes and user flows for planned features.
- **Scrum Master** facilitates sprint planning and confirms team capacity.
- **Technical Writer** identifies documentation needs and schedules writing alongside development.

### 3. Execution
- **Developers** implement features; keep PRs small, linked to issues, and acceptance criteria.
- **UX Designer** supports design clarifications and participates in design-review PRs.
- **Scrum Master** facilitates daily standups and removes blockers.
- **Business Analyst** answers requirements questions and validates acceptance criteria.
- **QA/Testing** performs incremental testing and maintains test coverage per Definition of Done.
- **Technical Writer** drafts documentation in parallel with feature development.
- **PM** tracks progress, updates the risk register, and sends weekly status updates.

### 4. Release
- **PM** drives the release checklist and coordinates communication.
- **PdM** approves release readiness and signs off on release notes messaging.
- **Developers** confirm CI/security checks pass and deploy to staging.
- **QA/Testing** executes final acceptance and smoke tests.
- **Technical Writer** finalizes and publishes documentation and release notes.
- **Customer / End User** participates in UAT (if applicable).

### 5. Close & Retrospective
- **Scrum Master** facilitates the retrospective; captures improvement actions.
- **PM** closes open items, archives project artifacts, and updates the risk register.
- **PdM** reviews outcome metrics against success criteria.
- **Business Analyst** closes requirements traceability and notes any deferred items.

---

## Role Handoff Checklists

Use these checklists to reduce gaps and miscommunication at key handoff points.

### UX Design → Development Handoff
- [ ] Finalized design files and assets shared in agreed tooling (e.g., Figma, Zeplin)
- [ ] All user flows and edge cases annotated in the design spec
- [ ] Acceptance criteria updated to include usability and accessibility requirements
- [ ] Design reviewed and questions answered before sprint begins
- [ ] Developer confirms they can implement the design within sprint scope

### Requirements → Development Handoff (Business Analyst → Developers)
- [ ] User stories written with clear acceptance criteria (Definition of Done-aligned)
- [ ] Edge cases and error states documented
- [ ] Dependencies and external integrations identified
- [ ] Stories sized and placed in the sprint backlog by the Scrum Master / PM
- [ ] Business Analyst available during sprint for clarification questions

### Development → QA Handoff
- [ ] Feature branch merged and CI checks pass
- [ ] PR linked to issue and acceptance criteria
- [ ] Developer has manually verified the happy-path locally
- [ ] Test environment updated and deployment notes shared with QA
- [ ] Known limitations or deferred items noted in the issue

### QA → Release Handoff
- [ ] All acceptance criteria verified and signed off by QA
- [ ] Regression tests passed
- [ ] Release notes drafted and reviewed by Technical Writer and PdM
- [ ] Rollback plan documented
- [ ] PM has confirmed release readiness with all stakeholders

### Release → Documentation (Technical Writer Handoff)
- [ ] Final feature behavior confirmed by Developers and QA
- [ ] Documentation drafted, reviewed, and approved by PdM
- [ ] Release notes finalized and linked to the release artifact
- [ ] Internal runbooks / API docs updated if applicable
- [ ] Documentation published alongside or before the release

---

## Communication Quick Reference

| Cadence | Owner | Participants | Purpose |
|---|---|---|---|
| Daily Standup | Scrum Master | Developers, QA/Testing, UX Designer, Business Analyst, Technical Writer | Surface blockers, progress, plan for the day |
| Weekly Status Update | PM | Stakeholders, PdM, Team Leads | Progress, risks, decisions needed |
| Sprint Planning | Scrum Master / PM | Full delivery team | Commit sprint scope and goals |
| Backlog Refinement | PdM / BA | Developers, UX, QA | Groom and size upcoming stories |
| Sprint Review / Demo | Scrum Master | Team + Stakeholders + Customers | Demonstrate completed work, gather feedback |
| Sprint Retrospective | Scrum Master | Full delivery team | Identify improvements; log action items |
| Risk Escalation | PM | PdM, Sponsor (if needed) | Escalate blockers beyond team resolution |
| Release Readiness | PM | PM, PdM, QA, Dev Lead, TW | Final go/no-go for release |

---

*This document supplements [Roles & Personas](octoacme-roles-and-personas.md) and should be updated when new roles are added or process changes affect handoffs.*
