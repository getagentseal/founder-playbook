# Frameworks - The Lean Startup

## Build-Measure-Learn - Detailed Breakdown

### Planning in Reverse

The loop reads Build-Measure-Learn, but you **plan in reverse order**:

```
PLANNING ORDER (reverse):
1. LEARN: What do we need to learn?
   "Do customers want automated contract tracking?"

2. MEASURE: What data would prove or disprove this?
   "Signup-to-active-use conversion rate above 40% within 7 days"

3. BUILD: What is the minimum we need to build to get that data?
   "Landing page + manual concierge service for 10 customers"

EXECUTION ORDER (forward):
1. BUILD the MVP
2. MEASURE customer behavior
3. LEARN whether the hypothesis holds
```

### The Build Phase

What to build:
- The minimum product/experiment needed to test the current hypothesis
- NOT the full vision. NOT "v1.0." NOT the product you're embarrassed by.
- Guided by: what assumption are we testing?

Common mistakes:
- Building too much ("while we're at it, let's also add...")
- Building for imaginary quality standards
- Over-engineering the experiment
- Waiting for "one more feature" before shipping

### The Measure Phase

What to measure:
- The specific metric tied to your leap-of-faith assumption
- Cohort-based, not cumulative
- Actionable (you can trace cause to effect)

Common mistakes:
- Measuring vanity metrics (total signups, page views, gross revenue)
- Measuring too many things at once
- Not establishing a baseline first
- Comparing against the plan instead of against the baseline

### The Learn Phase

What counts as learning:
- A validated or invalidated hypothesis, backed by data
- A specific decision: pivot, persevere, or run another experiment
- A change in future behavior based on what was discovered

What does NOT count:
- "We learned a lot" without specifics
- Anecdotal customer quotes without behavioral data
- Rationalizing why the experiment didn't work

> "Validated learning is not after-the-fact rationalization or a good story designed to hide failure. It is a rigorous method for demonstrating progress when one is embedded in the soil of extreme uncertainty."

---

## Leap-of-Faith Assumptions - Deep Dive

### Value Hypothesis

Tests whether the product delivers value to customers once they're using it.

**Leading indicators of value:**
- Repeat usage without prompting
- Willingness to pay (especially switching from free to paid)
- High engagement per session
- Organic word-of-mouth ("have you tried X?")
- Customer upset when product is removed or degraded

**Lagging indicators (weaker):**
- Revenue (can be driven by sales effort, not product value)
- NPS (can be gamed, not always predictive)
- Feature requests (can indicate interest without value delivery)

### Growth Hypothesis

Tests how new customers discover the product.

**Four sources of sustainable growth:**
1. **Word of mouth** - embedded in product; enthusiastic customers drive awareness
2. **Side effect of usage** - using the product exposes non-users (fashion, status, viral loops)
3. **Funded advertising** - revenue from existing customers funds acquisition of new ones
4. **Repeat purchase/use** - subscription, consumable, habitual use

Each source maps to an engine of growth (see below).

### Analogs and Antilogs

Before running experiments, study prior art:

| Tool | Purpose | Example (iPod) |
|---|---|---|
| **Analog** | Something similar that succeeded - proves part of the hypothesis | Walkman proved people want personal portable music |
| **Antilog** | Something similar that failed - warns where the hypothesis might break | Napster proved people want digital music but showed the business model problem |

Use analogs to build confidence. Use antilogs to identify the specific assumptions you must test.

> "If you're starting a new company, the analogs and antilogs provide the intellectual framework for planning."

---

## Minimum Viable Product - Selection Framework

### MVP Decision Matrix

```
UNCERTAINTY TYPE             BEST MVP TYPE
------------------------------------------------------------------------
"Do people want this?"       Smoke test (landing page, fake door)
                             Video MVP (explainer video + signup)

"Will people pay?"           Wizard of Oz (manual backend, real frontend)
                             Concierge (manual everything, one customer)

"Which approach works?"      Split test (A/B on a live product)
                             Single-feature MVP (one feature, full quality)

"Can we deliver at scale?"   Not an MVP question - this is engineering risk.
                             Build a technical prototype separately.
```

### The Concierge MVP - Detailed

Instead of building software, deliver the value proposition manually for a single customer. Then another. Then another.

**When it works:** When the cost of building is high and the value proposition is unclear. By delivering manually, you learn exactly what customers need before writing a line of code.

**When it doesn't:** When the value proposition IS the technology (e.g., "faster than humanly possible"). In that case, a Wizard of Oz MVP (automated frontend, manual backend) is better.

### The Video MVP - Detailed

Create a short video demonstrating the product concept. Measure demand by tracking signups, shares, or pre-orders.

