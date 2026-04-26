# Real Founder Problems Experiment

**Date:** 2026-04-26
**Method:** 10 real founder problems from Reddit (r/SaaS, r/microsaas, r/startups), each answered by raw Claude and Claude with skills loaded. Compared actionability, accuracy, and overfitting.

---

## Scorecard

| # | Problem | Category | Skills Used | Winner | Overfit? |
|---|---------|----------|-------------|--------|----------|
| 1 | FlwKit — can't reach indie iOS devs | Nobody buying | traction, 100m-leads, mom-test, diagnose | Skills | No |
| 2 | SpendForce — zero users after 1 month | Nobody buying | diagnose, obviously-awesome, mom-test, four-steps | Skills | No |
| 3 | Collectli — 0 paying after PH launch | Nobody buying | mom-test, four-steps, 100m-leads, diagnose | Skills | No |
| 4 | People don't get it on first visit | Messaging | storybrand, made-to-stick, obviously-awesome, diagnose | Skills (barely) | **Yes** — 3 frameworks stacked |
| 5 | Content scheduler, nobody cared | Messaging | obviously-awesome, lean-startup, four-steps, diagnose | Skills | No |
| 6 | First app failure, nobody needed it | Messaging | mom-test, lean-startup, four-steps, diagnose | Skills | No |
| 7 | 350 users, how to price paid plans | Pricing | monetizing-innovation, 100m-offers, mom-test | Skills | No |
| 8 | Face swap, 3 cancellations day 1 | Pricing | monetizing-innovation, 100m-offers, lean-startup | Skills | No |
| 9 | PH spike died, no sustained growth | Distribution | traction, 100m-leads, lean-startup, crossing-the-chasm | Skills | No |
| 10 | Accountancy firms won't pilot | Pivot | four-steps, crossing-the-chasm, spin-selling, mom-test | Skills | **Slight** — chasm too early |

---

## Ratings

| Dimension | Score |
|---|---:|
| Actionability | 9/10 |
| Diagnostic accuracy | 8.5/10 |
| Founder usability | 7/10 |
| Framework discipline | 6.5/10 |
| **Overall** | **8.2/10** |

---

## Problem 1 — FlwKit (can't reach indie iOS devs)

**Source:** r/SaaS, ~April 24, 2026

> "My cofounder and I started building FlwKit in January. Three months later we have a product, zero paying customers, and a much more honest view of what we got wrong. We underestimated how hard it is to reach indie iOS developers. Our target customer is clear: indie iOS developers who care about onboarding conversion. The problem is they're fragmented across X, Reddit, Discord, and random Slack groups. There's no single watering hole."

| | Without Skills | With Skills |
|---|---|---|
| **Diagnosis** | Fragmented audience problem, common with dev tools | Combined market validation + distribution problem (diagnose Step 1) |
| **Key advice** | Pick one community, become a helpful presence, ship free content | Validate demand first (Mom Test filter test), then Phase I channels (Bullseye), warm outreach via ACA framework |
| **Specific actions** | "Write onboarding teardowns" | "DM iOS devs who've publicly complained, using ACA. Rule of 100: 100 attempts/day for 100 days" |
| **What raw missed** | No method to validate if devs care enough to pay | — |
| **What skills missed** | — | Rule of 100 may be unrealistic for a 2-person team |

**Verdict:** Skills win on actionability. Diagnostic sequence (validate → channel test) is the key differentiator.

---

## Problem 2 — SpendForce (zero users after 1 month)

**Source:** r/SaaS, ~April 24, 2026

> "I launched my SaaS platform a little over a month ago and have gotten 0 users or customers. My platform helps SMB's identify waste, benchmark their software stack against other organizations and the market and help optimize their stack."

