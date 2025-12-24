# Process Update Request Template

Use this template to propose updates to OctoAcme project management process documentation. This standardizes how we capture, review, and implement process improvements.

---

## Request Information

### Title
**[Brief descriptive title of the proposed update]**

Example: "Add release rollback decision criteria to deployment guide"

---

## Process Document

**Which process document do you want to update?**

Select one:
- [ ] octoacme-project-management-overview.md
- [ ] octoacme-project-initiation.md
- [ ] octoacme-project-planning.md
- [ ] octoacme-execution-and-tracking.md
- [ ] octoacme-risks-and-communication.md
- [ ] octoacme-release-and-deployment.md
- [ ] octoacme-retrospective-and-continuous-improvement.md
- [ ] octoacme-roles-and-personas.md
- [ ] release-manager-checklist.md
- [ ] risk-escalation-flow.md
- [ ] qa-process-and-responsibilities.md
- [ ] Other (specify): `____________________`
- [ ] New document (describe): `____________________`

---

## Summary of Proposed Update

**Briefly describe the new content or update you want to add.**

Example:
> Add a section defining clear rollback criteria including error rate thresholds, performance degradation limits, and decision authority for triggering rollbacks during deployments.

[Provide 2-5 sentence summary here]

---

## Rationale

**Why is this update needed?**

Select all that apply:
- [ ] Addresses a documented gap in the current process
- [ ] Improves clarity or reduces ambiguity
- [ ] Incorporates team feedback or lessons learned
- [ ] Aligns with industry best practices or standards
- [ ] Supports compliance or governance requirements
- [ ] Addresses recurring issues or questions
- [ ] Other (explain below)

**Detailed explanation:**

[Provide context on why this change is important. What problem does it solve? What risk does it mitigate? What feedback prompted this?]

---

## Suggested Content

**Provide the proposed text, checklist, diagram, or example content you'd like to add.**

*Optional but encouraged. Even rough drafts or bullet points help reviewers understand your vision.*

```markdown
[Paste or write your suggested content here]

Example:

### Rollback Decision Criteria

Trigger immediate rollback if any of the following occur within 30 minutes post-deployment:
- Error rate > 1% (above baseline)
- P95 latency increase > 50% vs. baseline
- Critical functionality unavailable (login, checkout, etc.)
- Database migration failure detected

**Decision Authority**: Release Manager in consultation with Development Lead and on-call SRE
```

---

## Acceptance Criteria

**How will we know this update is complete and successful?**

Check all that apply:
- [ ] Content aligns with existing process doc structure and style
- [ ] Update improves clarity or closes a documented gap
- [ ] Proposed content has been reviewed with relevant stakeholders
- [ ] Related docs updated with cross-references (if applicable)
- [ ] Examples or templates provided (if applicable)
- [ ] No conflicts with other process documentation

**Additional acceptance notes:**

[Add any specific criteria for this update]

---

## Impact and Dependencies

**Who is impacted by this change?**

Select all that apply:
- [ ] Developers
- [ ] Product Managers
- [ ] Project Managers
- [ ] Scrum Masters
- [ ] QA Lead
- [ ] Release Manager
- [ ] DevOps/SRE
- [ ] Stakeholders
- [ ] Other: `____________________`

**Does this update depend on or relate to other process changes?**

[Describe any dependencies or related updates]

---

## Proposed Reviewers

**Who should review this update?**

List roles or individuals who should be consulted:
- `____________________`
- `____________________`
- `____________________`

---

## Priority and Timeline

**How urgent is this update?**

- [ ] Critical (blocks current work or major risk)
- [ ] High (needed for upcoming milestone or release)
- [ ] Medium (valuable improvement, plan within next sprint)
- [ ] Low (nice-to-have, can be prioritized in backlog)

**Target completion date** (if applicable): `____________________`

---

## Submitter Information

**Submitted by**: [Name]  
**Role**: [Your role]  
**Date**: [Submission date]  
**Contact**: [Email/Slack handle]

---

## For Reviewers

**Review Status**:
- [ ] Under review
- [ ] Approved
- [ ] Approved with changes
- [ ] Declined (reason: `__________________`)

**Assigned to**: `____________________`  
**Target date for implementation**: `____________________`

**Reviewer comments**:

[Reviewers add feedback and decisions here]

---

## Implementation Notes

**Once approved, track implementation here:**

- [ ] Content drafted and reviewed
- [ ] PR created and linked: `[PR #]`
- [ ] Related docs updated
- [ ] Team notified of new/updated process
- [ ] Retrospective check-in scheduled (if major change)

**Implemented by**: `____________________`  
**Completion date**: `____________________`

---

## References

- Link to related issue/ticket: `____________________`
- Link to discussion thread: `____________________`
- Related documentation: `____________________`

---

## Template Usage Tips

1. **Be specific**: Clearly articulate the gap or improvement opportunity
2. **Provide context**: Explain why this matters and who benefits
3. **Draft content**: Even rough content helps reviewers understand your proposal
4. **Identify stakeholders**: Ensure the right people are consulted
5. **Follow up**: Track your proposal through review and implementation

**Questions?** Contact the Project Manager or PMO Liaison for guidance on process updates.
