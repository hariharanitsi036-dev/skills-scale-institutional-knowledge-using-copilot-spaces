```markdown
# OctoAcme — Project Management Overview

This repository contains OctoAcme's project management process documents and templates. OctoAcme runs projects through a lightweight, stage-based lifecycle: Initiation, Planning, Execution, Release, and Retrospective. Initiation captures the problem, success metrics, stakeholders, and a high-level timeline in a Project One‑pager. Planning breaks that into a prioritized, estimated backlog, a Definition of Done, and a release/milestone map. The project repo and project board are treated as the single source of truth for artifacts like the one‑pager, backlog items with acceptance criteria, risk register, release notes, and retrospective action items.

Day-to-day workflows emphasize small, iterative delivery and disciplined collaboration. Teams operate a project board with columns such as Backlog, Ready, In Progress, In Review, QA, and Done. Pull requests are kept small, include linked issues and acceptance criteria, and must pass CI gates (tests, linting, security scans) and receive review approvals before merge. Sprint planning is timeboxed and only items meeting the Definition of Done are pulled into work; cross-team dependencies are tracked in the risk register and surfaced in weekly syncs.

Roles and communication are explicit: Product Managers (PdMs) define outcomes and prioritize, Project Managers (PMs) coordinate delivery and communications, Developers implement and test, QA validates acceptance criteria, and stakeholders provide inputs and approvals. Regular touchpoints include daily standups for triage, weekly delivery syncs and PM/PdM alignment meetings, demos at the end of sprints or milestones, and monthly stakeholder updates. Escalation follows team → PM → Product Lead → Sponsor, and security incidents follow the security incident runbook and on-call notification paths.

Quality assurance and continuous improvement are embedded throughout delivery. Testing is layered—unit tests for logic, integration tests where applicable, and end‑to‑end smoke tests for critical flows—with CI enforcing test and lint gates and security scanning before releases. Manual QA is used as needed for acceptance; releases follow a checklist (staging smoke tests, rollback plan, release notes) and post‑deploy verification. Retrospectives after sprints, releases, or incidents produce prioritized action items that are tracked in the backlog to close the loop on improvements.

How to use this folder:
- Keep project-specific process docs updated in docs/
- Use the issue template `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml` to propose edits
- Add action items from retrospectives to the project backlog so improvements are tracked and measurable
```
