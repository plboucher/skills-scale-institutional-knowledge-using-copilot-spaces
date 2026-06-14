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

## Delivery Lead

### Role Summary
Delivery Leads own day-to-day execution and operational excellence. They focus on removing blockers, maintaining team velocity, and ensuring milestones are met. They bridge product/project planning with development execution.

### Responsibilities
- Monitor sprint health and team capacity
- Identify and escalate blockers in real time
- Facilitate daily standups and iteration planning
- Track burn-down and flag velocity trends early
- Coordinate with PM and Project Manager on scope adjustments
- Manage technical debt and maintenance work balance
- Support incident response and post-mortems

### Goals
- Maximize predictable delivery cadence
- Reduce cycle time and handoff delays
- Keep the team unblocked and focused
- Build sustainable, repeatable delivery practices

### Interaction with Other Roles
- Works closely with **Developers** to prioritize work and remove obstacles
- Coordinates with **Project Manager** on scheduling and cross-team dependencies
- Collaborates with **Product Manager** on scope clarity and acceptance criteria
- Partners with **Tech Lead** on technical feasibility and refactoring priorities
- Reports metrics to **Project Manager** for stakeholder communication

### Typical Communication
- Daily standup facilitation
- Velocity and burn-down charts
- Blocker escalations and incident reports
- Weekly delivery health reviews

---

## Tech Lead

### Role Summary
Tech Leads provide technical strategy, architecture guidance, and code quality oversight. They mentor developers, make critical technical decisions, and ensure scalability and maintainability of the solution.

### Responsibilities
- Define technical architecture and design patterns
- Conduct code reviews and enforce quality standards
- Mentor developers and support technical growth
- Identify technical risks and propose mitigations
- Make go/no-go decisions on technical approaches
- Plan and prioritize technical debt reduction
- Coordinate with Security Engineer and Release Engineer on technical requirements

### Goals
- Deliver scalable, maintainable solutions
- Build a strong engineering culture of quality
- Reduce long-term maintenance burden
- Enable team autonomy and confidence

### Interaction with Other Roles
- Mentors **Developers** on best practices and design decisions
- Collaborates with **Delivery Lead** on refactoring and technical debt scheduling
- Works with **Product Manager** on feasibility and trade-offs
- Partners with **Security Engineer** on threat modeling and secure design
- Supports **Release Engineer** on deployment architecture

### Typical Communication
- Technical design reviews and RFCs
- Code review comments and feedback
- Architecture documentation and decisions
- Technical spike findings and recommendations

---

## UX Designer

### Role Summary
UX Designers define user experiences, validate usability, and ensure accessibility standards are met. They advocate for the user's perspective throughout the project lifecycle and collaborate closely with product and development teams.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and design specifications
- Define user workflows and interaction patterns
- Ensure WCAG accessibility compliance
- Participate in feature grooming and acceptance criteria definition
- Validate shipped features against user goals
- Support product and development teams on UX best practices

### Goals
- Deliver intuitive, accessible user experiences
- Reduce user friction and support burden
- Validate product-market fit through user feedback
- Build inclusive products

### Interaction with Other Roles
- Partners with **Product Manager** on user research and validation
- Collaborates with **Developers** on implementation feasibility and design system usage
- Works with **QA/Testing** on usability and accessibility test coverage
- Supports **Project Manager** on UX-related timeline and resource planning
- Advises **Delivery Lead** on UX acceptance criteria clarity

### Typical Communication
- Design specs and wireframes
- Usability testing findings and recommendations
- Design system updates and usage guidelines
- Accessibility checklist and validation

---

## Release Engineer

### Role Summary
Release Engineers own build automation, deployment pipelines, and operational readiness. They ensure reliable, repeatable deployments and minimize deployment-related risks and downtime.

### Responsibilities
- Design and maintain CI/CD pipelines
- Automate build, test, and deployment processes
- Manage deployment environments and infrastructure
- Coordinate release planning and deployment windows
- Create and test rollback procedures
- Monitor deployments and respond to deployment issues
- Document deployment runbooks and troubleshooting guides

### Goals
- Enable fast, safe, reliable deployments
- Reduce deployment errors and rollback incidents
- Minimize deployment-related downtime
- Automate repetitive operational tasks

### Interaction with Other Roles
- Collaborates with **Tech Lead** on deployment architecture and infrastructure requirements
- Works with **Developers** on test automation and CI configuration
- Coordinates with **Project Manager** on release timing and stakeholder communication
- Partners with **Security Engineer** on deployment security and secrets management
- Supports **QA/Testing** on staging environment setup and test automation

### Typical Communication
- CI/CD pipeline status and optimization reports
- Release runbooks and deployment procedures
- Incident reports and post-mortems
- Infrastructure and tooling recommendations

---

## Security Engineer

### Role Summary
Security Engineers embed security practices throughout the project lifecycle. They conduct threat assessments, define security requirements, and ensure compliance with security standards and regulations.

### Responsibilities
- Conduct threat modeling and security reviews
- Define security requirements and acceptance criteria
- Perform security code reviews and vulnerability scanning
- Ensure compliance with security policies and standards
- Support incident response and security investigations
- Recommend security tools and practices
- Participate in security training and awareness programs

### Goals
- Prevent security vulnerabilities and breaches
- Build security into the design and development process
- Maintain regulatory compliance and trust
- Enable rapid and confident security incident response

