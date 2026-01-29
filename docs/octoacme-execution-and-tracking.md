# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups facilitated by Scrum Master (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Bi-weekly backlog grooming/refinement (PdM, BA, Scrum Master, team representatives)
- UX design reviews (as needed, typically weekly or bi-weekly)
- Demo/Review at the end of each sprint or milestone (full team + stakeholders)
- Sprint retrospectives facilitated by Scrum Master

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic (Developers)
- Integration tests where applicable (Developers, QA/Tester)
- End-to-end smoke tests for critical flows before release (QA/Tester)
- Usability testing for new user-facing features (UX/UI Designer)
- Acceptance testing against BA-defined criteria (QA/Tester, BA)
- Security scanning in CI
- Manual QA for feature acceptance when needed
- Design review and QA before marking stories as done

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup (Scrum Master facilitates)
- Level 2: Scrum Master and PM escalate to Product Lead and dependent teams
- Level 3: PM escalates to Sponsor-level for business-impacting issues
- UX/Design blockers: Designer escalates to PdM and PM if impacting delivery
- Requirements clarification: BA works with Stakeholders, escalates to PdM if needed

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Agile ceremonies scheduled (standups, planning, reviews, retros)
- [ ] Backlog grooming sessions scheduled with PdM, BA, and Scrum Master
- [ ] UX design review cadence established (if applicable)
- [ ] Regular demos scheduled with stakeholders
- [ ] QA test plan and automation strategy in place
- [ ] Risk register updated weekly by PM
- [ ] Definition of Done includes design and testing sign-off
