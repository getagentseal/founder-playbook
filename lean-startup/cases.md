# Cases - The Lean Startup

## IMVU - The Founding Case Study

**Setup:** 2004. Eric Ries and Will Harvey co-founded IMVU, a 3D avatar social network. Harvey's original vision: an IM add-on that worked with existing networks (AIM, Yahoo Messenger, MSN). Users could add 3D avatars to their existing IM conversations.

**What went wrong (first attempt):**
- Built interoperability with every major IM network over 6 months
- Assumed customers wouldn't switch IM networks (they had existing buddy lists)
- Shipped product. Response: customers didn't want to add a plugin to their existing IM.
- Worse: customers didn't want their existing friends to see them using it
- The interoperability - the hardest engineering work - was worthless

**What they learned:**
- Customers PREFERRED a standalone network. They wanted new friends, not to bring existing ones.
- The "buddy list is sacred" assumption was wrong
- Six months of interoperability engineering was pure waste

**The pivot:**
- Stripped out all interoperability
- Built a standalone 3D chat network
- Customers found new people to talk to through the product itself
- Growth took off

**Key lesson:** "We had been building something nobody wanted. And the whole time, our so-called learning was leading us away from the insight we needed." Validated learning requires testing assumptions empirically, not planning from the armchair.

### IMVU: Continuous Deployment

Once IMVU found product/market fit, they pioneered continuous deployment:
- **50 code changes deployed per day** to production
- Automated test suite ran before every deploy
- Built a "cluster immune system" that could detect and rollback bad changes automatically
- New engineers were expected to deploy on their **first day** - and often broke something
- The response to breakage: "If our production process is so fragile that you can break it on your very first day of work, shame on us for making it so easy to do so"
- Each breakage triggered a Five Whys session, which made the system more robust

**Result:** Faster iteration, higher quality (paradoxically), and a culture where everyone was responsible for production reliability.

---

## Zappos - Wizard of Oz MVP

**Setup:** 1999. Nick Swinmurn hypothesized that people would buy shoes online. This was considered absurd - shoes need to be tried on.

**The MVP:**
- Went to local shoe stores
- Took photographs of their inventory
- Posted photos online
- When someone ordered, he went back to the store, bought the shoes at full price, and shipped them

**What it tested:**
- Value hypothesis: Will people buy shoes online without trying them on?
- NOT: Can we build a great e-commerce platform? Can we negotiate wholesale deals? Can we handle returns?

**What he learned:** People would indeed buy shoes online. The demand was real. Only then did it make sense to invest in warehouse infrastructure, wholesale relationships, and custom technology.

**Key lesson:** "Swinmurn wanted to validate his hypothesis that customers would buy shoes online. He didn't build a fancy website or spend millions on warehouse infrastructure. He ran the simplest possible test." The MVP tests the riskiest assumption first.

---

## Dropbox - Video MVP

**Setup:** 2007. Drew Houston believed people would want seamless file sync across all devices. The technology was complex (file syncing is an extremely hard engineering problem). Building a prototype would take months.

**The problem:** How do you test demand for a product that's too complex to prototype quickly?

**The MVP:**
- Three-minute screencast demonstrating the product concept
- Showed exactly how Dropbox would work from the user's perspective
- Posted to Digg (then a major tech community)

**Results:**
- Waiting list went from 5,000 to 75,000 signups overnight
- No product existed yet - just a video
- This validated the value hypothesis: people desperately wanted this

**What it tested:** "Do people want seamless file sync?" Not "can we build it?" (engineering risk, separate from market risk).

**Key lesson:** The video MVP works when the value proposition is clear but the build cost is high. Measure demand before committing to development.

---

## Groupon - Radical MVP

**Setup:** Originally "The Point" - a platform for collective action (petitions, fundraising). Wasn't growing. Team hypothesized that group buying might work.

**The MVP:**
- WordPress blog
- Posted one deal per day in Chicago
- Generated PDF coupons using FileMaker
- Emailed coupons manually to customers who bought

**No custom technology. No payment platform. No merchant tools.**

**What it tested:** Will people buy things together if the deal is good enough? Will merchants participate?

