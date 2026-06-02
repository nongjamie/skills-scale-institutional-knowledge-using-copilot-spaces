# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core Roles

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

#### Interactions

- Works closely with QA/Testing on acceptance criteria validation
- Collaborates with Scrum Master on sprint execution and impediment removal
- Partners with UX Designer on implementation feasibility and design details
- Reports blockers to Project Manager for escalation
- Engages with Business Analyst on requirements clarification

---

### Product Managers

#### Role Summary

Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

#### Responsibilities

- Define problem statements and success metrics
- Prioritize the roadmap and backlog based on customer and business value
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics
- Drive prioritization discussions with stakeholders and engineering

#### Goals

- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

#### Typical Communication

- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs
- Post-release metrics reviews and outcome analysis

#### Interactions

- Partners with Project Manager on timeline, scope, and resource planning
- Engages Business Analyst on requirements refinement and impact analysis
- Collaborates with UX Designer on user needs, research, and validation
- Updates External Stakeholders on priorities, progress, and decisions
- Works with Scrum Master on velocity trends and capacity planning

---

### Project Managers

#### Role Summary

Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

#### Responsibilities

- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives, standups)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication
- Escalate blockers and dependencies appropriately

#### Goals

- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

#### Typical Communication

- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation
- Daily standup facilitation and blocker escalation

#### Interactions

- Works with Product Manager on priorities and scope decisions
- Engages Scrum Master on team velocity, capacity, and sprint health
- Collaborates with Release Manager on deployment planning and release coordination
- Updates External Stakeholders and executives on project status and risks
- Partners with Business Analyst on requirements traceability and impact

---

## Supporting Roles

### Scrum Master

#### Role Summary

Scrum Masters facilitate agile ceremonies and coaching, removing impediments and helping teams optimize their delivery flow. They are servant-leaders who focus on process health and team dynamics.

#### Responsibilities

- Facilitate daily standups, sprint planning, sprint reviews, and retrospectives
- Identify and help remove team blockers and impediments
- Coach team members on agile best practices and continuous improvement
- Protect team from external distractions during sprints
- Monitor sprint velocity and flag capacity or workflow issues
- Help establish healthy team norms and psychological safety
- Escalate systemic impediments to Project Manager

#### Goals

- Enable consistent, predictable delivery
- Build a high-performing, collaborative team culture
- Foster a culture of continuous improvement and learning
- Remove process bottlenecks

#### Typical Communication

- Leads or co-facilitates all agile ceremonies
- Coaching conversations with team members (1:1 or group)
- Updates Project Manager on team health and velocity trends
- Escalates impediments that require PM or stakeholder attention
- Shares metrics (velocity, cycle time, burndown) with Product Manager

#### Interactions

- Partners with Project Manager on sprint planning and risk management
- Works directly with Developers on removing technical or process blockers
- Collaborates with QA/Testing on quality metrics and acceptance criteria clarity
- Shares velocity data and capacity insights with Product Manager for prioritization
- Supports Business Analyst on story point estimation and definition of done

---

### UX Designer

#### Role Summary

UX Designers lead user research, interaction design, and usability validation to ensure features are intuitive and meet user needs. They are advocates for the end-user experience and bridge customer insights with product decisions.

#### Responsibilities

- Conduct user research and gather requirements from customers
- Create wireframes, prototypes, and design mockups
- Perform usability testing and gather feedback on designs
- Collaborate with Developers on implementation feasibility and constraints
- Document design systems and interaction patterns for consistency
- Iterate designs based on user feedback, metrics, and testing results
- Ensure accessibility standards are met in all designs

#### Goals

- Deliver intuitive, user-centric product experiences
- Reduce friction and improve user satisfaction and adoption
- Establish consistent design standards and component libraries
- Minimize rework by validating designs early with users

#### Typical Communication

- Design reviews with Product Manager and stakeholders
- Collaboration sessions with Developers on implementation
- Research findings and usability test results
- Design specifications and interaction documentation
- Accessibility audit reports and recommendations

#### Interactions

- Partners with Product Manager on understanding user needs and validating solutions
- Works with Developers on design-to-implementation alignment and feasibility
- Engages External Stakeholders and real users in research and usability testing
- Shares user behavior insights with Business Analyst for requirements refinement
- Collaborates with Scrum Master on design work estimation and sprint planning

---

### Release Manager

#### Role Summary

Release Managers oversee the planning, execution, and monitoring of production releases. They coordinate across teams to ensure smooth deployments and manage rollback procedures when needed. They are the guardians of release quality and deployment communication.

#### Responsibilities

