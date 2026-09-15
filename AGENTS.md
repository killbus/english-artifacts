# Agent / Team Operating Rules

## Product layer

- Do not skip problem validation.
- Do not turn theories into products without identifying the user problem.
- Do not create a PDF merely because a PDF is easy to generate.

## Artifact layer

- Every page needs a clear user job.
- Avoid page-count-driven design.
- Every meaningful user input should have a future return path when Echo is part
  of the product concept.

## Team C

- Team C is implementation-focused.
- Do not delegate product strategy to code.
- Technical convenience must not introduce new user behaviors without product
  approval.

## Research

- Keep claims traceable to evidence.
- Keep licensing constraints visible.

## Experiments

- Prefer falsifiable hypotheses.
- Record negative results.
- Change one important variable at a time when practical.
<!-- TRELLIS:START -->
# Trellis Instructions

These instructions are for AI assistants working in this project.

This project is managed by Trellis. The working knowledge you need lives under `.trellis/`:

- `.trellis/workflow.md` — development phases, when to create tasks, skill routing
- `.trellis/spec/` — package- and layer-scoped coding guidelines (read before writing code in a given layer)
- `.trellis/workspace/` — per-developer journals and session traces
- `.trellis/tasks/` — active and archived tasks (PRDs, research, jsonl context)

If a Trellis command is available on your platform (e.g. `/trellis:finish-work`, `/trellis:continue`), prefer it over manual steps. Not every platform exposes every command.

If you're using Codex or another agent-capable tool, additional project-scoped helpers may live in:
- `.agents/skills/` — reusable Trellis skills
- `.codex/agents/` — optional custom subagents

Managed by Trellis. Edits outside this block are preserved; edits inside may be overwritten by a future `trellis update`.

<!-- TRELLIS:END -->
