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

## Business Sponsor / Executive Sponsor

### Role Summary
Business Sponsors own strategic sponsorship, funding decisions, and priority trade-offs. They provide executive direction and approval authority for significant scope, timeline, or resource changes. They receive milestone-level status and risk escalations.

### Responsibilities
- Provide strategic direction and business context for the project
- Approve funding, budget allocation, and resource commitments
- Make or escalate decisions on scope and priority trade-offs
- Review and approve major timeline or resource changes
- Escalate executive-level blockers and risks
- Receive and review milestone-level status and risk reports

### Goals
- Ensure project aligns with organizational strategy and objectives
- Maximize business value and ROI of project investments
- Reduce executive-level surprises and escalations

### Typical Communication
- Monthly or milestone-based status reviews
- Decision escalation meetings
- High-level risk and dependency updates
- Approval of scope, timeline, or budget changes

### Key Handoffs & Interactions
- **With Product Manager**: Approves business outcomes, provides strategic context
- **With Project Manager**: Approves major timeline, scope, or resource changes; receives escalated risks
- **With Developers & Technical Lead**: May participate in architecture or feasibility reviews for high-stakes decisions

---

## Technical Lead / Architect

### Role Summary
Technical Leads own technical direction, architecture decisions, integration design, and technical risk mitigation. They partner with developers on implementation and advise the Product Manager on feasibility and technical trade-offs.

### Responsibilities
- Define or review technical architecture and design decisions
- Ensure technical direction aligns with project goals and system constraints
- Identify and mitigate technical risks (performance, scalability, security, integration)
- Partner with Developers on implementation feasibility and approach
- Advise Product Manager on technical constraints and trade-offs
- Work with Project Manager to surface dependencies and decision points
- Facilitate technical design reviews and architecture discussions

### Goals
- Deliver a technically sound, scalable, and maintainable solution
- Reduce technical debt and rework
- Enable Developers to implement efficiently and with high quality

### Typical Communication
- Technical design reviews and architecture discussions
- Code reviews and design feedback
- Feasibility assessments and trade-off analysis
- Technical risk escalations

### Key Handoffs & Interactions
- **With Developers**: Partners on implementation, code reviews, and technical problem-solving
- **With Product Manager**: Advises on feasibility, timeline impact of technical decisions, and alternative approaches
- **With Project Manager**: Surfaces technical dependencies, decision points, and risks that impact schedule
- **With QA/Quality Lead**: Discusses testability and technical quality strategies

---

## UX / Design Lead

### Role Summary
UX/Design Leads own user research, experience design, usability validation, and design acceptance criteria. They ensure solutions are customer-centric and meet usability standards.

### Responsibilities
- Conduct or oversee user research and discovery
- Define user experience requirements and acceptance criteria
- Create and validate design solutions (wireframes, prototypes, final designs)
- Collaborate with Product Manager on customer outcomes and feature scope
- Work with Developers on feasibility and implementation details
- Partner with QA/Testing on usability testing and acceptance validation
- Document design decisions and design system updates

### Goals
- Deliver intuitive, accessible, and delightful user experiences
- Validate that solutions meet customer needs and expectations
- Reduce usability issues and user support burden

### Typical Communication
- Design reviews and feedback sessions
- User research findings and insights
- Usability test results and recommendations
- Design specification and documentation

### Key Handoffs & Interactions
- **With Product Manager**: Collaborates on customer outcomes, feature scope, and success metrics
- **With Developers**: Ensures design is implementable and provides implementation guidance
- **With QA/Testing**: Works together on usability testing, acceptance validation, and user scenario coverage

---

## QA / Quality Lead

### Role Summary
QA/Quality Leads define quality strategy, test coverage expectations, acceptance evidence, and release quality gates. They work across the team to ensure solutions meet acceptance criteria and quality standards.

### Responsibilities
- Define quality strategy, test coverage targets, and acceptance criteria
- Plan and execute testing (unit, integration, end-to-end, usability, security)
- Ensure acceptance criteria are met before release
- Work with Developers on testability and test automation
- Partner with Product Manager on acceptance criteria and feature validation
- Collaborate with Project Manager and Release Manager on quality gates
- Track and triage defects; escalate blockers and risks

### Goals
- Deliver solutions that meet acceptance criteria and quality standards
- Reduce production defects and customer-impacting issues
- Build confidence in release readiness

### Typical Communication
- Test plans and test case documentation
- Quality metrics and defect reports
- Test execution status and blockers
- Release readiness assessment and sign-off

### Key Handoffs & Interactions
- **With Developers**: Partners on test automation, testability, and quality practices
- **With Product Manager**: Validates acceptance criteria, feature completeness, and customer scenarios
- **With Project Manager & Release Manager**: Provides quality gate assessment for release decisions
- **With UX/Design Lead**: Collaborates on usability testing and acceptance validation

---

## Security and Privacy Partner

### Role Summary
Security and Privacy Partners identify security, privacy, compliance, and threat-modeling needs. They review relevant designs and release risks, ensuring security findings have owners and mitigations. They escalate critical issues through established incident and risk paths.

### Responsibilities
- Identify security, privacy, and compliance requirements for the project
- Conduct or oversee threat modeling and security architecture reviews
- Review designs, code, and deployments for security and privacy risks
- Ensure security and privacy acceptance criteria are defined and met
- Triage and track security findings with clear ownership and mitigation plans
- Escalate critical security issues through incident response channels
- Provide security and privacy guidance to Product Manager, Technical Lead, and Developers