- Create and maintain release schedules and deployment calendars
- Coordinate with QA, DevOps, and Developers on release readiness
- Verify pre-release requirements are met (tests, security scans, documentation, etc.)
- Manage the deployment process and coordinate post-deploy verification
- Document release notes and communicate releases to stakeholders and support teams
- Lead incident response and rollback decisions if critical issues occur post-deployment
- Maintain release history and lessons learned for future releases

#### Goals

- Execute reliable, predictable production releases with minimal risk
- Minimize deployment downtime and time to rollback if needed
- Maintain clear communication during and after releases
- Reduce post-release incidents and support burden

#### Typical Communication

- Release status updates and readiness reviews
- Pre-release checklists and verification reports
- Post-deployment verification and success reports
- Incident communication and rollback decisions
- Release notes and go/no-go communications

#### Interactions

- Collaborates with Project Manager on release timing and cross-team dependencies
- Works with QA/Testing on release acceptance criteria and smoke testing
- Partners with Developers on deployment procedures and rollback strategies
- Updates External Stakeholders and Support teams on go-live and known issues
- Coordinates with Business Analyst on release validation and success metrics

---

### Business Analyst

#### Role Summary

Business Analysts bridge the gap between business requirements and technical implementation. They refine requirements, analyze impact, and validate solutions to ensure projects deliver intended business value. They are translators between business needs and technical solutions.

#### Responsibilities

- Gather and document business and user requirements
- Refine user stories and acceptance criteria with clarity and detail
- Analyze requirements for completeness, testability, and dependencies
- Map cross-functional impacts and identify integration points
- Validate solutions against original requirements and acceptance criteria
- Analyze post-release metrics and measure business value delivered
- Document and communicate requirements changes and impact

#### Goals

- Ensure requirements are clear, complete, and actionable
- Reduce rework due to unclear or missed requirements
- Maximize business value delivered by projects
- Improve traceability between business needs and solutions

#### Typical Communication

- Requirements documentation and user story refinement
- Impact analysis and dependency mapping
- Post-release analysis and business value metrics
- Stakeholder clarification sessions and requirement walkthroughs
- Test scenario and acceptance criteria validation with QA

#### Interactions

- Works closely with Product Manager on requirement prioritization and business drivers
- Collaborates with UX Designer on user workflows and behavior patterns
- Engages Developers for feasibility assessment and implementation questions
- Supports QA/Testing with test scenario development and acceptance criteria
- Reports findings and outcomes to External Stakeholders
- Coordinates with Project Manager on timeline and resource implications

---

### QA / Testing

#### Role Summary

QA and Testing professionals ensure quality standards are met, acceptance criteria are validated, and risks are identified before release. They are quality advocates throughout the project lifecycle, focused on preventing defects before they reach customers.

#### Responsibilities

- Develop and execute comprehensive test plans and test cases
- Validate acceptance criteria for each feature and user story
- Perform manual and automated testing as appropriate
- Identify, document, and track defects with severity and reproduction steps
- Participate in release readiness verification and smoke testing
- Support post-deployment verification and production monitoring
- Provide quality metrics and defect trend analysis

#### Goals

- Deliver high-quality products with minimal defects reaching production
- Catch issues early in the development cycle to reduce cost of fixes
- Build confidence in releases through thorough validation
- Establish quality standards and testing best practices

#### Typical Communication

- Test plans and test case documentation
- Defect reports and issue severity assessments
- Release readiness status updates and verification reports
- Participation in feature acceptance meetings and sign-offs
- Quality metrics dashboards and trend reports

#### Interactions

- Partners with Developers on acceptance criteria clarity and quick bug fixes
- Collaborates with Release Manager on release testing and smoke tests
- Works with Business Analyst on test scenario development and validation
- Updates Project Manager on quality metrics, risks, and blockers
- Engages with Scrum Master on quality in sprint planning and retrospectives

---

## Extended Stakeholders

### External Stakeholder

#### Role Summary

External Stakeholders represent customer, business, or executive perspectives. They provide input on requirements, validate solutions, and approve key milestones to ensure projects remain aligned with business objectives and customer needs.

#### Responsibilities

- Articulate business, customer, or operational needs
- Participate in requirements definition and prioritization
- Review and approve key project decisions and milestone gates
- Provide feedback on prototypes, designs, and deliverables
- Approve release and go-live decisions
- Share feedback on outcomes, impact, and user adoption post-release

#### Goals

- Ensure projects deliver intended business value
- Maintain alignment between delivery and business strategy
- Build trust and transparency with delivery teams
- Ensure customer voice is heard in product decisions

#### Typical Communication

- Participation in kickoff and planning sessions
- Review and feedback on prototypes and deliverables
- Milestone approvals and go/no-go decision gates
- Post-release outcome reviews and impact analysis
- Executive status reports and business value summaries

#### Interactions

