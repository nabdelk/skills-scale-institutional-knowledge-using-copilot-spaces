# OctoAcme Role Interaction Checklist

## Purpose
This checklist helps teams clarify role interactions, handoffs, collaboration touchpoints, and accountability at project kickoff and throughout the delivery lifecycle. Use it to reduce communication gaps, prevent muddy handoffs, and ensure all team members understand their responsibilities and dependencies.

## How to Use
- Review this checklist during project kickoff and at key milestones
- Adapt to your specific project context and team structure
- Document agreed-upon interaction patterns in your project documentation
- Reference the [OctoAcme Roles and Personas](octoacme-roles-and-personas.md) document for detailed role definitions

---

## Project Initiation Phase

### Role Clarity
- [ ] All core roles identified and assigned (PM, PdM, Developers, UX Designer, Business Analyst, DevOps Engineer, etc.)
- [ ] Each team member understands their primary responsibilities
- [ ] Escalation paths and decision-making authority defined

### Cross-Role Alignment
- [ ] **Product Manager + Business Analyst**: Requirements gathering approach agreed upon, stakeholder interview plan created
- [ ] **Product Manager + UX Designer**: User research scope and timeline aligned, design validation process defined
- [ ] **Project Manager + All Roles**: Communication cadence established (standups, syncs, status reports)
- [ ] **DevOps Engineer + Developers**: Infrastructure and environment requirements discussed, deployment strategy outlined

### Deliverables & Handoffs
- [ ] Business Analyst: Initial requirements document or business case ready for review
- [ ] UX Designer: Research plan or early concept direction shared with Product Manager
- [ ] DevOps Engineer: Infrastructure needs and constraints identified, environment availability confirmed
- [ ] Project Manager: Project one-pager drafted with input from all key roles

---

## Planning Phase

### Role Clarity
- [ ] Work breakdown assignments clear across all roles
- [ ] Definition of Done agreed upon by all team members
- [ ] Review and approval responsibilities assigned

### Cross-Role Alignment
- [ ] **Business Analyst + Developers**: Functional requirements reviewed, technical feasibility validated, edge cases discussed
- [ ] **UX Designer + Developers**: Design handoff process established, design system or component library access confirmed
- [ ] **UX Designer + Business Analyst**: User flows aligned with business processes, acceptance criteria informed by both perspectives
- [ ] **DevOps Engineer + Project Manager**: Deployment windows, release cadence, and infrastructure timelines coordinated
- [ ] **Developers + All Roles**: Technical dependencies, API contracts, and integration points communicated

### Deliverables & Handoffs
- [ ] Business Analyst: Detailed functional specifications and acceptance criteria documented in backlog
- [ ] UX Designer: Wireframes, mockups, or prototypes delivered with design annotations
- [ ] DevOps Engineer: CI/CD pipeline, environments, and deployment checklist ready
- [ ] Project Manager: Sprint/iteration plan with clear ownership and dependencies mapped
- [ ] Developers: Technical design reviewed and approved, estimation completed

---

## Execution Phase

### Role Clarity
- [ ] Daily/regular sync attendance expectations set for each role
- [ ] Code review, design review, and QA responsibilities assigned
- [ ] Blocker escalation process understood by all

### Cross-Role Alignment
- [ ] **Developers + UX Designer**: Regular design check-ins scheduled, implementation questions resolved quickly
- [ ] **Developers + Business Analyst**: Ongoing clarifications on business logic and acceptance criteria as needed
- [ ] **Developers + DevOps Engineer**: Build and deployment issues triaged collaboratively, infrastructure changes coordinated
- [ ] **QA/Testing + Business Analyst**: Test scenarios validated against requirements, edge cases confirmed
- [ ] **UX Designer + QA/Testing**: Usability testing coordinated, design validation during QA cycle
- [ ] **Project Manager + All Roles**: Risk register updated, status reported consistently

### Deliverables & Handoffs
- [ ] Developers: Code with tests and documentation ready for review
- [ ] UX Designer: Design QA completed on implemented features, design feedback provided on PRs
- [ ] Business Analyst: Requirements clarifications and acceptance validation as features complete
- [ ] DevOps Engineer: Monitoring and observability instrumented, deployment runbooks updated
- [ ] Project Manager: Sprint demos scheduled, stakeholder communications sent

---

## Release Phase

### Role Clarity
- [ ] Release approval authority defined (who signs off?)
- [ ] Go/no-go decision-making process established
- [ ] Incident response roles and on-call schedule confirmed

### Cross-Role Alignment
- [ ] **DevOps Engineer + Developers**: Deployment plan reviewed, rollback procedure confirmed, smoke tests identified
- [ ] **Business Analyst + Product Manager**: Acceptance criteria verified, business validation completed
- [ ] **UX Designer + Product Manager**: User-facing changes validated, help documentation or announcements reviewed
- [ ] **Project Manager + DevOps Engineer**: Release timeline communicated to stakeholders, deployment window coordinated
- [ ] **All Roles**: Post-release monitoring plan understood, success metrics identified

### Deliverables & Handoffs
- [ ] DevOps Engineer: Production deployment executed, post-deploy verification completed, monitoring confirmed healthy
- [ ] Business Analyst: Final acceptance sign-off documented
- [ ] UX Designer: UI/UX spot-checks completed in production
- [ ] Product Manager: Release announcement and stakeholder communication sent
- [ ] Project Manager: Release notes published, stakeholder retrospective scheduled

---

## Retrospective Phase

### Role Clarity
- [ ] Retrospective facilitator assigned
- [ ] Action item ownership and follow-up process defined
- [ ] Feedback channels for continuous improvement established

### Cross-Role Alignment
- [ ] **All Roles**: Honest feedback on collaboration quality, handoff effectiveness, and communication gaps
- [ ] **Project Manager + Team**: Identify process improvements and document lessons learned
- [ ] **Product Manager + Business Analyst + UX Designer**: Review alignment on requirements and user outcomes
- [ ] **Developers + DevOps Engineer**: Discuss technical debt, tooling improvements, and deployment friction
- [ ] **UX Designer + Product Manager**: Evaluate design validation outcomes and iteration opportunities

### Deliverables & Handoffs
- [ ] All Roles: Action items captured with owners and due dates
- [ ] Project Manager: Retrospective notes documented and shared
- [ ] Business Analyst: Process improvement opportunities logged for future projects
- [ ] DevOps Engineer: Infrastructure and tooling improvements backlog updated
- [ ] UX Designer: Design system or pattern library updates identified

---

## General Best Practices for Role Interactions

### Communication
- Establish clear channels for each type of communication (Slack, email, project board comments, meetings)
- Use shared documentation to reduce information silos
- Proactively communicate blockers and dependencies
- Over-communicate during handoffs to ensure clarity

### Documentation
- Keep role responsibilities visible in project documentation (reference [octoacme-roles-and-personas.md](octoacme-roles-and-personas.md))
- Document decisions and rationale in accessible locations
- Maintain updated RACI (Responsible, Accountable, Consulted, Informed) charts for key deliverables

### Collaboration
- Schedule regular cross-functional sync meetings
- Use pairing or collaboration sessions for complex handoffs
- Celebrate cross-role wins and successful collaborations
- Provide constructive feedback to improve future interactions

---

## Customization Notes
- Not all projects require all roles—adapt this checklist to your team composition
- Add or remove sections based on project complexity and delivery methodology
- Consider project-specific risks or dependencies that may require additional checkpoints
- Review and refine this checklist based on retrospective feedback
