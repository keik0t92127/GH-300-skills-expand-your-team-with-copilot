# OctoAcme Roles and Personas

This document describes the key roles and personas involved in OctoAcme projects.

## Roles

### Project Manager (PM)

The Project Manager is responsible for overall project delivery. Key responsibilities include:

- Owning the project roadmap and milestone tracking
- Running weekly synchronization meetings
- Managing risks, blockers, and escalations
- Maintaining the project board and ensuring columns reflect current state
- Communicating status updates to stakeholders

### Product Manager (PdM)

The Product Manager owns the product vision and backlog. Key responsibilities include:

- Defining acceptance criteria for features and user stories
- Prioritizing the backlog in alignment with business goals
- Participating in sprint planning and review sessions
- Validating delivered features against requirements

### Developer (Dev)

Developers design, implement, and maintain the codebase. Key responsibilities include:

- Writing code that satisfies acceptance criteria
- Submitting small, focused pull requests with clear descriptions
- Participating in code reviews
- Ensuring CI checks pass before requesting review
- Flagging technical risks or blockers early

### Quality Assurance (QA)

QA engineers are responsible for verifying that features meet quality standards. Key responsibilities include:

- Writing and maintaining test plans (unit, integration, end-to-end)
- Reviewing pull requests for testability
- Executing regression testing before releases
- Maintaining release checklists and go/no-go criteria

### Stakeholders

Stakeholders are internal or external parties with an interest in the project outcome. Key responsibilities include:

- Providing input on requirements and priorities
- Attending demo and review sessions
- Reviewing and approving stakeholder update communications
- Escalating concerns through the PM

## RACI Overview

| Activity                    | PM  | PdM | Dev | QA  | Stakeholders |
|-----------------------------|-----|-----|-----|-----|--------------|
| Roadmap definition          | A   | R   | C   | C   | I            |
| Backlog prioritization      | C   | A   | C   | C   | I            |
| Sprint planning             | R   | A   | C   | C   | I            |
| Feature development         | I   | C   | R   | C   | I            |
| Code review                 | I   | I   | R   | C   | I            |
| QA sign-off                 | I   | C   | C   | A   | I            |
| Stakeholder update          | R   | C   | I   | I   | A            |
| Retrospective facilitation  | R   | C   | C   | C   | I            |

_R = Responsible, A = Accountable, C = Consulted, I = Informed_
