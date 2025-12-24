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

---

## Scrum Master

### Role Summary
The Scrum Master facilitates Agile ceremonies, removes blockers, and ensures the team follows Scrum principles for efficient sprint execution.

### Responsibilities
- Facilitate daily standups, sprint planning, reviews, and retrospectives
- Remove impediments and blockers that impact team velocity
- Coach the team on Agile and Scrum best practices
- Shield the team from external disruptions and scope changes mid-sprint
- Track and improve team metrics (velocity, cycle time, burndown)

### Interaction Points
- **Developers**: Daily standups, sprint planning, removing blockers
- **Product Owner**: Sprint planning, backlog refinement, aligning on priorities
- **Project Manager**: Coordination on timelines, risks, and status updates
- **QA Lead**: Sprint reviews, ensuring quality gates are met

### RACI - Typical Activities
- **Sprint Planning**: Responsible (facilitates), Consulted (Product Owner, team)
- **Sprint Execution**: Accountable (team delivery), Responsible (removing blockers)
- **Risk Escalation**: Informed, escalates team-level issues to PM
- **Release**: Consulted (ensures sprint commitments align with release goals)

### Goals
- Maximize team productivity and sprint predictability
- Foster continuous improvement through retrospectives
- Maintain team focus and minimize disruptions

---

## Product Owner

### Role Summary
The Product Owner maximizes product value by defining priorities, managing the backlog, and ensuring features align with business goals and user needs.

### Responsibilities
- Own and prioritize the product backlog based on business value
- Define acceptance criteria and ensure features meet requirements
- Represent customer and stakeholder needs to the development team
- Make trade-off decisions on scope, timelines, and feature priorities
- Accept or reject completed work based on acceptance criteria

### Interaction Points
- **Product Managers**: Strategic alignment, roadmap planning, metrics
- **Scrum Master**: Sprint planning, backlog refinement, prioritization
- **Developers**: Clarifying requirements, acceptance criteria, feature demos
- **Stakeholder Representative**: Gathering input, communicating progress

### RACI - Typical Activities
- **Planning**: Accountable (backlog prioritization), Responsible (acceptance criteria)
- **Execution**: Consulted (clarifications), Informed (progress updates)
- **Release**: Accountable (feature sign-off), Responsible (release content decisions)
- **Risk Escalation**: Informed, makes trade-off decisions on scope

### Goals
- Deliver maximum business value each sprint
- Maintain a clear, prioritized backlog
- Ensure alignment between development and business objectives

---

## Release Manager

### Role Summary
The Release Manager coordinates release planning, deployment activities, and post-release monitoring to ensure smooth and reliable production rollouts.

### Responsibilities
- Plan and coordinate release schedules and deployment windows
- Manage release readiness reviews and go/no-go decisions
- Coordinate with QA, DevOps, and development on release activities
- Oversee deployment execution and rollback procedures if needed
- Track and report on release metrics and post-deployment health

### Interaction Points
- **QA Lead**: Release sign-off, test completion verification
- **Developers**: Code freeze, hotfix coordination, deployment support
- **Project Manager**: Release timelines, risk assessment, stakeholder communication
- **DevOps/SRE**: Deployment execution, infrastructure readiness, monitoring

### RACI - Typical Activities
- **Planning**: Consulted (release timeline input)
- **Execution**: Informed (sprint progress relevant to releases)
- **Release**: Accountable (release coordination), Responsible (deployment execution)
- **Risk Escalation**: Responsible (release risks), escalates to PM for critical issues

### Goals
- Achieve zero-downtime deployments where possible
- Minimize production incidents related to releases
- Maintain predictable and reliable release cadence

---

## QA Lead

### Role Summary
The QA Lead ensures product quality by defining testing strategies, coordinating test activities, and validating that features meet acceptance criteria before release.

### Responsibilities
- Define test strategy and quality gates for features and releases
- Coordinate test planning and execution across QA team
- Review and approve test coverage and test results
- Sign off on release readiness from a quality perspective
- Track quality metrics (defect rates, test coverage, escape rate)

### Interaction Points
- **Developers**: Test planning, bug triage, quality feedback in PRs
- **Release Manager**: Release sign-off, test completion confirmation
- **Product Owner**: Acceptance criteria validation, feature quality expectations
- **Scrum Master**: Sprint planning, quality concerns escalation

### RACI - Typical Activities
- **Planning**: Consulted (test effort estimation, quality requirements)
- **Execution**: Responsible (test execution), Accountable (quality assurance)
- **Release**: Accountable (quality sign-off), blocks release if quality gates not met
- **Risk Escalation**: Responsible (quality risks), reports to PM and Product Owner

### Goals
- Prevent defects from reaching production
- Maintain high test coverage and automation rates
- Enable fast, confident releases through comprehensive testing

---

## Stakeholder Representative

### Role Summary
The Stakeholder Representative voices the interests of key business stakeholders, provides input on priorities, and ensures alignment between project outcomes and business needs.

### Responsibilities
- Represent stakeholder interests in planning and prioritization discussions
- Provide business context and requirements from stakeholder perspective
- Review and provide feedback on project deliverables and roadmaps
- Communicate project status and outcomes back to stakeholder groups
- Raise concerns or blockers related to business alignment

### Interaction Points
- **Product Owner**: Prioritization input, business requirements, feedback
- **Product Manager**: Strategic alignment, roadmap review, success metrics
- **Project Manager**: Status updates, risk awareness, decision input
- **PMO Liaison**: Portfolio-level updates, resource or priority conflicts

### RACI - Typical Activities
- **Planning**: Consulted (business priorities, requirements input)
- **Execution**: Informed (status updates, milestone progress)
- **Release**: Informed (release communications), validates business impact
- **Risk Escalation**: Consulted (business impact assessment), may escalate to executives

### Goals
- Ensure project delivers expected business outcomes
- Maintain stakeholder engagement and satisfaction
- Provide timely feedback and decision-making support

---

## Development Lead

### Role Summary
The Development Lead provides technical leadership, makes architectural decisions, and ensures code quality and technical consistency across the development team.

### Responsibilities
- Define technical architecture and design patterns
- Review and approve complex technical designs and PRs
- Mentor developers on coding standards and best practices
- Identify and mitigate technical risks and technical debt
- Coordinate with other technical leads on cross-team dependencies

### Interaction Points
- **Developers**: Code reviews, technical mentoring, design discussions
- **Product Owner**: Technical feasibility, effort estimation, trade-offs
- **Scrum Master**: Sprint planning, technical blocker resolution
- **Security/Compliance Rep**: Security reviews, compliance requirements

### RACI - Typical Activities
- **Planning**: Responsible (technical estimates), Consulted (architecture decisions)
- **Execution**: Accountable (code quality, technical delivery), reviews all major changes
- **Release**: Consulted (technical readiness, rollback plans)
- **Risk Escalation**: Responsible (technical risks), escalates to PM or CTO

### Goals
- Maintain high code quality and system reliability
- Foster technical growth within the development team
- Balance technical excellence with delivery timelines

---

## Project Coordinator

### Role Summary
The Project Coordinator supports the Project Manager by handling administrative tasks, coordinating meetings, tracking action items, and maintaining project documentation.

### Responsibilities
- Schedule and coordinate project meetings and communications
- Track action items, decisions, and meeting notes
- Maintain project documentation and status dashboards
- Support resource coordination and logistics
- Assist with status reporting and stakeholder communications

### Interaction Points
- **Project Manager**: Daily coordination, task delegation, status compilation
- **All team members**: Meeting scheduling, action item follow-up, documentation requests
- **PMO Liaison**: Status reporting, template compliance, documentation standards

### RACI - Typical Activities
- **Planning**: Responsible (meeting logistics, documentation), supports PM
- **Execution**: Responsible (tracking, documentation), Informed (project status)
- **Release**: Responsible (communication coordination), supports Release Manager
- **Risk Escalation**: Informed, tracks escalation actions and follow-ups

### Goals
- Enable efficient project operations and communication
- Ensure project information is organized and accessible
- Free up PM time for strategic activities

---

## PMO Liaison

### Role Summary
The PMO Liaison ensures alignment between individual projects and enterprise PMO standards, processes, and portfolio priorities.

### Responsibilities
- Ensure project follows PMO methodologies and reporting standards
- Coordinate portfolio-level dependencies and resource conflicts
- Provide guidance on PMO tools, templates, and governance requirements
- Escalate portfolio-level risks and issues to PMO leadership
- Support project audits and compliance reviews

### Interaction Points
- **Project Manager**: PMO compliance, portfolio updates, escalations
- **Project Coordinator**: Documentation standards, reporting templates
- **Stakeholder Representative**: Portfolio prioritization, resource allocation
- **PMO Leadership**: Portfolio reporting, risk escalations, governance issues

### RACI - Typical Activities
- **Planning**: Consulted (PMO standards, portfolio dependencies)
- **Execution**: Informed (project status for portfolio view)
- **Release**: Informed (release schedule for portfolio coordination)
- **Risk Escalation**: Responsible (portfolio-level escalations to PMO)

### Goals
- Maintain PMO governance and consistency across projects
- Optimize resource allocation at portfolio level
- Provide visibility into project health for leadership

---

## Security/Compliance Representative

### Role Summary
The Security/Compliance Representative ensures security best practices and regulatory compliance requirements are integrated throughout the project lifecycle.

### Responsibilities
- Review designs and code for security vulnerabilities and compliance
- Define security and compliance requirements for features
- Conduct security risk assessments and threat modeling
- Ensure proper security testing and audit requirements are met
- Support incident response for security-related issues

### Interaction Points
- **Development Lead**: Security reviews, threat modeling, secure coding guidance
- **Developers**: Security PR reviews, vulnerability remediation
- **QA Lead**: Security testing requirements, penetration test coordination
- **Release Manager**: Security sign-off for releases, deployment security

### RACI - Typical Activities
- **Planning**: Responsible (security/compliance requirements), must be consulted early
- **Execution**: Responsible (security reviews), Accountable (compliance adherence)
- **Release**: Accountable (security sign-off), can block release for security issues
- **Risk Escalation**: Responsible (security/compliance risks), escalates to CISO/Legal

### Goals
- Prevent security vulnerabilities in production
- Maintain compliance with regulatory requirements (GDPR, SOC2, etc.)
- Foster security-aware culture across the team

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

