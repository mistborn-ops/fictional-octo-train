<!--
purpose: Emergency break-glass PR — stabilization only.
-->

# 🚨 Break-Glass PR

> ⚠️ This template is for emergency or incident-driven changes ONLY.
> Standard changes must use the normal PR template and follow full governance.
> No new features. No refactors. No scope expansion.

## Incident Reference (REQUIRED)

- Incident issue / document:
- Related issue (if applicable):

## Summary (1-3 bullets)

-
-

## Risk (REQUIRED)

-
-

## Rollback Plan (REQUIRED)

```bash

```

## Verification Steps (REQUIRED)

- [ ] CI passed
- [ ] Service validated manually
- [ ] Logs checked

## Governance Acknowledgment (REQUIRED)

- [ ] This change is required to restore service
- [ ] Automation could not safely resolve the issue
- [ ] Manual steps are documented in the incident reference
- [ ] A follow-up issue has been created to prevent recurrence

## Security Considerations

- [ ] No secrets exposed
- [ ] No privilege escalation introduced
- [ ] Temporary overrides documented and scheduled for removal

## Post-Incident Follow-Up

- Follow-up issue:
- Root cause identified:
- Prevention planned:
