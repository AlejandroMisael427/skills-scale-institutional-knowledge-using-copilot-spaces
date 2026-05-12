---
name: "Create OctoAcme Project Management Docs README"
description: "Create a comprehensive README for the OctoAcme Project Management Docs with links to all documentation"
title: "[Process Doc Update]: Create OctoAcme Project Management Docs README with process summary and links"
labels: ["documentation", "process improvement"]
---

## Process Document
<new document>

## Summary of New Content
Create a new README.md file in the docs/ folder that serves as the central entry point for all OctoAcme Project Management process documentation. The README should include:
- A brief overview of OctoAcme's project management approach
- The core principles that guide our project execution
- Links to all existing process documentation files
- A quick reference guide to help team members navigate the docs

## Why is this update needed?
Currently, the process documentation is scattered across individual markdown files in the docs/ folder. New team members and stakeholders need a clear, centralized entry point to understand OctoAcme's project management processes and quickly find relevant documentation. A README will:
- Accelerate onboarding for new team members
- Provide a unified overview of all project management processes
- Make it easier for stakeholders to find information
- Establish the docs/ folder as the authoritative source for process knowledge

## Suggested Content
```markdown
# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management knowledge base. This directory contains comprehensive guides for running projects at OctoAcme, from initiation through retrospective and continuous improvement.

## Quick Start
- New to OctoAcme projects? Start with the [Project Management Overview](./octoacme-project-management-overview.md)
- Leading a new project? Follow the [Project Initiation Guide](./octoacme-project-initiation.md)

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
```

## Acceptance Criteria
- [x] Content aligns with existing process docs
- [x] Update improves clarity or closes a documented gap
- [x] Proposed content has been reviewed with stakeholders (if needed)
