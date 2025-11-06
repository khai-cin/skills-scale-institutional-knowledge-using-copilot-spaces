# OctoAcme Project Management Docs

This README collects core project management reference materials for OctoAcme, providing a one‑stop entry point for how projects are initiated, planned, executed, released, and improved. The docs in this folder describe our roles, key artifacts, communication cadence, and quality practices so teams can find consistent guidance and onboard quickly.

## Project Management Process Summary

OctoAcme follows a lightweight iterative lifecycle: Initiation → Planning → Execution → Release → Close & Retrospective. Initiation captures the problem, SMART objectives, success metrics, stakeholders, and a high‑level timeline in a one‑pager that gates whether work moves into planning. Planning turns approved initiatives into a prioritized, estimated backlog, defines the Definition of Done, maps dependencies, and creates a release plan and milestone map. Execution is timeboxed into sprints or iterations with a disciplined board and pull request workflow to keep work small, testable, and reviewable. Releases are validated with smoke tests, release notes, and rollback plans, and retrospectives capture learning and prioritized action items for continuous improvement.

Roles and ownership are explicit: each project names a Project Manager (PM) and a Product Lead (PdM). PMs coordinate delivery, manage schedules, risks and communications; Product Managers define outcomes, prioritize backlog and measure success; Developers implement, test and document; QA validates acceptance criteria; Stakeholders provide approvals. Regular ceremonies (kickoff, planning, daily standups, demos, retrospectives) and role‑specific responsibilities ensure clarity and accountability.

Communication and quality assurance are structured and frequent. Team rhythm includes daily standups, weekly delivery syncs, sprint demos, and monthly stakeholder updates. The single source of truth is the project README or release document in the project repo. Risks are tracked in a Risk Register (ID, impact, likelihood, owner, mitigation, status) and escalated via team → PM → PdM → Sponsor; security incidents follow the security runbook. QA combines automated unit, integration, and security scans in CI with manual QA for feature acceptance and end‑to‑end smoke tests before release. PR rules require small changes, CI passing before review, and at least one approval.

## Process Documents (links)
- docs/octoacme-project-management-overview.md
- docs/octoacme-project-initiation.md
- docs/octoacme-project-planning.md
- docs/octoacme-execution-and-tracking.md
- docs/octoacme-risks-and-communication.md
- docs/octoacme-release-and-deployment.md
- docs/octoacme-retrospective-and-continuous-improvement.md
- docs/octoacme-roles-and-personas.md

## How to use these docs
- Keep the Project One‑pager and Project README updated in the project repo.
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.
- Use the Risk Register template and Weekly Status template for consistent reporting.

## Acceptance Criteria
- Content aligns with existing process docs
- Improves clarity and discoverability of process guidance
- Reviewed by stakeholders where needed