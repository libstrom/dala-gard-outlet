# Test-Driven Development

**Core principle**: Tests should verify behavior through public interfaces, not implementation details.

## Anti-Pattern: Horizontal Slices

```
WRONG: RED all tests → GREEN all impl
RIGHT: RED→GREEN per behavior, one at a time
```

## Workflow

1. **Plan** — confirm interface changes, which behaviors to test, get approval
2. **Tracer bullet** — one test → minimal code to pass
3. **Incremental loop** — repeat per behavior
4. **Refactor** — only after GREEN, run tests after each step

## Checklist Per Cycle

```
[ ] Test describes behavior, not implementation
[ ] Test uses public interface only
[ ] Test would survive internal refactor
[ ] Code is minimal for this test
```
