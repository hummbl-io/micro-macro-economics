# Micro vs Macro Economics Framework

**Take any subject. Decompose it into micro and macro economic forces. See which level actually matters.**

This is a structured analysis framework — not a textbook, not a model, not a
prediction engine. It's a set of templates and a methodology that forces you
to look at any given thing from both the individual-actor level (micro) and
the system-level (macro), then identify where the leverage actually is.

## Why

Most economic analysis defaults to one level. Business strategy leans micro
(firms, costs, competition). Policy leans macro (aggregates, regulation,
trade). Both miss cross-level effects — the cases where micro decisions
produce macro outcomes that feed back into micro incentives.

The framework exists to make that cross-level thinking systematic, not
incidental.

## What's inside

```
.
├── README.md                  ← you are here
├── docs/
│   ├── methodology.md         ← the 6-step method, explained
│   ├── schema.md              ← the standard analysis schema (YAML frontmatter)
│   └── decision-tree.md       ← when micro matters more, when macro matters more
├── templates/
│   ├── analysis-template.md   ← blank template — copy this to start a new analysis
│   └── quick-pass.md          ← 1-page version for fast takes
├── analyses/
│   ├── coffee.md              ← worked example: the global coffee market
│   └── README.md              ← index of completed analyses
└── LICENSE
```

## How to use it

1. **Copy** `templates/analysis-template.md` to `analyses/<your-subject>.md`
2. **Fill in** each section — the template has prompts, not blanks
3. **Run the decision tree** in `docs/decision-tree.md` to identify the dominant level
4. **Write the synthesis** — where do micro and macro interact? What's the leverage point?

The `quick-pass.md` template is for when you need a 15-minute version, not a
2-hour deep dive.

## The core idea

Every economic subject has two layers:

| Layer | Questions it answers | Tools |
|-------|---------------------|-------|
| **Micro** | Who are the actors? What do they want? What are their constraints? How do prices form? | Supply/demand, marginal analysis, game theory, market structure |
| **Macro** | What are the aggregate outcomes? What forces shape the system as a whole? | GDP, inflation, trade balances, fiscal/monetary policy, regulation |

The interesting work is almost always in the **interaction** — where micro
decisions aggregate into macro patterns, or where macro conditions constrain
micro choices in non-obvious ways.

## Part of the HUMMBL ecosystem

This framework is part of [HUMMBL](https://github.com/hummbl-io) — **H**ighly
**U**seful **M**ental **M**odel **B**ase **L**anguage.

The "Mm" in HUMMBL has a dual reading:

- **M**ental **M**odels — the substrate: structured thinking as executable code
  ([Base120](https://github.com/hummbl-io/oss/tree/main/packages/python/base120),
  120 reasoning operators)
- **M**acro-**m**icro — the application: decompose any subject into levels and
  find the leverage point (this repo)

Both readings describe the same thing: **structured decomposition of complex
systems.** Engineers see "mental models" and think "executable reasoning
operators." Analysts see "macro-micro" and think "economic decomposition
framework." Same word, same substrate, different doors.

HUMMBL's broader positioning: *structured thinking at fleet scale — one
operator, governed agents, any domain.* This framework is one of those
domains.

## License

MIT OR Apache-2.0 — same as the rest of the hummbl-io fleet.