### Goals
- Prevent security and privacy incidents and breaches
- Ensure compliance with relevant regulations and standards
- Build secure and privacy-respecting solutions

### Typical Communication
- Security review findings and recommendations
- Threat modeling and risk assessments
- Security acceptance criteria
- Critical security escalations and incident response

### Key Handoffs & Interactions
- **With Technical Lead**: Partners on architecture reviews and threat modeling
- **With Developers**: Provides security guidance and reviews code and designs
- **With QA/Testing**: Collaborates on security testing and validation
- **With Project Manager**: Escalates critical security risks and dependencies
- **With Sponsor/Executive**: Escalates critical security incidents requiring executive action

---

## Delivery / Release Manager

### Role Summary
Delivery/Release Managers coordinate release readiness, deployment windows, release notes, rollback planning, and cross-team handoffs. They work with the Project Manager on milestones and with QA/Quality on quality gates.

### Responsibilities
- Coordinate release planning and scheduling across teams
- Ensure all release prerequisites are met (testing, documentation, deployment scripts)
- Prepare release notes and deployment runbooks
- Manage rollback plans and mitigation strategies
- Coordinate deployment execution (staging, production)
- Verify post-deployment health and performance
- Facilitate release communication to stakeholders and customers
- Coordinate handoff to Operations and support teams

### Goals
- Execute smooth, low-risk releases with minimal disruption
- Reduce deployment-related incidents and rollbacks
- Ensure clear communication and stakeholder confidence in releases

### Typical Communication
- Release checklists and deployment readiness reviews
- Release notes and customer communications
- Deployment execution and post-deployment verification
- Incident response coordination during deployments

### Key Handoffs & Interactions
- **With Project Manager**: Tracks milestones and release schedule alignment
- **With QA/Quality Lead**: Validates quality gates and release readiness
- **With Developers**: Coordinates build artifacts, deployment scripts, and runbooks
- **With Operations/SRE**: Hands off deployment and post-release monitoring
- **With Sponsor/Stakeholders**: Communicates release status and impact

---

## Operations / Site Reliability Partner

### Role Summary
Operations/Site Reliability (SRE) Partners own operational readiness, observability, capacity, support handoff, and incident preparedness. They collaborate with the delivery team on reliability and with the Project Manager on operational risks.

### Responsibilities
- Define and track operational readiness requirements (monitoring, alerting, runbooks)
- Ensure systems are observable and can be debugged in production
- Plan and validate capacity for expected load and growth
- Prepare support teams for handoff (documentation, knowledge transfer, runbooks)
- Establish incident response procedures and on-call coverage
- Monitor production health post-release and triage operational issues
- Identify and mitigate operational risks (downtime, data loss, performance degradation)
- Partner with Technical Lead and Developers on reliability and performance

### Goals
- Maximize system uptime and availability
- Reduce mean-time-to-detection (MTTD) and mean-time-to-resolution (MTTR) of incidents
- Enable rapid incident response and recovery

### Typical Communication
- Operational readiness checklists and handoff documentation
- Monitoring, alerting, and observability design
- Incident reports and post-incident reviews
- Operational risks and capacity planning updates

### Key Handoffs & Interactions
- **With Technical Lead & Developers**: Collaborates on reliability, observability, and performance optimization
- **With Release Manager**: Coordinates deployment verification and post-release monitoring
- **With Project Manager**: Provides operational risk assessments and readiness status
- **With Support & Customer Success**: Hands off runbooks, incident playbooks, and support procedures

---

## Responsibility and Interaction Matrix

| Project Phase | Accountability | Consulted | Informed |
|---|---|---|---|
| **Initiation** | Business Sponsor, Product Manager | Technical Lead, Project Manager | Developers, QA/Quality Lead, Operations |
| **Planning** | Project Manager, Product Manager | Technical Lead, Developers, QA/Quality Lead | UX/Design Lead, Security Partner, Operations, Release Manager, Business Sponsor |
| **Design & Development** | Technical Lead, Developers | UX/Design Lead, QA/Quality Lead, Security Partner | Project Manager, Product Manager, Operations |
| **Testing & Quality** | QA/Quality Lead | Developers, UX/Design Lead, Security Partner | Project Manager, Product Manager, Release Manager |
| **Release** | Release Manager, QA/Quality Lead | Project Manager, Operations, Technical Lead | Business Sponsor, Support teams |
| **Post-Release & Operations** | Operations/SRE | Technical Lead, Developers, Release Manager | Project Manager, Business Sponsor, Support teams |
| **Retrospective** | Project Manager | All roles | Business Sponsor |

---

## Decision Ownership & Escalation

### Technical Decisions
- **Owner**: Technical Lead (with input from Developers)
- **Escalation**: If impacting timeline or resources → Project Manager → Business Sponsor
- **Escalation**: If impacting security or performance → Security Partner or Operations → Project Manager

### Feature Scope & Prioritization
- **Owner**: Product Manager (with input from Business Sponsor)
- **Escalation**: If impacting timeline or resources → Project Manager → Business Sponsor

### Quality & Release Readiness
- **Owner**: QA/Quality Lead
- **Escalation**: If quality gates not met → Project Manager → Business Sponsor for scope or timeline trade-off decision

### Security & Compliance
- **Owner**: Security and Privacy Partner
- **Escalation**: Critical findings → Security Partner + Project Manager → Business Sponsor + Security leadership

### Operational Readiness
- **Owner**: Operations/SRE Partner
- **Escalation**: Readiness blockers → Project Manager + Release Manager → Business Sponsor

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the responsibility matrix and interaction patterns when planning cross-functional handoffs and decision points.
