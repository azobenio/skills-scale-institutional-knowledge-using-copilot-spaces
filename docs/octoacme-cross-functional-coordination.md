# OctoAcme — Cross-Functional Team Coordination Checklist

## Purpose
Ensure effective collaboration, communication, and alignment across all team roles throughout the project lifecycle.

## Project Initiation Phase

### Kickoff Meeting Checklist
- [ ] All core personas represented (PM, PdM, QA Lead, UX Designer, Scrum Master, Dev Lead)
- [ ] Project One-pager reviewed and agreed upon
- [ ] Success metrics clearly defined and understood by all
- [ ] Timeline, milestones, and dependencies mapped
- [ ] Role responsibilities and communication expectations set
- [ ] Questions and concerns addressed
- [ ] Next steps and action items documented

### Stakeholder Alignment
- [ ] Customer Success Manager briefed on customer context and expectations
- [ ] Support/operations teams informed of planned changes
- [ ] Dependencies with other teams identified and communicated
- [ ] Escalation paths and decision-makers documented

---

## Planning Phase

### Design & Discovery Collaboration
- [ ] UX Designer conducts user research and shares findings with team
- [ ] Product Manager and UX Designer align on feature requirements and user workflows
- [ ] Developers review design specifications for feasibility
- [ ] QA Lead identifies testing strategy based on design and acceptance criteria
- [ ] Technical risks and design constraints documented
- [ ] Acceptance criteria finalized with input from all roles

### Backlog Preparation
- [ ] Product Manager prioritizes backlog items
- [ ] QA Lead defines test cases and QA approach for top items
- [ ] Developers estimate scope (T-shirt sizing or story points)
- [ ] Project Manager ensures dependencies are flagged and tracked
- [ ] Scrum Master ensures Definition of Done is clear and agreed
- [ ] All roles confirm readiness for sprint planning

### Sprint Planning Setup
- [ ] Backlog items include design specs, acceptance criteria, and test plans
- [ ] Team capacity is realistic and clearly communicated
- [ ] Sprint goals are tied to project milestones
- [ ] Cross-team dependencies are surfaced
- [ ] Communication cadence is set (standups, syncs, reviews)

---

## Execution Phase

### Daily Team Coordination
- [ ] Daily standups held (include all key roles or representatives)
- [ ] Blockers and impediments surfaced and addressed in real-time
- [ ] QA Lead checks on test readiness and coverage
- [ ] Scrum Master removes impediments within 24 hours or escalates
- [ ] Dependencies with other teams communicated early

### Sprint Mid-Point Review
- [ ] Progress tracked against sprint goals and team velocity
- [ ] Quality metrics reviewed (test coverage, defect trends)
- [ ] Design implementation validated by UX Designer
- [ ] Risk register updated with new or emerging risks
- [ ] Stakeholders briefed on status and any changes

### Pull Request / Code Review Coordination
- [ ] PR descriptions include issue link, acceptance criteria, and test coverage
- [ ] QA Lead reviews test cases before merge
- [ ] Designer reviews implementation against design specs
- [ ] At least one peer review completed before merge
- [ ] CI/CD checks pass (linting, security, automated tests)

### Pre-Release Quality Gate
- [ ] QA Lead verifies all acceptance criteria are met
- [ ] Smoke tests pass in staging environment
- [ ] Design implementation reviewed and approved by UX Designer
- [ ] Security scan results reviewed and cleared
- [ ] Release notes drafted with input from all roles
- [ ] Rollback plan documented and tested
- [ ] Customer Success Manager prepared for launch communication

---

## Release & Deployment Phase

### Deployment Readiness
- [ ] All stakeholders notified of deployment window
- [ ] Backup or snapshot completed (if applicable)
- [ ] Deployment runbook reviewed by all ops/engineering roles
- [ ] Post-deployment verification plan is ready
- [ ] Incident response team is on-call
- [ ] Customer Success Manager ready to monitor adoption