**Growth:** The MVP worked. Groupon became the fastest company to reach $1 billion in revenue.

**Key lesson:** "Andrew Mason described the first version of Groupon as 'really hacky.'" The point of the MVP is learning, not product quality. A WordPress blog and manual email can test a billion-dollar hypothesis.

---

## Grockit - Innovation Accounting in Practice

**Setup:** Social learning platform for standardized test prep. Farb Dwork, the founder, was iterating but couldn't tell if changes were making things better.

**The problem:**
- Total users were growing (vanity metric: up and to the right)
- Lots of new features being shipped
- But was Grockit actually getting better at teaching people?

**The fix:**
- Switched from cumulative metrics to **cohort-based analysis**
- Tracked each weekly cohort of new students separately
- Measured: retention, study time, test score improvement per cohort
- Ran **split tests** for every major feature change

**What they discovered:**
- Many features that "felt good" had zero impact on learning outcomes
- Some features actually decreased engagement
- The features that moved real metrics were often small, unsexy improvements
- Eliminated features that didn't move the needle, even popular-seeming ones

**Key lesson:** "Until Grockit switched to cohort-based metrics and split testing, it was impossible to know which of their many changes were actually helping." Vanity metrics hide the truth. Actionable metrics reveal it.

---

## Votizen - Three Pivots with Acceleration

**Setup:** David Binetti founded Votizen to increase civic engagement through technology. The company went through three major pivots, each faster and more productive than the last.

### Pivot 1: Social Network for Voters

**Hypothesis:** Registered voters want to connect with each other online.
**MVP:** Built a social network for verified voters.
**Timeline:** 8 months to build and test.
**Result:** Users signed up but didn't engage. Retention was near zero.
**Learning:** Voters wanted to be heard, not to network with each other.

### Pivot 2: Contact Your Representative

**Hypothesis:** Voters want an easy way to contact elected officials.
**MVP:** Built a streamlined tool for voter-to-representative communication.
**Timeline:** 4 months.
**Result:** Usage improved but still insufficient. People used it once, then left.
**Learning:** One-time use isn't a business. Need recurring engagement.

### Pivot 3: Voter-Driven Lobbying Platform

**Hypothesis:** Voters will pay to amplify their voice on specific issues.
**MVP:** Built a platform where voters could pool resources for targeted advocacy.
**Timeline:** 3 months.
**Result:** Paying customers. Repeatable use case. Growth.

### Acceleration Pattern

| Metric | Pivot 1 | Pivot 2 | Pivot 3 |
|---|---|---|---|
| Time to MVP | 8 months | 4 months | 3 months |
| Registered users | ~4,000 | ~12,000 | ~42,000 |
| Revenue | $0 | $0 | First paid customers |
| Key learning | Social doesn't work | Single-use doesn't work | Recurring advocacy works |

**Key lesson:** Each pivot was faster, cheaper, and more targeted than the last. The team got better at identifying assumptions and testing them. This is the meta-pattern: **pivoting gets easier with practice because you learn how to learn.**

> "Binetti estimated that the third pivot cost approximately 10 percent of what the first one did."

---

## Wealthfront - Platform Pivot (kaChing to Financial Management)

**Setup:** Originally kaChing - a "fantasy stock market" game where amateur investors competed. Had good traction as a game.

**The problem:** Game users loved playing but wouldn't pay. The value hypothesis for gaming failed. But the growth hypothesis worked - people liked competing on investment performance.

**The pivot:** Transformed from a game into a real financial management platform. Renamed to Wealthfront. Same core mechanic (transparent investment performance tracking) but applied to real money.

**Result:** Over $180 million in assets under management within a few years. Eventually became one of the largest robo-advisors.

**Key lesson:** The original product validated a real behavior (people want transparent investment performance). The pivot changed the business architecture (game to financial services) while preserving what worked.

---

## QuickBooks - Large Company Transformation (Intuit)

**Setup:** QuickBooks, Intuit's flagship small-business accounting software, had been released annually in one giant batch for over two decades. Standard waterfall: 3-4 months strategizing, 6-9 months building, beta in June/July, ship in September.

### Year One: Achieving Failure

