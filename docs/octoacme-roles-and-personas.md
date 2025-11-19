# OctoAcme — Roles and Personas (expanded)

This document defines project roles and personas used across OctoAcme projects. The purpose of this update is to add clarity and accountability by introducing additional roles, detailing responsibilities, and describing interactions with existing roles.

## Core roles (summary)
- Project Manager (PM): Owns project delivery, schedule, budget, and stakeholder communication.
- Engineering Lead: Technical direction and code quality.
- Product Manager: Product vision and priority decisions.

## New/expanded personas

### Product Owner
Responsibilities:
- Own and communicate product vision and goals for the project.
- Maintain and prioritize the product backlog.
- Accept or reject delivered features based on acceptance criteria.
How they interact:
- Works with PM to align roadmap and release planning.
- Collaborates with Engineering Lead and Scrum Master on scope and sprint goals.
- Coordinates with Technical Writer to ensure release notes and user-facing docs reflect scope.

### Scrum Master
Responsibilities:
- Facilitate agile ceremonies (planning, standups, reviews, retrospectives).
- Remove impediments and protect the team from external distractions.
- Coach the team on agile practices and continuous improvement.
How they interact:
- Works closely with PM and Product Owner to maintain flow and realistic commitments.
- Escalates blockers to PM when cross-team coordination or organizational decisions are required.

### QA Lead
Responsibilities:
- Define and manage QA strategy, test plans, and acceptance criteria.
- Coordinate test execution across environments and ensure test coverage.
- Sign-off on releases from a quality perspective.
How they interact:
- Receives feature readiness notifications from Engineering Lead and Product Owner.
- Reports test status, defects and release readiness to PM and Product Owner.
- Works with Technical Writer to ensure testing instructions and release notes are accurate.

### Technical Writer
Responsibilities:
- Produce and maintain process documentation, runbooks, and release notes.
- Ensure documentation is clear, versioned, and accessible to stakeholders.
How they interact:
- Gathers inputs from Product Owner, Engineering Lead, QA Lead and PM.
- Publishes release notes and updates process docs prior to deployments.

### Data Analyst
Responsibilities:
- Define and track project KPIs; provide analysis to support decisions.
- Instrument product and process metrics; validate measurement accuracy.
How they interact:
- Works with PM and Product Owner to define success metrics for features/releases.
- Reports insights that drive prioritization and retrospective action items.

### Release Coordinator (optional persona for larger releases)
Responsibilities:
- Manage release windows, cutover plans and rollback procedures.
- Coordinate stakeholders during release execution.
How they interact:
- Works with PM, Engineering Lead, QA Lead and Technical Writer to execute release checklist and sign-offs.
- Ensures communication to stakeholders and users during release.

## Example interactions and RACI-style notes
- Feature prioritization: Product Owner (A), Product Manager (C), PM (C), Engineering Lead (R)
- Release sign-off: QA Lead (A), Release Coordinator (R), PM (C), Technical Writer (C)
- Documentation updates: Technical Writer (R), Product Owner (C), Engineering Lead (C)

## Why this matters
- Clear accountability reduces handoff ambiguity and missed responsibilities.
- Explicit interactions improve cross-team communication and speed up decision-making.
- Role-based checklists and sign-offs lower release risk and increase predictability.

## Next steps
- Add short checklists and stage-gate templates to docs/templates/ for operationalization.
- Review these roles with stakeholders and incorporate feedback.
