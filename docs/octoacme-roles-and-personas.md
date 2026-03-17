# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Scrum Master

### Role Summary
Scrum Masters facilitate agile ceremonies, protect the team from distractions, and continuously improve delivery processes. They act as servant-leaders who help the team adhere to agile principles and remove blockers that impede progress.

### Responsibilities
- Facilitate sprint planning, daily standups, sprint reviews, and retrospectives
- Identify and remove impediments that block the team
- Coach the team on agile best practices and continuous improvement
- Shield the team from unplanned interruptions during a sprint
- Track sprint health metrics (velocity, burndown, blockers)

### Goals
- Maximize team throughput and predictability
- Foster a culture of transparency, inspection, and adaptation
- Reduce blockers and unplanned work

### Typical Communication
- Daily standups and sprint ceremonies
- Impediment log and blockers board
- Retrospective action items and follow-ups

### Interaction with Existing Roles
- **Project Managers**: Coordinates on cross-team dependencies and timeline risks; escalates blockers that require PM-level intervention.
- **Product Managers**: Ensures backlog refinement happens on time and acceptance criteria are clear before planning.
- **Developers**: Removes technical and process blockers, facilitates estimation and retrospectives.

---

## UX Designer

### Role Summary
UX Designers ensure that products are usable, accessible, and deliver a high-quality user experience. They translate user needs and business requirements into clear interaction designs and validate solutions through research and testing.

### Responsibilities
- Conduct user research, interviews, and usability testing
- Create wireframes, prototypes, and interaction specifications
- Define and maintain design standards and component guidelines
- Participate in sprint planning to surface design dependencies early
- Collaborate on acceptance criteria related to usability and accessibility

### Goals
- Deliver intuitive, accessible, and delightful user experiences
- Reduce rework caused by late-stage usability feedback
- Maintain design consistency across the product

### Typical Communication
- Design reviews and stakeholder demos
- Figma/design tool comments and handoff notes
- User research reports and usability findings

### Interaction with Existing Roles
- **Product Managers**: Translates feature requirements into user-centered designs; participates in roadmap discussions to flag design effort.
- **Developers**: Provides detailed design specifications and is available for questions during implementation; reviews implemented features for fidelity.
- **Project Managers**: Flags design-related risks or dependencies that may affect sprint timelines.

---

## DevOps Engineer

### Role Summary
DevOps Engineers build and maintain the infrastructure, tooling, and automation that enable reliable, repeatable, and fast delivery. They bridge development and operations to improve deployment speed, stability, and observability.

### Responsibilities
- Design, build, and maintain CI/CD pipelines and release automation
- Manage cloud infrastructure, environments, and secrets
- Monitor production health, set up alerting, and support incident response
- Automate recurring operational tasks to reduce toil
- Ensure security and compliance controls are embedded in pipelines

### Goals
- Minimize deployment lead time and failure rate
- Maximize system reliability and observability
- Reduce manual, error-prone operational steps

### Typical Communication
- Deployment and release coordination with the delivery team
- Runbooks and operational playbooks
- Incident post-mortems and on-call handoffs

### Interaction with Existing Roles
- **Project Managers**: Coordinates deployment windows, communicates pipeline risks, and participates in release planning.
- **Developers**: Partners on CI/CD configuration, code quality gates, and environment provisioning.
- **Product Managers**: Advises on non-functional requirements (availability, scalability, compliance) that affect the roadmap.

---

## Data Analyst

### Role Summary
Data Analysts define, collect, and interpret project and product metrics to support data-driven decision making. They surface insights from data that help the team validate outcomes, identify improvement opportunities, and prioritize effectively.

### Responsibilities
- Define key performance indicators (KPIs) and success metrics aligned to project goals
- Build dashboards and reports for ongoing tracking and stakeholder communication
- Analyse data to validate feature impact and identify usage patterns
- Support retrospectives with quantitative evidence of progress and areas for improvement
- Flag data quality issues and work with Engineering to resolve them

### Goals
- Enable data-driven prioritization and decision making
- Reduce reliance on anecdotal evidence for assessing project outcomes
- Make success metrics visible and understandable to all stakeholders

### Typical Communication
- Weekly metrics summaries and dashboard updates
- Ad-hoc analysis reports during planning and retrospectives
- Data quality incident reports

### Interaction with Existing Roles
- **Product Managers**: Collaborates to define and refine success metrics; provides data to support roadmap decisions.
- **Project Managers**: Produces project health and progress dashboards; contributes data to status reports and retrospectives.
- **Developers**: Works with engineering to ensure instrumentation and data pipelines are correctly implemented.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See also: [RACI & Role Interaction Matrix](./octoacme-raci-matrix.md) for a quick reference on who owns what across the project lifecycle.
- See also: [Project Kickoff & Handoff Checklist](./octoacme-kickoff-and-handoff-checklist.md) for cross-functional delivery accountability.

