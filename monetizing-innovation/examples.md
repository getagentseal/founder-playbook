# Monetizing Innovation - Worked Examples & Templates

Practical templates and worked math referenced from [SKILL.md](SKILL.md).

---

## Pizza & Breadsticks Bundling Math

You sell pizza and breadsticks. 4 segments, 100 customers each, different WTP.

| Strategy | Revenue |
|----------|---------|
| Pizza $4.50 + Breadsticks $5 (à la carte) | $2,850 |
| Pizza $8 + Breadsticks $8.50 (optimal à la carte) | $3,300 |
| Bundle only at $10.50 (pure bundling) | $4,200 |
| **Mixed: Bundle $13 + Pizza $9 + Breadsticks $9** | **$4,400** (+33% over à la carte) |

**Less than 10% of executives find the optimal answer.**

**Bonus trick:** Bundle at $13 looks like a $5 discount vs $18 standalone. **Show discounting without discounting.**

**Key lesson:** In mixed bundles, the à la carte prices need to be HIGHER than they were in pure à la carte. This is counterintuitive.

---

## The 100-Point Goal Allocation Exercise

**Setup:** C-suite execs each independently allocate 100 points across goals.

| Goal | Exec A | Exec B | Exec C | CEO | Avg |
|------|--------|--------|--------|-----|-----|
| Revenue | 30 | 15 | 40 | 25 | 28 |
| Market share | 20 | 35 | 10 | 40 | 26 |
| Profit | 25 | 20 | 30 | 15 | 23 |
| Margin | 10 | 15 | 10 | 10 | 11 |
| CLV | 10 | 10 | 5 | 5 | 8 |
| ARPU | 5 | 5 | 5 | 5 | 5 |
| **Total** | **100** | **100** | **100** | **100** | |

**Reveals massive misalignment** in teams who thought they agreed.

**Output:** Discussion converges to a written goal like:
> "Maximize market share, but ensure overall profit increase of at least 10%."

This becomes the constraint for pricing strategy choice.

---

## The BECAUSE Test - Templates

Every pricing decision must end with a "because" traceable to customer data.

### Bad Examples

- "We priced at $99 to be competitive."
- "We priced at $99 because that's what our spreadsheet said."
- "We priced at $99 because the CEO said so."

### Good Examples

- "We priced at $99 BECAUSE 60% of segment B told us $100 was the threshold above which they'd reconsider, and our value advantage justifies the high end of acceptable."
- "We priced Better at $79 BECAUSE our G/B/B test showed the $69-$89 range produced 70% Better+Best with $79 maximizing total revenue."
- "We chose subscription BECAUSE 75% of interviewed prospects preferred predictable monthly cost over per-seat licensing, and our cost-to-serve scales with usage."

### Template

```
We priced [SKU/tier] at $[price] BECAUSE
[N]% of [segment] customers told us [specific data point about WTP/threshold/value],
AND [secondary data point about competitive position or willingness to upgrade].
```

---

## MOCA Matrix - Worked Example

### Setup

You're an industrial pump maker competing against an incumbent.

```
                          HIGH IMPORTANCE
                                |
    Service network             |    Reliability (you = better)
    (incumbent better)          |    Energy efficiency (you = better)
                                |
    ─────────────────────────────────────── Performance
                                |
    Industrial design           |    Onboarding software
    (incumbent better)          |    (you = better)
                                |
                          LOW IMPORTANCE
```

### Action by Quadrant

- **Top Right (Reliability, Efficiency):** Lead all marketing here. These are your wedge.
- **Bottom Right (Onboarding software):** Try to convince customers this matters - **only with proof points**. If you can't, don't waste budget.
- **Top Left (Service network):** Prepare defensive arguments. Bundle 3rd-party service partners. Consider proactive remote diagnostics.
- **Bottom Left (Industrial design):** Ignore for now.

### Critical Caveat

**Performance is "as your CUSTOMERS see it."** Many engineers fail MOCA by self-grading their own product. Run with customer interviews.

---

## Value-Selling Spreadsheet (B2B Pattern)

Best-in-class B2B sales build per-customer ROI calculators.

### Template

| Input (customer-specific) | Customer Value | Calculation |
|----------------------------|----------------|-------------|
| Current annual spend on Y | $___ | input |
| Current error rate | __% | input |
| Hours/week on manual task | __ | input |
| Average labor cost/hr | $___ | input |
| **Output** | | |
| Annual error cost | $___ | spend × error rate |
| Annual labor cost | $___ | hours × 52 × rate |
| Total addressable savings | $___ | sum |
| Our product cost | $___ | your price |
| **Net annual savings** | $___ | savings - cost |
| **Payback months** | __ | (cost / monthly savings) |

