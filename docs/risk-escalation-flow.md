# Risk Escalation Flow

## Purpose
This document defines the step-by-step process for escalating risks within the OctoAcme project to ensure timely decision-making and appropriate stakeholder involvement.

---

## When to Escalate a Risk

Escalate when:
- A risk threatens project timeline, budget, or quality beyond acceptable thresholds
- A risk requires decision-making authority beyond the current team level
- A risk has not been mitigated despite team-level efforts
- A risk has dependencies on external teams or resources not under team control
- A security, compliance, or legal concern is identified

---

## Risk Severity Levels

### Low Severity
- **Impact**: Minor delays (< 1 week), low impact on quality or scope
- **Examples**: Small technical challenges, minor resource constraints, easily mitigated issues
- **Escalation**: Handled at team level, monitored in sprint retrospectives

### Medium Severity
- **Impact**: Moderate delays (1-2 weeks), potential scope reduction, quality concerns
- **Examples**: Technical blockers, dependency delays, resource gaps, vendor issues
- **Escalation**: Requires PM and Product Owner involvement, may need stakeholder awareness

### High Severity
- **Impact**: Major delays (> 2 weeks), significant scope reduction, release at risk, security issues
- **Examples**: Critical dependencies blocked, key resource loss, major technical failures, security vulnerabilities
- **Escalation**: Requires immediate escalation to PM, Product Owner, and senior leadership

### Critical Severity
- **Impact**: Project failure, production outage, data breach, regulatory non-compliance
- **Examples**: Active security incidents, production-down issues, legal/compliance violations
- **Escalation**: Immediate escalation to executive level, activate incident response

---

## Escalation Path & Decision Points

### Level 1: Team-Level (Scrum Master, Development Lead, QA Lead)

**Who handles**: Scrum Master, Development Lead, QA Lead
**Decision authority**: Sprint-level adjustments, resource reallocation within team, technical approach changes

**Steps**:
1. **Identify and document risk**: Add to risk register with description, impact, likelihood, and proposed mitigation
2. **Attempt team-level mitigation**: Assign owner, implement mitigation actions
3. **Monitor for 1-2 sprints**: Track mitigation progress during sprint reviews

**Escalate to Level 2 if**:
- Mitigation not working after 1-2 sprints
- Risk severity increases to Medium or High
- Risk requires resources or decisions beyond team authority

---

### Level 2: Project Leadership (PM, Product Owner, Project Coordinator)

**Who handles**: Project Manager, Product Owner
**Decision authority**: Timeline adjustments, scope changes, cross-team coordination, budget requests

**Steps**:
1. **Review escalated risk**: PM and Product Owner assess impact and urgency
2. **Determine action plan**:
   - Adjust project timeline or scope
   - Allocate additional resources or budget
   - Coordinate with other teams or vendors
   - Re-prioritize backlog
3. **Communicate decision**: Update team, stakeholders, and risk register
4. **Assign accountability**: Clear owner for mitigation with timeline

**Escalate to Level 3 if**:
- Risk threatens overall project success or major milestone
- Risk requires portfolio-level resource reallocation
- Risk has business or strategic implications beyond single project
- Decision requires executive approval (budget, timeline, scope)

---

### Level 3: Portfolio/PMO Leadership (PMO Liaison, Stakeholder Representative, Senior Leadership)

**Who handles**: PMO Liaison, Stakeholder Representative, VP/Director level
**Decision authority**: Portfolio prioritization, strategic trade-offs, executive resource allocation

**Steps**:
1. **Assess portfolio impact**: PMO Liaison evaluates impact across multiple projects or business units
2. **Stakeholder consultation**: Stakeholder Representative gathers business input and priorities
3. **Executive decision**: Senior leadership makes strategic decision on:
   - Major budget or timeline changes
   - Project scope reduction or cancellation
   - Portfolio re-prioritization
   - Strategic vendor or partnership changes
4. **Communication plan**: PMO Liaison ensures decision communicated to all affected parties
5. **Update governance**: Risk register, portfolio dashboard, and status reports updated

