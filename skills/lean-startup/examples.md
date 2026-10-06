# Examples - The Lean Startup

## Build-Measure-Learn Cycle Planner

Use this template to plan each iteration through the loop. Remember: plan in reverse (Learn -> Measure -> Build), execute forward (Build -> Measure -> Learn).

```
CYCLE #: _____
DATE: _____

STEP 1: LEARN (what do we need to learn?)
------------------------------------------
Hypothesis to test: _________________________
Leap-of-faith type: [ ] Value hypothesis  [ ] Growth hypothesis
In plain language: "We believe that [customer segment]
  will [expected behavior] because [reason]."
What would DISPROVE this hypothesis? _________________________

STEP 2: MEASURE (what data would prove or disprove this?)
------------------------------------------
Success metric: _________________________
Current baseline (if known): _________________________
Target threshold: _________________________
How we'll measure: _________________________
Time box for this experiment: _________________________

STEP 3: BUILD (what's the minimum we need to build?)
------------------------------------------
MVP type: [ ] Smoke test  [ ] Video  [ ] Concierge
          [ ] Wizard of Oz  [ ] Single-feature  [ ] Split test
What we'll build: _________________________
What we will NOT build (explicitly): _________________________
Estimated build time: _________________________

RESULTS (fill in after experiment)
------------------------------------------
Actual metric: _________________________
Hypothesis: [ ] Validated  [ ] Invalidated  [ ] Inconclusive
Key learning: _________________________
Next action: [ ] Persevere (tune)  [ ] Pivot  [ ] Run another experiment
If pivot, type: _________________________
```

---

## MVP Selection Worksheet

### Step 1: Identify Your Riskiest Assumption

```
What's the ONE thing that, if wrong, kills your startup?

[ ] "Customers have this problem"
    --> Test with: customer interviews (Mom Test) + smoke test
    --> MVP type: Landing page, fake door, or explainer video

[ ] "Customers will pay for this solution"
    --> Test with: real transaction (even manual)
    --> MVP type: Concierge or Wizard of Oz

[ ] "Customers will use this regularly"
    --> Test with: retention data from real usage
    --> MVP type: Single-feature MVP with usage tracking

[ ] "Customers will tell others about this"
    --> Test with: referral/sharing data
    --> MVP type: Product with built-in sharing, track viral coefficient

[ ] "We can acquire customers affordably"
    --> Test with: ad spend experiment
    --> MVP type: Landing page + paid traffic, measure CPA

[ ] "We can build the technology"
    --> This is NOT an MVP question. Build a technical prototype.
    --> Keep market validation separate from engineering validation.
```

### Step 2: Choose MVP Type

```
Can you explain the value prop in under 3 minutes?
|-- YES --> Is the product too complex/expensive to prototype quickly?
|   |-- YES --> VIDEO MVP
|   |   How: Screencast or animated demo + signup CTA
|   |   Measure: Conversion rate on CTA
|   |   Example: Dropbox (5K to 75K signups from one video)
|   |
|   +-- NO  --> SMOKE TEST / LANDING PAGE
|       How: Landing page describing the product + signup/pre-order
|       Measure: Signup or pre-order conversion rate
|       Example: Buffer (landing page before building the product)
|
+-- NO  --> Can you deliver the value manually?
            |-- YES, for one customer at a time --> CONCIERGE MVP
            |   How: Personally deliver the service to 1-5 customers
            |   Measure: Willingness to pay, satisfaction, retention
            |   Example: Food on the Table (CEO did meal planning by hand)
            |
            |-- YES, with a human backend --> WIZARD OF OZ MVP
            |   How: Real frontend, manual backend
            |   Measure: Customer behavior as if product is real
            |   Example: Zappos (photos of shoes, bought at retail when ordered)
            |
            +-- NO  --> SINGLE-FEATURE MVP
                How: Build ONE core feature at full quality
                Measure: Engagement, retention, willingness to pay
                Example: Groupon (one deal per day, one city)
```

### Step 3: Quality Checklist

```
Before shipping the MVP, verify:

[ ] Does it test my RISKIEST assumption? (not the easiest one)
[ ] Have I defined success criteria BEFORE shipping?
[ ] Is there a clear metric tied to the hypothesis?
[ ] Am I measuring behavior, not opinions?
[ ] Can I trace the data back to real humans?
[ ] Have I removed everything that doesn't serve the experiment?
[ ] Am I OK being embarrassed by this? (If not, you've overbuild)
```

---

## Innovation Accounting Setup Template

### Baseline Establishment

