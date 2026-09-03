# Analysis Template

Copy this file to `analyses/<your-subject>.md` and fill in each section.

---
```yaml
---
subject: ""
unit_of_analysis: ""  # product | market | industry | policy | technology | resource
date_analyzed: ""
analyst: ""
tags: []
dominant_level: ""  # micro | macro | interaction
leverage_point: ""
confidence: ""  # low | medium | high
sources: 0
---
```

## 1. Subject

State the subject in one sentence. Then state the unit of analysis and
why this subject is worth analyzing.

> **Prompt**: What exactly are you looking at, and why does it matter?

## 2. Actors (Micro)

### Producers
- Who makes/sells the thing?
- What are their cost structures (fixed vs variable, marginal cost trends)?
- What constraints do they face (capacity, capital, regulation, technology)?
- Objective function: "Producers maximize ___ subject to ___."

### Consumers
- Who buys it?
- What are they willing to pay? Is demand elastic or inelastic?
- What substitutes exist? How close are they?
- Objective function: "Consumers maximize ___ subject to ___."

### Intermediaries
- What brokers, platforms, retailers, or speculators sit between producers and consumers?
- What friction do they add or remove?
- What margin do they capture?

### Complementors
- What adjacent goods/services affect demand for this subject?
- Are complements getting cheaper/more available (boosts demand) or more expensive (suppresses it)?

## 3. System (Macro)

### Supply-side aggregates
- Total production capacity and trends
- Input cost trends (labor, energy, materials, land)
- Technology shifts affecting production

### Demand-side aggregates
- Total market size and growth
- Demographic shifts, income effects
- Substitution trends at the population level

### Institutional forces
- Regulation (current and pending)
- Trade policy (tariffs, quotas, agreements)
- Taxation and subsidies
- Legal frameworks (property rights, contract enforcement)

### Monetary/fiscal
- Interest rate effects on the subject
- Exchange rate effects (if internationally traded)
- Government spending that affects demand or supply

### International
- Trade flows and balances
- Comparative advantage shifts
- Geopolitical risk

## 4. Price Mechanism

- How does price form? (auction, bilateral, posted, regulated)
- Is the price distorted (subsidies, price floors/ceilings, monopolies)?
- What information does the price carry? What does it hide?
- Who captures the margin between consumer price and producer revenue?

## 5. Feedback Loops

This is the most important section. Identify cross-level dynamics:

- **Composition effects**: Individual rational decisions → collectively irrational outcomes?
- **Policy leakage**: Macro interventions → distorted micro incentives?
- **Network effects**: Does value to one actor depend on participation of others?
- **Time lags**: Do micro responses to macro signals arrive too late, causing overshoot?

## 6. Leverage Point

Run the decision tree in `docs/decision-tree.md`. Then state:

- **Dominant level**: micro | macro | interaction
- **Leverage point**: "The highest-leverage intervention is ___ because ___."
- **Why this level**: Explain why intervening at the other level would be less effective.

## References

List all sources cited inline as `[N]`.

1. ...
2. ...
