# Release Manager Checklist

## Purpose
This checklist helps the Release Manager coordinate all activities for a successful production release. Use this for every planned release to ensure consistency and reduce risk.

---

## Pre-Release Phase

### Release Planning (T-2 weeks)
- [ ] **Release scope defined**: Review with Product Owner and Development Lead
- [ ] **Release date and window scheduled**: Coordinate with stakeholders and on-call teams
- [ ] **Release notes drafted**: Include features, bug fixes, breaking changes, and migration steps
- [ ] **Rollback plan documented**: Verify with DevOps/SRE team
- [ ] **Dependencies identified**: Check cross-team dependencies and external integrations
- [ ] **Risk assessment completed**: Review with Project Manager and Development Lead

### Quality & Testing (T-1 week)
- [ ] **QA sign-off obtained**: Confirm with QA Lead that all tests pass and quality gates are met
- [ ] **Security/compliance review completed**: Sign-off from Security/Compliance Representative
- [ ] **Performance testing done**: Baseline metrics captured, no regressions
- [ ] **Smoke test plan prepared**: Define critical paths to verify post-deployment
- [ ] **Test data prepared**: Staging environment reflects production scenarios

### Release Readiness (T-48 hours)
- [ ] **Code freeze enforced**: All PRs for release merged and final build created
- [ ] **Release branch created**: Tagged and ready for deployment
- [ ] **Staging deployment successful**: All smoke tests passing in staging
- [ ] **Deployment runbooks reviewed**: DevOps team familiar with procedures
  - Link to deployment runbook: `[Add link to deployment automation/runbook]`
- [ ] **Go/No-Go meeting scheduled**: With key stakeholders (PM, Product Owner, QA Lead, DevOps, Security)
- [ ] **Communication plan ready**: Stakeholders, support team, and customers notified of release window

### Final Checks (T-24 hours)
- [ ] **Go/No-Go decision made**: Document decision and any last-minute concerns
- [ ] **On-call coverage confirmed**: Engineering and SRE on-call engineers identified
- [ ] **Monitoring and alerts verified**: Dashboards and alerts configured for release monitoring
- [ ] **Rollback decision criteria defined**: Clear thresholds for triggering rollback

---

## Release Phase

### Deployment Execution
- [ ] **Deployment initiated**: Follow automated pipeline or runbook steps
  - Deployment start time: `________________`
- [ ] **Deployment progress monitored**: Watch logs, metrics, and error rates
- [ ] **Database migrations executed**: (if applicable) Verify migration success
- [ ] **Feature flags configured**: (if applicable) Ensure proper feature flag states
- [ ] **Deployment completed**: All services/components deployed successfully
  - Deployment end time: `________________`

### Post-Deployment Verification
- [ ] **Smoke tests executed**: All critical paths verified in production
- [ ] **Health checks passing**: Application and infrastructure health verified
- [ ] **Monitoring reviewed**: Error rates, latency, and throughput within acceptable ranges
- [ ] **User acceptance spot-check**: Key stakeholders verify critical functionality
- [ ] **No critical issues detected**: If issues found, assess severity and rollback decision

---

## Post-Release Phase

### Immediate Post-Release (T+2 hours)
- [ ] **Release announcement sent**: Notify stakeholders, support team, and relevant channels
- [ ] **Monitoring dashboard shared**: Link to real-time metrics and alerts
- [ ] **On-call handoff completed**: Ensure on-call team aware of release and watching for issues

### Post-Release Review (T+24-48 hours)
- [ ] **Release metrics captured**: Deployment duration, downtime (if any), error rates
- [ ] **Incident review**: Document any issues, hotfixes, or rollbacks that occurred
- [ ] **Customer/user feedback collected**: Check support tickets and user reports
- [ ] **Post-release retrospective scheduled**: Include Release Manager, QA Lead, DevOps, PM

### Documentation & Continuous Improvement
- [ ] **Release notes published**: Final version shared with stakeholders and documentation site
- [ ] **Lessons learned documented**: Capture what went well and improvement opportunities
- [ ] **Action items tracked**: Assign owners for any follow-up improvements
- [ ] **Release checklist updated**: Incorporate feedback for future releases

---

## Rollback Procedure

**If critical issues arise during or after release:**

1. **Assess severity**: Determine if issue warrants immediate rollback (consult with Product Owner, QA Lead, and Development Lead)
2. **Trigger rollback**: Follow documented rollback runbook
   - Link to rollback runbook: `[Add link to rollback automation/runbook]`
3. **Notify stakeholders**: Immediate communication about rollback decision and status
4. **Verify rollback success**: Run smoke tests on previous version
5. **Incident post-mortem**: Schedule blameless post-mortem within 48 hours
6. **Root cause analysis**: Document root cause and preventive actions

---

## Contacts & Resources

| Role | Contact | Availability |
|------|---------|--------------|
| Release Manager | `[Name/Slack/Email]` | Release window + 2 hours |
| DevOps/SRE On-Call | `[On-call rotation link]` | 24/7 |
| QA Lead | `[Name/Slack/Email]` | Release window |
| Development Lead | `[Name/Slack/Email]` | Release window + on-call |
| Product Owner | `[Name/Slack/Email]` | Go/No-Go meeting + post-release |

**Key Links:**
- Deployment Runbook: `[Link]`
- Rollback Runbook: `[Link]`
- Monitoring Dashboard: `[Link]`
- Incident Response Playbook: `[Link]`
- Release Notes Template: See [octoacme-release-and-deployment.md](octoacme-release-and-deployment.md)

---

## Notes

Use this section to capture release-specific notes, unexpected issues, or deviations from the standard process:

```
[Add notes here during release execution]
```
