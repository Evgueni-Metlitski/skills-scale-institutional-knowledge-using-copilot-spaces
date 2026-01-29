# OctoAcme Project Management Overview

## Purpose
Provide a concise, shareable introduction to how OctoAcme runs projects so new teammates can quickly understand our approach, roles, and key artifacts.

## Scope
Applies to all cross-functional projects that deliver product features, services, or integrations.

## Principles
- Customer-first: prioritize customer value and usability.
- Iterative delivery: deliver small, testable increments.
- Clear ownership: each project has a named Project Manager (PM) and Product Lead.
- Data-informed decisions: measure impact and iterate based on evidence.
- Psychological safety: encourage feedback and learning.

## Core Roles
- **Project Manager (PM)**: coordinates delivery, schedules, risk, communications.
- **Product Manager (PdM)**: defines outcomes, prioritizes backlog, and measures success.
- **Developers**: implement features, collaborate on design and testability.
- **Scrum Master**: facilitates agile ceremonies, removes impediments, coaches team on agile practices.
- **UX/UI Designer**: designs user experiences, creates prototypes, validates usability.
- **Business Analyst (BA)**: gathers requirements, documents user stories, bridges business and technical teams.
- **QA/Tester**: develops test plans, validates quality and acceptance criteria, ensures release readiness.
- **Stakeholders**: provide strategic input, review deliverables, and approve key decisions.

### Role Interaction & Handoffs
- **PM ↔ Scrum Master**: PM owns overall project coordination and stakeholder communication, while Scrum Master focuses on team-level agile practices and daily execution. They collaborate on sprint planning and risk removal.
- **PdM ↔ Business Analyst**: PdM sets product vision and priorities; BA translates these into detailed requirements and user stories with acceptance criteria.
- **UX/UI Designer ↔ Developer**: Designer creates design specifications and prototypes; Developer implements designs with regular sync points to ensure fidelity.
- **BA ↔ QA/Tester**: BA defines acceptance criteria; QA/Tester creates test plans based on those criteria and validates implementation.
- **PM ↔ Stakeholder**: PM provides regular status updates and manages stakeholder expectations; Stakeholder provides strategic direction and key approvals.

## Key Artifacts
- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items

## Lifecycle (high-level)
1. Initiation: problem statement, stakeholders, high-level timeline.
2. Planning: scope, resources, milestones, dependencies.
3. Execution: build, test, review, iterate.
4. Release: deploy, verify, announce.
5. Close & Retrospective: capture learnings and next steps.

## Communication Cadence
- Daily standups facilitated by Scrum Master (15 min)
- Weekly sync between PM + PdM
- Twice-weekly standups for delivery team (or as agreed)
- Bi-weekly backlog grooming/refinement sessions (PdM, BA, Scrum Master, Developers)
- Weekly or bi-weekly UX design reviews (UX/UI Designer, PdM, key stakeholders)
- Business analysis workshops as needed (BA, Stakeholders, PdM)
- Sprint planning, review, and retrospectives (full team)
- Monthly stakeholder updates (PM to Stakeholders)
- Ad-hoc escalations as needed

## How to use these docs
- Keep the Project Charter updated in the project repo.
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.