```
PRODUCT: _________________________
DATE OF BASELINE: _________________________
MVP USED: _________________________
CUSTOMERS IN BASELINE: _________________________

FUNNEL METRICS (measure each step):
  Awareness (heard of product):        _____%
  Interest (visited site/page):        _____%
  Signup/trial:                        _____%
  Activation (completed onboarding):   _____%
  Retention (returned in week 2):      _____%
  Revenue (paid):                      _____%
  Referral (told someone else):        _____%

UNIT ECONOMICS:
  Revenue per customer (month 1):      $_____
  Cost to acquire (CPA):              $_____
  Cost to serve:                       $_____
  Gross margin per customer:           $_____

ENGAGEMENT:
  DAU/MAU ratio:                       _____
  Average session length:              _____
  Feature usage (top 3):
    1. _____________ : _____%
    2. _____________ : _____%
    3. _____________ : _____%
```

### Tuning Tracker

```
EXPERIMENT #: _____
DATE: _____
HYPOTHESIS: "Changing [X] will improve [metric] from [baseline] to [target]"

BEFORE (baseline or previous cohort):
  Metric: _____________ = _____

CHANGE MADE:
  _____________________________________________

AFTER (new cohort, same time period):
  Metric: _____________ = _____

RESULT:
  [ ] Improved (by _____%)
  [ ] No change
  [ ] Got worse (by _____%)

LEARNING:
  _____________________________________________

NEXT ACTION:
  [ ] Ship this change permanently
  [ ] Revert and try something else
  [ ] Need more data - extend experiment
```

---

## Pivot-or-Persevere Meeting Template

### Pre-Meeting Prep

```
MEETING DATE: _________________________
TIME SINCE LAST PIVOT-OR-PERSEVERE MEETING: _____ weeks/months
ATTENDEES: Product team + business leadership (both required)

PREPARE IN ADVANCE:
1. Current state of innovation accounting metrics
2. Cohort analysis for last 3+ cohorts
3. List of experiments run since last meeting
4. Results of each experiment (validated / invalidated / inconclusive)
```

### Meeting Agenda

```
1. METRIC REVIEW (15 min)
   Current baseline vs. ideal model:

   Metric          Baseline    Current    Ideal     Gap
   ____________    ________    _______    _____    _____
   ____________    ________    _______    _____    _____
   ____________    ________    _______    _____    _____
   ____________    ________    _______    _____    _____

   Is the gap closing?  [ ] Yes  [ ] No  [ ] Mixed

2. EXPERIMENT REVIEW (15 min)
   Experiments run since last meeting:

   #  Hypothesis              Result         Metric Impact
   _  _____________________  ___________    ______________
   _  _____________________  ___________    ______________
   _  _____________________  ___________    ______________

   Are experiments producing useful learning?  [ ] Yes  [ ] No

3. RATE OF PROGRESS (10 min)
   At current rate of improvement, when do we reach the ideal model?
   _____ weeks/months

   Is this rate acceptable given our runway?
   [ ] Yes - persevere
   [ ] No  - consider pivot

4. DECISION (20 min)
   [ ] PERSEVERE - continue current strategy, plan next experiments
   [ ] PIVOT - change a fundamental hypothesis
       Pivot type: _________________________
       New hypothesis: _________________________
   [ ] INCONCLUSIVE - need more experiments before deciding
       Deadline for next meeting: _________________________
```

### Post-Meeting

```
DECISION: _________________________
RATIONALE: _________________________
NEXT EXPERIMENTS (if persevering):
  1. _________________________
  2. _________________________
  3. _________________________
NEW STRATEGY (if pivoting):
  _________________________
NEXT MEETING DATE: _________________________
```

---

## Engine of Growth Diagnostic

### Step 1: Identify Your Current Engine

```
Which engine are you currently running?
(Most startups know, even if they haven't named it)

STICKY ENGINE SIGNALS:
[ ] Your best growth comes from existing users staying longer
[ ] Churn is your biggest problem
[ ] New user acquisition is less important than retention
[ ] Revenue comes from subscriptions or repeat purchases
--> If most checked: You're running the STICKY engine

VIRAL ENGINE SIGNALS:
[ ] Users naturally share the product or invite others
[ ] Growth is organic (not from paid channels)
[ ] Usage of the product exposes non-users to it
[ ] Your best users are your best marketers
--> If most checked: You're running the VIRAL engine

PAID ENGINE SIGNALS:
[ ] You spend money to acquire customers
[ ] Growth tracks with advertising spend
[ ] You know your CPA and LTV
[ ] Sales or marketing drives most new customers
--> If most checked: You're running the PAID engine

[ ] None of these clearly apply
--> You may not have an engine yet. This is a critical problem.
```

### Step 2: Measure Your Engine

