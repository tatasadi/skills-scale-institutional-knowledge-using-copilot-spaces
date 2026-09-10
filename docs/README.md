# OctoAcme Project Management Process Docs

Welcome to the OctoAcme Project Management documentation hub. These guides standardize how we initiate, plan, execute, and close projects to ensure consistent delivery of customer value.

## Quick Links to Process Docs

- [Project Management Overview](./octoacme-project-management-overview.md) — High-level introduction to our approach, roles, and artifacts
- [Project Initiation Guide](./octoacme-project-initiation.md) — Steps to validate ideas, align stakeholders, and authorize work
- [Project Planning](./octoacme-project-planning.md) — Break work into shippable increments and create actionable plans
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Day-to-day delivery, standups, and progress tracking
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — Risk registers, escalation paths, and stakeholder updates
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) — Standardized release process and rollback procedures
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and drive improvements
- [Roles & Personas](./octoacme-roles-and-personas.md) — Definitions of key roles and responsibilities

## Project Lifecycle

Our projects follow a structured lifecycle:

1. **Initiation** — Validate business need, confirm stakeholders, define success criteria
2. **Planning** — Break down work, estimate scope, identify dependencies
3. **Execution** — Build, test, review, iterate with daily standups and regular demos
4. **Release** — Deploy to production with smoke tests and rollback procedures
5. **Close & Retrospective** — Capture learnings and incorporate improvements

## OctoAcme Project Management Overview

OctoAcme follows a structured project lifecycle grounded in five core principles: **customer-first**, **iterative delivery**, **clear ownership**, **data-informed decisions**, and **psychological safety**. Our approach moves projects through five distinct phases—Initiation, Planning, Execution, Release, and Close & Retrospective—ensuring alignment before significant effort is invested and maintaining transparency throughout delivery.

### Key Workflows & Roles

Our project structure defines four primary personas who collaborate throughout the lifecycle:

- **Project Managers** coordinate schedules, manage risks and dependencies, facilitate meetings, and maintain project documentation and status reporting
- **Product Managers** define outcomes, prioritize the backlog, validate solutions, and measure success metrics
- **Developers** implement features, write and maintain tests, participate in reviews, and help identify technical risks
- **QA/Testing teams** validate acceptance criteria and quality standards

Communication happens through a regular cadence: twice-weekly standups for delivery teams, weekly syncs between PM and Product Manager, and monthly stakeholder updates. Risks and blockers follow a three-level escalation path from team triage through PM escalation to sponsor involvement, ensuring rapid resolution.

### Quality Assurance & Execution

During execution, teams maintain strict pull request discipline with small PRs (≤400 lines), clear issue links and acceptance criteria, and mandatory CI testing before review. Quality is enforced through unit tests, integration tests, smoke tests for critical flows, and security scanning. The team tracks velocity and burndown, monitors success metrics from the Project One-pager, and holds demos at sprint or milestone completion.

Releases are gated by comprehensive pre-deployment checklists verifying acceptance criteria are met, CI passes, security scans complete, and rollback plans are documented. Teams use GitHub Projects with standard columns (Backlog, Ready, In Progress, In Review, QA, Done) to maintain visibility and flow.

### Continuous Improvement

After each sprint, release, or milestone, OctoAcme conducts retrospectives (45–75 minutes) to capture what went well, what could improve, and generate actionable items with assigned owners and due dates. These improvements feed back into the project backlog and are tracked in weekly PM syncs. The organization maintains living documentation in the repository to accelerate onboarding, reduce single-person dependency, and enable consistent, repeatable project execution across all cross-functional initiatives.

## For New Team Members

Start with [Project Management Overview](./octoacme-project-management-overview.md) to understand our principles, core roles, and key artifacts.

Then, follow the lifecycle links above based on which phase your project is in:

- **Just starting out?** Begin with [Project Initiation Guide](./octoacme-project-initiation.md)
- **Ready to plan?** Move to [Project Planning](./octoacme-project-planning.md)
- **In active development?** Reference [Execution & Tracking](./octoacme-execution-and-tracking.md) and [Risk Management & Communication](./octoacme-risks-and-communication.md)
- **Preparing to ship?** Review [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- **Wrapping up?** Complete [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)

For questions about team structure and responsibilities, see [Roles & Personas](./octoacme-roles-and-personas.md).

---

**Last Updated:** September 2026

For questions or suggestions on these processes, please [open an issue](https://github.com/tatasadi/skills-scale-institutional-knowledge-using-copilot-spaces/issues) with the `documentation` and `process improvement` labels.
