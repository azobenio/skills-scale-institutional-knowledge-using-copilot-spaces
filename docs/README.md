# OctoAcme Project Management Docs

## Welcome

Welcome to the central hub for OctoAcme's project management processes. These guides define how we start, plan, deliver, and improve projects with repeatable success. The approach emphasizes clear roles, iterative delivery, risk management, and continuous improvement.

---

## Process Overview

OctoAcme follows a structured five-phase project lifecycle designed to deliver customer value consistently and predictably.

### Project Lifecycle & Core Workflows

OctoAcme's project lifecycle consists of five phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. During initiation, teams validate business needs by creating a lightweight Project One-pager that captures the problem statement, success metrics, stakeholders, and resource requirements. Once approved, the planning phase breaks work into shippable increments with prioritized backlogs, acceptance criteria, and a Definition of Done. Execution leverages agile practices including daily standups (15 minutes), weekly delivery syncs, and GitHub Projects for workflow management with columns for Backlog, Ready, In Progress, In Review, QA, and Done. All work flows through pull requests (kept to ≤400 lines when possible) that require automated CI testing, linting, and at least one approval before merging. Finally, releases are standardized with pre-deployment checklists, smoke tests, and documented rollback plans, followed by retrospectives to capture learnings and drive continuous improvement.

### Roles & Clear Ownership

OctoAcme emphasizes **clear ownership** through defined personas: **Project Managers** coordinate schedules, risks, and communications; **Product Managers** define outcomes, prioritize the backlog, and measure success; **Developers** implement features and collaborate on design and testability; and **QA/Testing** validates quality and acceptance criteria. Each project has a named PM and Product Lead, supported by a weekly PM/PdM sync and twice-weekly standups for delivery teams. This role clarity reduces confusion and ensures accountability across cross-functional initiatives.

### Risk Management & Stakeholder Communication

OctoAcme uses a formal **Risk Register** (tracking ID, description, impact, likelihood, owner, and mitigation plan) reviewed at weekly syncs to proactively address threats. Risk escalation follows a tiered approach: Level 1 (team triage in standups), Level 2 (PM escalates to Product Lead and dependent teams), and Level 3 (sponsor-level escalation for business-impacting issues). Stakeholder communication is standardized through weekly status templates covering progress, next steps, risks/blockers, and decisions needed, along with consistent use of project documentation as a single source of truth.

### Quality Assurance & Continuous Improvement

Quality is built into execution through unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, and security scanning in CI. Manual QA validates feature acceptance when needed. Beyond deployment, OctoAcme institutionalizes learning through post-sprint retrospectives (45–75 minutes) using structured formats (what went well, what could improve, action items with owners and due dates) and tracks improvements in the project backlog. This commitment to measurement, iteration, and **psychological safety** creates a culture where small, data-driven changes compound into sustainable process improvements and predictable delivery.

---

## Process Documents

Navigate to each process document for detailed workflows, templates, and checklists:

- **[Project Management Overview](octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's approach, principles, core roles, and key artifacts.

- **[Project Initiation Guide](octoacme-project-initiation.md)** — Initial steps to validate and authorize work, align stakeholders, and create a lightweight plan.

- **[Project Planning](octoacme-project-planning.md)** — Turn an approved initiative into an actionable plan and backlog for delivery.

- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Guidance for managing day-to-day execution and tracking progress toward project milestones.

- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — How to identify, manage, and communicate risks and dependencies.

- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Standardized processes for releasing features to production with reduced risk and improved observability.

- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and convert them into actionable improvements.

- **[Roles & Personas](octoacme-roles-and-personas.md)** — Definitions of typical roles and responsibilities used in OctoAcme projects.

---

## Key Principles

- **Customer-first:** Prioritize customer value and usability.
- **Iterative delivery:** Deliver small, testable increments.
- **Clear ownership:** Each project has a named Project Manager and Product Lead.
- **Data-informed decisions:** Measure impact and iterate based on evidence.
- **Psychological safety:** Encourage feedback and learning.

---

## Getting Started

1. **New to OctoAcme?** Start with the [Project Management Overview](octoacme-project-management-overview.md).
2. **Starting a new project?** Follow the [Project Initiation Guide](octoacme-project-initiation.md).
3. **In execution mode?** Reference [Execution & Tracking](octoacme-execution-and-tracking.md) and [Risk Management & Communication](octoacme-risks-and-communication.md).
4. **Preparing a release?** Check the [Release & Deployment Guide](octoacme-release-and-deployment.md).
5. **Wrapping up?** Schedule a [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) session.

For questions or process improvements, open an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.
