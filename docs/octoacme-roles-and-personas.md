# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders or Sponsors are executive or business leaders who provide strategic direction, budget allocation, and approval authority for projects. They ensure alignment with organizational strategy and maintain visibility into project health and risks.

### Responsibilities
- Provide strategic context and business objectives for the project
- Approve project charter, scope, and major changes
- Allocate budget, resources, and personnel
- Escalate and resolve organizational blockers
- Receive executive status reports and make go/no-go decisions
- Champion the project within the broader organization

### Goals
- Ensure projects deliver business value aligned with organizational strategy
- Minimize project delays and cost overruns
- Maintain transparency and governance over cross-functional work
- Support teams by removing organizational obstacles

### Interaction with Other Roles
- **Product Manager**: Reviews roadmap prioritization and business impact assessments
- **Project Manager**: Receives escalations on significant risks or resource constraints
- **Technical Lead**: Engaged for major technical trade-off decisions
- **Stakeholder Communication**: Primary audience for monthly executive updates and gate reviews

### Typical Communication
- Monthly executive updates on project status, risks, and budget
- Ad-hoc escalation meetings for high-impact issues
- Go/no-go decision gates at project initiation and major milestones
- Quarterly alignment on roadmap and strategic priorities

### When to Involve
- Project initiation and charter approval
- Major scope changes or resource requests
- Risk escalation (Level 3 blockers)
- Go/no-go decision points for releases
- Stakeholder communication and reporting

---

## Technical Lead / Architect

### Role Summary
Technical Leads or Architects provide technical guidance, design authority, and risk assessment throughout the project. They ensure technical decisions are sound, scalable, and aligned with organizational standards.

### Responsibilities
- Review technical design and architecture decisions
- Identify and assess technical risks and mitigation strategies
- Ensure code quality standards and best practices are followed
- Provide guidance on technology choices and trade-offs
- Mentor developers and support knowledge sharing
- Validate that solutions meet performance and scalability requirements

### Goals
- Deliver technically sound, maintainable solutions
- Reduce technical debt and long-term maintenance burden
- Enable team growth through mentoring and knowledge sharing
- Ensure architectural consistency across the organization

### Interaction with Other Roles
- **Developers**: Reviews design decisions, code quality, and technical approaches
- **Product Manager**: Discusses technical feasibility of features and trade-offs
- **Project Manager**: Identifies technical risks and dependencies for planning
- **DevOps/Platform Engineer**: Collaborates on deployment architecture and infrastructure needs
- **Security Officer**: Reviews architecture for security implications

### Typical Communication
- Design review meetings before development begins
- Code review feedback and architectural guidance
- Weekly technical syncs with development team
- Risk assessment and mitigation planning
- Architecture decision records and documentation

### When to Involve
- Project planning phase (technical feasibility assessment)
- Design phase (architecture and design reviews)
- Development (code review and technical mentoring)
- Risk identification (technical risks and dependencies)
- Release planning (performance and scalability validation)

---

## Product Manager

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics
- Write acceptance criteria and user stories
- Track and communicate success metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability
- Enable fast iteration based on feedback

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs
- Success metrics tracking and reporting

---

## Project Manager

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication
- Track and report on project health and metrics

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders
- Enable smooth cross-functional collaboration

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation
- Daily standups and progress tracking

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
- Contribute to code quality and maintainability

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability
- Support team learning and best practices

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed
- Collaboration on acceptance criteria and edge cases

---

## Design / UX Lead

### Role Summary
Design or UX Leads ensure that features meet usability and user experience standards. They advocate for the user perspective and collaborate with product and development teams to balance functionality, usability, and technical feasibility.

### Responsibilities
- Define user experience requirements and acceptance criteria
- Create wireframes, prototypes, and design specifications
- Conduct user research and usability testing
- Collaborate with developers to ensure designs are implemented correctly
- Review finished features against design specifications
- Provide guidance on accessibility and inclusivity standards

### Goals
- Deliver delightful user experiences that drive adoption and satisfaction
- Reduce post-release usability issues and user complaints
- Ensure features are accessible to all user segments
- Balance user needs with technical and business constraints

### Interaction with Other Roles
- **Product Manager**: Aligns on feature requirements and user stories
- **Developers**: Reviews implementation against design specifications
- **QA/Testing**: Provides design acceptance criteria and edge cases
- **Stakeholders**: Presents user research findings and design rationale

### Typical Communication
- Design workshops during planning and discovery phases
- Design reviews with development team before implementation
- Feedback on implementation during development and QA phases
- User research presentations to stakeholders

