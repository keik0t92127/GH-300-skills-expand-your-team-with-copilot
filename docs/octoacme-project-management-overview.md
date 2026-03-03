# OctoAcme Project Management Overview

This document provides a high-level overview of the OctoAcme project management process.

## Purpose

This document serves as the entry point for understanding how OctoAcme delivers software projects. It summarizes the full project lifecycle and links to detailed process documents for each phase.

## Project Lifecycle

OctoAcme follows a structured lifecycle with five main phases:

```
Initiation → Planning → Execution → Release → Retrospective
```

| Phase         | Purpose                                               | Key Document |
|---------------|-------------------------------------------------------|--------------|
| Initiation    | Define the project, identify stakeholders, set up the board | [Project Initiation](octoacme-project-initiation.md) |
| Planning      | Refine the backlog, define acceptance criteria, plan sprints | [Project Planning](octoacme-project-planning.md) |
| Execution     | Build, review, and integrate features                | [Execution and Tracking](octoacme-execution-and-tracking.md) |
| Release       | Verify, deploy, and monitor the release              | [Release and Deployment](octoacme-release-and-deployment.md) |
| Retrospective | Reflect and improve                                   | [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) |

## Roles

Five primary roles participate in OctoAcme projects:

- **Project Manager (PM)**: Owns delivery, runs meetings, manages risks and communications
- **Product Manager (PdM)**: Owns the product vision, backlog, and acceptance criteria
- **Developer (Dev)**: Implements features, submits pull requests, participates in code review
- **Quality Assurance (QA)**: Writes test plans, verifies features, signs off releases
- **Stakeholders**: Provide input on requirements, attend demos, receive status updates

See [Roles and Personas](octoacme-roles-and-personas.md) for full role descriptions and the RACI matrix.

## Communication Cadence

| Event                | Frequency          | Owner |
|----------------------|--------------------|-------|
| Daily stand-up       | Daily              | PM    |
| Weekly sync          | Weekly             | PM    |
| Sprint demo / review | End of each sprint | PdM   |
| Stakeholder update   | Weekly (written)   | PM    |

All project information is stored in the GitHub repository as the single source of truth. See [Risks and Communication](octoacme-risks-and-communication.md) for details.

## Quality and CI

Quality is maintained through:

- Acceptance criteria on every story
- Small, focused pull requests with CI checks (unit, integration, security scan)
- Mandatory code review before merge
- QA sign-off and release checklists
- Documented rollback plans for every release
- Post-release monitoring and retrospectives

## Related Documents

- [Project Initiation](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution and Tracking](octoacme-execution-and-tracking.md)
- [Risks and Communication](octoacme-risks-and-communication.md)
- [Release and Deployment](octoacme-release-and-deployment.md)
- [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)
