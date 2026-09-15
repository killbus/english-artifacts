# Echo Contract

## Purpose

Define how a static artifact can produce a meaningful return loop without
dynamic software.

The PDF itself does not need to mutate. The user's filled state is the changing
layer.

## Required fields

For every meaningful user-generated item:

| Field | Meaning |
|---|---|
| `input_id` | Stable reference such as E-017 |
| `source_page` | Where the user first created it |
| `return_page` | Where it will be revisited |
| `return_action` | What the user does when it returns |
| `state` | Example: found / tried / reused / mine / retired |
| `evidence` | What observable change should be visible when the item returns |

## Echo patterns

### Cross-page return

A later page explicitly asks the user to revisit an earlier entry.

### Version comparison

The user creates a first version and later creates another without looking at
the first version, then compares them.

### Reuse

The artifact asks the user to use an earlier item in a new context.

### State transition

An item moves from one user-defined state to another.

### Personal library

A subset of user-generated items is indexed for future retrieval.

## Anti-pattern

Do not call an artifact "echo-based" if the user's input is collected once
and never used again.

## Static-PDF rule

The PDF itself does not need to mutate.

The user's filled state is the changing layer.

## Design test

For each important input, answer:

1. What does the user create here?
2. Where does it return?
3. What new action happens when it returns?
4. What visible evidence of change can the user observe?

If an important input never returns, question whether the field needs to exist.
