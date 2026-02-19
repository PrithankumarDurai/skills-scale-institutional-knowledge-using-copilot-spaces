# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management process documentation! This guide provides an overview of how we run projects and serves as a starting point for exploring our detailed process documents.

## Purpose

This documentation centralizes our project management knowledge and processes to help team members:
- Quickly understand how OctoAcme runs projects
- Navigate our roles, workflows, and key artifacts
- Use Copilot Spaces with institutional knowledge for role-specific guidance
- Maintain consistency across cross-functional teams

These documents are designed to work with **GitHub Copilot Spaces** to provide contextual, role-aware assistance. Add relevant process docs to your `.copilot/` directory to enable Copilot to use them as context.

## Guiding Principles

Our project work is guided by five core principles:

1. **Customer-first**: Prioritize customer value and usability in all decisions
2. **Iterative delivery**: Deliver small, testable increments frequently
3. **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
4. **Data-informed decisions**: Measure impact and iterate based on evidence
5. **Psychological safety**: Encourage feedback, learning, and blameless retrospectives

## Project Lifecycle

All cross-functional projects at OctoAcme follow a consistent lifecycle:

### 1. Initiation
Validate and authorize work, align stakeholders, and create a lightweight plan.
- Define problem statement and success metrics
- Identify stakeholders and champions
- Create initial timeline and resource plan

📄 **See:** [Project Initiation Guide](octoacme-project-initiation.md)

### 2. Planning
Turn an approved initiative into an actionable plan and backlog for delivery.
- Break work into shippable increments
- Identify dependencies and risks
- Create release plan and milestone map

📄 **See:** [Project Planning Guide](octoacme-project-planning.md)

### 3. Execution & Tracking
Manage day-to-day execution and track progress toward milestones.
- Daily standups and weekly delivery syncs
- Pull Request workflow and quality gates
- Regular demos and risk updates

📄 **See:** [Execution & Tracking Guide](octoacme-execution-and-tracking.md)

### 4. Release & Deployment
Standardize how features are released to production to reduce risk.
- Pre-release requirements and testing
- Deployment checklist and verification
- Rollback plans and incident response

📄 **See:** [Release & Deployment Guide](octoacme-release-and-deployment.md)

### 5. Retrospective
Capture learnings and convert them into actionable improvements.
- Review what went well and what could be improved
- Define action items with owners and due dates
- Track and measure improvement impact

📄 **See:** [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)

## Core Roles

Our teams consist of clearly defined roles with specific responsibilities:

- **Project Manager (PM)**: Coordinates delivery, schedules, risk, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, and measures success
- **Developers**: Implement features, collaborate on design and testability
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs, approvals, and feedback

📄 **See:** [Roles and Personas](octoacme-roles-and-personas.md) for detailed responsibilities and goals

## Key Workflows

### Development Workflow
- Use project boards with clear columns: Backlog → Ready → In Progress → In Review → QA → Done
- Submit small Pull Requests (≤400 lines when possible)
- Include issue links and acceptance criteria in PR descriptions
- Require automated tests and at least one approval before merging

### Communication Cadence
- **Daily**: Team standups (15 min)
- **Weekly**: PM + PdM sync and delivery team sync
- **Sprint-based**: Demo/review at end of each sprint or milestone
- **Monthly**: Stakeholder updates
- **Ad-hoc**: Escalations as needed

📄 **See:** [Risk Management & Communication](octoacme-risks-and-communication.md)

## Key Deliverables & Artifacts

Throughout the project lifecycle, we maintain these core artifacts:

### Planning Artifacts
- Project Charter / One-pager (problem, goal, success metrics)
- Roadmap and Release Plan
- Sprint/Iteration Backlog with acceptance criteria
- Definition of Done (DoD)

### Execution Artifacts
- Risk Register (ID, description, impact, likelihood, mitigation)
- Weekly status updates
- PR descriptions and code review comments
- Test plans and QA reports

### Release Artifacts
- Release notes (changes, migration steps, known issues)
- Deployment checklists
- Rollback and incident playbooks

### Retrospective Artifacts
- Retrospective notes (what went well, what to improve)
- Action items with owners and timelines
- Improvement metrics

## How to Use This Documentation

### For New Team Members
1. Start with this README to understand the big picture
2. Review the [Project Management Overview](octoacme-project-management-overview.md) for a concise summary
3. Explore role-specific guides based on your position ([Roles and Personas](octoacme-roles-and-personas.md))
4. Dive into phase-specific guides as you begin working on projects

### For Project Teams
- Keep the Project Charter updated in your project repository
- Add relevant process docs to `.copilot/` to enable Copilot Spaces to use them as context
- Use the checklists in each guide to ensure you don't miss critical steps
- Customize templates to fit your project's specific needs

### For Copilot Spaces
These documents are structured to work seamlessly with GitHub Copilot Spaces:
- Use persona definitions to frame role-specific guidance
- Reference process templates for creating project artifacts
- Query principles and workflows for contextual assistance

## Quick Reference

| Need to...                          | See this guide                                                                 |
|-------------------------------------|-------------------------------------------------------------------------------|
| Start a new project                 | [Project Initiation](octoacme-project-initiation.md)                         |
| Create a project plan               | [Project Planning](octoacme-project-planning.md)                             |
| Understand daily workflows          | [Execution & Tracking](octoacme-execution-and-tracking.md)                   |
| Prepare for a release               | [Release & Deployment](octoacme-release-and-deployment.md)                   |
| Run a retrospective                 | [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) |
| Manage risks and communicate status | [Risk Management & Communication](octoacme-risks-and-communication.md)       |
| Understand roles and responsibilities | [Roles and Personas](octoacme-roles-and-personas.md)                       |
| Get a concise overview              | [Project Management Overview](octoacme-project-management-overview.md)       |

---

**Questions or suggestions?** These process documents are living artifacts. If you have feedback or see opportunities for improvement, share them during retrospectives or reach out to your Project Manager.