```
STICKY ENGINE:
  Monthly churn rate:                _____%
  Monthly new customer rate:         _____%
  Net growth rate (new - churn):     _____%
  Healthy? [ ] Yes (net positive)  [ ] No

VIRAL ENGINE:
  % of users who invite/share:      _____%
  % of invitees who convert:        _____%
  Viral coefficient (k):            _____ (multiply above two)
  Viral cycle time:                  _____ days
  Healthy? [ ] Yes (k > 0.5)  [ ] Exceptional (k > 1.0)  [ ] No

PAID ENGINE:
  LTV (lifetime value):             $_____
  CPA (cost per acquisition):       $_____
  LTV/CPA ratio:                    _____
  Marginal profit per customer:     $_____
  Healthy? [ ] Yes (LTV > CPA)  [ ] No
```

### Step 3: Is Your Engine Running Out?

```
WARNING SIGNALS:
[ ] Growth is slowing despite same effort
[ ] Key metric (churn/k/LTV-CPA) is worsening
[ ] The easy improvements have been made
[ ] Competition is eroding your advantage

If 2+ checked: your engine may be running out.
Options:
  1. Find optimizations to extend the current engine
  2. Layer on a second engine (only after first is stable)
  3. Pivot to a different engine entirely
```

---

## Cohort Analysis Template

### Weekly Cohort Tracker

```
                    Week 1    Week 2    Week 3    Week 4    Week 5
                    (joined)  (active)  (active)  (active)  (active)
-----------------------------------------------------------------------
Cohort Jan 1-7:     100       65 (65%)  42 (42%)  30 (30%)  25 (25%)
Cohort Jan 8-14:    120       84 (70%)  60 (50%)  40 (33%)  ___
Cohort Jan 15-21:   95        71 (75%)  53 (56%)  ___       ___
Cohort Jan 22-28:   130       104 (80%) ___       ___       ___
Cohort Feb 1-7:     110       ___       ___       ___       ___

TRENDS:
  Week 1 retention improving?     [ ] Yes (65%->80%)  [ ] No
  Week 4 retention improving?     [ ] Yes  [ ] No  [ ] Not enough data
  New cohort size growing?        [ ] Yes (100->130)  [ ] Stable  [ ] Shrinking
```

### Reading the Cohort Table

```
GOOD SIGNS:
- Retention rates improving across cohorts (e.g., 65% -> 80% week 1)
- Cohort sizes growing (more new users over time)
- Later-week retention stabilizing (a "floor" of retained users)

BAD SIGNS:
- Retention rates worsening across cohorts
- Cohort sizes shrinking (fewer new users over time)
- No retention floor (users keep dropping every week)
- Total users growing but retention getting worse
  (growth masking churn - this is the vanity metric trap)

AMBIGUOUS:
- Retention improving but cohort size shrinking
  (product is better but fewer people are finding it - growth engine problem)
- Cohort size growing but retention worsening
  (more people arriving but wrong audience - targeting problem)
```

---

## Five Whys Session Template

### Setup

```
PROBLEM: _________________________
DATE: _________________________
FIVE WHYS MASTER: _________________________
ATTENDEES (everyone affected must be present):
  - _________________________
  - _________________________
  - _________________________
  - _________________________

RULES (read aloud at start):
  1. Focus on bad process, not bad people
  2. "Shame on us for making it so easy to make that mistake"
  3. Proportional investment at each level
  4. We are looking for root causes, not blame
```

### The Session

```
SYMPTOM: _________________________

1. WHY? ___________________________________________________
   PROPORTIONAL INVESTMENT: _________________________
   OWNER: _____________ EFFORT: _____ (hours/days)

2. WHY? ___________________________________________________
   PROPORTIONAL INVESTMENT: _________________________
   OWNER: _____________ EFFORT: _____ (hours/days)

3. WHY? ___________________________________________________
   PROPORTIONAL INVESTMENT: _________________________
   OWNER: _____________ EFFORT: _____ (hours/days)

4. WHY? ___________________________________________________
   PROPORTIONAL INVESTMENT: _________________________
   OWNER: _____________ EFFORT: _____ (hours/days)

5. WHY? ___________________________________________________
   PROPORTIONAL INVESTMENT: _________________________
   OWNER: _____________ EFFORT: _____ (hours/days)
```

### Post-Session

```
ROOT CAUSE SUMMARY: _________________________
TOTAL INVESTMENT: _____ (hours/days across all levels)
FOLLOW-UP DATE: _________________________
SUCCESS CRITERIA: How will we know this problem is fixed?
  _________________________
```

---

## Validated Learning Scorecard

Use this weekly or biweekly to track whether you're actually learning.

