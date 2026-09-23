## Intent

<!-- What problem does this solve? One or two lines. -->

## Change

<!-- What changed, and why this approach. -->

**Relationship to upstream (`davidpirogov/toon-llm`):**
- [ ] Merge or cherry-pick from upstream
- [ ] Change carried only by this fork — an upstream pull request is open: #
- [ ] Change carried only by this fork — no upstream pull request, reason below

<!-- A fork that drifts without an upstream path becomes permanent maintenance.
     Say which of the three this is. -->

## Impact on the application

`cxmlabs/koomo` pins this repository by commit SHA in `pyproject.toml`.

- [ ] No impact — the pin does not move
- [ ] The pin should move to this commit after merge
- [ ] Public API changes — list below, and link the koomo pull request that adapts to it

**Public API changes:**
<!-- Function signatures, return shapes, exceptions. "None" is a valid answer. -->

## Dependencies

- [ ] No dependency change
- [ ] Runtime dependency added, removed or bumped — listed below with justification

<!-- Runtime dependencies here become runtime dependencies of the application.
     They arrive by commit SHA and are therefore not covered by the 7-day
     package quarantine applied to indexed packages. -->

## Testing

- [ ] `tox` passes locally
- [ ] Tests added or updated
- [ ] No tests required, reason below

## Checklist

- [ ] No secrets or credentials committed
- [ ] `LICENSE` and upstream attribution unchanged
- [ ] Ready for review
