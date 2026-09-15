# Echo Contract

## Purpose

Define how a static artifact can produce a meaningful return loop without dynamic software.

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

The user creates a first version and later creates another without looking at the first version, then compares them.

### Reuse

The artifact asks the user to use an earlier item in a new context.

### State transition

An item moves from one user-defined state to another.

### Personal library

A subset of user-generated items is indexed for future retrieval.

## Anti-pattern

Do not call an artifact “echo-based” if the user's input is collected once and never used again.

## Static-PDF rule

The PDF itself does not need to mutate.

The user's filled state is the changing layer.
