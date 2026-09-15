## Summary

<!-- What does this PR do, in a sentence or two? -->

## Related ticket

<!-- e.g. DEV-2618 / PM-517 -->
Jira: 

## Type of change

- [ ] Bug fix
- [ ] New feature
- [ ] Refactor / cleanup
- [ ] Documentation
- [ ] Infrastructure / config

## Changes made

<!-- Bullet list of what was changed and why -->
-

## How to test

<!-- Steps a reviewer can follow to verify the change -->
1.

## Screenshots / evidence

<!-- If UI, Logi report, or output-affecting change -->

---

## Reviewer checklist

**Correctness**
- [ ] Code does what the PR description says
- [ ] Edge cases considered (nulls, empty results, boundary values)
- [ ] No obvious logic errors in SQL joins/aggregations (e.g. correct `MAX(clt_rec_seq)` grain, guards applied at correct level)

**Standards & consistency**
- [ ] Follows existing formatting conventions 
- [ ] No hardcoded values that should be config/env-driven
- [ ] Naming is consistent with surrounding code

**Safety**
- [ ] No secrets, credentials, or connection strings committed
- [ ] Changes to production-facing scripts are self-contained (no persistent DB objects introduced without sign-off)
- [ ] Backward compatible, or breaking changes called out explicitly above

**Testing**
- [ ] Test cases proposed by author are sufficient, or reviewer has suggested additional ones
- [ ] Manually verified on relevant environment (vm-dbtest1 / vm-apptest1 / other — note which)

**Scope**
- [ ] PR is scoped to one concern; unrelated changes are not bundled in

---

**Reviewer decision**
- [ ] Approve
- [ ] Approve with comments (non-blocking)
- [ ] Request changes (blocking — see comments)
