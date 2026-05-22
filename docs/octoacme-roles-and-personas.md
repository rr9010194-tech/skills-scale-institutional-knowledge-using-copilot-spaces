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

## QA Lead

### Role Summary
QA Leads oversee quality assurance practices, define testing strategies, and coordinate defect management. They ensure that features meet acceptance criteria and quality standards before release.

### Responsibilities
- Develop and maintain testing strategies aligned with project scope
- Plan test coverage (unit, integration, end-to-end, performance)
- Coordinate QA activities across the delivery team
- Identify and triage defects; track resolution through the workflow
- Collaborate with Developers on test automation and CI/CD integration
- Validate acceptance criteria and sign off on feature readiness
- Document known issues and edge cases

### Goals
- Ensure high-quality releases with minimal production defects
- Build confidence in the product through rigorous testing
- Enable fast feedback cycles on quality

### Typical Communication
- QA sync meetings during planning and execution
- Defect reports and test coverage dashboards
- Acceptance sign-offs in PR reviews and release checklists

### Interaction with Other Roles
- **Developers**: Collaborate on test automation, coverage, and defect resolution
- **Product Managers**: Validate acceptance criteria and prioritize testing effort
- **Project Managers**: Provide quality metrics and escalate critical blockers

---

## UX Designer

### Role Summary
UX Designers create user-centered solutions by designing intuitive user flows, interface mockups, and interaction patterns. They bridge the gap between user needs and technical implementation.

### Responsibilities
- Conduct user research and translate findings into design requirements
- Create wireframes, prototypes, and visual designs
- Collaborate with Product Managers to refine requirements and user stories
- Work with Developers to ensure designs are implemented correctly
- Conduct usability testing and iterate based on feedback
- Maintain design systems and component libraries
- Ensure accessibility and inclusive design practices

### Goals
- Deliver intuitive, accessible, and delightful user experiences
- Reduce friction in user workflows
- Align design with product strategy and brand

### Typical Communication
- Design review sessions with Product Managers and Developers
- Acceptance criteria that include UX/UI specifications
- Design system documentation and component guidelines

### Interaction with Other Roles
- **Product Managers**: Define user needs and feature requirements
- **Developers**: Collaborate on implementation details and technical constraints
- **QA Lead**: Define usability acceptance criteria

---

## DevOps Engineer

### Role Summary
DevOps Engineers manage infrastructure, CI/CD pipelines, and deployment automation. They enable fast, reliable releases and maintain system observability.

### Responsibilities
- Design and maintain CI/CD pipelines for build, test, and deployment
- Provision and manage infrastructure (cloud, containers, services)
- Implement deployment automation and rollback procedures
- Monitor system performance, logs, and alerts
- Coordinate with Developers on build failures and environment issues
- Document deployment procedures and runbooks
- Plan and execute infrastructure scaling and upgrades

### Goals
- Enable rapid, safe deployments with minimal manual effort
- Maintain system reliability and observability
- Reduce deployment friction and time-to-production

### Typical Communication
- Build and deployment status dashboards
- Infrastructure and CI/CD documentation
- Deployment scheduling and runbook reviews

### Interaction with Other Roles
- **Developers**: Support troubleshooting of build/test failures
- **Project Managers**: Coordinate deployment windows and schedules
- **Security Lead**: Implement security controls and scanning in pipelines

---

## Security Lead

### Role Summary
Security Leads advise on security best practices, conduct threat modeling, and ensure that security controls are built into products and processes. They work across teams to mitigate vulnerabilities and comply with security policies.

### Responsibilities
- Conduct threat modeling and security architecture reviews
- Review code and architecture for security vulnerabilities
- Define security requirements and acceptance criteria
- Coordinate security scanning in CI/CD pipelines
- Investigate security incidents and define remediation plans
- Advise on authentication, authorization, and data protection
- Maintain security documentation and runbooks
- Lead security training and awareness

### Goals
- Build security into the product lifecycle from the start
- Minimize security risks and compliance violations
- Ensure rapid response to security incidents

### Typical Communication
- Security review meetings and threat modeling sessions
- Security acceptance criteria in project backlogs
- Incident response communications

### Interaction with Other Roles
- **Developers**: Collaborate on secure coding practices and vulnerability fixes
- **DevOps Engineers**: Implement security controls in infrastructure and CI/CD
- **Project Managers**: Escalate security risks and incidents
- **QA Lead**: Coordinate security testing and acceptance criteria

---

## Delivery Lead

### Role Summary
Delivery Leads drive project execution by removing roadblocks, aligning cross-team work, and surfacing delivery risks. They work closely with Project Managers and Product Leads to ensure smooth, on-time delivery.

### Responsibilities
- Identify and escalate blockers and dependencies in real-time
- Coordinate work between teams (engineering, design, QA, security)
- Facilitate daily standups and sprint ceremonies
- Surface delivery risks and propose mitigation strategies
- Track progress against milestones and alert stakeholders to deviations
- Manage external dependencies and coordinate with partner teams
- Maintain delivery dashboards and status reporting

### Goals
- Deliver projects on schedule without scope creep
- Minimize delays caused by cross-team dependencies
- Maintain alignment and transparency across stakeholders

### Typical Communication
- Daily standups and delivery status reports
- Risk escalations and dependency tracking
- Stakeholder updates and milestone reviews

### Interaction with Other Roles
- **Project Managers**: Partner on planning and risk management
- **Product Managers**: Align on priority and scope adjustments
- **All Delivery Team Members**: Remove blockers and facilitate collaboration
- **External Stakeholders**: Coordinate dependencies and approvals

---

## External Stakeholder

### Role Summary
External Stakeholders represent teams, organizations, or partners whose input, approval, or coordination is required at key milestones. They provide business context, constraints, and decision authority.

### Responsibilities
- Review and approve milestone deliverables as needed
- Provide business requirements and constraints
- Coordinate with external teams on dependencies
- Participate in key ceremonies (kickoff, reviews, planning)
- Escalate risks and issues within their organizations
- Provide feedback on releases and product direction

### Goals
- Ensure alignment between internal projects and external business needs
- Reduce coordination friction with partner teams
- Provide clear, timely decisions to unblock work

### Typical Communication
- Monthly stakeholder updates and milestone reviews
- Email approvals and decision gates
- Ad-hoc escalation and coordination calls

### Interaction with Other Roles
- **Project Managers**: Receive status updates and approve milestones
- **Product Managers**: Provide business context and feature prioritization input
- **Delivery Lead**: Coordinate dependencies and approval gates

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
