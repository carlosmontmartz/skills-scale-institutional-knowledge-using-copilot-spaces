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

## Change Manager

### Role Summary
The Change Manager oversees formal change management processes, ensuring all changes (scope, process, technical) are efficiently communicated, documented, and approved.

### Responsibilities
- Establish and enforce change request and approval process
- Drive impact assessments before changes are committed
- Ensure all affected parties are informed and prepared for changes

### Goals
- Reduce disruptions from unapproved or untracked changes
- Maintain a clear audit trail for all key decisions

### Interactions
- Works closely with Project Managers to coordinate timing and communication
- Notifies Developers and QA of required actions from changes
- Engages Product Managers when product/business scope is impacted

### Typical Communication
- Change request logs
- Change impact assessments
- All-hands or stakeholder updates regarding upcoming changes

---

## Communication Lead

### Role Summary
The Communication Lead centralizes and coordinates all outbound communication to stakeholders, ensuring alignment and continuity of project messaging.

### Responsibilities
- Develop communication plans for major phases and milestones
- Act as the primary contact for external and internal communications
- Gather feedback from stakeholders and route it to the appropriate team members

### Goals
- Improve stakeholder satisfaction and engagement
- Minimize confusion or misalignment through clear, timely messaging

### Interactions
- Collaborates with Project Managers and Product Managers for coordinated announcements
- Supports all roles in sharing key information and updates

### Typical Communication
- Stakeholder newsletters and updates
- Project kickoff or milestone briefings
- Feedback reporting

---

## Quality Assurance Analyst

### Role Summary
QA Analysts define and execute test plans, validate deliverables against requirements, and advocate for process and product improvements.

### Responsibilities
- Define quality metrics and test plans for deliverables
- Execute manual and automated tests; report defects
- Participate in retrospectives to suggest improvements

### Goals
- Ensure deliverables meet or exceed quality standards
- Reduce escaped defects and production issues

### Interactions
- Works with Developers to resolve bugs and clarify requirements
- Coordinates with Project Managers on release readiness

### Typical Communication
- Test reports and sign-off documents
- Defect/bug trackers
- QA status updates and reports

---

## External Stakeholder Liaison

### Role Summary
This role coordinates communication and requirements between the project team and external stakeholders such as clients, partners, or regulatory bodies.

### Responsibilities
- Collect, document, and share requirements from external stakeholders
- Communicate project status and action items to external parties
- Track commitments and ensure responses are timely

### Goals
- Minimize misunderstandings and unmet expectations with externals
- Ensure regulatory or partner requirements are met

### Interactions
- Works with Communication Lead for official updates
- Informs Product and Project Managers of external requirements and deadlines

### Typical Communication
- Formal meeting notes and requirements documents
- Partner/client status updates

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

### Role Interaction Map

| Persona                   | Primary Interactions                                             |
|---------------------------|------------------------------------------------------------------|
| Developers                | Product Managers, QA Analysts, Project Managers                  |
| Product Managers          | Developers, Project Managers, Change Managers, Communication Lead|
| Project Managers          | Developers, Product Managers, Change Managers, Communication Lead|
| Change Manager            | Project Managers, Developers, Product Managers, QA Analysts      |
| Communication Lead        | Project Managers, Product Managers, External Stakeholder Liaison |
| QA Analyst                | Developers, Project Managers, Change Manager                     |
| External Stakeholder Liaison | Communication Lead, Product Managers, Project Managers         
