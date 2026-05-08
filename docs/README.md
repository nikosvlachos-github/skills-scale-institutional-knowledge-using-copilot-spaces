# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management Documentation hub. This folder contains comprehensive guidance for how OctoAcme runs projects, defines roles, manages risks, and delivers value to customers.

## OctoAcme Project Management Approach

OctoAcme follows a **customer-first, iterative delivery model** with clear ownership, data-informed decisions, and a strong commitment to psychological safety and continuous learning. Our approach is structured around a five-phase project lifecycle and emphasizes collaboration across cross-functional teams.

### Core Principles

- **Customer-first**: Prioritize customer value and usability in all decisions
- **Iterative delivery**: Deliver small, testable increments rather than monolithic releases
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead with defined responsibilities
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback, learning, and transparent communication

### Organizational Roles

OctoAcme operates through four primary personas with distinct responsibilities:

- **Developers**: Design, build, and test software components; maintain high test coverage; reduce cycle time to production; collaborate on design reviews
- **Product Managers**: Define product vision and success metrics; prioritize backlogs; validate solutions through research and data; drive customer value
- **Project Managers**: Coordinate delivery activities; manage schedules, risks, and dependencies; facilitate meetings; ensure transparency across stakeholders
- **QA/Testing**: Validate quality and acceptance criteria; conduct manual and automated testing; ensure reliability before release

### Project Lifecycle

OctoAcme projects follow a structured five-phase lifecycle:

1. **Initiation**: Define problem statement, identify stakeholders, establish high-level timeline
2. **Planning**: Scope work, allocate resources, map milestones, identify dependencies
3. **Execution**: Build features, run tests, conduct reviews, iterate based on feedback
4. **Release**: Deploy to production, verify functionality, communicate changes
5. **Close & Retrospective**: Capture learnings, document improvements, plan next iterations

### Communication Strategy

- **Weekly PM + PdM sync**: Alignment between project and product leadership
- **Twice-weekly delivery standups**: 15-minute daily standups focused on progress, blockers, and dependencies
- **Weekly delivery sync**: Show progress, updates, and flagged risks
- **Monthly stakeholder updates**: High-level status for sponsors and external stakeholders
- **Milestone-based demos**: Review completed work with stakeholders and gather feedback
- **Ad-hoc escalations**: Clear escalation paths (Team → PM → Product Lead → Sponsor)

### Quality Assurance & Execution Practices

- **Rigorous testing**: Unit tests, integration tests, end-to-end smoke tests, and security scanning in CI
- **Code review discipline**: Small pull requests (≤ 400 lines), require automated tests, mandate approvals before merging
- **Structured workflows**: GitHub Projects with standardized columns (Backlog → Ready → In Progress → In Review → QA → Done)
- **Risk management**: Maintain Risk Register, identify/assess/mitigate/monitor risks throughout execution
- **Progress tracking**: Monitor velocity, burndown, and key success metrics identified in project one-pagers

---

## Documentation Guide

Below is a complete index of all project management documentation. Start with the **Project Management Overview** for a high-level introduction, then explore topic-specific guides based on your role and project phase.

### Getting Started

- **[Project Management Overview](octoacme-project-management-overview.md)** — Start here for an introduction to OctoAcme's approach, core roles, key artifacts, and communication cadence

### By Project Phase

- **[Project Initiation](octoacme-project-initiation.md)** — Guidance for defining problem statements, identifying stakeholders, and establishing project scope
- **[Project Planning](octoacme-project-planning.md)** — How to break work into shippable increments, create backlogs, identify dependencies, and define the Definition of Done
- **[Execution and Tracking](octoacme-execution-and-tracking.md)** — Day-to-day execution, team rhythms (standups, syncs, demos), PR workflows, and progress reporting
- **[Release and Deployment](octoacme-release-and-deployment.md)** — Preparing for production release, deployment strategies, and go-live activities
- **[Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Post-release retrospectives, capturing learnings, and iterating on processes

### Cross-Cutting Topics

- **[Risks and Communication](octoacme-risks-and-communication.md)** — Risk identification and mitigation, communication templates, stakeholder updates, and escalation paths
- **[Roles and Personas](octoacme-roles-and-personas.md)** — Detailed persona definitions, responsibilities, goals, and typical communication patterns

---

## How to Use These Docs

1. **New to OctoAcme PM processes?** Start with [Project Management Overview](octoacme-project-management-overview.md) and [Roles and Personas](octoacme-roles-and-personas.md)
2. **Starting a new project?** Follow the phased guides: Initiation → Planning → Execution → Release → Retrospective
3. **Need guidance on a specific topic?** Use the index above to jump to the relevant doc
4. **Tailoring for your project?** Keep a Project Charter in your project repo; reference these docs as templates
5. **Using Copilot Spaces?** Add process-specific docs to `.copilot/` if you want Copilot to use them as context for guidance

---

## Contributing & Feedback

These docs are living documentation that evolve with OctoAcme's practices. If you have feedback, questions, or suggestions for improvements, please open an issue or pull request in this repository.

---

**Last Updated**: May 2026  
**Maintained by**: OctoAcme Project Management Team
