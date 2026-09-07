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

## Additional Roles

The roles below are referenced across OctoAcme's execution, release, risk management, and retrospective documents but were not previously defined here. Adding them closes gaps in accountability and gives teams a clear reference for who owns quality, business context, technical direction, process facilitation, security/compliance, and production support.

## QA / QA Lead

### Role Summary
QA Lead owns quality strategy, acceptance testing, and quality metrics. Works with Product and Engineering to define and validate acceptance criteria and ensure features meet quality standards before release.

### Responsibilities
- Define quality acceptance criteria alongside product and engineering
- Create and maintain test plans, including unit, integration, and end-to-end test coverage
- Execute or coordinate QA testing for features in development and releases
- Track quality metrics and identify trends
- Participate in retrospectives to improve quality processes
- Coordinate with operations on production issue triage and root cause analysis

### Goals
- Deliver high-quality features that meet customer expectations
- Reduce production incidents through comprehensive testing
- Make quality decisions transparent and data-driven

### Typical Communication
- Sprint planning and acceptance criteria definition sessions
- QA status updates during execution standups
- Quality metrics reviews in milestone retrospectives
- Post-release smoke test coordination

### Interaction with Other Roles
- **With Product Managers**: Define and refine acceptance criteria
- **With Developers**: Coordinate testing strategy and edge case coverage
- **With Project Managers**: Report quality risks and blockers
- **With Support/Operations**: Triage production issues and validate fixes

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, funding, and organizational priorities for a project. They approve resource allocation, validate that outcomes align with strategic goals, and are escalation points for major decisions and blockers.

### Responsibilities
- Provide business context, goals, and success criteria for the project
- Approve budget, staffing, and other resource allocation decisions
- Review and sign off on major milestones and scope changes
- Escalate and help resolve blockers outside the team's control
- Represent the interests of the broader organization or customer base

### Goals
- Ensure the project delivers expected business value
- Keep the project aligned with organizational strategy and priorities
- Enable timely decisions on scope, budget, and risk trade-offs

### Typical Communication
- Kickoff and milestone review meetings
- Executive status reports and steering committee updates
- Escalation calls or emails when blockers threaten delivery

### Interaction with Other Roles
- **With Project Managers**: Receive status updates and escalation requests; approve scope or resource changes
- **With Product Managers**: Validate that the roadmap reflects business priorities
- **With Engineering/Tech Lead**: Weigh in on trade-offs that affect budget, timeline, or risk
- **With Security/Compliance Officer**: Review and accept residual risk on compliance matters

---

## Engineering / Tech Lead

### Role Summary
The Engineering/Tech Lead provides technical direction for a project, owns key architecture decisions, and ensures the engineering team can deliver a maintainable, scalable solution. They act as the primary technical escalation point for the team.

### Responsibilities
- Define and document architecture and technical design decisions
- Provide technical guidance and mentorship to developers
- Identify, track, and mitigate technical risks and tech debt
- Review designs and code for consistency, security, and scalability
- Partner with Product and Project Managers on technical feasibility and estimates

### Goals
- Ensure technical decisions support long-term maintainability and scalability
- Reduce technical risk and unplanned rework
- Maintain a healthy, consistent engineering standard across the team

### Typical Communication
- Architecture and design review sessions
- Technical risk updates in planning and status meetings
- Design docs, RFCs, and code review guidance

### Interaction with Other Roles
- **With Developers**: Provide technical guidance, review designs and code
- **With Product Managers**: Advise on technical feasibility and trade-offs
- **With Project Managers**: Surface technical risks and dependencies for planning
- **With Security/Compliance Officer**: Incorporate security requirements into architecture
- **With Support/Operations Lead**: Ensure designs meet operability requirements

---

## Scrum Master / Delivery Coordinator

### Role Summary
The Scrum Master/Delivery Coordinator facilitates team ceremonies, removes blockers, and coaches the team on process adherence. They help the team stay focused on delivery while continuously improving how the team works.

### Responsibilities
- Facilitate ceremonies such as standups, planning, and retrospectives
- Identify and help remove blockers impeding the team's progress
- Coach the team on agile practices and process adherence
- Track team velocity and delivery health metrics
- Foster a collaborative, continuous-improvement team culture

### Goals
- Keep the team focused, unblocked, and delivering predictably
- Improve team processes through regular retrospectives
- Support healthy team dynamics and collaboration

### Typical Communication
- Daily standups, sprint planning, and retrospectives
- Blocker escalation messages to Project Managers or leadership
- Process improvement notes and action items

### Interaction with Other Roles
- **With Project Managers**: Coordinate on schedules, risks, and blocker escalation
- **With Developers**: Facilitate ceremonies and remove day-to-day impediments
- **With Product Managers**: Help ensure backlog is ready for planning
- **With Stakeholders/Sponsors**: Communicate delivery health and process changes

---

## Security / Compliance Officer

### Role Summary
The Security/Compliance Officer ensures that projects meet security and regulatory requirements. They review designs and releases for security risk, and manage compliance obligations throughout the project lifecycle.

### Responsibilities
- Define and communicate security and compliance requirements
- Review architecture, designs, and releases for security risk
- Track and manage compliance-related risks and remediation plans
- Support incident response and post-incident compliance reporting
- Advise on data handling, privacy, and regulatory obligations

### Goals
- Minimize security vulnerabilities and compliance gaps
- Ensure releases meet applicable regulatory and organizational standards
- Enable fast, informed risk-based decision-making

### Typical Communication
- Security design reviews and threat modeling sessions
- Compliance risk updates in risk management reviews
- Incident response communications and post-incident reports

### Interaction with Other Roles
- **With Engineering/Tech Lead**: Review architecture and designs for security requirements
- **With Developers**: Provide guidance on secure coding practices and remediation
- **With Project Managers**: Report compliance risks for the risk register
- **With Stakeholders/Sponsors**: Escalate and obtain sign-off on residual risk
- **With Support/Operations Lead**: Coordinate on incident response and monitoring

---

## Support / Operations Lead

### Role Summary
The Support/Operations Lead bridges product delivery and production support. They define operability requirements, manage the transition of new releases into production support, and ensure issues are triaged and resolved efficiently.

### Responsibilities
- Define operability, monitoring, and alerting requirements for new features
- Own the handoff process from delivery teams to production support
- Triage, prioritize, and coordinate resolution of production incidents
- Provide feedback to product and engineering on recurring operational issues
- Maintain runbooks and support documentation

### Goals
- Ensure smooth, low-risk transitions from delivery to production support
- Reduce mean time to detect and resolve production issues
- Improve long-term system reliability through operational feedback

### Typical Communication
- Release readiness and operability review sessions
- Incident triage and status updates
- Post-incident reviews and operational feedback to delivery teams

### Interaction with Other Roles
- **With Engineering/Tech Lead**: Validate designs meet operability requirements
- **With QA/QA Lead**: Coordinate on production issue triage and root cause analysis
- **With Developers**: Provide feedback on recurring issues and request fixes
- **With Project Managers**: Report on operational risks and incident status
- **With Security/Compliance Officer**: Coordinate on incident response and monitoring

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

