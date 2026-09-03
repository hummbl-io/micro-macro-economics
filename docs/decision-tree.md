# Decision Tree: Which Level Matters More?

Use this after completing steps 1-5 of the methodology to determine whether
the micro level, the macro level, or their interaction is the dominant force
for your subject.

## The tree

```
START: Is the subject primarily a single firm or individual decision?
│
├── YES → Does the decision depend on aggregate conditions
│         (market size, interest rates, regulation, trade)?
│         │
│         ├── YES → DOMINANT LEVEL: interaction
│         │         (micro decision constrained by macro environment)
│         │
│         └── NO  → DOMINANT LEVEL: micro
│                   (firm-level strategy, cost structure, competition)
│
└── NO (it's a market, industry, or system)
          │
          ├── Are outcomes driven primarily by individual actor decisions
          │   aggregating up (e.g., commodity cycles, bank runs)?
          │   │
          │   ├── YES → DOMINANT LEVEL: interaction
          │   │         (micro aggregation produces macro patterns)
          │   │
          │   └── NO  → Are outcomes driven by external/systemic forces
          │             (regulation, monetary policy, geopolitics,
          │              technology shifts, climate)?
          │             │
          │             ├── YES → DOMINANT LEVEL: macro
          │             │         (system-level forces dominate)
          │             │
          │             └── NO  → DOMINANT LEVEL: interaction
          │                       (genuinely bidirectional — revisit
          │                        step 5, feedback loops)
```

## Heuristics

When the tree is ambiguous, these heuristics help:

| Signal | Points to |
|--------|-----------|
| Price is set by a central authority or regulator | macro |
| Price is set by competitive market with many small actors | micro |
| The subject is a commodity with global trade | interaction (micro producers, macro trade) |
| The subject is a regulated utility | macro |
| The subject is a new technology with no established market | micro (until standards/policy emerge) |
| The subject is financial markets | interaction (micro trading, macro policy) |
| The subject is labor markets | interaction (micro bargaining, macro conditions) |
| The subject is housing | interaction (micro location decisions, macro rates/zoning) |

## Why this matters

The dominant level tells you where to focus your analysis and where to
look for leverage. If you get the level wrong, you'll optimize at the
wrong scale — a firm-level strategy for a macro problem, or a policy
proposal for a micro problem.

The `interaction` answer is the most common and the most important. Pure
micro and pure macro cases are rare in practice. When you land on
`interaction`, the real work is in step 5 (feedback loops) — that's where
the non-obvious dynamics live.