**Rules:**
- Under 3 minutes
- Show the product solving a real problem (not a feature tour)
- Include a clear call to action (signup, email, pre-order)
- The metric is the conversion rate on the CTA, not video views

### MVP Quality and the "Ship Something Terrible" Misconception

Ries does NOT say "ship garbage." He says: **"If we do not know who the customer is, we do not know what quality is."**

Your assumptions about quality may be wrong. Ship the MVP, and customer behavior will tell you which quality dimensions actually matter.

> "Customers don't care about our development methodology, our approach to structuring the engineering team, or our internal planning documents."

Common fear: "competitors will copy us if we ship early." Ries's response: the reality of startups is that competitors are rarely paying attention, and even if they are, the learning you gain from real customers is worth more than competitive secrecy.

---

## Innovation Accounting - Three Milestones in Practice

### Milestone 1: Establish the Baseline

**How:**
1. Build an MVP
2. Get it in front of real customers (not friends, not investors)
3. Measure current state of the growth model

**What to measure at baseline:**
- Conversion rates at each step of the funnel
- Customer retention / churn rate
- Revenue per customer
- Referral rate (if applicable)
- Feature engagement rates

**The baseline will be terrible.** That's the point. You need a starting point, not a good number.

### Milestone 2: Tune the Engine

**How:**
1. Make changes designed to improve metrics from baseline toward the ideal
2. Each change = one experiment testing one hypothesis
3. Track whether changes actually move the numbers

**Rules:**
- One change at a time (or use split tests if testing multiple)
- Compare cohorts, not totals
- Every experiment has a success criteria defined BEFORE running it
- Time-box experiments

**The critical question:** Is the metric moving in the right direction at a sufficient rate?

### Milestone 3: Pivot or Persevere

If tuning is working (metrics are improving toward the ideal) --> persevere.

If tuning has stalled (you're making changes but metrics aren't moving) --> pivot.

> "A pivot is not just an exhortation to change. It is a special kind of structured change designed to test a new fundamental hypothesis."

---

## Metrics Framework - Vanity vs. Actionable

### The Cohort Analysis Method

Instead of looking at cumulative totals, group customers by when they joined and track behavior over time.

```
CUMULATIVE (vanity):
  Jan: 100 users
  Feb: 250 users      <-- looks like growth!
  Mar: 370 users

COHORT (actionable):
  Jan cohort:  100 joined, 40 active month 2, 25 active month 3 (75% churn)
  Feb cohort:  150 joined, 70 active month 2, 45 active month 3 (70% churn)
  Mar cohort:  120 joined, 65 active month 2, ???

  --> Churn is improving slightly (75% -> 70%)
  --> But growth of NEW customers is slowing (150 -> 120)
  --> Total users going up masks TWO problems
```

### Split Testing (A/B Testing)

Ship two versions simultaneously. Measure which performs better against your target metric.

**Rules:**
- Test ONE variable at a time
- Measure behavioral outcomes, not opinions
- Run until statistically significant
- The control group matters - always have one

### The Three A's - Expanded

**Actionable:** The metric must demonstrate clear cause and effect. If a metric doesn't tell you what to do differently, it's vanity.

**Accessible:** Use simple formats. Cohort-based reports everyone can read. At IMVU, Ries replaced complex dashboards with simple cohort reports accessible to every employee.

> "Reports should be drawn directly from master data, not from an intermediate system."

**Auditable:** You must be able to spot-check the data against real customers. Talk to the people behind the numbers. "Managers must be able to test the data by talking to customers themselves."

---

## The Ten Pivots - Detailed Catalog

### 1. Zoom-In Pivot
A single feature of the current product becomes the entire product.
**Signal:** One feature drives all the engagement while the rest is ignored.

### 2. Zoom-Out Pivot
The entire product becomes just one feature of a larger product.
**Signal:** Customers keep asking for something bigger; your product isn't sufficient alone.

### 3. Customer Segment Pivot
The product is right, but for a different customer than originally planned.
**Signal:** Unexpected customer segment adopts the product while the target segment doesn't.

### 4. Customer Need Pivot
The target customer has a real problem, but not the one you're solving.
**Signal:** During customer conversations, you discover a bigger, more urgent problem.

### 5. Platform Pivot
A change from an application to a platform (or vice versa).
**Signal:** Third-party developers want to build on your product, or your "platform" only has one useful app.

### 6. Business Architecture Pivot
Switch from high-margin/low-volume (B2B) to low-margin/high-volume (consumer), or vice versa.
**Signal:** Sales complexity doesn't match the product's value proposition, or consumer pricing can't sustain the business.

### 7. Value Capture Pivot
The monetization or revenue model changes.
**Signal:** Customers love the product but won't pay the current way; or a different revenue model is more sustainable.

