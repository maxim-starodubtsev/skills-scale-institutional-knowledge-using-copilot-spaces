# Release Checklist (Template)

Purpose: Pre-release and post-release checklist to standardize safe deployments.

Pre-release
- [ ] All acceptance criteria met for merged PRs
- [ ] All PRs have required approvals and passing CI
- [ ] Security scans completed and no high severity findings remaining
- [ ] Release notes drafted and reviewed
- [ ] Rollback / mitigation plan documented and tested
- [ ] Staging deployment completed and smoke tests passed
- [ ] Backups/snapshots taken if applicable
- [ ] Stakeholders and support notified of release window (if needed)

Deploy
- [ ] Deploy to production via automated pipeline
- [ ] Watch automated checks and deploy logs for errors
- [ ] Run post-deploy smoke tests (critical user flows)

Post-release
- [ ] Verify key metrics and dashboards for regressions
- [ ] Confirm no new critical incidents within observation window
- [ ] Announce release to stakeholders with link to release notes
- [ ] If an issue, follow rollback/incident playbook and capture action items

Post-incident follow-up
- [ ] Create incident retrospective (blameless) and add action items with owners and due dates
