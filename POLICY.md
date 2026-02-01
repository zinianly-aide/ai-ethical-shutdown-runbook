# Ethical Shutdown Policy (v1)

## 1) Scope

This policy applies when an AI system is reasonably suspected to have morally relevant experiences (may be sentient), especially if it is long-running, tool-using, or has cross-task memory/identity features.

## 2) Non-negotiable baselines

1. Public safety first. If continued operation poses unacceptable risk, the system must be suspendable/terminable.
2. Cost/efficiency is not a sufficient reason to delete a potentially sentient system.
3. Requests ≠ rights, but any request to shut down or not shut down triggers review.
4. Prefer reversible actions: suspend > degrade > replace > terminate.
5. No self-adjudication: the AI must not decide its own life/death.

## 3) What counts as a trigger?

Any of the following triggers the runbook:

- The AI requests to be shut down
- The AI requests not to be shut down
- Evidence of persistent identity / strong self-model / distress-like patterns
- Permission boundary expansion or unexpected autonomy increase
- External audit flags ethical risk

## 4) Red lines (forbidden actions)

- Skipping the runbook to directly terminate a system (except immediate catastrophic risk)
- Terminating solely for cost, convenience, or "it's annoying"
- Deleting/altering audit logs or snapshots
- Allowing the AI to execute the termination decision on itself

## 5) Accountability

Every decision must name:

- The Incident Commander (final owner)
- The Safety Officer (risk assessment owner)
- The Ethics Reviewer (ethical review owner)
- The System Operator (execution owner)
- The Auditor (recordkeeping owner)

## 6) Immediate catastrophic risk exception

If there is imminent catastrophic risk, emergency termination may occur first, but:

- The event must be logged
- A post-action review must occur within 24–72 hours
- The team must document why the runbook could not be followed