- Shipped a new online banking system
- First beta feedback in June was negative - customers struggled with reconciliation
- But it was "technically flawless" so there was no cause to stop
- **Shipped anyway. Results were terrible.** Customers took 4-5x longer to reconcile banking transactions
- Took 9 months to fix through the next waterfall cycle
- NPS score dropped 20 points - first time the needle had moved that much at Intuit
- This was a textbook case of "achieving failure" - successfully executing a flawed plan

### Year Two: Muscle Memory

Greg Wright, tasked with driving change, tried to shift to Lean methods:
1. Smaller teams with cross-functional roles
2. Shorter cycle times
3. Faster customer feedback
4. Empowered decision-making

**Problem:** "Organizations have muscle memory, and it is hard for people to unlearn old habits." The team kept defaulting to waterfall patterns even while trying to work differently.

### Year Three: Explosion

Greg and product development lead Himanshu Baxi threw out ALL old processes:
- Cross-functional teams formed around ideas, not features
- Engineers in front of customers from inception
- "idea/code/solution jams" replaced annual roadmaps
- Pipeline of ideas instead of fixed release plan

**Results:**
- 5 "branches" of QuickBooks instead of one monolithic release (eventually 25 branches)
- Each team iterated with real customers for ~6 weeks end-to-end
- Built virtualization technology so new versions couldn't corrupt customer data
- NPS recovered. Customer satisfaction ratings increased. Units sold increased.

**Key lesson:** Transforming an established product to Lean methods takes at least 3 years. Year 1 is diagnosis. Year 2 is fighting muscle memory. Year 3 is when the new system actually takes hold - if leadership commits to tearing out old processes rather than incrementally tweaking them.

---

## IGN Entertainment - Five Whys in Practice

**Setup:** IGN, a large online video games media company (45M+ gamers, ~100 engineers). Wanted to accelerate product development using Lean methods.

### First Attempt: Failure

- Brought engineering, product, and design together
- Attempted Five Whys on a "laundry list" of existing problems
- First session lasted an hour, went on many tangents
- Result: "a disaster" - unfocused, no clear outcomes

### Three Mistakes

1. **Used Five Whys on OLD problems** instead of new ones. Baggage issues are overwhelming.
2. **Missing people.** Key stakeholders weren't in the room.
3. **No context-setting.** Attendees didn't understand the format or its purpose.

### Second Attempt: Success

Appointed a Five Whys master - Tony Ford, a director of engineering with entrepreneurial background. Tony:
- Picked a **narrow, specific problem** (a project missing its deadlines)
- Brought more experienced attendees
- Kept the session focused

**The turnaround:** "The success had to do with a more experienced master and more experienced attendees. We all knew what the Five Whys was, and I did a really good job keeping us on track and away from tangents."

### Example Five Whys Session (IGN blog post issue)

```
Problem: Users can't add or edit blog posts.

1. Why can't they? --> Content API returning 500 errors.
   Investment: Make CMS more forgiving for users. (Jim)

2. Why is API returning 500s? --> bson_ext gem incompatible.
   Investment: Remove the gem. (King - already done)

3. Why was the gem incompatible? --> Added new version alongside old one.
   Investment: Convert to bundler for gem management. (Bennett)

4. Why did we add a new version without testing? --> We didn't think we needed tests.
   Investment: Write functional tests for API and CMS. (Bennett + Jim)

5. Why do we add gems we don't intend to use right away? --> Wanted everything ready for a code push.
   Investment: Automate gem management in CI/CD. (Bennett)

Bonus: Why are we doing production changes on Friday nights?
   Investment: No production changes Friday-Sunday unless approved by VP Engineering. (Tony)
```

**Result:** "We would have never discovered all of the information we did here. My guess is that we would have told that one developer not to do stupid things on Friday nights and moved on." The proportional investments at each level compounded into systemic improvement.

---

## SGW Designworks - Small Batches for Physical Products

**Setup:** SGW Designworks works with military and physical product clients. Traditional hardware development has long batch cycles (months to years).

