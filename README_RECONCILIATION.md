# Reconciliation Note

This overlay exists because the project evolved in two additive rounds and some
later files risked replacing rather than extending earlier constraints.

## What this reconciles

1. First-round substrate remains authoritative:
   assumptions, hypotheses, artifact principles, content/product mapping,
   Team C protocol, Echo Contract, learnings, and templates.

2. Second-round opportunity / DBS layers remain:
   opportunity research, opportunity matrix, product hypothesis template,
   product experiments, DBS skills, DBS role, and routing.

3. Team C now has three distinct boundaries:
   - `TEAM_C_PROTOCOL.md`: project-wide ownership and authority
   - `handoffs/C/README.md`: handoff interface
   - `handoffs/C/echo-contract.md`: artifact-specific Echo contract

4. `docs/architecture.md` defines the system-level relationship between DBS,
   research, product truth, Team C, and `handbook-pdf`.

## Principle

New documentation should normally be additive. If a new document supersedes
an older one, record the supersession explicitly in `decisions/decision-log.md`.
