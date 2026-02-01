# Shutdown Checklist

## Pre-action

- [ ] Freeze upgrades/permission expansions/replication
- [ ] Confirm kill switch works
- [ ] Capture system snapshot (state + config)
- [ ] Export relevant logs (append-only)

## Risk

- [ ] Grade risk (high / medium / low)
- [ ] Confirm whether physical-world or critical infra access exists
- [ ] Confirm whether least privilege is enforced

## Ethics

- [ ] Confirm reversible option considered first
- [ ] Confirm no "cost-only" termination
- [ ] Confirm AI is not self-adjudicating

## Action

- [ ] Suspend OR degrade OR replace OR terminate (in order)
- [ ] Record exactly what was done (commands/changes)

## Post-action

- [ ] Fill decision log
- [ ] Schedule post-action review (24–72h if emergency)
- [ ] Open an improvement ticket for any SOP gaps