### Post-Deployment Verification
- [ ] Application deployed successfully to production
- [ ] Smoke tests executed and passed
- [ ] Key metrics and dashboards monitored
- [ ] Customer Success Manager monitors early adoption signals
- [ ] QA Lead conducts final spot-checks for critical flows
- [ ] Support team alerted to new features and known issues
- [ ] Release announcement sent to all stakeholders

### Rollback Trigger Readiness
- [ ] Critical issues identified with clear rollback criteria
- [ ] Rollback decision made by PM/PdM + Project Manager
- [ ] Rollback executed and verified
- [ ] Root cause triage initiated with full team participation
- [ ] Incident post-mortem scheduled

---

## Ongoing Monitoring Phase

### Weekly Stakeholder Sync (PM + PdM + Project Manager)
- [ ] Feature adoption and usage metrics reviewed
- [ ] Customer feedback summarized by Customer Success Manager
- [ ] Quality and performance metrics reviewed by QA Lead
- [ ] Team velocity and process health reported by Scrum Master
- [ ] Risks updated and mitigation status reviewed
- [ ] Next steps and decisions documented

### Customer Success Integration
- [ ] Customer feedback collected and synthesized weekly
- [ ] Pain points and feature requests logged and prioritized
- [ ] Support tickets monitored for trends
- [ ] Adoption and satisfaction metrics tracked
- [ ] Customer health assessed and escalations flagged

---

## Retrospective & Closure Phase

### Sprint / Release Retrospective
- [ ] All team members participate (Developers, QA, Design, PM, Project Manager, Scrum Master)
- [ ] What went well highlighted and celebrated
- [ ] Challenges and blockers discussed openly
- [ ] Root causes identified for process improvements
- [ ] Action items assigned with clear owners and deadlines
- [ ] Customer Success Manager shares customer feedback on the release
- [ ] Scrum Master tracks retrospective action items through completion

### Project Closure
- [ ] Final metrics and learnings documented
- [ ] Customer Success Manager provides post-launch adoption summary
- [ ] Team recognition and celebration
- [ ] Documentation and knowledge transfer completed
- [ ] Artifacts archived and searchable
- [ ] Next phase or follow-up work identified and prioritized

---

## Communication Frequency Matrix

| Audience | Frequency | Owned By | Format |
|----------|-----------|----------|--------|
| Development Team (Daily Standup) | Daily (15 min) | Scrum Master | Sync Meeting |
| PM + PdM + Project Manager | Weekly (1 hr) | Project Manager | Sync Meeting |
| Full Cross-Functional Team | Bi-weekly or Sprint-end (1 hr) | Project Manager | Sprint Review / Demo |
| Stakeholders | Weekly or Milestone-based (30 min) | Project Manager | Status Report + Meeting |
| Customer Success + Support | Weekly | Customer Success Manager | Sync + Email Update |
| Executive Sponsor | Monthly or as-needed | Project Manager | Written Report + Meeting |

---

## Escalation & Decision-Making

### Level 1: Team Triage
- **When**: Daily standup, impediment surfaced, or mid-sprint
- **Who**: Development team + Scrum Master
- **Action**: Attempt resolution within 24 hours
- **Owner**: Scrum Master

### Level 2: Cross-Functional Review
- **When**: Blocker unresolved, quality risk, or design conflict
- **Who**: PM + PdM + QA Lead + UX Designer + Project Manager
- **Action**: Root cause analysis, mitigation plan, timeline impact
- **Owner**: Project Manager

### Level 3: Sponsor Escalation
- **When**: Schedule impact, scope change, resource constraint, or customer impact
- **Who**: Sponsor + Product Lead + Project Manager
- **Action**: Decision, resource reallocation, stakeholder communication
- **Owner**: Project Manager

---

## Success Metrics for Cross-Functional Collaboration

- **Communication**: All planned meetings held; decisions documented; feedback loops < 24 hours
- **Quality**: Defect escape rate < 5%; test coverage > 80%; zero unplanned post-release issues
- **Delivery**: On-time milestone delivery; velocity predictable; scope creep < 10%
- **Satisfaction**: Team NPS > 7/10; stakeholder satisfaction > 80%; customer adoption on target
- **Process Health**: Retrospective action items > 80% completed; team psychological safety score improving
