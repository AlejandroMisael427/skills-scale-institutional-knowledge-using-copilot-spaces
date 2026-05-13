# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management knowledge base. This directory contains comprehensive guides for running projects at OctoAcme, from initiation through retrospective and continuous improvement.

## Quick Start

- **New to OctoAcme projects?** Start with the [Project Management Overview](./octoacme-project-management-overview.md)
- **Leading a new project?** Follow the [Project Initiation Guide](./octoacme-project-initiation.md)
- **Need a process overview?** Jump to [OctoAcme Project Management Summary](#octoacme-project-management-summary) below

---

## OctoAcme Project Management Summary

### Overview and Core Principles

OctoAcme follows a structured, lifecycle-based approach to project management that emphasizes customer value, iterative delivery, and clear ownership. The methodology is built on five key phases: Initiation, Planning, Execution, Release, and Retrospective. At its foundation, OctoAcme operates with three core roles—Project Manager (PM), Product Manager (PdM), and Development Team—each with distinct responsibilities. The PM coordinates delivery and manages risks, the PdM defines outcomes and prioritizes work, while developers implement features collaboratively. This role clarity, combined with data-informed decision-making and psychological safety, ensures projects remain aligned with business objectives while maintaining team morale and engagement.

### Project Lifecycle and Execution Workflows

Projects begin with an Initiation phase where teams validate business need through a lightweight Project One-pager that captures the problem statement, success metrics, stakeholders, and initial timeline. Once approved, teams move into Planning, where work is broken into shippable increments with clear acceptance criteria, dependencies are identified, and a Definition of Done is established. During Execution, teams follow a structured workflow using GitHub Projects with columns spanning Backlog through Done, supported by small PRs (≤400 lines), automated CI/CD checks, and regular demos. Execution is maintained through a consistent team rhythm: daily standups (15 min), weekly delivery syncs, and sprint/iteration planning sessions. Quality assurance is embedded throughout with unit tests, integration tests, security scanning in CI, and manual QA for feature acceptance when needed.

### Risk Management and Communication Strategy

OctoAcme centralizes risk and dependency tracking through a Risk Register maintained across all project phases, with items assessed by impact, likelihood, owner, and mitigation plan. Risks are escalated through a three-level model: team-level triage in standups, PM escalation to Product Lead and dependent teams, and sponsor-level escalation for business-impacting issues. Communication is standardized through multiple channels: weekly PM-PdM syncs, twice-weekly team standups, and monthly stakeholder updates using consistent templates for status, blockers, and decisions needed. This multi-layered approach ensures transparency, reduces surprises, and keeps stakeholders aligned throughout the project lifecycle.

### Release, Learning, and Continuous Improvement

Before release, teams verify all acceptance criteria are met, pass CI and security scans, prepare release notes and rollback plans, and conduct smoke testing. Deployments are staged and may include coordinated windows; post-deployment verification and stakeholder announcements follow. After each sprint, release, or milestone, the team conducts a retrospective (45–75 minutes) to capture what went well, identify improvements, and assign 2–3 prioritized action items with clear owners and due dates. These improvements are tracked back into the project backlog, creating a feedback loop that drives continuous refinement of both product and process. This emphasis on learning, measurement, and iterative enhancement helps OctoAcme teams reduce risk, accelerate delivery cycles, and build sustainable, high-performing delivery capabilities.

---

## Project Management Process Guide

### Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named Project Manager and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

### Project Lifecycle

Our standard project lifecycle consists of five phases:

1. **[Initiation](./octoacme-project-initiation.md)** - Validate the business need, align stakeholders, and create a lightweight plan
2. **[Planning](./octoacme-project-planning.md)** - Turn an approved initiative into an actionable plan and backlog
3. **[Execution & Tracking](./octoacme-execution-and-tracking.md)** - Manage day-to-day execution and track progress toward milestones
4. **[Release & Deployment](./octoacme-release-and-deployment.md)** - Standardize releases to production and reduce risk
5. **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** - Capture learnings and convert them into actionable improvements

### Cross-Cutting Guides

- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** - Identify, manage, and communicate risks and dependencies across all phases
- **[Roles and Personas](./octoacme-roles-and-personas.md)** - Understand responsibilities and communication patterns for key project roles

## Key Artifacts

- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items

## Communication Cadence

- Weekly sync between PM + Product Manager
- Twice-weekly standups for delivery team (or as agreed)
- Monthly stakeholder updates
- Ad-hoc escalations as needed

## How to Use These Docs

- Keep your Project Charter updated in your project repo
- Reference process-specific docs to guide your project decisions
- Add project-specific process docs into `.copilot/` if you want Copilot Spaces to use them as additional context
- Share relevant sections with your team and stakeholders
- Use the process documents as templates for your own project management artifacts