- Engages with Product Manager on priorities, success metrics, and outcome validation
- Provides input to Project Manager on business constraints and approval authority
- Reviews mockups and designs with UX Designer and provides user feedback
- Validates outcomes and business value with Business Analyst post-release
- Participates in retrospectives and provides strategic direction

---

## How these personas are used in exercises and projects

- Use these persona definitions to frame scenarios and sample interactions in Skills Exercises.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance and recommendations.
- Reference these roles when defining responsibilities in project charters or when onboarding new team members.
- Use the interaction map below to clarify handoffs and communication points during project execution.
- Tailor role definitions to your organization by adding or modifying responsibilities based on your context.

---

## Cross-Functional Interaction Matrix

This matrix shows which roles work together, what they collaborate on, and typical frequency/format of interaction.

| Role                     | Primary Works With                                                                                 | Key Touchpoints                                                                                                     | Interaction Type         |
| ------------------------ | -------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------- | ------------------------ |
| **Developer**            | Scrum Master, QA, Project Manager, UX Designer, Business Analyst                                   | Daily standups, code review, sprint planning, design collaboration, acceptance criteria clarification               | Daily/Weekly sync        |
| **Product Manager**      | Project Manager, Business Analyst, UX Designer, External Stakeholder, Scrum Master                 | Weekly sync, backlog refinement, prioritization, roadmap reviews, metrics analysis                                  | Weekly/Monthly sync      |
| **Project Manager**      | Product Manager, Scrum Master, Developers, Release Manager, External Stakeholder, Business Analyst | Planning, status updates, risk management, escalation, resource coordination                                        | Daily/Weekly sync        |
| **Scrum Master**         | Developers, Project Manager, Product Manager, QA/Testing, Business Analyst                         | Sprint ceremonies (daily standup, planning, review, retrospective), coaching, velocity tracking, impediment removal | Daily/Sprint-based       |
| **UX Designer**          | Product Manager, Developers, Business Analyst, External Stakeholder, Scrum Master                  | Research, design reviews, usability testing, implementation alignment, feedback incorporation                       | Weekly/On-demand         |
| **Release Manager**      | Developers, QA/Testing, Project Manager, External Stakeholder, Release/DevOps team                 | Release planning, deployment coordination, verification, communication, rollback procedures                         | Per-release basis        |
| **Business Analyst**     | Product Manager, Developers, UX Designer, QA/Testing, External Stakeholder, Project Manager        | Requirements refinement, impact analysis, validation, metrics review, test scenario development                     | Weekly/On-demand         |
| **QA / Testing**         | Developers, Release Manager, Business Analyst, Product Manager, Scrum Master                       | Test planning, acceptance criteria validation, release verification, quality metrics, bug triage                    | Sprint-based/Per-release |
| **External Stakeholder** | Product Manager, Project Manager, UX Designer, Business Analyst                                    | Requirements input, milestone approval, feedback, outcome validation, strategic direction                           | Monthly/Per-milestone    |

---

## Role Interaction Examples

### Example 1: Feature Development Cycle

**Roles involved**: Product Manager → Business Analyst → Developer → QA/Testing → Release Manager → External Stakeholder

1. **Product Manager** defines feature vision and success metrics
2. **Business Analyst** refines requirements and acceptance criteria
3. **Developer** implements feature, works with **UX Designer** on design details, collaborates with **Scrum Master** on sprint planning
4. **QA/Testing** validates against acceptance criteria, identifies issues
5. **Release Manager** coordinates release timing and deployment
6. **External Stakeholder** reviews outcome and provides feedback

### Example 2: Project Planning Meeting

**Roles involved**: Project Manager, Product Manager, Scrum Master, Business Analyst, External Stakeholder

- **Project Manager** facilitates and sets timeline
- **Product Manager** presents goals and success metrics
- **Business Analyst** explains requirements and scope
- **Scrum Master** discusses team capacity and velocity
- **External Stakeholder** approves timeline and resources

### Example 3: Incident / Blocker Escalation

**Roles involved**: Developer → Scrum Master → Project Manager → External Stakeholder

1. **Developer** identifies blocker in daily standup
2. **Scrum Master** works to remove blocker (coaching, facilitation)
3. If unresolved, **Scrum Master** escalates to **Project Manager**
4. **Project Manager** escalates to **External Stakeholder** if business decision needed
5. Roles coordinate on resolution and timeline impact

---

## Tips for Using These Personas

- **Customize for your org**: Add or modify responsibilities based on your organization's structure and needs
- **Use in onboarding**: Reference specific personas when bringing new team members into a role
- **Clarify handoffs**: When a process breaks down, check the interaction matrix to ensure all necessary roles are involved
- **Design meetings**: Structure meetings to include all personas needed for decisions
- **Document decisions**: Capture who had input, who decided, and who will execute
- **Review in retrospectives**: Use persona definitions to discuss whether roles were clear and interactions were effective
