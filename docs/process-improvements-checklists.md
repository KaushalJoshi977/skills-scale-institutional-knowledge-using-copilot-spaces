# Process Improvement Checklists

This file collects lightweight checklists to ensure consistent handoffs and readiness for releases, observability, security, and documentation.

## Release Readiness Checklist
- [ ] All PRs merged and CI green
- [ ] Release notes drafted and reviewed
- [ ] Rollback plan documented
- [ ] Staging smoke tests passed
- [ ] Post-release verification plan and owner assigned
- [ ] Stakeholders notified of deployment window

## Observability & On-call Checklist
- [ ] Key metrics defined and dashboard created
- [ ] Alerts configured and tested for new/changed flows
- [ ] Runbook steps documented for likely failure modes
- [ ] On-call owner and escalation path assigned

## Security Pre-release Checklist
- [ ] Dependency and SCA scans completed
- [ ] Known vulnerabilities triaged and remediated (or risk accepted)
- [ ] Security review completed for new architecture changes
- [ ] Secrets and config reviewed for appropriate protections

## Documentation Checklist
- [ ] User-facing docs updated (features, migration steps)
- [ ] Internal runbooks / playbooks updated
- [ ] Support knowledge base updated with common troubleshooting
- [ ] Docs owner assigned for publication and follow-up

## Acceptance
These checklists are intended to be included into the Definition of Done for features where applicable. Ownership for each checklist item should be explicit in the backlog item or release plan.
