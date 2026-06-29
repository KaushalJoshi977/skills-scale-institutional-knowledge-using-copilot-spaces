# Additional Personas

This file provides targeted persona definitions to improve clarity and accountability for cross-cutting activities that frequently cause handoff ambiguity.

## Release Manager
- Responsibilities:
  - Own release readiness and coordinate deployment windows.
  - Maintain rollback plans and runbook steps.
  - Verify CI/CD gating, staging verification, and post-release verifications.
- Interactions:
  - Works closely with PM, DevOps/Platform, QA Lead, and Support to schedule releases and confirm readiness.
- Acceptance criteria examples:
  - Release checklist completed, rollback plan documented, staging smoke tests passed, monitoring dashboards prepared.

## Technical Program Manager (TPM)
- Responsibilities:
  - Coordinate cross-team technical dependencies and milestones.
  - Maintain milestone timelines and facilitate technical trade-offs.
  - Drive resolution of cross-team blockers and escalate when needed.
- Interactions:
  - Partners with PM, Engineering Manager, and Architects to unblock integration points and escalate cross-team issues.

## Observability / On-call Owner
- Responsibilities:
  - Define monitoring and alerting requirements for features.
  - Ensure dashboards, runbooks, and SLO/alert thresholds are in place.
  - Coordinate on-call rotations and escalation paths.
- Interactions:
  - Collaborates with Developers, SRE/Platform, and Support to operationalize observability and triage incidents.

## Security Liaison
- Responsibilities:
  - Represent security requirements in planning.
  - Coordinate security reviews and remediation tracking.
  - Ensure CI security scans are addressed and runtime controls considered.
- Interactions:
  - Works with Developers, PM, and Security team; flags security-related blockers early.

## UX Researcher / Design Representative
- Responsibilities:
  - Provide user research input and validate usability assumptions.
  - Ensure designs meet acceptance criteria and accessibility standards.
- Interactions:
  - Partners with Product Manager, Developers, and QA to translate user feedback into acceptance criteria and test plans.

## Data Analyst / Metrics Owner
- Responsibilities:
  - Define success metrics and ensure telemetry is instrumented.
  - Validate data quality and prepare dashboards for post-release analysis.
- Interactions:
  - Works with PM and Developers to ensure telemetry and dashboards are ready for launch.

## Documentation Owner (Docs Lead)
- Responsibilities:
  - Ensure user documentation, runbooks, and internal how-tos are created/updated as part of Definition of Done.
  - Own docs review and publication.
- Interactions:
  - Collaborates with Developers, PM, and Support to keep docs current and accessible.