**The approach:**
- Applied small-batch thinking to physical product development
- Reduced iteration cycle to **15 days** for hardware prototypes
- Used rapid prototyping, 3D printing, and modular designs
- Each 15-day cycle produced a testable prototype that went in front of real users

**Key lesson:** Small batches aren't just for software. Physical products can iterate rapidly if the team invests in reducing setup costs (the hardware equivalent of SMED). The 15-day cycle for a physical product mirrors what continuous deployment does for software.

---

## School of One - Education (Public School System)

**Setup:** NYC public school system experiment. Traditional education: all students receive the same lesson at the same pace (large batch).

**The approach:**
- Each student gets a personalized learning plan generated daily
- Teachers use multiple modalities (tutoring, software, group work, solo practice)
- Daily assessment determines the next day's plan
- Each day is effectively a small batch - immediate feedback, immediate adjustment

**Key lesson:** Even in bureaucratic, heavily-regulated environments like public education, small-batch thinking can be applied. The constraint isn't technology but organizational willingness to shift from "teach the plan" to "teach the student."

---

## Alphabet Energy - Clean Tech Small Batches

**Setup:** Clean technology startup. Clean tech typically has very long development cycles (5-10 years) and massive capital requirements.

**The approach:**
- Applied small-batch thinking to materials science development
- Instead of building a full production facility before testing, created small-scale experiments
- Reduced capital requirements by validating demand and technology in parallel

**Key lesson:** Even in capital-intensive industries with physical constraints, the principle of reducing batch size and testing assumptions early applies. The goal isn't to eliminate large investments but to defer them until they're validated.

---

## Food on the Table - Concierge MVP

**Setup:** Meal planning service. Founder Manuel Rosso hypothesized that busy families would pay for a service that planned meals around grocery store sales.

**The MVP:**
- Rosso personally went to one customer's house each week
- Asked what her family liked to eat
- Checked local grocery store sales
- Created a meal plan and shopping list by hand
- Charged real money for the service

**No software. No app. No automation.** Pure concierge.

**What he learned:**
- Which parts of the service customers valued most
- What questions to ask to create good meal plans
- How to match recipes to sales
- What customers would actually pay

**Only after serving multiple customers manually** did he begin building technology to automate the process.

**Key lesson:** The concierge MVP eliminates all technology risk and isolates the value hypothesis. If customers won't pay a human to do it, they won't pay software to do it.

---

## Intuit SnapTax - Innovation Sandbox

**Setup:** Intuit created a small team to explore mobile tax filing. This was a radical departure from TurboTax's desktop model.

**What made it work:**
- The team operated inside an "innovation sandbox" - contained scope, real customers, standard metrics
- Cross-functional: engineering, marketing, customer service all represented
- Could build, market, and deploy without prior approval (within sandbox constraints)
- Reported progress using actionable metrics, not vanity metrics
- Clear team leader (like Toyota's shusa) with end-to-end ownership

**Result:** SnapTax became a successful mobile product. Demonstrated that a large company can innovate like a startup if the structural conditions are right: scarce but secure resources, independent authority, personal stake in outcome.

---

## Product Disasters Referenced

| Company/Product | Lean Startup Lesson |
|---|---|
| **Webvan** | Built $40M warehouses before validating demand. Classic "achieving failure." |
| **Apple Newton** | Right product idea, wrong execution timeline. No MVP; shipped full product too early. |
| **Iridium** | $5B engineering triumph. Never asked if customers wanted satellite phones at $3K/minute. |
| **Kodak Photo CD** | 10 years too early. Treated new market like existing market. |
| **IMVU v1 (IM interop)** | 6 months of engineering on an assumption (buddy lists are sacred) that turned out to be wrong. |

## Product Successes Referenced

| Company/Product | Lean Startup Lesson |
|---|---|
| **Toyota** | Originator of small batches, pull systems, andon cord, Five Whys - the manufacturing roots of Lean Startup |
| **Intuit** | Multiple examples of validated learning (SnapTax, QuickBooks transformation) |
| **Dropbox** | Video MVP validated demand before building complex technology |
| **Groupon** | WordPress + email MVP became fastest company to $1B revenue |
| **Hotmail** | Viral engine of growth: "PS: Get your free email at Hotmail" in every email |
