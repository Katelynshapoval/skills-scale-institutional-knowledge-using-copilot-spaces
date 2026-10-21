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

## Additional Cross-Functional Personas

### Executive Sponsor

#### Role Summary
Provides strategic sponsorship, funding alignment, and organizational support so the team can deliver outcomes that matter to the business.

#### Responsibilities
- Confirm strategic fit and success outcomes at initiation
- Approve major scope, funding, or priority changes
- Remove cross-org blockers escalated by Product Managers or Project Managers
- Champion stakeholder alignment during high-risk or high-visibility delivery

#### Goals
- Ensure initiatives deliver measurable business value
- Reduce decision latency for critical trade-offs
- Keep executive stakeholders aligned on outcomes and risk

#### Typical Communication
- Initiation and quarterly alignment reviews
- Monthly stakeholder updates with Product Managers and Project Managers
- Escalation briefings for critical risks or delivery conflicts

#### Decision Rights
- Final approval on go/no-go for major initiatives
- Approval on major scope, timeline, or investment changes

#### Expected Artifacts
- Sponsor approval notes (charter/one-pager sign-off)
- Escalation decisions and priority directives

#### Lifecycle Touchpoints
- Initiation: approves one-pager direction and success criteria
- Planning: confirms major milestone and funding alignment
- Execution: resolves escalated cross-functional conflicts
- Release: approves risk acceptance for high-impact launches
- Retrospective: reviews major outcomes and systemic improvements

#### Interactions with Existing Roles
- Product Managers: aligns strategy, value, and priority decisions
- Project Managers: supports risk escalation and dependency resolution
- Developers: indirect, typically via trade-off decisions

---

### Business Analyst

#### Role Summary
Translates business and stakeholder needs into clear requirements, workflows, and acceptance criteria that delivery teams can execute.

#### Responsibilities
- Elicit and document functional/non-functional requirements
- Clarify workflows, edge cases, and business rules
- Partner with Product Managers on backlog readiness
- Support QA/Test Lead with testable acceptance criteria

#### Goals
- Reduce ambiguity before work enters execution
- Improve quality of backlog items and acceptance criteria
- Increase shared understanding across business and engineering

#### Typical Communication
- Requirement workshops and stakeholder interviews
- Backlog refinement with Product Managers, Developers, and QA/Test Lead
- Clarification follow-ups during execution

#### Decision Rights
- Recommends requirement interpretations and traceability
- Approves requirement completeness before planning commitments

#### Expected Artifacts
- Requirements summaries and process flows
- Refined acceptance criteria and scope clarifications
- Requirement-to-test traceability notes

#### Lifecycle Touchpoints
- Initiation: shapes problem statement and measurable outcomes
- Planning: refines backlog and dependency assumptions
- Execution: resolves requirement questions and scope boundaries
- Release: validates readiness against intended business flows
- Retrospective: identifies requirement-quality improvements

#### Interactions with Existing Roles
- Product Managers: co-own backlog clarity and business value translation
- Project Managers: align requirement changes with timeline/risk impacts
- Developers: clarify implementation expectations and edge cases

---

### UX/Product Designer

#### Role Summary
Owns user experience discovery and design to ensure solutions are usable, accessible, and aligned with customer needs.

#### Responsibilities
- Conduct user research and synthesize findings
- Create interaction flows, wireframes, and design specifications
- Validate usability before and after implementation
- Partner with Developers on feasibility and implementation fidelity

#### Goals
- Deliver intuitive and accessible user experiences
- Reduce rework caused by late usability findings
- Improve adoption and customer satisfaction

#### Typical Communication
- Discovery sessions with Product Managers and Business Analyst
- Design reviews with Developers and Technical Lead/Architect
- Usability findings shared with Project Managers and stakeholders

#### Decision Rights
- Approves UX patterns, interaction flows, and design standards
- Recommends design trade-offs when scope or timeline pressure occurs

#### Expected Artifacts
- Personas/journey updates, wireframes, prototypes
- Design specs and acceptance criteria notes for UX quality
- Usability findings and recommendations

#### Lifecycle Touchpoints
- Initiation: validates user problem framing
- Planning: defines design deliverables and UX acceptance criteria
- Execution: supports implementation reviews and design QA
- Release: verifies final UX quality and messaging alignment
- Retrospective: feeds usability learnings into future planning

#### Interactions with Existing Roles
- Product Managers: align user outcomes and feature priorities
- Project Managers: plan design milestones and cross-team handoffs
- Developers: ensure feasible and accurate implementation

---

### Technical Lead/Architect

#### Role Summary
Guides technical direction, architecture decisions, and engineering risk management across delivery and release activities.

#### Responsibilities
- Define architecture boundaries, integration patterns, and standards
- Lead technical design reviews and implementation trade-offs
- Surface and mitigate technical risks and debt
- Partner with DevOps, Security, and QA on release readiness

#### Goals
- Maintain system reliability, scalability, and maintainability
- Reduce architecture-related delivery risk
- Enable predictable technical execution across teams

#### Typical Communication
- Technical design docs and architecture review sessions
- Ongoing collaboration with Developers and QA/Test Lead
- Escalation of technical risks to Project Managers and Product Managers