### When to Involve
- Project planning (user research and requirements)
- Design phase (wireframes and specifications)
- Development (design reviews and feedback)
- QA phase (acceptance criteria validation)
- Release planning (usability verification)

---

## Security / Compliance Officer

### Role Summary
Security or Compliance Officers ensure that projects meet security requirements, compliance standards, and organizational policies. They assess risk, validate controls, and provide guidance on secure development practices.

### Responsibilities
- Review features for security implications and risks
- Validate compliance with regulatory and organizational standards
- Recommend security controls and mitigation strategies
- Review code and architecture for security vulnerabilities
- Participate in threat modeling and risk assessment
- Provide secure coding guidelines and training

### Goals
- Prevent security incidents and data breaches
- Ensure regulatory compliance and organizational alignment
- Embed security into the development process early
- Reduce post-release security remediation work

### Interaction with Other Roles
- **Product Manager**: Discusses compliance requirements for features
- **Technical Lead**: Reviews architecture and design for security implications
- **Developers**: Provides secure coding guidance and code review feedback
- **Project Manager**: Identifies security risks and dependencies for planning
- **DevOps/Platform Engineer**: Reviews deployment security and access controls

### Typical Communication
- Security requirements gathering during planning
- Threat modeling and risk assessment workshops
- Security code review feedback
- Compliance validation and sign-off before release
- Monthly security update and vulnerability briefings

### When to Involve
- Project planning (security requirements and compliance needs)
- Design phase (threat modeling and security architecture)
- Development (secure coding guidance and review)
- Testing (security testing and validation)
- Pre-release (compliance sign-off)

---

## DevOps / Platform Engineer

### Role Summary
DevOps or Platform Engineers manage deployment infrastructure, CI/CD pipelines, and operational readiness. They ensure features can be reliably deployed, monitored, and supported in production.

### Responsibilities
- Design and maintain CI/CD pipelines and deployment infrastructure
- Ensure applications can be deployed reliably and rolled back if needed
- Provide monitoring, logging, and observability solutions
- Manage infrastructure capacity and performance
- Participate in incident response and post-incident reviews
- Provide operational runbooks and deployment procedures

### Goals
- Enable fast, safe, and reliable deployments
- Minimize deployment failures and production incidents
- Reduce time to detect and resolve production issues
- Scale infrastructure efficiently to support business growth

### Interaction with Other Roles
- **Developers**: Provides CI/CD best practices and deployment procedures
- **Technical Lead**: Collaborates on infrastructure architecture and scalability planning
- **Project Manager**: Identifies deployment windows and operational dependencies
- **Security Officer**: Reviews access controls and operational security practices
- **QA/Testing**: Coordinates smoke testing and production verification

### Typical Communication
- Infrastructure planning during project planning phase
- CI/CD pipeline design and configuration reviews
- Deployment coordination and go-live activities
- Incident response and post-incident retrospectives
- Operational metrics and performance reviews

### When to Involve
- Project planning (infrastructure and deployment needs)
- Design phase (scalability and operational architecture)
- Development (CI/CD integration and feedback)
- Pre-release (deployment readiness and testing)
- Release (deployment coordination and monitoring)

---

## Quality Assurance Manager

### Role Summary
Quality Assurance Managers lead test strategy, define testing standards, and coordinate QA activities. They ensure features meet acceptance criteria and quality standards before release.

### Responsibilities
- Develop comprehensive test plans and test cases
- Define testing standards and best practices
- Coordinate manual and automated testing efforts
- Identify and triage defects
- Validate release readiness against acceptance criteria
- Identify patterns in quality issues and recommend improvements

### Goals
- Deliver high-quality features that meet acceptance criteria
- Reduce defects found in production
- Enable fast, confident releases
- Continuously improve testing practices and efficiency

### Interaction with Other Roles
- **Product Manager**: Clarifies acceptance criteria and success metrics
- **Developers**: Coordinates integration testing and defect triage
- **Technical Lead**: Reviews test approach for complex features
- **Design Lead**: Validates UI/UX implementation against design specifications
- **Project Manager**: Provides test status and release readiness assessments

### Typical Communication
- Test planning workshops during project planning
- Defect triage and prioritization meetings
- Test progress reports in weekly standups
- Release readiness sign-off before deployment
- Post-release quality metrics and improvement recommendations

### When to Involve
- Project planning (test strategy and approach)
- Design phase (test case planning)
- Development (integration testing and feedback)
- QA phase (comprehensive testing and validation)
- Release (release readiness and sign-off)

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference these personas when clarifying responsibilities and decision authority in project discussions.
