# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core Project Delivery Roles

### Developers

#### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

#### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

#### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

#### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

#### Collaborates With
- Product Managers (on requirements and acceptance criteria)
- Project Managers (on scheduling and dependencies)
- QA/Testing (on test coverage and quality)
- DevOps Engineers (on deployment and infrastructure)

---

### Product Managers

#### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

#### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics
- Work with Business Analysts to translate requirements

#### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

#### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

#### Collaborates With
- Project Managers (on timelines and dependencies)
- Developers (on feasibility and tradeoffs)
- UX/UI Designers (on user experience and design)
- Business Analysts (on requirements clarity)
- Customer Support Liaison (on customer feedback and support readiness)

---

### Project Managers

#### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

#### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication
- Track progress against milestones and escalate blockers

#### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

#### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

#### Collaborates With
- Product Managers (on prioritization and scope)
- Developers (on estimates and progress)
- All other roles (for scheduling, dependencies, and communication)

---

## Extended Project Team Roles

### UX/UI Designers

#### Role Summary
UX/UI Designers create user-centered designs, interactions, and visual experiences. They ensure that products are intuitive, accessible, and aligned with user needs and business goals.

#### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and design specs
- Collaborate on user flows and interaction patterns
- Ensure accessibility and design consistency across products
- Participate in design reviews and iterate based on feedback
- Document design decisions and provide design system guidance

#### Goals
- Deliver intuitive and delightful user experiences
- Reduce support burden through clear, usable interfaces
- Maintain design consistency and brand alignment

#### Typical Communication
- Design kickoff and requirements gathering sessions
- Design review meetings with Product and Development teams
- Usability testing reports and findings
- Design documentation and component specifications

#### Collaborates With
- Product Managers (on user needs and requirements)
- Developers (on feasibility and implementation)
- Project Managers (on timeline and resource planning)
- Customer Support Liaison (on user feedback and pain points)

#### Decision Rights
- Final approval on user experience and visual design
- Input on feature prioritization based on user impact
- Participates in acceptance criteria definition

---

### DevOps Engineers

#### Role Summary
DevOps Engineers own infrastructure, build automation, deployment pipelines, and system monitoring. They ensure reliable, scalable, and secure systems that support rapid, safe delivery.

#### Responsibilities
- Design and maintain CI/CD pipelines
- Manage infrastructure, cloud resources, and automation
- Monitor system health, performance, and security
- Support deployment planning and release execution
- Establish observability, logging, and alerting
- Respond to and help diagnose production incidents
- Work with developers on deployment standards and best practices

#### Goals
- Enable fast, safe, and repeatable releases
- Maintain system reliability, security, and performance
- Reduce time-to-resolution for incidents

#### Typical Communication
- Deployment planning and release coordination meetings
- Infrastructure design and architecture reviews
- Incident response and post-mortems
- Runbooks and deployment documentation

#### Collaborates With
- Developers (on deployment, infrastructure requirements, and incident response)
- Project Managers (on release scheduling and deployment windows)
- QA/Testing (on test environment setup and deployment verification)

#### Decision Rights
- Owns deployment standards and infrastructure decisions
- Provides input on feasibility of delivery timelines
- Escalates production incidents and recovery needs

---

### Business Analysts

#### Role Summary
Business Analysts bridge business stakeholders and technical teams by gathering requirements, translating business needs into technical specifications, and validating solutions against business objectives.

#### Responsibilities
- Gather and document business requirements
- Translate requirements into functional specifications
- Map business processes and identify improvement opportunities
- Validate solutions against business needs and success metrics
- Facilitate communication between business and technical teams
- Support testing and acceptance criteria validation
- Document standard operating procedures and workflows

#### Goals
- Ensure solutions deliver on business objectives
- Reduce rework and scope creep through clear requirements
- Enable smooth handoff to support and operations

#### Typical Communication
- Requirements gathering and refinement sessions
- Stakeholder interviews and documentation
- Requirements review meetings with Product and Development
- Process documentation and standard operating procedures

#### Collaborates With
- Product Managers (on requirement refinement and prioritization)
- Project Managers (on scope and timeline impacts)
- Developers (on feasibility and technical constraints)
- Compliance Lead (on regulatory and policy requirements)
- Customer Support Liaison (on operational procedures and training needs)

