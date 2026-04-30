# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management Documentation hub. This README summarizes OctoAcme's project management processes and links to all detailed process guides.

## Overview of Project Management Processes

OctoAcme follows a lightweight, repeatable delivery lifecycle that emphasizes customer value, iterative delivery, and clear ownership. Work progresses through five phases: **Initiation** (clarify the problem, goals, success metrics, stakeholders, and an initial timeline), **Planning** (turn an approved initiative into an actionable backlog and release plan), **Execution** (deliver in small, testable increments with ongoing tracking and a team board moving cards through Backlog → Ready → In Progress → In Review → QA → Done), **Release** (deploy with risk controls, staging verification, and post-deploy validation), and **Close/Retrospective** (capture learnings and convert them into tracked improvement actions). Key artifacts—project charter, backlog with acceptance criteria, Definition of Done, risk register, and retrospective action items—are kept current and visible throughout all phases.

Roles and personas are explicitly defined to prevent ambiguity and ensure single-threaded ownership. The **Project Manager (PM)** coordinates delivery mechanics—planning, schedules, risks, and cross-team communication—while the **Product Manager (PdM)** defines outcomes, prioritizes the backlog, and measures success. **Developers** implement and test features, collaborate on design and estimation, and surface technical risks early. **QA/Testing** validates quality and acceptance criteria at each increment. **Stakeholders** contribute inputs and approvals at key decision points, with a named PM and Product Lead providing accountable leadership throughout.

Communication and risk management are anchored by a consistent team rhythm and structured escalation. Teams hold daily standups focused on progress and blockers, weekly delivery syncs to surface risks and dependencies, and demos at sprint or milestone boundaries. Stakeholder updates follow a standard weekly status template covering progress, next steps, risks/blockers, and decisions needed. Risks and dependencies are tracked in a simple risk register (impact, likelihood, owner, mitigation, status), with a clear escalation path: team triage first, then PM escalation to the Product Lead and dependent teams, and finally sponsor-level escalation for business-impacting issues.

Quality assurance is built into both day-to-day development and release practices. Developers are expected to keep PRs small, link them to issues and acceptance criteria, and ensure automated tests and linting pass in CI before requesting review—at least one approval is required before merge. The testing strategy calls for unit tests for new logic, integration tests where relevant, end-to-end smoke tests for critical flows, and security scanning in CI. Releases follow a standardized checklist: confirm acceptance criteria and CI/security checks pass, draft release notes, document rollback plans, validate in staging, verify post-deploy, and communicate outcomes. Incidents trigger an immediate rollback and a blameless retrospective with tracked action items.

## Process Documentation

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risks & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)