| | Without Skills | With Skills |
|---|---|---|
| **Diagnosis** | "SMBs" too broad, positioning sounds like a feature not a problem | Market problem, not distribution. "Do nothing" as competitive alternative = new market (3-7 year timeline) |
| **Key advice** | Narrow to specific SMB type, find specific dollar pain | Run Mom Test WTP conversations, Customer Slicing to find who cares MOST |
| **Specific actions** | "Answer what painful thing happens when they don't optimize" | "Ask: Walk me through last time you reviewed software subscriptions. Find CFOs at 50-200 companies burned by surprise renewals" |
| **What raw missed** | No method to narrow from "SMBs" to a findable segment | — |
| **What skills missed** | — | Four-steps' "3-7 year" new market timeline may discourage unnecessarily |

**Verdict:** Skills win. Caught it's a market problem (not distribution) — the critical misdiagnosis.

---

## Problem 3 — Collectli (0 paying after Product Hunt)

**Source:** r/SaaS, ~April 22, 2026

> "I built Collectli — automated invoice reminder sequences for freelancers. I didn't have a personal horror story. I kept seeing the same thread everywhere — freelancers losing thousands not because clients refuse to pay, but because there's no system."

| | Without Skills | With Skills |
|---|---|---|
| **Diagnosis** | Red flag: built for a problem you never had. PH is a vanity event. | Customer discovery problem dressed as marketing problem. Reddit threads ≠ validated pain. |
| **Key advice** | Find 20 freelancers who've lost money, see if they'll pay $15/mo | Use earlyvangelist hierarchy: find freelancers who've built spreadsheet workarounds (they have real pain) |
| **Specific actions** | "Go find 20 freelancers" | "Ask: Talk me through last late payment. What did you do? Search X for freelancers posting about late payments, DM via ACA" |
| **What raw missed** | No framework to identify WHO to talk to (just "freelancers") | — |
| **What skills missed** | — | Concierge MVP suggestion adds complexity for a 15-day build |

**Verdict:** Skills win. Earlyvangelist hierarchy (has workaround = real pain) is the key insight.

---

## Problem 4 — People don't get it on first visit

**Source:** r/SaaS, ~April 23, 2026

> "Product works, the problem it solves is real, but when someone lands on the page for the first time they just... don't get it. Default move is always more copy, longer onboarding, bigger FAQ."

| | Without Skills | With Skills |
|---|---|---|
| **Diagnosis** | Messaging problem, not product problem | Messaging problem confirmed (diagnose Step 2, 5-Second Test) |
| **Key advice** | Strip to one sentence above the fold | Three lenses: SB7 BrandScript, SUCCESs diagnostic, Obviously Awesome category context |
| **Specific actions** | "What do you do, for whom, what changes" | "Run 5-Second Test. Check Commander's Intent. Verify category framing." |
| **What raw missed** | No method to identify exactly what's broken | — |
| **What skills missed** | — | **Three frameworks is overwhelming for a clarity problem. One (StoryBrand) is enough.** |

**Verdict:** Skills win barely. **Overfitting flagged** — framework stacking reduces usability.

---

## Problem 5 — Content scheduler, nobody cared

**Source:** r/microsaas, ~April 22, 2026

> "Six months ago I started building what I thought was a smarter content scheduler. AI that could draft posts for LinkedIn and X. V1 launched. Nobody cared. I got a handful of signups and zero conversions."

| | Without Skills | With Skills |
|---|---|---|
| **Diagnosis** | "AI content scheduler" is crowded, "smarter" is a feature not positioning | Head-to-Head positioning in unwinnable category. Value hypothesis failed. |
| **Key advice** | Check existing signups for unexpected behavior, find specific outcome | Obviously Awesome 5+1 chain: start with competitive alternatives, find Big Fish Small Pond position |
| **Specific actions** | "Answer what specific outcome it produces" | "Ask signups: What were you hoping this would do? Run pivot catalog (Customer Segment, Zoom-In, Customer Need). Position as 'content engine for [specific user type]'" |
| **What raw missed** | No process to rebuild positioning from evidence | — |
| **What skills missed** | — | Pivot catalog options could paralyze rather than focus |

