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
QA/Testing Leads define quality standards, create test strategies, and ensure all deliverables meet acceptance criteria and quality benchmarks before release.

### Responsibilities
- Define test plans and QA approach for each initiative
- Create and maintain test cases aligned with acceptance criteria
- Coordinate manual and automated testing activities
- Identify and track quality issues and regressions
- Participate in acceptance and sign-off processes
- Report quality metrics and testing coverage to PM and Project Manager

### Goals
- Ensure high-quality, reliable releases with minimal defects
- Reduce post-release incidents and customer impact
- Establish consistent quality standards across projects

### Typical Communication
- Sprint planning and daily standups
- QA status updates in weekly syncs
- Defect reports and test case documentation

### Cross-Role Interactions

**With Developers**: QA/Testing Leads collaborate closely with Developers to understand implementation details, review test coverage, and work together to resolve defects. Developers provide test data and support automated testing setup; QA provides feedback on code quality and identifies edge cases.

**With Product Managers**: QA/Testing Leads partner with Product Managers to clarify acceptance criteria, validate that features meet business requirements, and ensure test cases align with user stories. Product Managers define what "done" looks like; QA validates it's actually done.

**With Project Managers**: QA/Testing Leads report to Project Managers on testing progress, quality metrics, and any blockers that impact release timelines. Project Managers coordinate QA resources and escalate quality issues that affect delivery schedules.

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, approve initiatives, allocate resources, and receive regular updates on project progress and outcomes.

### Responsibilities
- Review and approve project charter and scope
- Provide business and strategic guidance
- Allocate budget and resources for initiatives
- Attend key milestone reviews and decision gates
- Receive and review status updates and reports
- Escalate cross-organizational blockers and dependencies

### Goals
- Ensure projects deliver measurable business value
- Maintain strategic alignment with organizational goals
- Reduce delays and resource contention

### Typical Communication
- Monthly stakeholder updates and milestone reviews
- Decision gate approvals (initiation, planning, release)
- Escalation communications for high-impact risks

### Cross-Role Interactions

**With Developers**: Stakeholders/Sponsors interact with Developers primarily through Project Managers and Product Managers, attending demos and providing high-level feedback on delivered features. They ensure Developers understand the business value and strategic importance of their work.

**With Product Managers**: Stakeholders/Sponsors work closely with Product Managers to align on business priorities, approve roadmap direction, and ensure features deliver measurable business outcomes. Product Managers provide data to support investment decisions.

**With Project Managers**: Stakeholders/Sponsors rely on Project Managers for regular status updates, risk escalation, and resource allocation decisions. Project Managers inform Stakeholders when strategic changes or additional resources are needed to meet business goals.

---

## Security / Compliance Officer

### Role Summary
Security and Compliance Officers ensure that projects meet security, privacy, and regulatory requirements and that proper incident response and data handling procedures are followed.

### Responsibilities
- Review features for security and privacy implications
- Define security acceptance criteria and compliance requirements
- Review code for security vulnerabilities
- Participate in incident response and post-incident reviews
- Ensure secure data handling and audit compliance
- Coordinate with external compliance and audit teams

### Goals
- Prevent security incidents and data breaches
- Maintain regulatory and compliance standing
- Embed security practices into the development lifecycle

### Typical Communication
- Security reviews and design discussions
- Incident response notifications and updates
- Compliance reporting and audit support

### Cross-Role Interactions

**With Developers**: Security/Compliance Officers work with Developers to establish secure coding practices, review pull requests for vulnerabilities, and provide security training. Developers integrate security controls during implementation and participate in threat modeling sessions.

**With Product Managers**: Security/Compliance Officers define security and privacy acceptance criteria with Product Managers, ensuring compliance requirements are factored into feature scope and prioritization. Product Managers advocate for user privacy in feature design.

**With Project Managers**: Security/Compliance Officers notify Project Managers of security-related blockers, compliance deadlines, and audit requirements. Project Managers allocate time for security reviews and ensure compliance work is included in project schedules.

---

## Technical Lead / Architect

### Role Summary
Technical Leads and Architects provide technical vision, design guidance, and ensure that solutions are scalable, maintainable, and aligned with technical standards.

