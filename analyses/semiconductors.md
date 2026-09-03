---
subject: "The global semiconductor industry — fabrication, design, and geopolitics"
unit_of_analysis: industry
date_analyzed: 2026-09-03
analyst: jarvis
tags: [semiconductors, manufacturing, geopolitics, technology, supply-chain, chips]
dominant_level: interaction
leverage_point: "interaction — fab capacity and lithography equipment are the leverage point because they sit at the seam between micro (firm-level production decisions) and macro (geopolitical control of production capability)"
confidence: high
sources: 8
---

# Semiconductors: Micro vs Macro Economic Analysis

## 1. Subject

The global semiconductor industry — the design, fabrication, and distribution
of integrated circuits. The most strategically important manufacturing
industry in the world, with ~$600B annual revenue projected to reach $1T by
2030 [1]. Semiconductors are the physical substrate of the entire digital
economy: every AI model, every phone, every car, every weapon system depends
on chips.

The industry is a textbook case of micro-macro interaction: firm-level
decisions about where to build fabs, what to manufacture, and how to price
chips interact with macro forces (geopolitics, trade policy, technology
cycles, capital intensity) in ways that produce global power dynamics.

## 2. Actors (Micro)

### Producers (Foundries + IDMs)
Three tiers of producers:

- **Pure-play foundries**: TSMC (~60% of global foundry revenue), Samsung
  Foundry, UMC, SMIC [2]. They manufacture chips designed by others.
- **Integrated Device Manufacturers (IDMs)**: Intel, Samsung, SK Hynix,
  Micron — design and manufacture their own chips.
- **Fabless designers**: NVIDIA, AMD, Qualcomm, Apple, Broadcom — design
  chips but outsource manufacturing to foundries.

Cost structure is the most extreme in any industry. A leading-edge fab
costs $20-40B to build and 2-3 years to construct [3]. Once built, it
must run at near-100% utilization to be profitable — a fab running at 70%
capacity loses money. Marginal cost per wafer is low once the fab is
operational, but the fixed cost is astronomical. This creates extreme
barriers to entry and extreme pricing pressure.

Objective: "Producers maximize fab utilization and technology leadership
subject to capital constraints, geopolitical access, and multi-year
investment cycles."

### Consumers
Every industry. The largest chip consumers are: smartphones (~25% of
demand), PCs/servers (~20%), automotive (~10%, growing fast with EVs),
data center/AI (~15%, growing fastest), consumer electronics (~15%),
industrial/defense (~15%) [4].

Demand is derived — nobody buys chips for their own sake. Chip demand
tracks the demand for everything electronic. This makes semiconductor
demand highly cyclical: it amplifies upswings and downswings in the
broader economy.

Objective: "Consumers maximize functionality per dollar subject to
availability, performance requirements, and supply chain risk."

### Intermediaries
- **EDA companies** (Synopsys, Cadence, Siemens EDA): provide the design
  tools. Oligopoly — three companies control ~75% of the EDA market [5].
- **Equipment manufacturers** (ASML, Applied Materials, Lam Research,
  Tokyo Electron, KLA): provide fab equipment. ASML is the only company
  in the world that makes EUV lithography machines — a monopoly within
  the monopoly.
- **Distributors** (Arrow, Avnet): handle logistics for commodity chips.
  High-volume chips (CPUs, GPUs) go direct from foundry to OEM.

### Complementors
- **Software**: chips are useless without software. The x86/Windows and
  ARM/Android ecosystems are complement stacks that determine chip demand.
  NVIDIA's CUDA ecosystem is a complement moat that makes NVIDIA GPUs
  harder to substitute.
- **AI models**: the AI boom is a complement-driven demand surge — bigger
  models need more GPUs, which drives foundry demand, which drives
  equipment demand.

## 3. System (Macro)

### Supply-side aggregates
- Global semiconductor capacity is concentrated in Taiwan (~65% of
  leading-edge logic), South Korea (~20% of memory), and China (~mid-range
  logic, expanding) [2]. This geographic concentration is the defining
  macro feature.
