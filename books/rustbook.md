# The Rust Programming Language

## Common Programming Concepts

### Variables and Mutability

- Variables are immutable by default
  - make them mutable by adding `mut` keyword
- Constants are **always** immutable
  - type of the value *must* be annotated
    - can be declared in any scope (including global)
    - constant may be set only to a constant expression
- variables can be *shadowed* by a second declaration (repeat the `let` keyword)
  - difference to `mut` is that the variable becomes immutable after the fact
  - effectively creating a new variable, so type change is possible

### Data Types
