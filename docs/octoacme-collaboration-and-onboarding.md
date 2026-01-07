# OctoAcme — Cross-Role Collaboration & Onboarding Guide

## Purpose
Provide practical guidance for effective cross-functional collaboration and streamlined onboarding of new team members to OctoAcme projects.

## Cross-Role Collaboration Checklist

Use this checklist at project kickoff to ensure all necessary roles are engaged and collaboration patterns are established.

### Project Kickoff Collaboration Setup
- [ ] All required roles identified and assigned (see [Roles and Personas](octoacme-roles-and-personas.md))
- [ ] Kickoff meeting scheduled with all core team members
- [ ] Communication channels established (Slack, Teams, email lists)
- [ ] Collaboration tools configured (project board, wiki, shared docs)
- [ ] Regular meeting cadence agreed upon (standups, planning, reviews)
- [ ] Escalation paths and decision-making authority clarified

### Early Cross-Role Engagement

#### Security Involvement
- [ ] Security Lead engaged during project initiation for high-risk or compliance-sensitive projects (see criteria below)
- [ ] Security requirements documented in acceptance criteria
- [ ] Security review checkpoints scheduled in project timeline
- [ ] Threat modeling session scheduled (if applicable)

**When to engage Security Lead:**
- Projects handling sensitive customer data (PII, payment information, credentials)
- Authentication or authorization changes
- External integrations or API exposures
- Compliance requirements (SOC 2, GDPR, HIPAA, etc.)
- Infrastructure or deployment changes affecting security posture
- Any project identified as high-risk in the risk register

#### UX/Design Involvement
- [ ] UX/UI Designer engaged before detailed implementation planning
- [ ] User research needs identified and scheduled
- [ ] Design review cycles planned and integrated into project timeline
- [ ] Accessibility requirements documented
- [ ] Design handoff process established with Developers

#### QA Involvement
- [ ] QA Engineer involved in acceptance criteria definition
- [ ] Test strategy defined and agreed upon
- [ ] Test environments identified and provisioned
- [ ] Automation opportunities identified
- [ ] Release testing timeline allocated in project plan

#### Customer Support Involvement
- [ ] Customer Support Liaison engaged for customer-facing changes (see criteria below)
- [ ] Customer impact assessment completed
- [ ] Support documentation needs identified
- [ ] Release communication plan established
- [ ] Support team training scheduled (if needed)

**When to engage Customer Support Liaison:**
- UI/UX changes that affect customer workflows
- New features or functionality requiring customer education
- Changes to existing behavior that may generate support inquiries
- Pricing, billing, or subscription changes
- Deprecation or removal of features
- Changes affecting API clients or integrations
- Any change expected to impact customer satisfaction metrics

## New Team Member Onboarding Checklist

### General Onboarding (All Roles)
- [ ] Access to communication channels (Slack/Teams, email lists)
- [ ] Access to project management tools (GitHub, project boards, wiki)
- [ ] Introduction to team members and their roles
- [ ] Review of [Project Management Overview](octoacme-project-management-overview.md)
- [ ] Review of [Roles and Personas](octoacme-roles-and-personas.md)
- [ ] Review of current project charter or one-pager
- [ ] Assigned an onboarding buddy for questions
- [ ] Scheduled 1:1s with key collaborators

### Role-Specific Onboarding

#### Developer Onboarding
- [ ] Repository access and local environment setup
- [ ] Code review process and standards reviewed
- [ ] CI/CD pipeline overview
- [ ] Security best practices and secure coding guidelines
- [ ] Design system and UI component library (if applicable)
- [ ] Pair programming session scheduled with senior developer
- [ ] First simple task assigned to validate environment setup

#### QA Engineer Onboarding
- [ ] Test environment access and configuration
- [ ] Test management tools and defect tracking access
- [ ] Current test plan and test cases reviewed
- [ ] Automation framework overview (if applicable)
- [ ] Release process and quality gates reviewed
- [ ] Shadow a testing cycle with experienced QA team member

