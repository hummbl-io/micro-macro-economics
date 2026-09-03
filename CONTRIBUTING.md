# Contributing

## Adding an analysis

1. Copy `templates/analysis-template.md` (or `templates/quick-pass.md`)
   to `analyses/<subject>.md`
2. Fill in the YAML frontmatter and all sections
3. Add a row to `analyses/README.md`
4. Cite sources inline as `[N]` and list them in References
5. Open a PR

## Quality bar

- Every factual claim should have a source
- The `dominant_level` field must match what the decision tree in
  `docs/decision-tree.md` would produce
- The `leverage_point` must be a single sentence with a "because" clause
- State `confidence: low` if you have fewer than 3 sources or any
  unresolved ambiguity in the feedback loops section

## Improving the framework

Changes to `docs/`, `templates/`, or the schema should be discussed in an
issue first. The framework should stay simple — 6 steps, one decision tree,
one schema. If you want to add complexity, add it as an optional extension,
not a replacement.

## License

By contributing, you agree your contributions are licensed under both the
MIT and Apache-2.0 licenses (see `LICENSE-MIT` and `LICENSE-APACHE`).
