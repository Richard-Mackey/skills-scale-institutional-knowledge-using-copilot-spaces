# OctoAcme Project Management Docs

Welcome! This README provides an overview of OctoAcme's approach to project management and links to detailed process documentation.

## Project Management Approach (Summary)

OctoAcme follows a structured yet iterative approach to project delivery, grounded in these core principles:

- **Customer-first**: Prioritize customer value and usability in all decisions
- **Iterative delivery**: Deliver small, testable increments rather than large monolithic releases
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead with defined responsibilities
- **Data-informed decisions**: Measure impact and iterate based on evidence and metrics
- **Psychological safety**: Encourage feedback, learning, and continuous improvement

### Project Lifecycle

OctoAcme projects flow through five key phases:

1. **Initiation**: Problem statement, stakeholder alignment, high-level timeline
2. **Planning**: Scope definition, resource allocation, milestones, dependencies
3. **Execution**: Build, test, review, and iterate on deliverables
4. **Release**: Deploy, verify, and announce to stakeholders
5. **Close & Retrospective**: Capture learnings and identify improvements

### Core Roles

- **Project Manager (PM)**: Coordinates delivery, schedules, risk management, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes the backlog, and measures success
- **Developers**: Implement features, collaborate on design and testability
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs, approvals, and business context

### Communication Cadence

- **Daily standups** (15 min): Progress, blockers, dependencies
- **Weekly PM + PdM sync**: Alignment on priorities and risks
- **Twice-weekly delivery team standups**: As-needed execution updates
- **Monthly stakeholder updates**: Progress and milestone achievements
- **Ad-hoc escalations**: For blockers and urgent decisions

---

## Core Documents

### Starting a New Project
- **[Project Management Overview](octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's approach, roles, and key artifacts
- **[Project Initiation Guide](octoacme-project-initiation.md)** — Steps to validate business need, align stakeholders, and make a go/no-go decision

### Planning & Scoping
- **[Project Planning](octoacme-project-planning.md)** — How to break work into shippable increments, estimate scope, identify dependencies, and create a release plan

### Day-to-Day Execution
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Guidance on managing execution, using project boards, PR workflows, quality standards, and metrics

### Managing Risks & Staying Aligned
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — How to identify, assess, and mitigate risks; manage stakeholder communication; and escalate blockers

### Releasing & Deploying
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Release types, pre-release requirements, deployment checklists, rollback procedures, and release notes

### Learning & Improving
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — How to run retrospectives, track action items, and embed continuous improvement into team culture

### Understanding Roles
- **[Roles and Personas](octoacme-roles-and-personas.md)** — Detailed descriptions of typical roles, responsibilities, goals, and communication patterns

---

## Quick Reference: Checklists

### Project Initiation Checklist
- [ ] One-pager completed and reviewed by Product Lead
- [ ] Stakeholder alignment confirmed (email or meeting)
- [ ] Decision: Approve to move into planning?
- [ ] Create repo or project board skeleton
- [ ] Add initial artifacts to repo

### Project Planning Checklist
- [ ] Project kickoff held
- [ ] Backlog prioritized and estimated
- [ ] Release timeline and milestones agreed
- [ ] Definition of Done documented
- [ ] Initial test plan / QA approach drafted

### Execution Checklist
- [ ] Branching and PR conventions documented
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly

### Pre-Release Checklist
- [ ] All acceptance criteria met and PRs merged
- [ ] Passing CI and security scans
- [ ] Release notes drafted
- [ ] Rollback / mitigation plan documented
- [ ] Smoke tests prepared

---

## Using These Docs

### For New Team Members
1. Start with **[Project Management Overview](octoacme-project-management-overview.md)** to understand our approach
2. Review **[Roles and Personas](octoacme-roles-and-personas.md)** to understand your role and key responsibilities
3. Bookmark this README and the specific docs relevant to your role (PM, PdM, Dev, QA)

### For Project Managers
1. Use **[Project Initiation Guide](octoacme-project-initiation.md)** when starting a new project
2. Follow **[Project Planning](octoacme-project-planning.md)** to create your project plan
3. Reference **[Execution & Tracking](octoacme-execution-and-tracking.md)** and **[Risk Management & Communication](octoacme-risks-and-communication.md)** during execution
4. Use **[Release & Deployment Guide](octoacme-release-and-deployment.md)** for release activities
5. Facilitate **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** sessions at project milestones

### For Product Managers
1. Align on strategy using **[Project Management Overview](octoacme-project-management-overview.md)**
2. Define success criteria and validate customer need (covered in **[Project Initiation Guide](octoacme-project-initiation.md)**)
3. Prioritize the backlog and define acceptance criteria (covered in **[Project Planning](octoacme-project-planning.md)**)
4. Participate in execution and retrospectives to measure impact

### For Developers
1. Understand project structure using **[Roles and Personas](octoacme-roles-and-personas.md)**
2. Reference **[Execution & Tracking](octoacme-execution-and-tracking.md)** for PR workflows, testing standards, and CI requirements
3. Review **[Project Planning](octoacme-project-planning.md)** for acceptance criteria and Definition of Done

### For QA/Testing Teams
1. Review **[Execution & Tracking](octoacme-execution-and-tracking.md)** for quality standards and testing approach
2. Understand acceptance criteria and Definition of Done from **[Project Planning](octoacme-project-planning.md)**

---

## Key Templates & Artifacts

All process documents include templates and examples for:
- **Project One-pagers** (problem, goal, success metrics)
- **Backlog item templates** (title, description, acceptance criteria, priority, estimate)
- **Risk register** (ID, description, impact, likelihood, owner, mitigation)
- **Weekly status updates** (progress, next steps, risks, decisions needed)
- **Release notes** (name, summary, notable changes, migration steps)
- **Retrospective action items** (title, description, owner, due date, success criteria)

Refer to each document for detailed guidance and examples.

---

## Questions or Feedback?

If you have questions about these processes or suggestions for improvement:
1. Open an issue using the **[Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)** template
2. Or reach out to your Product Lead or Project Manager

---

**Last Updated**: June 10, 2026
