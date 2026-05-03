<!--
purpose: Security PR template — for sensitive changes.
-->

# Security PR

> ⚠️ Do not include exploit details, credentials, or sensitive IPs.

## Linked Issue (REQUIRED)

Closes #

## Summary

<!-- Describe the security change without exposing sensitive details -->

## Exposure Window

<!-- How long was the system exposed, if applicable -->

## Changes Made

-
-

## Risk Assessment

- Severity: Low / Medium / High / Critical
- Blast radius:

## Rollback Plan (REQUIRED)

```bash

```

## Validation Steps (REQUIRED)

- [ ] No secrets or credentials in diff
- [ ] No new privilege escalation introduced
- [ ] pre-commit run --all-files
- [ ] CI passed
- [ ] Manual security validation performed

## Post-Merge Actions

<!-- Key rotation, secret rotation, notifications, etc. -->

## Governance Acknowledgment

- [ ] This change reduces risk, not increases it
- [ ] A follow-up issue exists for any remaining exposure
