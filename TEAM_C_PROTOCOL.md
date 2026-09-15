# Team C Protocol

Team C is the implementation team for PDF artifacts.

Its purpose is to turn an already-defined product behavior into a reliable
`handbook-pdf` artifact without silently changing the product.

## C owns

- `handbook-pdf` implementation
- Typst / code
- reusable components
- build
- QA
- previews
- technical reporting
- implementation structure
- build strategy
- QA automation

## C may decide

Within the product boundary, Team C may decide implementation details such as:

- component structure
- file organization
- Typst details
- reusable component design
- build strategy
- QA automation
- rendering optimizations that preserve behavior

## C does NOT own

Team C must not decide without upstream approval:

- audience definition
- user problem
- product promise
- pricing strategy
- product positioning
- core user behavior
- behavioral loop
- Echo mechanism
- product scope expansion
- whether the product should exist

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

## Product-behavior boundary

Technical convenience must not silently change product behavior.

Examples of changes that require upstream approval:

- adding a calendar because it is visually convenient
- adding streaks or progress tracking
- adding new learning modules
- expanding a small artifact into a course or workbook
- adding pages merely to improve page count or visual density
- changing the behavioral loop to simplify implementation

## Ambiguity rule

If implementation reveals a product ambiguity, report the ambiguity instead
of silently resolving it by adding or removing user behavior.

## Fidelity rule

The implementation is successful only when it preserves the intended user
behavior, not merely when the PDF compiles or looks polished.
