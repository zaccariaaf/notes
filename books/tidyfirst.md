**Tidyings**
- Use guard clauses
- Remove dead code (code that doesn't get executed
- Normalize symmetries (code that does the same thing, but is written differently)
- New interface, old implementation (pass-through interface... don't like this one because of complexity)
- Reading order
- Cohesion Order
- Move declaration and initialization together
- Use variable declarations to explain concepts
- Use constant declarations to explain concepts
- Explicit parameters (parameters passed around in maps obscures the content)
- Chunk statements by cohesion
- Extract helper functions
- Put code into one pile when it is split up too much, then start tyding from there
- Write explaining comments
- Delete redundant comments

**When to tidy**
Tidy never when:
- You’re never changing this code again.
- There’s nothing to learn by improving the design.

Tidy later when:
- You have a big batch of tidying to do without immediate payoff.
- There’s eventual payoff for completing the tidying.
- You can tidy in little batches.

Tidy after when:
- Waiting until next time to tidy first will be more expensive.
- You won’t feel a sense of completion if you don’t tidy after.

Tidy first when:
- It will pay off immediately, either in improved comprehension or in cheaper behavior changes.
- You know what to tidy and how.