### Effect

- Reframes conversation from "how much does it cost" to "how much do I save"
- Forces salespeople to engage with customer-specific value math
- Gives the customer a quantified justification for procurement

### SaaS Warehouse Case

- Built spreadsheet computing inventory carrying costs reduced, picking hours saved, shipping errors avoided, paper-doc savings
- Sales "took off like a rocket" while competitors were still explaining features

---

## SmugMug Case (Benefit-not-Feature Messaging)

### Before

- 100+ feature statements
- Customers confused, didn't buy

### After

Reduced to <10 benefit statements + 4 segment-specific tiers:

| Segment Need | Tier |
|--------------|------|
| Want photo storage | **Basic** |
| Want personalization | **Power** |
| Want to sell online | **Portfolio** |
| Want to market a business | **Business** |

Headline benefits: "beautiful design," "unlimited storage."

### Result

Double-digit % increase in revenue and conversion.

---

## Manheim DealShield Case (Living Business Case)

### Setup

Used-car auctioneer wanted to launch return guarantee.

### Process

- Some execs: "Just launch it"
- Pricing team: "Test first"
- Found: WTP varied by car type, condition, return window
- Risk-averse dealers wanted **21 days, 500 miles**
- Built business case linking risks, value, WTP, demand

### Outcome

- Launched with that exact spec
- Now protects billions in vehicle purchases

**Lesson:** WTP testing reveals product spec, not just price. Living business case forces this discovery.

---

## Behavioral Pricing - Anchoring (The Economist)

### Setup

Magazine subscription test.

### Group A

| Option | Price | Pick Rate |
|--------|-------|-----------|
| Online only | $59 | 68% |
| Print + online | $125 | 32% |

### Group B (added an anchor)

| Option | Price | Pick Rate |
|--------|-------|-----------|
| Online only | $59 | 16% |
| Print only | $125 | 0% |
| **Print + online** | **$125** | **84%** |

### Lesson

The $125 print-only option made the $125 print+online bundle look like a no-brainer. Adding a useless option increased revenue ~30%.

**Rule:** Always have an anchor product. Start B2B negotiations with a HIGH anchor.

---

## Behavioral Pricing - Threshold Mapping

### How To Find Your Thresholds

1. Run an A/B test at multiple price points: $69, $69.99, $71, $74, $79, $89, $99
2. Compare conversion at each level
3. Look for **discontinuities** - cliffs where conversion drops sharply

### Common Thresholds (Western Markets)

- $40, $70, $99, $100, $199

### Rule

**Stay on the cliff** - the price just below a threshold (e.g., $69.99 instead of $71). The $1.01 difference dropped acceptance >20% in one online subscription study.

---

## Razor & Blades - When to Use

### Coffee Machine Example

| Option | Machine | Coffee/mo | 12-mo Total |
|--------|---------|-----------|-------------|
| A | $480 | $10 | $600 |
| B | $120 | $40 | $600 |

Same total. Customers strongly prefer B.

### Decision Rule

Use razor & blades **only if you're 100% sure you can sell the downstream products**:
- Lock-in mechanism (proprietary cartridges, accounts, data)
- High switching cost
- Customer can't easily skip the consumable

If you're not sure, don't give away the razor.

---

## CEO Checklist - Quick Self-Diagnosis

Run this before approving any new product launch.

| Question | Yes/No |
|----------|--------|
| Have we held WTP conversations with ≥10 customers? | |
| Are our segments based on needs/value/WTP (not demographics)? | |
| Do we have ≤4 segments? | |
| Have we explicitly named our Leaders, Fillers, and Killers? | |
| Is our G/B/B configured with FENCES (visible differences)? | |
| Have we picked a monetization model (not assumed)? | |
| Is our pricing strategy documented (max/penetration/skimming)? | |
| Does our living business case link Price/Value/Volume/Cost? | |
| Have we tested benefit-not-feature messaging? | |
| Have we considered behavioral tactics? | |
| Are we prepared to maintain price integrity post-launch? | |
| Can anyone on the team answer "Why this price?" with a customer-data BECAUSE? | |

If any answer is NO, stop and fix it before launch.