### Interaction with Other Roles
- Works with **Tech Lead** on secure design and architecture reviews
- Collaborates with **Developers** on secure coding practices and vulnerability remediation
- Partners with **Release Engineer** on secrets management and secure deployment
- Coordinates with **Project Manager** on security-related timeline impacts
- Advises **QA/Testing** on security test coverage and penetration testing

### Typical Communication
- Threat model documentation and security reviews
- Vulnerability reports and remediation recommendations
- Security policy and compliance checklists
- Incident response coordination

---

## Data Analyst / Data Engineer

### Role Summary
Data Analysts and Engineers define metrics, build instrumentation, and analyze product and operational data. They provide data-driven insights to support decision-making and measure project success.

### Responsibilities
- Define success metrics and KPIs aligned with project goals
- Design data collection and instrumentation strategy
- Build dashboards and reporting tools
- Analyze trends and provide insights to stakeholders
- Support A/B testing and experimentation
- Ensure data quality and governance
- Identify operational anomalies and investigate root causes

### Goals
- Measure and demonstrate project impact
- Enable data-driven decision-making
- Reduce guesswork in prioritization and optimization
- Build organizational data literacy

### Interaction with Other Roles
- Partners with **Product Manager** on success metrics definition and analysis
- Collaborates with **Developers** on instrumentation implementation
- Works with **Delivery Lead** on operational metrics (velocity, cycle time)
- Supports **Project Manager** on stakeholder reporting and dashboards
- Advises **Tech Lead** on logging and observability architecture

### Typical Communication
- Metric definitions and dashboards
- Weekly or milestone-based analytics reports
- Experimentation design and results
- Data quality and anomaly alerts

---

## Customer Success / Support Liaison

### Role Summary
Customer Success Liaisons represent the customer and support perspectives within project teams. They ensure solutions address real customer needs and are operationally supportable by the support organization.

### Responsibilities
- Gather customer feedback and pain points
- Participate in feature grooming to ensure customer viability
- Validate features meet customer expectations
- Coordinate with support teams on training and documentation needs
- Identify support risks and operational concerns early
- Gather and prioritize customer-reported issues and feature requests
- Support go-to-market planning and customer communication

### Goals
- Deliver customer-centric solutions
- Reduce post-launch support burden
- Increase customer satisfaction and retention
- Build feedback loops for continuous improvement

### Interaction with Other Roles
- Collaborates with **Product Manager** on customer needs and feature validation
- Works with **Developers** on feature usability and support-friendly design
- Coordinates with **Project Manager** on training and documentation planning
- Partners with **UX Designer** on user experience validation
- Advises **Release Engineer** on support readiness and runbook completeness

### Typical Communication
- Customer feedback summaries and pain point analysis
- Feature validation reports
- Support readiness checklists and training materials
- Go-to-market and customer communication plans

---

## Business Analyst

### Role Summary
Business Analysts translate business requirements into structured specifications and ensure alignment between business objectives and technical delivery. They serve as a bridge between stakeholders, product, and engineering.

### Responsibilities
- Gather and document business requirements
- Create detailed process flows and specifications
- Validate that solutions align with business objectives
- Identify and analyze business impacts and dependencies
- Support ROI analysis and business case development
- Facilitate stakeholder workshops and requirements sessions
- Document business rules and compliance requirements

### Goals
- Ensure business objectives are clearly understood and delivered
- Reduce scope creep and rework through clear requirements
- Maximize business value realization
- Enable informed business trade-off decisions

### Interaction with Other Roles
- Works with **Product Manager** on requirements translation and prioritization
- Collaborates with **Developers** on specification clarity and feasibility
- Partners with **Project Manager** on scope and stakeholder management
- Coordinates with **Tech Lead** on business rule implementation
- Advises **Compliance Officer** on regulatory and policy implications

### Typical Communication
- Requirements specifications and process flows
- Business case and ROI analysis
- Stakeholder alignment documents
- Trade-off analysis and recommendations

---

## Compliance / Privacy Officer

### Role Summary
Compliance and Privacy Officers ensure solutions adhere to regulatory requirements, data protection standards, and organizational policies. They identify and mitigate compliance risks and guide the team through regulatory obligations.

### Responsibilities
- Assess regulatory and compliance requirements for the project
- Conduct compliance impact assessments
- Define data privacy and protection requirements
- Review and approve security and data handling practices
- Maintain compliance documentation and audit trails
- Support compliance audits and investigations
- Recommend compliance tools and controls
- Stay current on regulatory changes affecting the project

### Goals
- Ensure regulatory compliance and avoid penalties
- Protect customer and company data
- Build trust through transparent compliance practices
- Enable confident regulatory audits and investigations

### Interaction with Other Roles
- Works with **Security Engineer** on data protection and security controls
- Collaborates with **Tech Lead** on compliance-relevant architecture decisions
- Partners with **Business Analyst** on regulatory requirement translation
- Coordinates with **Release Engineer** on compliance in deployment and infrastructure
- Advises **Project Manager** on compliance-related timeline and risk management
- Supports **Developers** on compliant data handling practices

### Typical Communication
- Compliance assessment and impact analysis
- Privacy and data protection policies and procedures
- Compliance checklists and audit documentation
- Regulatory update notifications and guidance

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Cross-reference interaction models to understand handoffs and collaboration points across the project lifecycle.
