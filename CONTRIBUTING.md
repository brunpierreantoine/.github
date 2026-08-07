# Contributing

## Workflow

1. Start from current `dev` unless the repository documents another base branch.
2. Create a focused `feature/*`, `fix/*`, or `docs/*` branch.
3. Keep changes small, tested, and documented.
4. Open a pull request into `dev`; release through a separate `dev` to `main` PR.

Before editing, inspect working-tree status. Never overwrite, reset, or auto-stash
in-progress work. If branches diverge unexpectedly, inspect history before acting.

## Quality

- Reuse existing components and design tokens before adding local alternatives.
- Keep domain rules out of route and visual components.
- Validate user input and use parameterized database queries.
- Add or update tests for changed behavior.
- Update stable source-of-truth documentation; avoid duplicate explanations.
- Verify keyboard behavior, focus, contrast, responsive layout, and both themes.

## Commits and pull requests

Use clear conventional commit subjects where practical. Pull requests should state
the outcome, verification, risks, migrations, rollback, and documentation impact.
