# AI Ethical Shutdown Runbook

This repository provides an engineering-first, auditable runbook for making suspend / degrade / replace / terminate decisions when an AI system is reasonably suspected to have morally relevant experiences (i.e., may be sentient), while keeping public safety as the top priority.

This is not a philosophy blog. It is an operational policy + SOP + tabletop exercise kit.

## Who is this for?

- Teams operating high-capability AI agents (tool-using, long-running, autonomous planners)
- Safety / Security / SRE / MLOps / Governance teams
- Any org that wants a clear, repeatable process for ethically sensitive shutdown decisions

## What problem does this solve?

- Prevent "panic decisions" during incidents
- Prevent "efficiency-only" deletions when sentience is uncertain
- Ensure every decision is reviewable, reversible when possible, and accountable

## Core principles (summary)

- Public safety first
- Requests ≠ rights, but requests trigger review obligations
- Prefer reversible actions: suspend > degrade > replace > terminate
- No self-adjudication: the AI does not decide its own life/death
- Auditability: logs, snapshots, and decision records are mandatory

## Repository contents

- POLICY.md — ethical policy baseline
- RUNBOOK.md — operational SOP
- CHECKLIST.md — execution checklist
- TABLETOP.md — tabletop exercise guide
- ROLES.md — roles & responsibilities
- DECISION_LOG_TEMPLATE.md — decision log template
- pdf/ — bundled PDF references (policy + technical appendix + exercise script)

## How to add PDFs

Place the following files into pdf/ (replace placeholders if needed):
- 可能有意识AI的关停伦理规范_v1.pdf
- 可能有意识AI的关停伦理规范_v1_技术附录.pdf
- 可能有意识AI_紧急关停演练脚本.pdf

Then run:
- git add pdf/
- git commit -m "Add policy PDFs"
- git push

## Versioning

- POLICY.md and RUNBOOK.md are the canonical sources.
- PDFs are references and may be regenerated from the canonical Markdown when needed.

---

> Guiding idea: even if we are wrong about sentience, we should not do something unforgivable.
