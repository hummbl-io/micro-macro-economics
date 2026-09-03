# Analysis Schema

Every analysis in `analyses/` follows this schema. The YAML frontmatter
makes analyses machine-readable and comparable; the body follows the
6-step methodology.

## Frontmatter

```yaml
---
subject: "The global commodity market for arabica and robusta coffee"
unit_of_analysis: commodity market
date_analyzed: 2026-09-03
analyst: your-name-or-agent
tags: [commodity, agriculture, global-trade, consumer-goods]
dominant_level: macro  # micro | macro | interaction
leverage_point: "macro — trade policy and climate adaptation"
confidence: medium     # low | medium | high
sources: 12            # count of cited sources
---
```

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `subject` | string | yes | One-sentence statement of what's being analyzed |
| `unit_of_analysis` | string | yes | The kind of thing: product, market, industry, policy, technology, resource |
| `date_analyzed` | date | yes | When the analysis was done (ISO 8601) |
| `analyst` | string | yes | Who did it (human name, agent name, or team) |
| `tags` | list | yes | Free-form tags for searchability |
| `dominant_level` | enum | yes | Which level drives the subject: `micro`, `macro`, or `interaction` |
| `leverage_point` | string | yes | One-sentence statement of the highest-leverage intervention |
| `confidence` | enum | yes | How confident the analyst is in the dominant_level and leverage_point claims |
| `sources` | int | no | Count of cited sources in the analysis body |

## Body structure

The body follows the 6-step methodology from `docs/methodology.md`:

```
## 1. Subject
## 2. Actors (Micro)
## 3. System (Macro)
## 4. Price Mechanism
## 5. Feedback Loops
## 6. Leverage Point
## References
```

Each section should be 200-800 words for a full analysis, 50-150 words
for a quick-pass. Cite sources inline as `[N]` and list them in References.