```
WEEK OF: _________________________

EXPERIMENTS RUN THIS PERIOD:
  Planned: _____
  Completed: _____
  Abandoned (why?): _____

HYPOTHESES TESTED:
  Validated: _____
  Invalidated: _____
  Inconclusive: _____

DECISIONS MADE BASED ON DATA:
  1. _________________________
  2. _________________________
  3. _________________________

DECISIONS WE'RE AVOIDING:
  1. _________________________
  (If this list is growing, you may be in "theater of learning")

KEY METRIC MOVEMENT:
  Primary metric: _____________ from _____ to _____
  Direction: [ ] Toward ideal  [ ] Away from ideal  [ ] Flat

VANITY METRIC CHECK:
  Are we citing any metric that only goes up?  [ ] Yes  [ ] No
  If yes, replace with: _________________________

RUNWAY CHECK:
  Cash remaining: $_____
  Monthly burn: $_____
  Months of cash: _____
  Pivots remaining (estimate): _____
  Next pivot-or-persevere meeting: _________________________
```

---

## End-to-End Example: MealSync (Fictional Startup)

### Cycle 1: Smoke Test

**Hypothesis:** Busy parents will pay for automated weekly meal plans based on their dietary preferences and local grocery store sales.

**MVP:** Landing page describing the service. "Enter your email to join the waitlist." Facebook ads targeting parents aged 28-42 in Austin, TX.

**Metrics:**
- Ad spend: $500
- Landing page visitors: 1,200
- Email signups: 180 (15% conversion)
- Pre-order at $9.99/month: 22 (1.8% of visitors, 12.2% of signups)

**Learning:** Demand exists. 22 pre-orders from a landing page is strong. The value hypothesis has initial support. But: we don't know if they'll STAY once they see the actual product.

**Decision:** Persevere. Move to Concierge MVP.

---

### Cycle 2: Concierge MVP

**Hypothesis:** Customers who receive personalized meal plans will use them weekly and continue paying.

**MVP:** Founder personally emails each of 22 pre-order customers Sunday night with a customized meal plan + shopping list based on a brief survey of their preferences + manual checking of local store sales.

**Metrics (4 weeks):**
- Week 1: 22/22 opened email, 18 used the plan (82%)
- Week 2: 20/22 opened, 14 used (64%)
- Week 3: 18/22 opened, 12 used (55%)
- Week 4: 15/22 opened, 10 used (45%)

**Cohort analysis:**
- Retention floor appears around 45% (10 of 22 are consistent users)
- Churn is steepest in week 2-3
- Exit survey: "The recipes were too complicated for weeknights"

**Learning:** Core value (save time, save money) is validated for ~45% of signups. But recipe complexity is a retention killer. The product needs simpler recipes, not more variety.

**Decision:** Persevere with adjustment. Next cycle: test simple-recipe-only plans.

---

### Cycle 3: Split Test (Simple vs. Complex Recipes)

**Hypothesis:** Simpler recipes (< 30 min, < 8 ingredients) will improve week-4 retention from 45% to 65%+.

**MVP:** Same concierge approach, but 12 new customers split into two groups:
- Group A (6 customers): Complex recipes (status quo)
- Group B (6 customers): Simple recipes only (< 30 min, < 8 ingredients)

**Metrics (4 weeks):**
| | Group A (complex) | Group B (simple) |
|---|---|---|
| Week 1 retention | 83% (5/6) | 100% (6/6) |
| Week 4 retention | 50% (3/6) | 83% (5/6) |

**Learning:** Hypothesis validated. Simple recipes dramatically improve retention. The feature customers want most is NOT variety - it's speed and ease. This contradicts what customers SAID they wanted (variety) but aligns with their behavior.

**Decision:** Persevere. All plans shift to simple recipes. Begin building automation (the concierge phase has served its purpose - we know what to build).

---

### Cycle 4: Engine of Growth Selection

**Question:** Which engine should MealSync run?

**Analysis:**
- Sticky engine: 83% week-4 retention with simple recipes. Churn ~17%/month. Promising.
- Viral engine: Meal planning is somewhat private. k likely < 0.3. Not a natural viral loop.
- Paid engine: LTV at $9.99/month with 83% retention = ~$60 LTV. CPA from Facebook was ~$23. LTV/CPA = 2.6x. Workable.

**Decision:** Primary engine = STICKY (retain existing customers). Secondary = PAID (Facebook ads to parents). Do NOT invest in viral features yet.

**Next:** Build the automated product, launch to 200 customers via paid acquisition, track cohort retention with innovation accounting. Set pivot-or-persevere meeting for 8 weeks post-launch.