- Technology cycles (Moore's Law): each generation shrinks transistors,
  requiring new fab equipment. The cycle is slowing — moving from 2nm to
  1nm is exponentially harder. This means the technology treadmill is
  slowing, giving existing leaders more time to amortize investments.
- EUV lithography: the single most constrained production input. ASML
  produces ~50 EUV machines per year at $200-300M each [6]. Without EUV,
  you cannot make leading-edge chips. This is a single-point-of-failure
  in the global supply chain.

### Demand-side aggregates
- AI is the dominant demand driver: NVIDIA data center revenue went from
  $15B (2022) to $115B (2024 projected) [7]. This is the fastest demand
  surge in semiconductor history.
- Automotive electrification: EVs use 2-3x more chips than ICE vehicles.
  As EV penetration grows, automotive semiconductor demand grows
  non-linearly.
- Geopolitical stockpiling: governments and corporations are building
  inventories as a hedge against supply disruption. This creates
  artificial demand that disappears once stockpiles are adequate.

### Institutional forces
- **CHIPS Act (US)**: $52B in subsidies to bring fab capacity to the US.
  Target: 20% of global leading-edge production by 2030 (from ~10% today) [8].
- **EU Chips Act**: €43B to double EU's global market share to 20% by 2030.
- **China export controls**: US restrictions on exporting advanced chipmaking
  equipment to China (ASML EUV banned, DUV restricted). China is investing
  $150B+ in domestic semiconductor self-sufficiency.
- **Taiwan**: the geopolitical flashpoint. A Taiwan conflict would disable
  ~65% of global leading-edge chip production overnight. This is the
  tail risk that drives every macro decision in the industry.

### Monetary/fiscal
- Semiconductor capex is interest-rate sensitive: a $20B fab financed at
  5% costs $1B/year in interest. Low rates (2020-2022) enabled a fab
  building boom; higher rates (2023+) slow new investment.
- Government subsidies (CHIPS Act, EU Chips Act) are fiscal interventions
  that distort the market — they make fabs viable in locations that
  pure economics would reject.

### International
- The semiconductor industry is the front line of US-China strategic
  competition. Chips are to the 21st century what oil was to the 20th.
- Comparative advantage has been inverted: the US leads in design but
  manufactures little; Taiwan manufactures but doesn't design leading
  chips; China has demand but limited access to leading-edge supply.
- Trade policy (export controls, tariffs, subsidies) is the primary
  macro lever. Technology policy (Moore's Law, EUV) is the secondary lever.

## 4. Price Mechanism

Price formation varies by chip type:

- **Commodity chips** (memory, standard logic): priced on spot markets
  and long-term contracts. Highly cyclical — prices swing 50-200% over
  the cycle.
- **Leading-edge logic** (CPUs, GPUs): priced bilaterally by the foundry-
  fabless relationship. TSMC has significant pricing power because
  alternative capacity doesn't exist. NVIDIA's GPU prices are set by
  AI demand urgency, not production cost — an H100 sells for $30-40K
  while costing ~$3-5K to manufacture [7].
- **Equipment**: ASML EUV machines are priced at $200-300M with 2-3 year
  delivery lead times. The price reflects monopoly scarcity, not
  production cost.

The price carries information about technology generation, capacity
availability, and demand urgency. But it hides: (a) the geopolitical
risk premium (Taiwan uncertainty is not priced into chip costs), (b)
the environmental externalities (fab water and energy consumption), (c)
the subsidy distortion (CHIPS Act money makes US fabs look cheaper than
they are).

**Margin distribution**: NVIDIA captures ~75% gross margin on AI GPUs.
TSMC captures ~50-55% on leading-edge wafers. The fabless designer
captures more margin than the manufacturer — a reversal of the
traditional manufacturing relationship. This is because design
complexity (NVIDIA's CUDA ecosystem, Apple's silicon) is harder to
replicate than manufacturing process (which TSMC has industrialized).

## 5. Feedback Loops

### The capacity cycle (composition effect)
When chip demand rises, producers build fabs. But fabs take 2-3 years
to construct. By the time new capacity comes online, demand may have
shifted. The result: chronic cycles of shortage and oversupply. In
2021, auto chips were scarce (prices 10x normal). In 2023, memory chips
were in oversupply (prices down 50%). Individual rational decisions
(build when demand is high) produce collectively irrational outcomes
(boom-bust cycles). This is the semiconductor version of the coffee
cobweb cycle — but with $20B fab investments instead of coffee trees.

### The AI demand loop (micro → macro → micro)
NVIDIA designs a better GPU → AI labs train bigger models → bigger
models need more GPUs → NVIDIA designs a better GPU. This reinforcing
loop is driving the fastest demand surge in semiconductor history. The
macro effect (AI becomes a $100B+ chip market) feeds back into micro
decisions (every fabless company now designs AI accelerators). The
loop will break when either (a) model scaling plateaus, (b) alternative
compute (analog, optical, neuromorphic) becomes viable, or (c) power
constraints limit data center growth.

### The geopolitics loop (macro → micro → macro)
US export controls restrict Chinese access to advanced chips → China
invests $150B in domestic capacity → domestic chips close the technology
gap → US tightens controls further → China accelerates investment. This
is a classic arms race dynamic (Schelling). Each side's rational
response to the other's move escalates the competition. The macro
outcome (bifurcation of the global chip supply chain) reshapes micro
decisions (firms must choose "US stack" or "China stack" and can't
easily serve both).

### The talent loop (micro → macro)
Semiconductor manufacturing requires extreme specialized expertise.
Leading-edge process engineers are a tiny global pool. When TSMC opens
a fab in Arizona, it needs US-based engineers with experience that only
exists in Taiwan. The talent constraint limits how fast capacity can
expand, creating a macro bottleneck from a micro scarcity. The CHIPS
Act can fund fabs but cannot instantly create the engineers to run them.

## 6. Leverage Point

**Dominant level**: interaction — but the seam is where leverage exists.

**Leverage point**: "The highest-leverage intervention is at the seam —
fab capacity and lithography equipment — because these sit at the
interface between micro firm-level production decisions and macro
geopolitical control of production capability. Whoever controls fab
capacity and EUV access controls the industry."

**Why not micro**: Individual firm decisions (NVIDIA's next GPU, Intel's
next process node) matter but are downstream of the capacity constraint.
A better GPU still needs TSMC to manufacture it. A better process node
still needs ASML EUV. Micro innovation is bounded by macro capacity.

**Why not pure macro**: Pure macro interventions (CHIPS Act subsidies,
export controls) can shift where fabs are built but cannot change the
underlying economics — a fab in Arizona costs 2-3x more to operate than
one in Taiwan due to labor, regulatory, and ecosystem differences.
Subsidies can offset this temporarily but cannot make it structurally
efficient. The macro intervention creates capacity but not competitiveness.

**The real leverage**: Cross-level interventions:
- **EUV access**: controlling who gets ASML's machines controls who can
  make leading-edge chips. This is the single most powerful leverage
  point in the industry — a single company in a single country.
- **Ecosystem lock-in**: NVIDIA's CUDA, Apple's silicon ecosystem. These
  are micro products that create macro dependencies — once the software
  stack is built on your chips, switching costs become prohibitive.
- **Talent pipelines**: the long-term constraint. Investing in
  semiconductor engineering education creates the human capital that
  makes new fabs viable. This is a micro investment with macro returns.

The semiconductor industry's economics are defined by extreme capital
intensity, geographic concentration, and geopolitical competition. The
leverage is not in any single chip or any single fab. It's in the
infrastructure that makes chips possible — the equipment, the talent,
and the ecosystems. That's the seam.

## References

1. Semiconductor Industry Association, "2024 State of the U.S.
   Semiconductor Industry" (2024)
2. TrendForce, "Global Foundry Revenue Market Share" (Q2 2024)
3. SEMI, "World Fab Forecast" (2024) — fab construction cost data
4. McKinsey, "Semiconductor Industry Report" (2024) — demand segmentation
5. EE Times, "EDA Market Report" (2024) — Synopsys/Cadence/Siemens share
6. ASML, "Annual Report 2023" — EUV shipment and pricing data
7. NVIDIA, "FY2024 Annual Report" — data center revenue and GPU pricing
8. CHIPS and Science Act, Public Law 117-167 (2022) — $52B subsidy
   authorization
