# Release Checklist (owned by Release Manager)

Pre-release
- [ ] Release scope documented and linked to issue(s)
- [ ] Release date scheduled and communicated
- [ ] Rollback plan documented and tested
- [ ] Release notes drafted and reviewed by Technical Writer and Product Manager
- [ ] QA smoke tests defined and owners assigned
- [ ] Security review completed (if applicable)
- [ ] Data instrumentation validated for key success metrics

Staging
- [ ] Deploy to staging completed
- [ ] QA smoke tests passed in staging
- [ ] Performance or load checks (if required) completed
- [ ] Stakeholder sign-off (Product / PM / Security if needed)

Production
- [ ] Backup/snapshot in place (if applicable)
- [ ] Deployment to production executed by Platform/DevOps
- [ ] Post-deploy smoke tests passed
- [ ] Monitoring alerts observed for first 30 min
- [ ] Communicate release to Support and stakeholders

Post-release
- [ ] Collect initial metrics and verify instrumentation
- [ ] Triage any incidents and apply rollbacks if required
- [ ] Publish finalized release notes
- [ ] Retrospective or blameless postmortem scheduled (if issues)