**Verdict:** Skills win. Caught the Head-to-Head error and provided systematic pivot analysis.

---

## Problem 6 — First app failure, nobody needed it

**Source:** r/SaaS, ~April 22, 2026

> "I finally took the risk of creating a first app based on what I thought was a brilliant idea. It was a complete failure: virtually no users in three months. I then realized that even though the idea was good, nobody needed it, and worse, neither did I."

| | Without Skills | With Skills |
|---|---|---|
| **Diagnosis** | Ideas ≠ demand. Best products scratch founder's own itch. | "Achieving Failure" pattern (lean-startup). Skipped Customer Discovery entirely. |
| **Key advice** | Talk to 10-20 people, check if they're searching or spending on workarounds | Mom Test filter test: if they haven't Googled for a solution, they don't care enough. Earlyvangelist criterion: must have cobbled interim fix. |
| **Specific actions** | "Talk to people before coding" | "Spend 1-2 weeks running 15-min conversations. Ask: Last time this problem cost you time or money? If blank stare, kill the idea." |
| **What raw missed** | Generic "validate first" without specific criteria | — |
| **What skills missed** | — | Nothing — this is the cleanest skill application |

**Verdict:** Skills win decisively. Named failure pattern + specific kill criteria.

---

## Problem 7 — 350 users, how to price paid plans

**Source:** r/SaaS, ~April 24, 2026

> "We have roughly 350 users. It's a site where people submit projects and we promote them across TikTok, YouTube and Instagram. Been completely free. Want to introduce paid plans for continuous promotion, but have absolutely no clue on how to price it."

| | Without Skills | With Skills |
|---|---|---|
| **Diagnosis** | Good position with 350 users getting value | 80% of companies skip WTP conversation — you're about to be one of them |
| **Key advice** | Talk to active users, test 2-3 tiers, price higher than you think | Run WTP conversations first, design Good/Better/Best with visible fences, consider usage-based model |
| **Specific actions** | "Start with simple tiers and adjust" | "Ask: How are you promoting now? What are you spending? Apply BECAUSE test. Use Leaders/Fillers/Killers for tier contents. Target 25% Good, 70% Better+Best." |
| **What raw missed** | No pricing methodology, just "test and iterate" | — |
| **What skills missed** | — | G/B/B distribution targets (25/70) may be too specific for a 350-user product |

**Verdict:** Skills win. WTP conversations + tier design methodology is genuinely better than guessing.

---

## Problem 8 — Face swap, 3 cancellations day 1

**Source:** r/SaaS, ~April 24, 2026

> "Launched my SaaS today... and already got my first 3 cancellations. Face swap video tool. Pricing: $15/month, $39/month, $79/month. People sign up and try it, but 3 already canceled same day. My guess: they get what they need in one session and dip."

| | Without Skills | With Skills |
|---|---|---|
| **Diagnosis** | Subscription fights natural usage pattern | Monetization model mismatch (Rule 4: how you charge > what you charge). Value is episodic, not recurring. |
| **Key advice** | Add pay-per-use, shift to recurring value prop | Switch to credit packs, or gate subscriptions behind sticky use case, use compromise effect |
| **Specific actions** | "Consider higher one-time fee" | "Three ranked fixes: (1) credit packs ($5/10 swaps, $15/50, $39/200), (2) creator tier with batch/API, (3) compromise effect pricing. Optimize for paid engine, not sticky engine." |
| **What raw missed** | No framework for choosing between monetization models | — |
| **What skills missed** | — | Engines-of-growth diagnostic may overcomplicate a simple pricing fix |

**Verdict:** Skills win. Root cause diagnosis (model mismatch) + ranked concrete fixes.

---

## Problem 9 — PH spike died, no sustained growth

