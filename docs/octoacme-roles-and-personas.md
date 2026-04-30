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

## UX Designer

### Role Summary
UX Designers are responsible for understanding user needs, designing intuitive interfaces, and validating usability. They bridge the gap between user research and engineering implementation.

### Responsibilities
- Conduct user research, interviews, and usability testing
- Create wireframes, mockups, and interactive prototypes
- Define user flows and information architecture
- Collaborate with Product Managers to translate requirements into design specs
- Deliver design assets and annotated specs to Developers for implementation
- Participate in acceptance testing to validate usability against the Definition of Done

### Goals
- Ensure product usability and accessibility meet user expectations
- Reduce rework by clarifying design intent before development begins
- Advocate for the end user throughout the project lifecycle

### Typical Communication
- Design reviews and prototype walkthroughs with PM and Developers
- Usability test reports shared with Product Manager and stakeholders
- Design handoff notes and annotated specs in project tooling

### How they interact with existing roles
- **Product Manager (PdM):** Collaborates on requirements and success metrics; receives prioritized user stories and returns design specs and usability findings.
- **Developers:** Provides implementation-ready design assets; participates in design-review PRs and answers implementation questions.
- **Project Manager (PM):** Coordinates design milestones and flags usability risks in the risk register.
- **QA/Testing:** Supports usability acceptance criteria as part of the Definition of Done.

---

## Scrum Master

### Role Summary
Scrum Masters facilitate agile ceremonies, remove impediments, and coach the team on agile best practices. They protect the team's focus and promote continuous improvement.

### Responsibilities
- Facilitate daily standups, sprint planning, sprint reviews, and retrospectives
- Identify and remove blockers escalating as needed via the risk escalation path
- Track team health metrics (velocity, cycle time, impediment log)
- Coach the team on agile principles and practices
- Shield the team from unplanned interruptions during a sprint
- Maintain the sprint board and ensure cards move correctly through Backlog → Ready → In Progress → In Review → QA → Done

### Goals
- Maximize team throughput and predictability
- Foster a culture of continuous improvement and psychological safety
- Keep ceremonies effective and time-boxed

### Typical Communication
- Daily standups and sprint cadence facilitation
- Retrospective action items and improvement tracking
- Impediment log updates shared with Project Manager

### How they interact with existing roles
- **Project Manager (PM):** Partners on planning cadence and escalation; shares impediment log and team health metrics.
- **Product Manager (PdM):** Coordinates backlog refinement and sprint goal alignment.
- **Developers:** Removes blockers and coaches on agile practices; ensures sprint commitments are realistic.
- **Stakeholders:** Facilitates sprint reviews and demos; helps manage expectations around scope changes.

---

## Business Analyst

### Role Summary
Business Analysts analyze business needs, elicit requirements, and translate them into actionable work items. They serve as a bridge between stakeholders and the delivery team.

### Responsibilities
- Conduct stakeholder interviews and workshops to elicit requirements
- Document business processes, use cases, and acceptance criteria
- Decompose epics into user stories with clear acceptance criteria
- Maintain requirements traceability from business need to implemented feature
- Support Product Manager in backlog grooming and prioritization
- Validate that delivered features meet documented business requirements

### Goals
- Reduce ambiguity in requirements before development begins
- Ensure delivered solutions align with business objectives
- Maintain a traceable, up-to-date requirements baseline

### Typical Communication
- Requirements documents and user story write-ups shared with PM, PdM, and Developers
- Traceability matrices and change-impact assessments
- Participation in sprint planning and backlog refinement sessions

### How they interact with existing roles
- **Product Manager (PdM):** Collaborates on requirement definition and backlog prioritization; supports roadmap analysis.
- **Project Manager (PM):** Provides scope documentation to support planning, scheduling, and risk identification.
- **Developers:** Clarifies requirements during development; reviews implementation against acceptance criteria.
- **Customer / End User:** Gathers input through interviews and feedback sessions to ground requirements in real need.

---

## Customer / End User

### Role Summary
Customers and End Users are the intended recipients of the product. Their feedback validates that the team is building the right thing and drives continuous improvement cycles.

### Responsibilities
- Participate in user research sessions, interviews, and usability tests
- Provide feedback on prototypes, betas, and released features
- Engage in user acceptance testing (UAT) to confirm features meet real-world needs
- Communicate pain points and feature requests to the Product Manager or Business Analyst

### Goals
- Receive a product that solves real problems effectively and with minimal friction
- Feel heard and represented throughout the development process

### Typical Communication
- Feedback surveys and usability test sessions organized by UX Designer or Product Manager
- Beta and UAT participation coordinated by the Project Manager
- Release notes reviewed to understand what changed

### How they interact with existing roles
- **Product Manager (PdM):** Primary feedback channel; inputs shape prioritization and roadmap decisions.
- **UX Designer:** Participates in research and usability tests; provides direct usability signal.
- **Business Analyst:** Contributes to requirements elicitation; validates that documented needs reflect real-world usage.
- **QA/Testing:** Participates in UAT to confirm acceptance criteria from an end-user perspective.

---

## Technical Writer

### Role Summary
Technical Writers create and maintain clear, accurate documentation for users, developers, and internal teams. They ensure knowledge is captured and accessible as features ship.

### Responsibilities
- Draft, review, and publish user-facing documentation (user guides, help articles, FAQs)
- Maintain internal developer documentation (API references, architecture notes, runbooks)
- Update documentation in lockstep with releases following the release checklist
- Work with Developers and Product Manager to understand features before writing
- Review draft release notes for clarity and completeness
- Identify documentation gaps and raise them as tracked work items

### Goals
- Ensure every shipped feature has accurate, discoverable documentation
- Reduce support burden by providing clear self-service resources
- Maintain documentation as a first-class artifact alongside code

### Typical Communication
- Documentation drafts shared with Developers and Product Manager for accuracy review
- Release notes contributions coordinated with the Project Manager's release checklist
- Documentation status included in weekly status updates when relevant

### How they interact with existing roles
- **Developers:** Receives feature walkthroughs and reviews code/API changes to produce accurate documentation; participates in PR reviews for doc strings and inline docs.
- **Product Manager (PdM):** Aligns on feature intent and user-facing messaging; reviews documentation for correctness against acceptance criteria.
- **Project Manager (PM):** Coordinates documentation milestones in the release checklist; flags documentation risks.
- **QA/Testing:** Validates documentation accuracy against tested behavior; ensures release notes reflect actual changes.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See [Role Interaction & RACI-lite Reference](octoacme-role-interaction-raci.md) for a quick reference on who does what across lifecycle phases and a role-handoff checklist.

