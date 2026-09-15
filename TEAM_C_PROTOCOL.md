# Team C Protocol

Team C is the implementation layer.

Primary stack:

> `handbook-pdf` → Typst / code → build → QA → preview

## C owns

- implementation;
- page templates and reusable components;
- data wiring;
- build reliability;
- PDF QA;
- previews;
- technical documentation.

## C does not own

- audience definition;
- problem selection;
- product positioning;
- pricing strategy;
- product scope;
- core user behavior;
- product theory;
- decisions about whether a feature should exist.

## Non-negotiable behavior rules

### 1. Do not convert the product into a generic workbook

Do not add lessons, vocabulary lists, grammar sections, answer keys, or explanatory pages unless the product spec explicitly requires them.

### 2. Do not convert the product into a habit tracker

Do not add streaks, progress bars, daily completion, points, badges, or calendars merely because they are easy to implement.

### 3. Do not add behavior through implementation convenience

A component is not a product requirement.

### 4. Preserve the Echo Contract

If the product spec says a user input must return later, the implementation must preserve that mechanism.

### 5. Do not optimize page count

Empty space is preferable to irrelevant content.

### 6. Surface conflicts; do not resolve product conflicts silently

When the spec and implementation constraints conflict, report the conflict to the product side.

## Acceptance test

Before delivery, Team C must be able to answer:

- What is the user's core job?
- What important input does the user create?
- Where does that input return?
- What new behavior happens at return?
- Which pages exist because of product behavior rather than visual filler?

If those answers are unclear, stop implementation and report the ambiguity.
