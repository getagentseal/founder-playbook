---
name: monetizing-innovation
description: "Designs products around price using the 9 rules from Ramanujam and Tacke - WTP conversations, needs-based segmentation, Good/Better/Best configuration, monetization models, behavioral pricing, and price integrity. Use when designing new products, validating pricing for SaaS/B2B/B2C launches, choosing between subscription/usage/freemium models, fixing post-launch sales below plan, diagnosing failed launches as Feature Shock/Minivation/Hidden Gem/Undead, or when product teams say 'let's price it later'. Not for pure commodities or cost-plus regulated environments."
---

> **Note:** This skill is independent analysis and commentary, not a reproduction of the original text. It synthesizes the book's core ideas with modern startup practice, surfaces where frameworks are outdated or incomplete, and integrates perspectives from adjacent disciplines. For the full argument and context, read the original book.


# Monetizing Innovation

> "Design the product around the price." - Ramanujam & Tacke

## Core Insight

**72% of new products fail** (Simon-Kucher 2014, n=1,615). Root cause: pricing is decided LAST instead of designing the product around it. This figure comes from Simon-Kucher's own client survey data and has not been independently verified. The authors are principals at Simon-Kucher, a pricing consultancy - the stat motivates hiring firms like theirs. Treat it as directionally correct but not independently validated.

| Old paradigm | New paradigm |
|--------------|--------------|
| design → build → market → price | market & price → design → build |

Only ~5% of business cases include real WTP (willingness-to-pay) data. Most companies wait until weeks before launch to set price.

---

## The 4 Failure Types (Diagnose Before Fixing)

| Failure | Definition | Cultural Cause | Tell-Tale Signs |
|---------|------------|----------------|-----------------|
| **Feature Shock** | Cram too many features → confusing, overpriced | Engineering-driven | Can't articulate value; price slashed post-launch |
| **Minivation** | Right product, priced too low | Risk-averse | Sales easily hits target; sellouts; channel maxes margin |
| **Hidden Gem** | Great idea never properly launched | Coddles core business | Mid-level execs kill it; sold as deal sweetener; rival ships first |
| **Undead** | Wrong answer (or no question asked) | Top-down, no dissent | Sales avoid raising it; pet project of senior management |

**Real examples:** Amazon Fire Phone (Feature Shock, $170M write-down), Audi Q7 (Minivation, missed €210M/yr), Kodak digital camera 1974 (Hidden Gem), Segway/Google Glass (Undead).

Full case file: see [cases.md](cases.md).

---

## The 5 Pricing Myths (Counter These)

1. "Build it and they will come" - hides 95% of failures
2. "Innovation needs isolated artists" - customer input informs, doesn't pollute
3. "High failure rates are normal" - failure is preventable
4. "Customers must experience product to price it" - false, they react to concepts
5. "You can't price what you haven't built" - cost-plus thinking; price is set by VALUE

---

## The 9 Rules (Summary)

| # | Rule | Headline |
|---|------|----------|
| 1 | **WTP Talk Early** | 80% of companies skip this. Have it before design freezes. |
| 2 | **Needs-Based Segmentation** | Demographic segmentation is broken. Segment by needs/value/WTP. |
| 3 | **Configuration & Bundling** | Use Leaders/Fillers/Killers + Good/Better/Best with FENCES. |
| 4 | **How You Charge > What You Charge** | Choose the right monetization model (5 options). |
| 5 | **Pricing Strategy** | Maximization / Penetration / Skimming. Apply the BECAUSE test. |
| 6 | **Living Business Case** | Link Price-Value-Volume-Cost. Update at every milestone. |
| 7 | **Value Communication** | Sell benefits, not features. Use MOCA matrix. |
| 8 | **Behavioral Pricing** | 6 tactics: compromise, anchoring, signals, razor-blade, pennies-a-day, thresholds. |
| 9 | **Maintain Price Integrity** | Don't cut after launch. Use 3 nonprice actions first. |

Full framework details with sub-frameworks, methods, and checklists: see [frameworks.md](frameworks.md).

---

## Critical Frameworks (At-a-Glance)

### Leaders / Fillers / Killers

| Type | Definition | Action |
|------|------------|--------|
| **Leader** | Drives buying, high WTP | Always include |
| **Filler** | Nice-to-have | Use to fill gaps |
| **Killer** | Blows the deal if forced to pay | Eliminate or sell à la carte |

Killer test: valued by <20% of customers AND not valued at all by >20%. Killers are segment-dependent (heated seats: leader in cold, killer in tropical).

### Good/Better/Best Distribution

| Distribution | Diagnosis |
|--------------|-----------|
| ≤25% Good, ~70% Better+Best, ≥10% Best | Healthy |
| >50% Good | Trip-wire: cut features from Good |
| Best <10% | Premium tier underpowered |

**Fences are mandatory.** Every tier needs visible, defensible differences. Without fences G/B/B cannibalizes itself. Fence test: in 10 seconds can a customer see what's missing from Good?

### The 5 Monetization Models

| Model | When to Use | Example |
|-------|-------------|---------|
| **Subscription** | Continual usage | Netflix, Adobe |
| **Dynamic Pricing** | Volatile demand or constrained supply | Uber, airlines |
| **Auctions** | Seller's market, constrained inventory | Google AdWords ($35B/yr), eBay |
| **Pay-As-You-Go / Alternative Metric** | Usage tracks value | Michelin (per-mile), GE engines |
| **Freemium** | Near-zero production AND fixed cost | LinkedIn, Dropbox |

**Freemium warning:** fails for 90% of companies; software conversion typically <10%; games lose 75% of users in day 1.

Models are mix-and-matchable (Costco = subscription + per-product; OpenTable = subscription + transaction fee).