**Escalate to Level 4 (Executive/C-Suite) if**:
- Risk threatens company-wide objectives or reputation
- Legal, regulatory, or compliance exposure
- Major financial impact or public relations concern
- Security incident with potential data breach

---

### Level 4: Executive/C-Suite (CEO, CTO, CISO, CFO, Legal)

**Who handles**: C-level executives, Legal, Compliance leadership
**Decision authority**: Company-wide strategy, legal action, public statements, regulatory response

**Steps**:
1. **Immediate assessment**: Executive team briefed on risk and implications
2. **Crisis management activation**: (if needed) Activate incident response, crisis communications
3. **Strategic decision**: Executives make high-stakes decisions:
   - Product launch delays or cancellations
   - Public statements or customer notifications
   - Legal or regulatory filings
   - Board of Directors notification
4. **External coordination**: PR, legal counsel, regulatory bodies, customers, partners
5. **Post-incident review**: Blameless post-mortem and strategic changes to prevent recurrence

---

## Risk Escalation Template

Use this template when escalating a risk:

```markdown
### Risk Escalation

**Risk ID**: [e.g., R-042]
**Date Escalated**: [Date]
**Escalated By**: [Name, Role]
**Escalated To**: [Name, Role, Level]

**Risk Title**: [Brief descriptive title]

**Description**: 
[Clear description of the risk and its context]

**Current Severity**: [Low / Medium / High / Critical]
**Impact**: [Impact on timeline, budget, quality, scope, security]
**Likelihood**: [Probability of risk occurring if not mitigated]

**Mitigation Attempts**:
- [What has been tried at team/PM level]
- [Results and why mitigation was insufficient]

**Decision Needed**:
[Specific decision or action required from escalation level]

**Proposed Options**:
1. [Option 1 with pros/cons]
2. [Option 2 with pros/cons]
3. [Option 3 with pros/cons]

**Timeline for Decision**: [When decision is needed]
**Impact of Delay**: [What happens if no decision made by timeline]

**Attachments/Links**: 
- Risk register entry: [Link]
- Related documentation: [Link]
```

---

## Key Contacts for Escalation

| Escalation Level | Roles | Contact Method | Response Time SLA |
|------------------|-------|----------------|-------------------|
| Level 1 - Team | Scrum Master, Dev Lead, QA Lead | Slack, standup | Same day |
| Level 2 - Project | PM, Product Owner | Slack, email, sync meeting | 1-2 business days |
| Level 3 - Portfolio/PMO | PMO Liaison, Stakeholder Rep, VP/Director | Email, scheduled meeting | 3-5 business days |
| Level 4 - Executive | CTO, CISO, CEO, Legal | Executive escalation process | Immediate for Critical |

**For security/compliance risks**: Always cc Security/Compliance Representative at any escalation level.

**For incident response**: Follow [Incident Response Playbook] and notify on-call immediately.

---

## Integration with Risk Register

All escalated risks must be:
1. **Logged in the risk register**: See [octoacme-risks-and-communication.md](octoacme-risks-and-communication.md)
2. **Tracked with owner and status**: Updated weekly during PM syncs
3. **Monitored post-escalation**: Verify mitigation actions are effective
4. **Reviewed in retrospectives**: Capture lessons learned for future risk management

---

## Escalation Best Practices

- **Escalate early**: Don't wait until a risk becomes a crisis
- **Provide context**: Include background, attempted mitigations, and decision options
- **Be solution-oriented**: Propose options, not just problems
- **Follow up**: Track escalation outcomes and communicate decisions back to team
- **Document thoroughly**: Maintain clear escalation trail for audits and retrospectives
- **Blameless approach**: Focus on problem-solving, not assigning blame

---

## Continuous Improvement

After each major escalation:
- **Retrospective**: Discuss what worked well and what could improve in escalation process
- **Update process**: Refine escalation criteria, contacts, or decision authority as needed
- **Training**: Share lessons learned with team to improve future risk identification and escalation
