# OctoAcme Project Management Docs

This folder contains the core project management process documents used by OctoAcme. The files below index our lightweight, outcome-oriented approach and provide templates, checklists, and guidance for initiating, planning, executing, releasing, and improving work.

## Brief overview of OctoAcme processes
OctoAcme runs projects iteratively through a clear lifecycle: Initiation, Planning, Execution, Release, and Retrospective. Initiation captures the problem, stakeholders, and measurable success criteria in a concise one‑pager. Planning turns approved initiatives into a prioritized backlog with acceptance criteria, estimates, and a Definition of Done; teams map work to releases and identify dependencies and risks up front.

Execution prioritizes small, testable increments and a disciplined PR workflow (small PRs, linked issues and acceptance criteria, CI checks, and required approvals). Day‑to‑day work uses a project board with Backlog → Ready → In Progress → In Review → QA → Done, alongside regular rhythms (daily standups, weekly delivery syncs, sprint demos) to surface progress and blockers. Risk and dependency management are tracked in a Risk Register and escalated along a defined path when necessary.

Quality assurance combines automated and manual checks: unit and integration tests for new logic, smoke tests for critical flows, security scanning in CI, and manual QA as needed prior to release. Releases follow a checklist (pre‑release verification, staging smoke tests, rollback plans) and include post‑deploy verification and stakeholder communication. Retrospectives and tracked action items drive continuous improvement.

## Process documents
- octoacme-project-management-overview.md — introduction to roles, principles, lifecycle, and key artifacts  
- octoacme-project-initiation.md — one‑pager template, initiation checklist, and decision gate  
- octoacme-project-planning.md — backlog templates, sprint planning, and release mapping  
- octoacme-execution-and-tracking.md — team rhythm, workflows, PR conventions, and reporting  
- octoacme-risks-and-communication.md — risk register format, communication templates, and escalation paths  
- octoacme-release-and-deployment.md — release types, deployment checklist, and rollback playbook  
- octoacme-retrospective-and-continuous-improvement.md — retrospective structure and tracking action items  
- octoacme-roles-and-personas.md — role summaries and responsibilities used in the process docs

## How to use
- Use this README as the index for process guidance and onboarding.  
- Update individual docs as processes evolve and keep this README's links and summaries in sync.  
- To request edits to these process docs, use the "Add Content to Project Management Process Docs" issue template in .github/ISSUE_TEMPLATE/.
