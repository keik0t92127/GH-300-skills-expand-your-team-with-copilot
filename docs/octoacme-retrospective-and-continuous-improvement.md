# OctoAcme Retrospective and Continuous Improvement

This document describes OctoAcme's retrospective process and approach to continuous improvement.

## Overview

Retrospectives are held at the end of every sprint and after every production release. They are the primary mechanism by which OctoAcme teams learn from experience and improve their processes.

## Retrospective Cadence

| Type              | Trigger                       | Duration  | Facilitator |
|-------------------|-------------------------------|-----------|-------------|
| Sprint retrospective | End of each sprint          | 45–60 min | PM          |
| Release retrospective | After each production release | 60–90 min | PM        |
| Incident retrospective | After any significant incident | As needed | PM       |

## Retrospective Format

OctoAcme retrospectives follow a structured format:

1. **Set the stage** (5 min): Establish a safe environment for open discussion. The PM reminds the team of the retrospective norms (blameless, constructive, focused on process not individuals).

2. **Gather data** (15–20 min): The team reflects on the sprint or release using prompts:
   - What went well?
   - What didn't go well?
   - What surprised us?
   - What did we learn?

3. **Generate insights** (15 min): The team identifies patterns and root causes behind the data gathered.

4. **Decide on actions** (10–15 min): The team agrees on a small number of actionable improvements. Each action item has an owner and a target completion date.

5. **Close** (5 min): The PM summarizes agreed actions and thanks the team.

## Action Item Tracking

Action items from retrospectives are tracked as GitHub issues labeled `retrospective-action`. The PM reviews open action items at each weekly sync to ensure progress.

## Continuous Improvement Practices

Beyond retrospectives, OctoAcme promotes continuous improvement through:

- **Process documentation updates**: When a process improvement is agreed upon, the relevant documentation in `docs/` is updated in the same sprint.
- **Metrics review**: The PM reviews key delivery metrics (cycle time, defect rate, CI pass rate) monthly and shares trends with the team.
- **Knowledge sharing**: Lessons learned from retrospectives are shared with other teams through internal channels to avoid repeated mistakes.

## Outputs

- Action items logged as GitHub issues
- Updated process documentation (if process changes are agreed)
- Metrics trends shared with stakeholders on a monthly basis
