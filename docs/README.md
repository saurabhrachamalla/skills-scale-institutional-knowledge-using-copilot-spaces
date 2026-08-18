# OctoAcme Project Management Docs

## Overview

Welcome to OctoAcme's Project Management process documentation. This collection provides comprehensive guidance for running projects following the OctoAcme methodology, which emphasizes customer-first delivery, iterative development, clear ownership, and data-informed decision-making.

## Core Principles

- **Customer-First**: Prioritize customer value and usability
- **Iterative Delivery**: Deliver small, testable increments
- **Clear Ownership**: Each project has a named Project Manager and Product Lead
- **Data-Informed**: Measure impact and iterate based on evidence
- **Psychological Safety**: Encourage feedback and learning

## OctoAcme Project Management Process Summary

OctoAcme employs a customer-first, iterative project management methodology built on five core principles: delivering customer value, breaking work into small testable increments, maintaining clear ownership, making data-informed decisions, and fostering psychological safety. The project lifecycle follows a structured five-phase approach: Initiation (validating business need and aligning stakeholders), Planning (breaking work into shippable increments and defining milestones), Execution (day-to-day delivery with regular cadences), Release (standardized deployment with quality gates), and Retrospective (capturing learnings and continuous improvement). Each project has a named Project Manager who coordinates delivery and a Product Manager who defines outcomes and measures success, ensuring clear accountability throughout.

The framework defines distinct roles with complementary responsibilities: Project Managers coordinate schedules, risks, and communications; Product Managers define what should be built and prioritize the backlog; Developers implement features while collaborating on design and testability; and QA/Testing validates acceptance criteria. Regular communication is structured through daily 15-minute standups focused on progress and blockers, weekly syncs between PM and Product Manager to review risk registers and dependencies, twice-weekly delivery team standups, and monthly stakeholder updates. This multi-layered communication ensures transparency across technical teams, leadership, and business stakeholders while enabling escalation through three levels: team triage, PM escalation to Product Lead, and sponsor-level escalation for business-impacting issues.

Execution follows GitHub Projects-based workflows with columns for Backlog, Ready, In Progress, In Review, QA, and Done. Pull requests are kept small (≤400 lines when possible), include issue links and acceptance criteria, and require automated CI testing, linting, and at least one approval before merging. Quality assurance is comprehensive, encompassing unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA for feature acceptance. Release management includes pre-release requirements (passing CI, security scans, documented rollback plans, smoke tests), a deployment checklist with staging verification, and incident playbooks for rapid rollback if needed. Finally, retrospectives are held after each sprint or milestone to capture what went well, identify improvements, and create prioritized action items with clear owners—reinforcing a culture of continuous improvement and iterative enhancement of processes themselves.

## Process Documentation

### Getting Started

- **[Project Management Overview](octoacme-project-management-overview.md)** - High-level introduction to OctoAcme's approach, core roles, key artifacts, and lifecycle
- **[Roles & Personas](octoacme-roles-and-personas.md)** - Definitions of Project Manager, Product Manager, Developer, and other key roles

### Project Lifecycle

1. **[Project Initiation](octoacme-project-initiation.md)** - Steps to validate work, align stakeholders, and authorize projects
2. **[Project Planning](octoacme-project-planning.md)** - Breaking work into shippable increments, estimating, and defining dependencies
3. **[Execution & Tracking](octoacme-execution-and-tracking.md)** - Day-to-day execution, team rhythm, quality standards, and blocker escalation
4. **[Release & Deployment](octoacme-release-and-deployment.md)** - Standardized release processes, deployment checklists, and rollback procedures
5. **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** - Capturing learnings and converting them to actionable improvements

### Cross-Cutting Concerns

- **[Risk Management & Communication](octoacme-risks-and-communication.md)** - Risk registers, stakeholder communication, and escalation paths

## How to Use These Docs

- **For New Projects**: Start with Project Initiation, then Project Planning
- **For Delivery Teams**: Reference Execution & Tracking and Risk Management & Communication weekly
- **For Releases**: Consult Release & Deployment before going live
- **For Process Improvements**: Use Retrospective & Continuous Improvement after each milestone
- **For Onboarding**: Read the Project Management Overview and Roles & Personas first

## Communication Cadence

- Weekly sync between PM and Product Manager
- Twice-weekly standups for delivery teams
- Monthly stakeholder updates
- Ad-hoc escalations as needed

## Need Help?

Refer to the relevant process document or reach out to your Project Manager or Product Manager.
