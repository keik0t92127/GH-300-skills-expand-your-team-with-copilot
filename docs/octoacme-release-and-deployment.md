# OctoAcme Release and Deployment

This document describes the release and deployment process used by OctoAcme.

## Overview

The Release phase covers all activities from feature freeze through deployment to production and post-release monitoring. No release proceeds without meeting all go/no-go criteria.

## Release Prerequisites

Before a release can proceed, the following conditions must be met:

- All planned stories for the release are in the **Done** column on the project board
- All CI checks are green on the release branch
- QA has completed and signed off on the release test plan
- Security scanning has been completed with no unresolved high or critical findings
- The release checklist is complete (see below)
- Stakeholder approval has been obtained

## Release Checklist

The QA engineer and PM jointly complete the release checklist before deployment:

- [ ] All acceptance criteria verified in staging environment
- [ ] Unit, integration, and end-to-end tests passing
- [ ] Performance benchmarks within acceptable thresholds
- [ ] Security scan completed and findings addressed
- [ ] Release notes drafted and reviewed
- [ ] Rollback plan documented and tested
- [ ] On-call rotation confirmed for post-release monitoring period

## Deployment Process

1. **Staging deployment**: Changes are deployed to the staging environment for final verification.
2. **Go/No-Go meeting**: PM, QA, and PdM confirm go/no-go status using the checklist.
3. **Production deployment**: Deployment is executed during the approved maintenance window.
4. **Smoke testing**: QA runs a smoke test suite against production immediately after deployment.
5. **Monitoring**: The team monitors error rates, performance metrics, and user reports for 24 hours post-release.

## Rollback Plan

Every release must have a documented rollback plan. The rollback plan includes:

- The steps to revert the deployment
- The person responsible for initiating the rollback
- The criteria that would trigger a rollback (e.g., error rate exceeds threshold)

The rollback plan is reviewed and tested in staging before each production release.

## Post-Release

After deployment, the PM:

- Sends a release notification to stakeholders
- Updates the project board to close the release milestone
- Schedules a retrospective (see [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md))