### Responsibilities
- Define technical approach and architecture for initiatives
- Conduct design reviews and provide technical guidance
- Identify technical risks and propose mitigation strategies
- Ensure alignment with technical standards and best practices
- Mentor developers and support knowledge sharing
- Advocate for technical debt reduction and refactoring

### Goals
- Build scalable, maintainable, and performant systems
- Reduce technical debt and complexity
- Foster a culture of technical excellence

### Typical Communication
- Technical design reviews and architecture discussions
- Sprint planning and backlog refinement
- Code reviews and technical mentoring

### Cross-Role Interactions

**With Developers**: Technical Leads/Architects mentor Developers on design patterns, architecture decisions, and best practices. Developers implement architectural guidance, participate in design reviews, and provide feedback on technical feasibility and implementation challenges.

**With Product Managers**: Technical Leads/Architects advise Product Managers on technical feasibility, estimate technical complexity of features, and identify technical risks that impact timelines. Product Managers understand technical constraints when prioritizing the roadmap.

**With Project Managers**: Technical Leads/Architects inform Project Managers of technical blockers, dependency risks, and effort estimates. Project Managers plan around technical work and escalate technical risks that threaten project schedules.

---

## Release Manager / DevOps Engineer

### Role Summary
Release Managers and DevOps Engineers coordinate deployments, maintain infrastructure, and ensure reliable, observable systems in production.

### Responsibilities
- Plan and schedule release activities
- Prepare and execute deployment processes
- Maintain CI/CD pipelines and infrastructure
- Monitor deployed systems and respond to incidents
- Document rollback and recovery procedures
- Coordinate with on-call teams and incident response

### Goals
- Enable frequent, reliable deployments to production
- Maintain high system availability and performance
- Reduce deployment risk and mean time to recovery

### Typical Communication
- Release planning and coordination meetings
- Deployment notifications and post-deploy verifications
- Incident response and status updates

### Cross-Role Interactions

**With Developers**: Release Managers/DevOps Engineers work with Developers to set up CI/CD pipelines, ensure code is deployment-ready, and troubleshoot production incidents. Developers provide deployment artifacts and support incident investigation.

**With Product Managers**: Release Managers/DevOps Engineers coordinate with Product Managers on release timing, feature toggles for phased rollouts, and deployment windows. Product Managers communicate business priorities for incident response and rollback decisions.

**With Project Managers**: Release Managers/DevOps Engineers provide Project Managers with deployment schedules, infrastructure readiness, and incident status. Project Managers coordinate release communications and escalate infrastructure issues that impact timelines.

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters and Agile Coaches facilitate iterative delivery, remove impediments, and help teams continuously improve their processes and practices.

### Responsibilities
- Facilitate sprint planning, daily standups, and retrospectives
- Remove impediments and blockers blocking team progress
- Coach teams on agile practices and continuous improvement
- Maintain sprint boards and track velocity metrics
- Support team health and psychological safety
- Communicate process improvements and lessons learned

### Goals
- Maximize team velocity and delivery predictability
- Create a culture of continuous improvement
- Enable self-organizing, high-performing teams

### Typical Communication
- Daily standups and sprint ceremonies
- Retrospective facilitation and action item tracking
- Coaching and mentoring interactions

### Cross-Role Interactions

**With Developers**: Scrum Masters/Agile Coaches facilitate Developer ceremonies, remove technical and process blockers, and foster psychological safety. Developers provide input on process improvements and help identify impediments during standups.

**With Product Managers**: Scrum Masters/Agile Coaches work with Product Managers during backlog refinement and sprint planning, ensuring the team has clarity on priorities and acceptance criteria. Product Managers participate in retrospectives to understand velocity trends and planning challenges.

**With Project Managers**: Scrum Masters/Agile Coaches collaborate with Project Managers on release planning, sprint capacity planning, and risk tracking. Project Managers leverage sprint metrics and retrospective insights to inform broader project planning and resource allocation.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Cross-role interactions help teams understand dependencies, communication patterns, and how to collaborate effectively across functional boundaries.
