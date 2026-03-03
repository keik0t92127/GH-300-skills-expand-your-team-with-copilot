# OctoAcme Execution and Tracking

This document describes the execution and tracking phase of OctoAcme's project management process.

## Overview

The Execution phase is where the team builds, reviews, and integrates features. The PM tracks progress daily and adjusts plans as needed to keep the project on track.

## Development Workflow

### Small Pull Requests

Developers are expected to submit small, focused pull requests. Each PR should:

- Address a single concern or user story
- Include a clear description linking to the related issue or story
- Pass all CI checks before requesting review
- Reference the acceptance criteria in the PR description

### Project Board Workflow

Items flow through the board columns in order:

1. **Backlog** → refined and estimated
2. **Ready** → acceptance criteria agreed, ready to start
3. **In Progress** → developer has started work
4. **In Review** → pull request open and under review
5. **Done** → PR merged, CI green, QA verified

### Code Review

- At least one approval from another Developer is required before merging
- QA reviews testability and coverage
- PdM reviews against acceptance criteria for significant features
- The PR author is responsible for resolving all review comments

### Continuous Integration

All repositories are configured with CI pipelines that run on every pull request:

- Unit tests
- Integration tests
- Linting and static analysis
- Security scanning

PRs may not be merged with failing CI checks.

## Daily Tracking

### Stand-up

The team holds a brief daily stand-up (async or synchronous) covering:

- What was completed since the last stand-up
- What is planned for today
- Any blockers or risks

### Project Board Hygiene

The PM reviews the board daily to:

- Ensure items are in the correct column
- Identify items stuck in **In Review** for more than two days
- Flag any items with no activity for follow-up

## Weekly Sync

The PM facilitates a weekly synchronization meeting with the full team to:

- Review sprint progress against the plan
- Update the risk register
- Discuss upcoming dependencies
- Prepare the stakeholder update

## Outputs

- Merged pull requests with CI passing
- Updated project board
- Weekly status summary shared with stakeholders