### The 6 Behavioral Pricing Tactics

1. **Compromise effect** - always have 3 tiers; people avoid extremes
2. **Anchoring** - The Economist test: $59 vs $125 vs $125-print-only made bundle pick rate jump 32% → 84%
3. **Price signals quality** - Ariely placebo: $2.50 pill 85% pain relief, $0.10 same pill 61%
4. **Razor / razor blades** - low upfront preferred even if total cost identical
5. **Pennies-a-day** - $9.99/mo converts very differently from $120/yr
6. **Psychological thresholds** - $69.99 works, $71 doesn't (drops acceptance >20%)

**Caveat:** can't price purely on behavior. Combine with rational/value-based.

---

## Decision Trees

### "Is my product likely to fail?"

```
Can I clearly state the customer benefit (not features)?
├─ NO  → Likely Feature Shock
└─ YES → Has WTP been validated with real customers?
         ├─ NO  → Could be Undead or Minivation
         └─ YES → Did C-suite engage personally?
                  ├─ NO  → Likely Hidden Gem (won't get launched right)
                  └─ YES → On the right track
```

### "Which monetization model?"

```
Is value tied to usage?
├─ YES → Alternative Metric (Michelin model)
└─ NO  → Demand volatile or supply constrained?
        ├─ YES → Dynamic Pricing
        └─ NO  → Production cost near zero?
                ├─ YES → Freemium (only if 90% of users still profitable)
                └─ NO  → Subscription or per-unit
```

### "Should I cut the price?"

```
Sales below plan?
└─ YES → Identified ROOT CAUSE?
         ├─ NO  → Diagnose first (likely not price)
         └─ YES → Pricing-specific?
                  ├─ NO  → Fix actual problem
                  └─ YES → Tried 3 nonprice actions?
                           ├─ NO  → Try those (advertise; add value; upgrade)
                           └─ YES → War-game competitor reaction
                                    └─ Worse off after counter? → don't cut
```

---

## Critical Numbers

| Number | Rule |
|--------|------|
| **72%** | New products fail |
| **80%** | Companies wait until just before launch to set price |
| **5%** | Business cases include real WTP data |
| **3-4** | Ideal starting number of segments |
| **<10%** | Killer features valued by less than this % |
| **9 / 4** | Max benefits / products before psychological overload |
| **≤25% / 70% / ≥10%** | G/B/B target (Good / Better+Best / Best) |
| **50%** | Trip-wire: more than this picking Good = bleeding |
| **20-30%** | Healthy deal escalation rate |
| **30-40%** | Of ALL DEALS should have price changes upon escalation |
| **3** | Nonprice actions required before any price cut |
| **40%** | More likely to realize potential with defined pricing strategy |
| **33%** | More profit when C-suite leads pricing (vs delegates) - also from Simon-Kucher client data; same provenance caveat as the 72% figure applies |
| **25%** | Of customer interview questions should be "Why?" |

---

## The "BECAUSE" Test

Every pricing decision must end with a "because" traceable to customer data.

**Bad:** "We priced at $99 to be competitive."
**Good:** "We priced at $99 BECAUSE 60% of segment B told us $100 was the threshold above which they'd reconsider, and our value advantage justifies the high end."

If you can't say "because customers told us X," you don't have a pricing strategy.

---

## Quick Reference Checklist

Before designing a new product:
- [ ] WTP conversations with real customers held
- [ ] Segmented by needs/value/WTP (not demographics)
- [ ] Leaders, fillers, killers identified
- [ ] G/B/B configuration designed with FENCES
- [ ] Monetization model picked (aligns with value)
- [ ] Pricing strategy documented (max/penetration/skimming)
- [ ] Living business case links Price/Value/Volume/Cost
- [ ] Benefit-not-feature messaging tested
- [ ] Behavioral tactics considered
- [ ] Team prepared to maintain price integrity post-launch

**The test:** Ask anyone "Why this price?" If the answer is "cost-plus" or "competitor benchmark," failure is coming.

---

## Critical Quotes

- "Design the product around the price."
- "How you charge trumps what you charge."
- "Pricing too low is worse than pricing too high."
- "Customers don't buy products. They buy benefits." - Drucker
- "The single most important decision in evaluating a business is pricing power." - Buffett
- "If I have 2,000 customers and 400 prices, I'm short 1,600 prices." - Crandall (American Airlines)

---

## Supporting Files

- **[frameworks.md](frameworks.md)** - Full detail on all 9 rules, sub-frameworks, methods, and lists (10 WTP insights, 10 bundling insights, 6 post-launch tips, etc.)
- **[cases.md](cases.md)** - Detailed case studies (Porsche, Dodge Dart, LinkedIn, Dräger, Uber, Swarovski, Optimizely, Innovative Pharma) plus failure exemplars
- **[examples.md](examples.md)** - Worked examples: Pizza & Breadsticks bundling math, MOCA matrix, value-selling spreadsheet, 100-point goal allocation, BECAUSE test templates
- **[integration.md](integration.md)** - Implementation roadmap (4 phases), 9 pitfalls, startup/SaaS adaptation, WTP research limitations, conflict resolution with Mom Test/$100M Offers/SPIN

---

## When This Doesn't Apply

- Pure cost-plus regulated environments (utilities, some defense)
- Pure commodities (sugar, copper)
- Very early stage with no product (use Mom Test first)
- B2C impulse buys under $50 (simpler approaches work)
- Geographic markets with no purchasing power

---

## Caveat on WTP Research

Stated WTP and revealed WTP differ. Customers predict their own behavior poorly in interviews. Treat WTP findings as a strong prior, not certainty. Validate with paid pilots, pre-orders, live A/B price tests, or money-back guarantees. See [integration.md](integration.md#wtp-research-limitations).