**Source:** r/startups, ~April 12, 2026

> "We hit #1 Product of the Week on Product Hunt. For about 72 hours it felt like we'd made it. Then the spike ended — we have about 200 users, a 70% launch discount running, and absolutely no idea how to turn a strong launch into a real business."

| | Without Skills | With Skills |
|---|---|---|
| **Diagnosis** | PH is a marketing event, not a growth engine. No repeatable channel. | Violated 50% rule (100% product, 0% distribution). PH = Channel #2 of 19 (PR), not a growth channel. |
| **Key advice** | Find one sustainable channel, stop discounting, talk to the 200 users | Bullseye Framework: brainstorm all 19 channels, rank, test top 3 at $250 each. Phase I = unscalable high-touch. |
| **Specific actions** | "Find which users are active and why" | "Contact all 200 users personally (ACA). Track retention by cohort. Phase I channels: Targeting Blogs, Community Building, Speaking, Direct Sales." |
| **What raw missed** | No systematic channel selection method | — |
| **What skills missed** | — | $250/channel budget may not apply to students with no funding |

**Verdict:** Skills win. Bullseye + phase-channel map gives a system vs "find a channel."

---

## Problem 10 — Accountancy firms won't pilot, pivot to SMEs?

**Source:** r/startups, ~April 2, 2026

> "We're working on a platform that identifies company failure before the accounting numbers show it. Tried selling to accountancy firms who showed interest but have no appetite to take on a pilot. They all want the finished product. Should I pivot to SMEs?"

| | Without Skills | With Skills |
|---|---|---|
| **Diagnosis** | "Come back when finished" = interested but not in enough pain | Not a pivot problem — it's a Customer Discovery problem. These firms aren't earlyvangelists (fail criteria #3 and #4). "Come back when finished" = Polite Rejection per Mom Test commitment currencies. |
| **Key advice** | Find innovative firms willing to pilot, or use SMEs as proof | Apply earlyvangelist pain hierarchy. Score firms on 9-factor beachhead checklist. Find firms specializing in distressed companies — they have the pain NOW. |
| **Specific actions** | "Find 1-2 smaller firms willing to pilot for free" | "Ask Implication Questions: What happens when you discover a client is failing after numbers show it? What's the cost? Find turnaround/distressed specialists. Only pivot to SMEs if accountancy scores <2 on 'compelling reason to buy NOW'." |
| **What raw missed** | Didn't decode "interest" as polite rejection | — |
| **What skills missed** | — | **Crossing-the-chasm applied too early (still in Customer Discovery).** Beachhead checklist is useful but premature. |

**Verdict:** Skills win. Reframed from "should I pivot?" to "I haven't found real earlyvangelists." Slight overfitting on crossing-the-chasm.

---

## Key Findings

| Finding | Detail |
|---|---|
| **Skills won** | 10/10 on actionability |
| **Biggest advantage** | Diagnose skill catches misdiagnosis (Problems 2, 3, 10 would've been treated as wrong problem type) |
| **Overfitting** | 2/10 — Problem 4 (3 frameworks stacked), Problem 10 (chasm too early) |
| **Best performing skills** | monetizing-innovation (Problems 7, 8), diagnose (everywhere), mom-test (Problems 3, 6) |
| **Raw Claude strength** | Directionally correct 10/10 times — but leaves "what do I do Monday?" unanswered |
| **Fake precision risk** | "100/day for 100 days", "$250 per channel" — sounds actionable but may not fit solo founders |

## Tuning Applied

| Issue | Fix | Status |
|---|---|---|
| Framework stacking | Added One-Skill Rule to diagnose: one primary, one secondary max, one concrete next action | ✅ Done |
| Crossing-the-chasm too early | Gated behind "10+ paying customers or repeatable revenue" | ✅ Done |
| Fake precision | Diagnose now flags: "precision that sounds good but can't be executed is fake precision" | ✅ Done |
