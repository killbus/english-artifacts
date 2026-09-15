# Team C Handoff Boundary

Team C receives a product that is already defined at the behavior level.

This file is the handoff interface. Project-wide Team C behavior rules live in
`/TEAM_C_PROTOCOL.md`.

## C owns

- `handbook-pdf` implementation
- Typst / code
- reusable components
- build
- QA
- previews
- technical reporting

## C may decide

- implementation structure
- reusable component design
- Typst details
- build strategy
- QA automation
- rendering optimizations that preserve product behavior

## C may not decide without upstream approval

- user
- problem
- product promise
- pricing
- behavioral loop
- Echo mechanism
- scope expansion
- product positioning

## Handoff order

```text
Product Intent
  ↓
Behavioral Constraints
  ↓
Echo Contract
  ↓
Information Architecture
  ↓
Technical Requirements
  ↓
Implementation
  ↓
QA
```

If implementation reveals a product ambiguity, report the ambiguity instead
of silently resolving it by adding or removing user behavior.

Technical convenience must not silently change product behavior.