### 8. Engine of Growth Pivot
Switch between sticky, viral, or paid growth.
**Signal:** The current engine is stalling; a different engine might be more natural for the product.

### 9. Channel Pivot
Change the distribution mechanism.
**Signal:** The product reaches customers more efficiently through a different channel than originally planned.

### 10. Technology Pivot
Same solution delivered using a different underlying technology.
**Signal:** A new technology can achieve the same result with superior price, performance, or experience.

---

## Three Engines of Growth - Detailed Mechanics

### The Sticky Engine

**Mechanic:** Customers who start using the product continue using it. Growth comes from high retention and low churn.

**Math:**
```
Growth rate = new customer acquisition rate - churn rate

If you acquire 10% new customers/month and lose 8% to churn:
  Net growth = 2% per month

To grow faster: reduce churn OR increase acquisition.
Reducing churn is usually more impactful.
```

**Key metric:** Churn rate (and its inverse: retention rate)

**Dominant strategy:** Invest in product quality, engagement, and customer success. Acquisition matters less than retention.

### The Viral Engine

**Mechanic:** Each customer brings in one or more additional customers as a natural side effect of using the product.

**Math:**
```
Viral coefficient (k) = infections per customer
  k = (% of users who invite) x (% of invitees who convert)

If 50% of users invite and 20% of invitees convert:
  k = 0.50 x 0.20 = 0.10

For 100 initial users with k = 0.10:
  100 -> 10 -> 1 -> 0 = 111 total (viral fizzle)

For 100 initial users with k = 0.60:
  100 -> 60 -> 36 -> 22 -> 13 -> 8 -> 5 -> 3 -> 2 -> 1 = 250 total

For 100 initial users with k = 1.10:
  100 -> 110 -> 121 -> 133 -> ... (exponential growth)
```

**Critical threshold:** k > 1.0 = viral growth. k < 1.0 = viral decay.

**Warning:** Small changes in k produce massive changes in outcome. Going from k=0.9 to k=1.1 is the difference between fizzle and explosion. **Do not try to optimize for virality with marketing. Optimize the product so that using it naturally exposes non-users.**

**Key metric:** Viral coefficient (k) and viral cycle time

### The Paid Engine

**Mechanic:** Spend money to acquire customers. Growth comes from reinvesting revenue into acquisition.

**Math:**
```
Profitable when: LTV > CPA
  LTV = lifetime value of a customer
  CPA = cost per acquisition

Marginal profit per customer = LTV - CPA
Growth rate = marginal profit reinvested into acquisition

If LTV = $100 and CPA = $30:
  Marginal profit = $70
  Reinvest $70 -> acquire 2.3 more customers -> each worth $70 marginal...

To grow faster: increase LTV (pricing, upsell, retention)
  OR decrease CPA (better targeting, conversion optimization)
```

**Key metric:** LTV/CPA ratio

**Warning:** Paid engine breaks when competitors bid up CPA or when your LTV decreases. It is the most fragile engine.

### Engine Focus Rule

> "Startups should focus on just one engine of growth."

Trying to run multiple engines simultaneously dilutes effort and makes it impossible to know what's working. Once one engine is running, you can consider layering on another - but not before.

---

## Small Batches - Toyota Production System for Startups

### The Envelope Experiment

Which is faster for stuffing 100 envelopes: fold all 100, stuff all 100, seal all 100, stamp all 100 (large batch)? Or fold-stuff-seal-stamp one at a time (small batch)?

**Counter-intuitively, small batch wins.** Large batch creates invisible overhead: sorting, stacking, re-handling. And if the envelopes don't fit? In small batch, you find out on envelope #1. In large batch, you find out after folding all 100.

### SMED (Single-Minute Exchange of Die)

Toyota's Shigeo Shingo reduced die changeover times from hours to minutes. This made small production runs economical. The startup equivalent: reduce deployment friction so you can ship changes in minutes, not weeks.

### Continuous Deployment

At IMVU, Ries's team deployed code changes **50 times per day**. Each change:
- Was small enough to understand its impact
- Was monitored by automated tests
- Could be rolled back immediately if problems emerged
- Created an "immune system" that got stronger over time

### The Andon Cord

Toyota's famous pull cord that any worker can yank to stop the entire production line when a defect is spotted. In startups:
- Anyone can halt a deployment that breaks something
- Stopping to fix is faster than shipping broken + patching later
- Builds quality into the process rather than inspecting it in afterward

### Pull, Don't Push

Toyota's just-in-time system: don't build inventory ahead of demand. In startups:
- Don't build features ahead of validated demand
- Don't plan sprints based on a roadmap nobody validated
- Each experiment "pulls" exactly the work needed to test the current hypothesis
- WIP (work in progress) is waste if it hasn't been validated