#### Decision Rights
- Validates acceptance criteria align with business requirements
- Escalates scope or requirement changes that impact timelines or resources
- Approves standard operating procedures and documentation

---

### Compliance Lead

#### Role Summary
Compliance Leads identify regulatory, legal, and policy requirements that impact the project. They ensure that solutions embed necessary controls and meet organizational governance standards.

#### Responsibilities
- Identify applicable regulations and compliance requirements
- Review solution designs and implementations for compliance
- Define controls and security measures to be built into the product
- Coordinate compliance reviews and approvals
- Document compliance decisions and rationale
- Provide guidance on data handling, privacy, and security practices
- Escalate compliance risks and mitigation plans

#### Goals
- Ensure products meet regulatory and organizational requirements
- Minimize compliance-related rework and release delays
- Build trust through transparent compliance practices

#### Typical Communication
- Compliance review checkpoints during planning and execution
- Regulatory requirement briefings and guidance
- Risk assessments and mitigation plans
- Post-release compliance verification and audits

#### Collaborates With
- Product Managers (on regulatory impact of features)
- Business Analysts (on compliance requirements translation)
- Developers (on control implementation and security)
- Project Managers (on compliance-driven timeline impacts)
- DevOps Engineers (on infrastructure and data security)

#### Decision Rights
- Blocks release if compliance gaps are identified
- Approves compliance controls and security measures
- Escalates regulatory risks requiring sponsor approval

---

### Customer Support Liaison

#### Role Summary
Customer Support Liaisons represent customer needs and support operations in project delivery. They ensure that solutions are supportable, bring customer feedback to prioritization decisions, and drive support readiness for new features.

#### Responsibilities
- Gather and communicate customer feedback and pain points
- Escalate customer issues and feature requests to the team
- Ensure new features include adequate documentation and training materials
- Review designs and implementations for supportability
- Participate in acceptance testing from a support perspective
- Develop support runbooks, FAQs, and troubleshooting guides
- Plan support team training and onboarding for new features

#### Goals
- Reduce support burden and customer escalations
- Improve time-to-resolution for customer issues
- Enhance customer satisfaction through proactive support readiness

#### Typical Communication
- Customer feedback and issue reports
- Support readiness review meetings
- Acceptance testing from support operations perspective
- Support documentation and training materials

#### Collaborates With
- Product Managers (on customer priorities and feedback)
- UX/UI Designers (on usability issues and user feedback)
- Developers (on troubleshooting and edge cases)
- Project Managers (on support readiness timeline)
- Business Analysts (on operational procedures and training needs)

#### Decision Rights
- Escalates customer-impacting issues and feature requests
- Blocks release if support readiness gaps exist
- Approves support documentation and training materials

---

## Role Interaction Matrix

| Role | Primary Decision Authority | Key Dependencies | Communication Frequency |
|------|---------------------------|------------------|------------------------|
| **Product Manager** | What to build, prioritization, success metrics | Stakeholders, Customers, Engineering | Weekly sync with PM, ongoing with team |
| **Project Manager** | Timeline, resource allocation, risk management | All roles, stakeholders | Daily standup, weekly risk review |
| **Developer** | How to build, technical design, code quality | PM, Design, DevOps, QA | Daily standup, code reviews, planning |
| **UX/UI Designer** | User experience, visual design, interaction patterns | Product, Developers, Support Liaison | Weekly design review, ongoing collaboration |
| **DevOps Engineer** | Infrastructure, deployment, monitoring, security | Developers, QA, Compliance | Release planning, incident response |
| **Business Analyst** | Requirements clarity, process design, acceptance | Product, Developers, Compliance, Support | Requirements gathering, reviews, validation |
| **Compliance Lead** | Regulatory adherence, security controls | Product, Developers, DevOps, BA | Compliance checkpoints, risk assessment |
| **Customer Support Liaison** | Support readiness, customer feedback integration | Product, Design, Developers, BA | Requirements gathering, testing, releases |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When running retrospectives or planning sessions, reference the appropriate personas and collaboration points to ensure all perspectives are represented.
