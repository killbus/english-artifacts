# System Architecture

`english-artifacts` is the upstream product truth and experimentation layer.
`handbook-pdf` is the downstream production engine.
DBS is a reasoning and routing layer used to improve decisions under uncertainty.

## System map

```text
DBS
  ↓
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

Helps determine what to investigate, diagnose, compare, ground in theory, or
test next.

### english-artifacts

Owns final product hypotheses, evidence-backed decisions, product principles,
product specifications, and experiment records.

### Team C

Owns implementation decisions within the approved product boundary.

### handbook-pdf

Owns the technical mechanism for producing reliable PDF artifacts.
