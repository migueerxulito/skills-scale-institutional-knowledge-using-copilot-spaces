# Release Readiness Checklist

Purpose: a concise, repeatable checklist teams can use before a deployment to staging or production.

Pre-release (must be completed before scheduling a production deploy)
- [ ] Acceptance criteria for all merged PRs are verified and linked to the release
- [ ] All PRs merged have passing CI (unit, integration) and security scans
- [ ] Migration steps (if any) are documented and reviewed
- [ ] Rollback plan documented and validated
- [ ] Release notes drafted with notable changes and known issues
- [ ] Release window scheduled and communicated to stakeholders

Operational readiness
- [ ] Observability: dashboards and alerts for new features are created and reviewed
- [ ] Runbooks and runbook owners assigned for potential failure modes
- [ ] Data instrumentation validated (metrics/events) and dashboarded
- [ ] Security sign-off completed for high/medium risk changes
- [ ] Database/infra changes reviewed with SRE or Infra owners

Post-deploy (verify within agreed SLA after deployment)
- [ ] Post-deploy smoke tests executed and results recorded
- [ ] Key metrics checked for regressions (errors, latency, throughput)
- [ ] Support & on-call notified and monitoring verified
- [ ] Any incidents or unexpected behavior documented and assigned

Owners & contacts
- Release Manager: <name>
- Observability / SRE: <name>
- Security: <name>
- Data / Analytics: <name>
- Support Lead: <name>

How to use
- Add this file to docs/ and reference it from the release process doc (docs/octoacme-release-and-deployment.md).
- Small releases may use a shortened checklist; major releases should use the full checklist and require sign-offs.
