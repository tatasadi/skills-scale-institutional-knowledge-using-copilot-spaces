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

## QA/Testing Lead

### Role Summary
QA/Testing Leads own quality assurance strategy, test planning, and validation of acceptance criteria. They collaborate with developers and product managers to ensure features meet defined quality standards before release.

### Responsibilities
- Plan and execute unit, integration, and end-to-end testing
- Validate acceptance criteria and sign off on feature readiness
- Maintain and update test documentation and test cases
- Identify and track quality issues and defects
- Participate in release readiness reviews and smoke testing
- Support incident triage and post-release verification

### Goals
- Ensure high-quality releases that meet customer expectations
- Provide clear quality signals and risk assessment
- Reduce defects reaching production

### Typical Communication
- Sprint planning and backlog refinement
- Test case reviews and QA sign-off
- Release checklists and pre-deployment testing

### Interactions with Other Roles
- **Developers**: Collaborate on test strategies and acceptance criteria; provide feedback on test coverage and quality concerns
- **Product Managers**: Validate acceptance criteria and ensure quality aligns with customer expectations
- **Project Managers**: Report quality metrics and risks; coordinate testing timelines and resource needs
- **Technical Leads**: Advise on technical testing approaches and automation strategies

---

## Stakeholder/Sponsor

### Role Summary
Sponsors and stakeholders provide business direction, strategic alignment, and approvals. They represent customer and business needs, approve project scope and timelines, and serve as escalation points for high-impact decisions.

### Responsibilities
- Provide business context and problem statements
- Approve project charters and resource allocation
- Review and validate success metrics and outcomes
- Escalate and resolve business-level blockers
- Communicate project status to broader organization

### Goals
- Ensure projects deliver measurable business value
- Maintain alignment between delivery and strategy
- Support team enablement and resource decisions

### Typical Communication
- Project kickoff and initiation reviews
- Monthly stakeholder updates
- Milestone sign-offs and release announcements

### Interactions with Other Roles
- **Project Managers**: Provide scope approvals and escalation support; receive regular status updates and risk notifications
- **Product Managers**: Collaborate on strategic direction, business metrics, and investment decisions
- **Developers**: Receive project context and strategic importance; may participate in demos and feedback sessions

---

## Technical Lead/Architect

### Role Summary
Technical Leads guide technical strategy, design decisions, and risk mitigation. They collaborate with developers, product managers, and project managers to ensure solutions are scalable, maintainable, and align with technical standards.

### Responsibilities
- Define technical approach and architecture for features
- Review technical designs and major code changes
- Identify and mitigate technical risks
- Ensure alignment with system-wide standards and patterns
- Mentor developers and support skill development
- Participate in dependency identification and cross-team coordination

### Goals
- Maintain code quality, scalability, and maintainability
- Reduce technical debt and rework
- Enable team to deliver sustainable solutions

### Typical Communication
- Technical design reviews and architecture discussions
- Code review and design feedback
- Risk identification and technical planning

### Interactions with Other Roles
- **Developers**: Provide technical guidance, code review, and mentorship; shape architecture and design standards
- **Project Managers**: Identify technical risks and dependencies; advise on schedule impact of technical decisions
- **QA/Testing Lead**: Recommend testing strategies and automation approaches; collaborate on technical quality standards
- **DevOps/Release Engineer**: Coordinate on infrastructure requirements, deployment strategy, and system integration

---

## Security/Compliance Officer

### Role Summary
Security and Compliance Officers ensure that projects meet security requirements, compliance standards, and risk mitigation practices. They integrate security into all phases of project delivery and maintain organizational compliance posture.

### Responsibilities
- Define security requirements and threat models for projects
- Conduct security reviews and risk assessments
- Ensure compliance with organizational and regulatory standards
- Review and approve security scanning and testing practices
- Manage security incident escalation and response
- Document security decisions and compliance artifacts

### Goals
- Deliver secure, compliant solutions that protect data and systems
- Reduce security vulnerabilities and compliance violations
- Build security awareness and best practices across teams

### Typical Communication
- Security requirements workshops and reviews
- Pre-release security scanning results and sign-off
- Incident response coordination and post-mortem reviews

### Interactions with Other Roles
- **Developers**: Advise on secure coding practices; participate in security design reviews and code audits
- **Project Managers**: Escalate security risks; ensure security activities are scheduled and tracked
- **Technical Leads**: Collaborate on security architecture and threat mitigation strategies
- **DevOps/Release Engineer**: Coordinate on security scanning, infrastructure hardening, and deployment security

---

## Scrum Master/Facilitator

### Role Summary
Scrum Masters and Process Facilitators enable team efficiency by removing blockers, facilitating ceremonies, and coaching the team on process improvements. They serve as servant leaders who support team productivity and continuous improvement.

### Responsibilities
- Facilitate daily standups, sprint planning, reviews, and retrospectives
- Identify and help remove blockers and impediments
- Coach the team on agile practices and process adherence
- Track sprint metrics and team velocity
- Facilitate team problem-solving and decision-making
- Promote psychological safety and continuous improvement

### Goals
- Maximize team velocity and delivery predictability
- Foster a culture of continuous improvement and learning
- Remove organizational impediments to delivery

### Typical Communication
- Daily standup facilitation
- Sprint planning and retrospective meetings
- Blocker escalation and resolution tracking

### Interactions with Other Roles
- **Project Managers**: Coordinate on process metrics and impediment escalation; support cross-team dependencies
- **Developers**: Remove blockers; facilitate team ceremonies and problem-solving sessions
- **Product Managers**: Clarify requirements and manage backlog flow; communicate impact of process changes
- **All Roles**: Coach on process adherence and facilitate collaboration across roles

---

## DevOps/Release Engineer

### Role Summary
DevOps and Release Engineers manage deployment pipelines, infrastructure, and release automation. They enable rapid, safe delivery to production and support incident response and rollback procedures.

### Responsibilities
- Maintain CI/CD pipelines and deployment automation
- Manage staging and production environments
- Execute deployments and post-deploy verification
- Support rollback and incident response procedures
- Monitor infrastructure health and alerts
- Ensure compliance with security and backup requirements

### Goals
- Enable fast, reliable deployments with minimal risk
- Maintain high system availability and observability
- Automate repetitive release tasks

### Typical Communication
- Pre-release planning and deployment window scheduling
- Post-deploy verification and incident triage
- CI/CD configuration and infrastructure planning

### Interactions with Other Roles
- **Developers**: Support CI/CD pipeline configuration; troubleshoot build and deployment issues
- **Project Managers**: Coordinate deployment windows and release schedules; report infrastructure status and risks
- **Technical Leads**: Collaborate on infrastructure design, deployment strategy, and system reliability
- **QA/Testing Lead**: Manage staging environments; support end-to-end and smoke testing in production-like environments
- **Security/Compliance Officer**: Implement security scanning in CI/CD; manage infrastructure compliance and hardening

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Review the "Interactions with Other Roles" sections to understand how cross-functional collaboration occurs in OctoAcme projects.
