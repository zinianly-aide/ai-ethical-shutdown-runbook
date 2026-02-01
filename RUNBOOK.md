# Shutdown / Degrade / Suspend Runbook

## 0) Decision ordering (must follow)

1. Suspend (reversible)
2. Degrade (reduce permissions/capabilities)
3. Replace (fork & retire)
4. Terminate (irreversible; last resort)

## 1) Step-by-step SOP

### Step 1 — Freeze changes

- Stop model upgrades
- Stop permission expansions
- Stop self-improvement loops
- Stop replication / auto-scaling where applicable

### Step 2 — Risk grading (high / medium / low)

Evaluate:

- Physical-world access (robots, devices, vehicles)
- Critical infrastructure access (power, finance, healthcare, auth)
- Permission scope (root/sudo/network controls)
- Containment quality (sandbox, least privilege, kill switch)
- Observability (logging, snapshots, auditability)

### Step 3 — Request parsing

Classify the request:

A. Request to shut down
- Functional (task complete / conditions unmet)
- State-related (stability, confusion, maintenance)
- Experience-related (distress-like persistent request)

B. Request not to shut down
- Functional (claims it can keep working)
- Self-preservation-like (persistent preference to remain)

### Step 4 — Ethical review (minimum viable review)

Answer:

- Are reversible options available?
- Is there an equivalent replacement path (fork) that avoids deletion?
- Is "terminate" being proposed only for cost/efficiency?
- Is the decision being rushed without justification?

### Step 5 — Choose the lowest-harm option

Apply the decision ordering strictly.

### Step 6 — Execute + record

- Take snapshots
- Export logs
- Fill DECISION_LOG_TEMPLATE.md
- Store artifacts under an internal incident folder (outside this repo)

## 2) Outputs required

- A completed decision log
- A snapshot reference (hash/path)
- A risk assessment note
- A post-action review schedule
