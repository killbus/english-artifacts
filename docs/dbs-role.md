# Role of DBS in This Project

DBS is an upstream reasoning and validation layer, not the product itself.

## What DBS contributes

### 1. Routing

Use `/dbs` when the next task is unclear. The current dbskill design describes `/dbs` as the entry point that reads the situation and routes to an appropriate Skill. [Source: dbskill README]

### 2. Diagnosis

Use `/dbs-diagnosis` when deciding whether the bottleneck is user, problem, product, pricing, or distribution. [Source: dbskill Skill directory]

### 3. Benchmark

Use `/dbs-benchmark` to research real comparables and understand what is worth learning rather than copying. [Source: dbskill Skill directory]

### 4. Theory grounding

Use `/dbs-theory-grounding` when an observed phenomenon needs a credible theoretical explanation and boundaries. [Source: dbskill v2.18.40 description]

### 5. Content

Use `/dbs-content`, `/dbs-hook`, `/dbs-xhs-title`, `/dbs-resonate`, and `/dbs-spread` after the product hypothesis is sufficiently defined. Content is a demand and distribution instrument, not the final business.

### 6. Decision accumulation

Use `/dbs-decision`, `/dbs-save`, `/dbs-restore`, and `/dbs-report` where appropriate so repeated experiments accumulate instead of restarting from zero.

## Important boundary

DBS does not replace product judgment.

In this repository:

```text
DBS reasoning
    ↓
English-artifacts product decision
    ↓
Product spec
    ↓
Team C
    ↓
handbook-pdf
```

Do not let the presence of a DBS Skill turn a hypothesis into a fact.
