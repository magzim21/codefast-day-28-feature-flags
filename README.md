# Codefast Day 28 · Feature Flags

## Mission
- Build a feature flag service integrating LaunchDarkly-style targeting with configuration UI and audits.

## Implementation Checklist
1. Model flags, environments, and targeting rules with Prisma, exposing typed APIs.
2. Provide management UI with percentage rollouts, prerequisites, and change history.
3. Emit evaluation telemetry to Datadog, correlating with UX metrics.
4. Add SDK snippets for Next.js apps with offline bootstrap and fallback logic.

## Telemetry & QA
- Ensure audit log coverage for all changes and add alerting for long-lived experiments.
- Unit test rule evaluation engine and integration tests for rollout workflows.

## Deliverables
- README covering architecture, SDK integration, and incident response.
- Policy document defining flag lifecycle and cleanup expectations.
