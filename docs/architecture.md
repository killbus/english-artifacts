# System Architecture

`english-artifacts` is the upstream product truth and experimentation layer.
`handbook-pdf` is the downstream production engine.
DBS is a reasoning and routing layer used to improve decisions under uncertainty.

## System map

```text
Research / Evidence
  ↓
Problem
  ↓
Opportunity
  ↓
Product Hypothesis
  ↓
Experiment
  ↓
Product Spec
  ↓
Team C Handoff
  ↓
handbook-pdf
  ↓
Artifact
  ↓
Market / Usage Evidence
  ↓
Learning
  ↓
Decision

DBS is a re-entry layer: invoke it whenever uncertainty requires routing,
diagnosis, comparison, theory grounding, content reasoning, or a decision about
the next evidence-generating action.
```

Conceptually:

```text
                         ┌──────────────┐
                         │     DBS      │
                         │ re-entry     │
                         └──────┬───────┘
                                │
                                ▼
Research → Problem → Opportunity → Hypothesis → Experiment
    ▲                                             │
    │                                             ▼
    └──────────── Learning ← Evidence ←────── Artifact
                                │
                                ▼
                             Decision
```

## Epistemic layers

- **Assumption** — what we currently believe but have not established.
- **Hypothesis** — what we are willing to test.
- **Observation** — what happened.
- **Learning** — what changed in our understanding.
- **Decision** — what we choose to do because of evidence.
- **Product Spec** — what the current product must do.
- **Implementation** — how Team C makes it happen.

Do not collapse these categories.

## Source of truth

### DBS

Helps determine what to investigate, diagnose, compare, ground in theory, test,
or reconsider next. DBS may be invoked at multiple points in the lifecycle;
its output is guidance, not product truth.

### english-artifacts

Owns final product hypotheses, evidence-backed decisions, product principles,
product specifications, and experiment records.

### Team C

Owns implementation decisions within the approved product boundary.

### handbook-pdf

Owns the technical mechanism for producing reliable PDF artifacts.