#### UX/UI Designer Onboarding
- [ ] Design tools access (Figma, Sketch, Adobe XD, etc.)
- [ ] Design system and component library reviewed
- [ ] User research repository and insights reviewed
- [ ] Accessibility guidelines and standards reviewed
- [ ] Review session with Product Manager on product vision
- [ ] Attend user research or usability testing session

#### Security Lead Onboarding
- [ ] Security policies and compliance requirements reviewed
- [ ] Access to security scanning and monitoring tools
- [ ] Current threat model and risk register reviewed
- [ ] Incident response process overview
- [ ] Security review checkpoints in SDLC clarified
- [ ] Introduction to compliance and audit stakeholders

#### Customer Support Liaison Onboarding
- [ ] Support ticketing system access
- [ ] Knowledge base and documentation repository access
- [ ] Customer feedback collection process reviewed
- [ ] Product roadmap and recent releases reviewed
- [ ] Shadow support team to understand common customer issues
- [ ] Introduction to escalation process and key stakeholders

## Communication Best Practices

### Daily Collaboration
- **Standups**: Keep updates brief, focused on progress, blockers, and next steps
- **Async updates**: Use project boards and status comments for asynchronous teams
- **Quick questions**: Use designated chat channels, respect time zones and focus time

### Weekly Collaboration
- **Status syncs**: PM + PdM + Tech Lead alignment on progress and priorities
- **Design reviews**: Regular UX/UI review sessions with Product and Engineering
- **Risk reviews**: Review risk register, update mitigation plans, escalate as needed

### Milestone Collaboration
- **Sprint planning**: Full team participates to define scope and acceptance criteria
- **Sprint reviews**: Demonstrate completed work to stakeholders and gather feedback
- **Retrospectives**: All core team members reflect on what went well and what to improve

### Cross-Role Handoffs

#### Product → Design
- Product Manager provides: user stories, business requirements, success metrics
- UX/UI Designer delivers: wireframes, prototypes, design specifications
- Collaboration point: Design review with Product Manager for alignment

#### Design → Development
- UX/UI Designer provides: finalized designs, specs, assets, accessibility notes
- Developers deliver: implemented UI matching design specs
- Collaboration point: Design handoff meeting, ongoing design QA during implementation

#### Development → QA
- Developers provide: feature complete in test environment, acceptance criteria met
- QA Engineer delivers: test results, defect reports, release sign-off
- Collaboration point: Feature demo, bug triage, exploratory testing sessions

#### QA → Support
- QA Engineer provides: validated release notes, known issues list
- Customer Support Liaison delivers: support documentation, team training
- Collaboration point: Release readiness review, support team Q&A session

## Escalation and Conflict Resolution

### When to Escalate
- Blockers that cannot be resolved within 24 hours
- Scope changes that impact timeline or resources
- Cross-team dependencies causing delays
- Disagreements on technical approach or priorities
- Security or compliance issues
- Customer-impacting incidents

### Escalation Path
1. **Team level**: Discuss with direct collaborators first
2. **Project Manager**: Escalate to PM for resource or timeline issues
3. **Product Manager**: Escalate to PdM for scope or priority conflicts
4. **Leadership**: Escalate to stakeholders for strategic decisions or major blockers

### Conflict Resolution Principles
- Assume positive intent
- Focus on project goals and customer outcomes
- Bring data and specific examples
- Involve the right stakeholders early
- Document decisions and rationale
- Follow up to ensure resolution

## Continuous Improvement

### Regular Team Health Checks
- Use retrospectives to identify collaboration gaps
- Track action items from retrospectives and review progress
- Measure team satisfaction and psychological safety
- Adjust processes based on feedback

### Knowledge Sharing
- Document decisions in project wiki or decision logs
- Share learnings in team meetings or presentations
- Update process documentation based on real experiences
- Create runbooks and playbooks for common scenarios

## Related Documentation
- [Roles and Personas](octoacme-roles-and-personas.md)
- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