#### Decision Rights
- Final technical authority on architecture and integration choices
- Approval for major technical deviations from agreed standards

#### Expected Artifacts
- Architecture/design decision records
- Integration and dependency plans
- Technical risk and mitigation updates

#### Lifecycle Touchpoints
- Initiation: assesses feasibility and key constraints
- Planning: validates estimates and technical sequencing
- Execution: governs design quality and technical risk burn-down
- Release: approves technical readiness, rollback feasibility, and observability
- Retrospective: identifies architecture/process improvements

#### Interactions with Existing Roles
- Developers: direct mentorship and implementation alignment
- Product Managers: align scope with technical constraints
- Project Managers: coordinate sequencing, dependencies, and escalation

---

### QA/Test Lead

#### Role Summary
Defines and coordinates quality strategy so releases meet acceptance criteria, reliability expectations, and risk thresholds.

#### Responsibilities
- Define test strategy across functional, integration, and release checks
- Ensure test coverage maps to acceptance criteria and risk
- Coordinate defect triage and quality evidence for readiness decisions
- Partner with Developers and DevOps on automated and smoke testing

#### Goals
- Prevent defect leakage into production
- Provide transparent quality status for decision-making
- Improve repeatability of verification activities

#### Typical Communication
- Test planning with Product Managers, Business Analyst, and Developers
- Defect triage with Developers and Project Managers
- Release quality summaries for stakeholder visibility

#### Decision Rights
- Recommends release readiness from a quality perspective
- Approves test exit criteria completion

#### Expected Artifacts
- Test strategy and test plan
- Test results, defect reports, and quality gates summary
- Release verification and smoke-test evidence

#### Lifecycle Touchpoints
- Initiation: identifies quality risks and testing constraints
- Planning: defines QA approach and quality gates
- Execution: runs/coordinates testing and defect prioritization
- Release: signs off quality readiness and post-deploy validation
- Retrospective: drives quality process improvement actions

#### Interactions with Existing Roles
- Developers: coordinate defect resolution and test automation
- Product Managers: align acceptance criteria interpretation
- Project Managers: align readiness with timeline and risk reporting

---

### DevOps/Site Reliability or Operations Lead

#### Role Summary
Owns deployment operations, service reliability, and production readiness so releases are safe, observable, and supportable.

#### Responsibilities
- Manage environments, pipelines, and deployment controls
- Define reliability objectives, monitoring, and alerting
- Coordinate incident response and operational handoffs
- Ensure rollback plans and runbooks are prepared

#### Goals
- Maintain high service availability and operational stability
- Reduce change failure rate and recovery time
- Improve deployment consistency and observability

#### Typical Communication
- Release readiness reviews with Technical Lead, QA/Test Lead, and Project Manager
- Incident and post-incident communication with stakeholders and support
- Operational updates on reliability trends and risks

#### Decision Rights
- Approves operational readiness and deployment execution approach
- Can halt/revert deployment when reliability risk is unacceptable

#### Expected Artifacts
- Deployment plans and rollback procedures
- Monitoring dashboards, alerts, and operational runbooks
- Incident timelines and post-incident action items

#### Lifecycle Touchpoints
- Initiation: identifies operational constraints and environment needs
- Planning: defines release pipeline and reliability requirements
- Execution: supports environment readiness and observability setup
- Release: leads deployment execution and post-deploy verification
- Retrospective: drives reliability and operability improvements

#### Interactions with Existing Roles
- Developers: align deployment practices and observability instrumentation
- Project Managers: coordinate release windows and operational risk
- Product Managers: communicate operational impact and trade-offs

---

### Security/Privacy Lead

#### Role Summary
Ensures security and privacy requirements are defined early and enforced through delivery, release, and operations.

#### Responsibilities
- Define security/privacy requirements and control expectations
- Review architecture and implementation for threats and compliance risk
- Coordinate security testing and vulnerability remediation priorities
- Advise on incident response and risk acceptance decisions

#### Goals
- Reduce exploitable vulnerabilities and privacy gaps
- Ensure compliance obligations are addressed in delivery workflows
- Shift security and privacy validation earlier in the lifecycle

#### Typical Communication
- Threat/risk reviews with Technical Lead and Developers
- Compliance and control discussions with Product/Project Managers
- Release security status summaries with QA and DevOps

#### Decision Rights
- Approval authority for security/privacy control readiness
- Escalates unacceptable risk to Executive Sponsor and delivery leads

#### Expected Artifacts
- Threat model and control checklist
- Security/privacy risk assessments
- Vulnerability findings with remediation tracking

#### Lifecycle Touchpoints
- Initiation: identifies regulatory/privacy constraints and high-level risks
- Planning: defines security gates and required controls
- Execution: reviews changes and validates remediation
- Release: confirms security/privacy readiness or documents accepted risk
- Retrospective: recommends control and process hardening

#### Interactions with Existing Roles
- Developers: guide secure implementation and remediation priorities
- Product Managers: align controls with product commitments
- Project Managers: track security dependencies and escalations

---

### Customer Support/Service Owner

