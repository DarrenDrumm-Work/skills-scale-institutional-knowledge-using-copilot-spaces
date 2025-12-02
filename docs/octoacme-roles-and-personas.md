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
Change Managers oversee change management processes, ensuring that all changes are properly documented, communicated, and managed throughout the project lifecycle. They maintain the change log and coordinate with stakeholders to minimize disruption.

### Responsibilities
- Manage the change request process from initiation to closure
- Maintain and update the change log for all project changes
- Evaluate change impacts on scope, schedule, and resources
- Ensure changes are properly communicated to affected stakeholders
- Coordinate with Project Managers on change implementation timing
- Facilitate change review meetings and approvals
- Document lessons learned from significant changes

### Key Interactions
- **Project Manager**: Coordinate on scheduling and resource impacts
- **Communications Lead**: Ensure change notifications reach stakeholders
- **Developers**: Assess technical feasibility and impact
- **Product Managers**: Align changes with product priorities

### Reporting Lines
- Reports to: Project Manager
- Escalates to: Project Sponsor for high-impact changes

### Goals
- Minimize unplanned changes and scope creep
- Ensure changes are traceable and auditable
- Reduce change-related disruptions to project delivery
- Maintain stakeholder alignment on approved changes

### Typical Communication
- Weekly change review meetings
- Change request forms and impact assessments
- Change log updates and status reports
- Approval notifications

### Example Scenario
A stakeholder requests adding a new feature mid-sprint. The Change Manager evaluates the request using the change request form, assesses its impact on timeline and resources with the Project Manager and developers, presents the findings in the change review meeting, and documents the approved change in the change log with communication to all affected parties.

---

## Communications Lead

### Role Summary
Communications Leads are responsible for developing and executing internal and external communication plans. They ensure that project updates, announcements, and key messages are delivered to stakeholders consistently and effectively.

### Responsibilities
- Develop and maintain the project communications plan
- Craft project announcements, updates, and release communications
- Coordinate messaging across internal teams and external stakeholders
- Ensure consistent branding and tone in all communications
- Manage communication channels (email lists, Slack channels, newsletters)
- Measure communication effectiveness and adjust strategies

### Key Interactions
- **Project Manager**: Align on status updates and key milestones
- **Product Manager**: Coordinate on feature announcements and positioning
- **Stakeholder Engagement Coordinator**: Ensure stakeholder groups receive appropriate messaging
- **Marketing/PR (if applicable)**: Coordinate external communications

### Reporting Lines
- Reports to: Project Manager
- Collaborates with: Product Manager for messaging alignment

### Goals
- Ensure stakeholders are informed and aligned
- Reduce miscommunication and information gaps
- Increase stakeholder confidence through transparent updates
- Support successful change adoption through effective messaging

### Typical Communication
- Weekly stakeholder newsletters
- Release announcements and feature updates
- Meeting summaries and action item distributions
- Crisis communication when issues arise

### Example Scenario
Before a major release, the Communications Lead works with the Product Manager to draft release notes and user-facing announcements. They coordinate with the Stakeholder Engagement Coordinator to identify impacted user groups, schedule communication timing with the Project Manager, and distribute updates via email, Slack, and the project wiki.

---

## Quality Assurance Specialist

### Role Summary
Quality Assurance Specialists define and monitor quality criteria, advocate for process improvements, and ensure that deliverables meet acceptance standards before release. They bridge the gap between development and acceptance criteria validation.

### Responsibilities
- Define quality standards and acceptance criteria with Product Managers
- Create and maintain the quality acceptance checklist
- Review deliverables against defined quality criteria
- Identify quality risks and recommend mitigations
- Advocate for automated testing and quality tooling
- Report on quality metrics (defect rates, test coverage, etc.)
- Participate in retrospectives to improve quality processes

### Key Interactions
- **Developers**: Collaborate on test coverage and quality implementation
- **Product Managers**: Align on acceptance criteria and quality expectations
- **Project Manager**: Report quality status and risks
- **Team Leads**: Coordinate on quality improvement initiatives

### Reporting Lines
- Reports to: Project Manager (or Engineering Lead)
- Escalates to: Product Lead for acceptance criteria disputes

### Goals
- Ensure deliverables meet quality standards before release
- Reduce production defects and customer-facing issues
- Improve team quality practices over time
- Maintain clear traceability from requirements to acceptance

### Typical Communication
- Quality status in daily standups
- Defect triage meetings
- Quality acceptance signoff before releases
- Test coverage and metrics dashboards

### Example Scenario
Before a release, the Quality Assurance Specialist reviews the [Quality Acceptance Checklist](./quality-acceptance-checklist.md), verifies that all acceptance criteria are met, confirms test coverage meets team standards, and provides formal signoff. If issues are found, they document defects, work with developers to resolve them, and re-validate before approving the release.

---

## Stakeholder Engagement Coordinator

### Role Summary
Stakeholder Engagement Coordinators manage stakeholder analysis, ensure feedback is captured and addressed, and organize engagement sessions. They serve as the bridge between the project team and business stakeholders.

### Responsibilities
- Conduct stakeholder analysis and mapping
- Maintain the stakeholder engagement log
- Organize and facilitate stakeholder engagement sessions
- Capture and synthesize stakeholder feedback
- Track stakeholder concerns and ensure follow-up
- Collaborate with Communications Lead on stakeholder messaging
- Measure stakeholder satisfaction and engagement levels

### Key Interactions
- **Business Stakeholders**: Primary point of contact for engagement
- **Project Manager**: Align on stakeholder priorities and concerns
- **Communications Lead**: Coordinate on stakeholder communication
- **Product Manager**: Ensure stakeholder needs inform product decisions

### Reporting Lines
- Reports to: Project Manager
- Escalates to: Project Sponsor for stakeholder conflicts

### Goals
- Ensure stakeholder voices are heard and considered
- Reduce stakeholder-related project risks
- Maintain high stakeholder satisfaction and engagement
- Create clear documentation of stakeholder interactions and outcomes

### Typical Communication
- Stakeholder engagement sessions (monthly or milestone-based)
- Feedback summaries shared with project team
- Updates to the stakeholder engagement log
- Stakeholder satisfaction surveys

### Example Scenario
During the planning phase, the Stakeholder Engagement Coordinator identifies key stakeholder groups using the [Stakeholder Engagement Log](./stakeholder-engagement-log.md), schedules a kickoff engagement session, captures feedback on requirements and priorities, and shares a summary with the Product Manager and Project Manager to inform backlog prioritization.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

## Related Templates and Checklists
- [Change Management Checklist](./change-management-checklist.md)
- [Communications Plan Template](./communications-plan-template.md)
- [Quality Acceptance Checklist](./quality-acceptance-checklist.md)
- [Stakeholder Engagement Log](./stakeholder-engagement-log.md)