---

## Five Whys - Detailed Method

### The Proportional Investment Principle

At each level of the five whys, make an investment **proportional to the severity** of the symptom. Small symptom = small fix. Deep root cause = bigger investment.

```
Example (IMVU):
1. Feature disabled for customers. Why?
   --> Server failed.
   Fix: restart server (5 minutes)

2. Why did the server fail?
   --> Obscure subsystem used wrong.
   Fix: refactor the subsystem (few hours)

3. Why was the subsystem used wrong?
   --> Engineer didn't know the right way.
   Fix: brief the engineer (30 minutes)

4. Why didn't the engineer know?
   --> Never trained.
   Fix: start first hour of training program (1 hour setup)

5. Why wasn't he trained?
   --> Manager thinks training is waste of time.
   Fix: conversation with manager (uncomfortable but necessary)
```

### Getting Started Rules

1. **Be tolerant of all mistakes the first time**
2. **Never allow the same mistake to be made twice**

This simplified system works for teams new to Five Whys. It builds the muscle without overwhelming the team.

### Five Whys Master

Appoint a dedicated facilitator for each area using Five Whys:
- Senior enough to ensure follow-through
- Not so senior they can't attend regularly
- Tracks proportional investments and whether they pay off
- Prevents descent into Five Blames

### Common Pitfalls

| Pitfall | Symptom | Fix |
|---|---|---|
| **Five Blames** | Finger-pointing instead of root cause analysis | Senior people go first: "shame on us for making it so easy" |
| **Starting with baggage** | Trying to solve legacy problems first | Start with NEW problems only; old ones surface naturally |
| **Missing participants** | Key people not in the room | Everyone affected by the problem attends; especially senior leadership |
| **Too broad** | Trying to fix everything at once | Pick one narrow class of problems; expand later |
| **No follow-through** | Proportional investments identified but not made | Five Whys master tracks completion |

---

## Innovation Sandbox - For Established Companies

### The Seven Rules

1. Any team can create a true split-test that affects only the sandboxed parts of the product, or certain customer segments or territories
2. One team must see the whole experiment through from end to end
3. No experiment can run longer than a specified time limit
4. No experiment can affect more than a specified number of customers (as a % of total base)
5. Every experiment is evaluated on a single standard report of five to ten actionable metrics
6. Every team and product in the sandbox uses the same metrics for evaluation
7. Any team running an experiment must monitor customer reactions and abort if something catastrophic happens

### Why Sandbox, Not Skunkworks

**Skunkworks (hidden innovation):** Protects the startup team but alienates the parent org. Managers feel ambushed when innovation surfaces. Leads to political sabotage.

**Sandbox (open innovation):** Contains the blast radius while keeping innovation visible. Managers see what's happening. Success is measured by the same standards. Reintegration is natural.

> "The challenge here is to create a mechanism for empowering innovation teams out in the open."

---

## Four Kinds of Work (Management Portfolio)

As products mature, companies must manage four simultaneous types of work:

| Phase | Activity | Manager Profile |
|---|---|---|
| **1. Innovation** | Finding new customers, new markets, new business models | Entrepreneur: visionary, scrappy, comfortable with chaos |
| **2. Growth** | Scaling what works, conquering new segments | Growth leader: execution-focused, data-driven |
| **3. Optimization** | Line extensions, incremental upgrades, margin improvement | Optimizer: process-oriented, efficiency-focused |
| **4. Legacy** | Operating costs, infrastructure maintenance, cost reduction | Operator: reliability-focused, cost-conscious |

**The talent trap:** Companies tend to promote innovators into growth/optimization roles. Innovators hate these roles and do them badly. Let people choose the phase that suits their temperament.

> "Entrepreneurship should be considered a viable career path for innovators inside large organizations."

---

## Adaptive Organization - Speed Regulators

### The Paradox of Slowing Down to Speed Up

Adaptive processes (training, Five Whys, small batches) initially feel like they slow you down. But they create **speed regulators** that prevent catastrophic failures and compound over time.

```
WITHOUT speed regulators:
  Sprint → Crash → Firefight → Sprint → Bigger Crash → ...
  Average velocity: LOW (most time spent on rework and crises)

WITH speed regulators:
  Small step → Check → Adjust → Small step → Check → ...
  Average velocity: HIGH (steady progress, minimal rework)
```

### Training as Investment

At IMVU, every new engineer was assigned a mentor and put through a training program. Seemed expensive for a startup. But:
- New hires broke fewer things
- Fewer interruptions for existing engineers
- Each training improvement compounded over time
- The Five Whys sessions that built the training were themselves learning

> "At no point did we drop everything to focus solely on training. Instead, we made incremental improvements to the process constantly, each time reaping incremental benefits."