#### Role Summary
Represents customer-facing operations and support readiness, ensuring launches are understandable, supportable, and feedback-informed.

#### Responsibilities
- Define support readiness requirements and service-impact expectations
- Prepare support teams with known issues, runbooks, and messaging
- Triage customer feedback and recurring issues into backlog signals
- Coordinate incident communication with Project Managers and Product Managers

#### Goals
- Improve post-release customer experience and response quality
- Reduce support escalation volume and resolution time
- Ensure customer feedback informs product and delivery priorities

#### Typical Communication
- Release readiness and launch communication planning
- Ongoing customer issue trend reviews with Product Managers
- Incident/status communications with Project Managers and DevOps

#### Decision Rights
- Approves support-readiness checklist completion before launch
- Escalates customer-impact risks requiring release or communication changes

#### Expected Artifacts
- Support readiness checklist and enablement notes
- Customer communication templates and known-issues updates
- Feedback summaries and recurring issue reports

#### Lifecycle Touchpoints
- Initiation: provides support impact context and service constraints
- Planning: contributes support requirements and launch dependencies
- Execution: validates support documentation and enablement progress
- Release: coordinates customer-facing communications and escalation routing
- Retrospective: shares support trends and improvement recommendations

#### Interactions with Existing Roles
- Product Managers: convert customer feedback into roadmap/backlog input
- Project Managers: align launch communications and escalation ownership
- Developers: route high-severity defects and known-issue details

---

## Cross-Role Collaboration Across the Lifecycle

### Initiation
- **Primary handoffs:** Product Managers and Business Analyst produce problem framing; Executive Sponsor approves strategic direction; Project Managers establish initial stakeholder/risk structures.
- **Approvals:** Sponsor/lead go-no-go to move into planning.
- **Escalation path:** Project Manager -> Product Manager -> Executive Sponsor for priority/funding conflicts.
- **Accountability boundary:** Product value definition (Product Manager) remains distinct from schedule/governance orchestration (Project Manager).

### Planning
- **Primary handoffs:** Business Analyst and UX/Product Designer refine requirements/design; Technical Lead/Architect validates feasibility; QA/Test Lead and Security/Privacy Lead define gates; DevOps defines release/operational requirements.
- **Approvals:** Product Manager accepts backlog priority; Technical Lead approves architecture direction; Security/Privacy and QA confirm required gates.
- **Escalation path:** Domain lead (Technical/QA/Security/DevOps) -> Project Manager for delivery impact -> Product Manager/Sponsor for trade-off decisions.
- **Accountability boundary:** Domain leads own quality of their discipline; Project Manager owns cross-discipline dependency tracking.

### Execution
- **Primary handoffs:** Developers implement; UX/BA clarify edge cases; QA validates increments; Security and Technical Lead review higher-risk changes.
- **Approvals:** Feature acceptance by Product Manager with QA quality evidence.
- **Escalation path:** Team lead/Developer -> Technical Lead or QA/Test Lead -> Project Manager -> Product Manager.
- **Accountability boundary:** Developers own implementation quality; Product Manager owns acceptance decisions; Project Manager owns coordination/escalation cadence.

### Release
- **Primary handoffs:** QA provides test evidence; DevOps executes deployment plan; Security/Privacy confirms controls; Customer Support/Service Owner confirms support readiness.
- **Approvals:** Release readiness requires aligned sign-offs from Product, QA, DevOps/Operations, and Security/Privacy (as applicable).
- **Escalation path:** Release manager/DevOps -> Project Manager -> Product Manager -> Executive Sponsor for major risk acceptance.
- **Accountability boundary:** DevOps owns deployment safety, while Product Manager owns value/timing trade-offs and Sponsor owns exceptional risk acceptance.

### Retrospective & Continuous Improvement
- **Primary handoffs:** Project Manager facilitates actions; each lead provides metrics/findings from their discipline; Product Manager prioritizes improvement work.
- **Approvals:** Action-item owners and due dates confirmed in retrospective closeout.
- **Escalation path:** Unresolved systemic blockers -> Project Manager -> Executive Sponsor.
- **Accountability boundary:** Continuous-improvement actions must have a single owner, but outcomes are reviewed cross-functionally.

---

## Lightweight Responsibility/Collaboration Matrix

Legend: **A** = Accountable, **R** = Responsible, **C** = Consulted, **I** = Informed

| Activity | Exec Sponsor | Product Manager | Project Manager | Business Analyst | UX/Product Designer | Tech Lead/Architect | Developers | QA/Test Lead | DevOps/Operations | Security/Privacy | Support/Service Owner |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Initiation charter and success metrics | A | R | R | C | C | C | I | I | I | C | C |
| Backlog and plan definition | I | A | R | R | R | C | C | C | C | C | C |
| Build and iterative delivery | I | A | R | C | C | R | R | R | C | C | I |
| Release readiness and go-live | C | A | R | I | C | R | R | R | A/R | A/R | R |
| Incident escalation and customer comms | C | A | R | I | I | C | R | C | A/R | C | A/R |
| Retrospective actions and follow-through | I | A | R | C | C | C | C | C | C | C | C |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
