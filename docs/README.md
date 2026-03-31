# OctoAcme Project Management Docs — README

## Overview

This README serves as the central entry point for OctoAcme's project management documentation. These guides ensure all projects follow a clear, repeatable lifecycle with well-defined roles, quality practices, and communication standards. Whether you're initiating a new project, planning a sprint, or retrospecting after delivery, you'll find the processes and templates you need here.

## Project Management Process Summary

OctoAcme operates a structured, lifecycle-based project management framework designed to deliver customer value iteratively while maintaining clear ownership and accountability. The approach spans five core phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. Each phase is anchored by lightweight but essential artifacts—such as the Project One-pager, prioritized backlog with acceptance criteria, and risk registers—that serve as single sources of truth.

At the heart of OctoAcme's execution model are clearly defined roles with distinct ownership: **Project Managers** coordinate schedules, risks, and communications; **Product Managers** define outcomes and prioritize work; **Developers** implement features with quality and maintainability in focus; and **QA professionals** validate acceptance criteria. This role clarity is reinforced through a consistent communication cadence—daily standups, weekly PM-PdM syncs, monthly stakeholder updates, and ad-hoc escalations—ensuring that blockers surface quickly and decisions flow through defined channels.

Quality is embedded throughout execution rather than treated as a final gate. Teams maintain unit and integration tests, run automated CI/CD pipelines with security scanning, and conduct manual QA for feature acceptance when needed. Pull requests follow strict discipline—kept to ≤400 lines, include issue links and acceptance criteria, and require at least one approval before merge. Risk management is equally systematic: teams identify and assess risks during planning, maintain a live Risk Register, and escalate blockers through defined levels (team triage → PM → Product Lead → Sponsor) to unblock critical dependencies.

Finally, OctoAcme closes the feedback loop through structured retrospectives after each sprint, release, or milestone. Teams capture what went well, what could improve, and convert insights into tracked action items with clear owners and due dates. This continuous improvement mindset, combined with shared access to process documentation and decision rationale, accelerates onboarding and reduces single-person dependency risk—enabling consistent, repeatable execution across the organization.

## Docs Table of Contents

- [OctoAcme Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)

---

**How to use these docs:**
- Start with the [Project Management Overview](octoacme-project-management-overview.md) for a high-level introduction.
- Follow the lifecycle phases in order (Initiation → Planning → Execution → Release → Retrospective) for a new project.
- Use individual guides as reference materials during execution (e.g., consult Execution & Tracking during sprints, Release & Deployment before deploying to production).
- Add process-specific docs or templates to `.copilot/` if you want to ground Copilot Spaces with additional context.
