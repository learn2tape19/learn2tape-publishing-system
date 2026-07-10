# Document: Analytics Scorecard

| Field | Value |
|-------|-------|
| **Title** | Learn2Tape Analytics Scorecard |
| **Version** | 1.0 |
| **Status** | PENDING VALIDATION |
| **Owner** | Drew Freedman |
| **Created** | 2026-07-10 |
| **Last Updated** | 2026-07-10 |
| **Review Cycle** | Monthly synthesis; quarterly strategy review |

---

## Purpose

This document defines what Learn2Tape measures, how we measure it, and what it means.

Analytics inform decisions about what's working and what needs adjustment. We track only what matters for the publishing mission.

---

## Scope

This document governs:
- What metrics matter and why
- How to collect each metric
- What time windows to measure
- How to synthesize findings into insights
- What decisions analytics can inform

This document does NOT govern:
- Production workflow (see 03_CONTENT_WORKFLOW)
- Which articles to publish (see 02A_CURRICULUM_DELIVERY_PLAN)
- Platform strategies (see 05_DERIVATIVE_STANDARDS)

---

## Core Principle: Measure What Matters

We don't measure everything. We measure what tells us whether the system is working.

**We measure:** Production velocity, engagement depth, educational resonance, business impact

**We don't measure:** Likes, shares, impressions, vanity metrics

Vanity metrics go up whether content is good or not. They don't tell us if clinicians are learning.

---

## The Three Pillars of Analytics

### 1. Production Health

**Question:** Can we publish consistently and fast enough?

**Metrics:**
- Days from topic approval to publication
- Asset readiness at production start
- Number of revision cycles
- Publishing schedule adherence
- Production friction (subjective: was there a blocker?)

**Why:** If production stalls, the system fails. We need to know if timing is realistic.

### 2. Educational Engagement

**Question:** Are readers actually engaging with the content and learning?

**Metrics:**
- Newsletter open rate
- Newsletter click-through rate (CTR)
- Blog page views (organic traffic)
- Average time on page
- Scroll depth (how far down the page readers go)
- Comments (meaningful engagement only)
- Assessment question responses
- Saved or bookmarked articles

**Why:** If readers aren't reading or engaging deeply, the content isn't working.

### 3. Business Impact

**Question:** Does this publishing lead to enrollment and revenue?

**Metrics:**
- Course enrollment page visits from content
- Enrollments attributable to specific articles
- Revenue attributable to article/campaign
- Email list growth
- Brevo segment engagement (by automation)
- Cost per acquisition (revenue ÷ marketing spend, if tracked)

**Why:** Publishing exists to support the business. We need to know if it's working.

---

## PRODUCTION VELOCITY KPI

### Definition

**Production Velocity = calendar days from approved learning objective to published canonical article**

### Target

10 days or fewer

### Why This Matters

- Production velocity proves the system works
- Slow velocity reveals workflow friction
- Fast velocity enables scaling
- Consistency matters more than absolute speed

### How to Measure

| Milestone | Date | Days Elapsed |
|-----------|------|--------------|
| Topic approved (LO assigned) | | |
| Research complete | | |
| First draft complete | | +3 days |
| Clinical review complete | | +1 day |
| Editorial revisions complete | | +1 day |
| Derivatives complete | | +1 day |
| Scheduled and ready to publish | | +1 day |
| Published live | | 1 day |
| **TOTAL** | | |

### Tracking

Record in a spreadsheet:
- Article title and LO#
- Approval date
- Publication date
- Days elapsed
- Any blockers or delays
- Notes on what slowed it down

### Benchmark

First article will take longer (7–10 days). After Blog #1, target is 5–7 days as team learns rhythm.

If any article exceeds 10 days, document why:
- Was it a research gap?
- Was it a workflow bottleneck?
- Was it approval delays?
- Was it unexpected complexity?

Use these insights to improve the system.

---

## EDUCATIONAL ENGAGEMENT METRICS

### Newsletter Open Rate

**What:** Percentage of people who received the email and opened it

**How to track:**
- Brevo reports this automatically
- View per email campaign
- Record weekly/monthly

**Target:** 30% or higher (industry average is ~25%)

**What it means:**
- Below 20%: Subject line or timing issue
- 20–30%: Normal
- 30%+: Strong subject line and audience alignment

### Newsletter Click-Through Rate (CTR)

**What:** Percentage of opens that resulted in a click to the blog

**How to track:**
- Brevo reports this automatically
- View per email campaign
- Record weekly/monthly

**Target:** 20% or higher

**What it means:**
- Below 10%: Content doesn't motivate action
- 10–20%: Normal
- 20%+: Strong content, good CTA

**Note:** CTR matters more than open rate. People can open but not engage.

### Blog Page Views (Organic)

**What:** Number of people visiting the blog via search engines (not email or social)

**How to track:**
- Google Analytics 4 (GA4)
- Filter for organic traffic
- View per article
- Track: Week 1, Week 4, Week 12 (publication, early traction, long-term)

**Target:** 200+ organic visits within 4 weeks of publication

**What it means:**
- SEO is working if organic traffic is growing
- First articles may be low; should improve as content accumulates
- Topics that rank well should inform future publishing

**Note:** Organic traffic compounds over time. Old articles continue driving traffic.

### Average Time on Page

**What:** Average minutes spent reading each article

**How to track:**
- Google Analytics 4
- View per article
- Average for all articles in a month

**Target:** 2.5+ minutes average

**What it means:**
- 1–2 minutes: Readers skimmed it
- 2.5–4 minutes: Good engagement, readers reading full article
- 4+ minutes: Excellent engagement, deep reading

### Scroll Depth

**What:** How far down the page readers scroll (percentage of page)

**How to track:**
- Google Analytics event setup (may require custom code)
- Alternative: Hotjar (heatmapping tool)
- Track: % scrolling to 50%, 75%, 100%

**Target:**
- 50% scroll: 70%+ of readers
- 75% scroll: 50%+ of readers
- 100% scroll: 30%+ of readers

**What it means:**
- If <50% scroll to 75%: Content isn't engaging or article is too long
- If >30% scroll to 100%: Excellent engagement
- Use scroll depth to identify which sections lose readers

### Comments and Engagement

**What:** Meaningful comments on blog posts or social media

**How to track:**
- Manual count (not algorithm-driven likes)
- Substance of comment (must show they read and thought about it)
- Record comments per article

**Target:** 3+ meaningful comments per article (over 2–4 weeks)

**What it means:**
- Comments show readers are engaged enough to reflect
- One "Thanks!" comment ≠ engagement; "I tried this and here's what happened" does
- Respond to comments to encourage more

### Email List Growth

**What:** New subscribers added to email list per week

**How to track:**
- Brevo dashboard: new subscribers per week
- Filter by source (blog, website, etc.)
- Track weekly and monthly totals

**Target:** 50+ new subscribers per month from publishing

**What it means:**
- Growing list = publishing is reaching new people
- Stagnant list = no reach beyond existing audience
- List growth fuels future campaign reach

---

## BUSINESS IMPACT METRICS

### Course Page Visits from Content

**What:** People clicking from blog/email to course enrollment page

**How to track:**
- Google Analytics 4 (UTM tracking)
- Tag all content links with: ?utm_source=blog&utm_medium=content&utm_campaign=LO01
- View "Acquisition" → "Traffic acquisition" to see source breakdown
- Alternative: UTM parameters in links

**Target:** 5+ visits per article within 4 weeks

**What it means:**
- Low visits: CTA not compelling or content not aligned with course
- Normal visits: 5–15 per article
- High visits: 15+ per article (replicable success)

### Enrollments Attributed to Content

**What:** Course enrollments from readers who came via blog/email

**How to track:**
- Checkout page setup: Ask "How did you hear about us?"
- Manually attribute via email sequence tracking
- Brevo automation tracking (if automation leads to checkout)
- Spreadsheet: Content → Enrollment attribution

**Target:** 1–3 enrollments per article per month

**What it means:**
- 0 enrollments: Content isn't converting; check CTA and course fit
- 1–2 enrollments: Normal
- 3+ enrollments: Excellent conversion; replicate this approach

### Revenue Attributed to Content

**What:** Dollar amount of enrollment revenue from content-driven customers

**How to track:**
- Course price × attributable enrollments
- Example: 2 enrollments × $299 course = $598 revenue per article
- Track monthly and campaign-total

**Target:** $300+ per article per month (2–3 enrollments at $299)

**What it means:**
- Publishing ROI: Monthly revenue ÷ production time investment
- Example: $3,600/month revenue ÷ 40 hours production = $90/hour
- Validates whether publishing is worth the time investment

### Brevo Automation Performance

**What:** How well email sequences convert readers through funnel

**How to track:**
- Brevo automation dashboard
- Track per automation: opens, clicks, unsubscribes
- Track enrollments from each automation

**Target:**
- Open rate: 25%+
- CTR: 15%+
- Unsubscribe rate: <1% (people aren't leaving)

**What it means:**
- Sequence is aligned if people stay subscribed and engage
- Unsubscribe spikes mean content isn't matching expectations

---

## MEASUREMENT WINDOWS

### Real-Time (During Production)

- Publication checklist (did everything happen?)
- No errors (broken links, missing images?)

### Weekly (Every Friday)

- Email engagement (opens, CTR)
- Social media comments (meaningful engagement only)
- Production velocity check (on track for next article?)

### Monthly

- Blog traffic synthesis (organic + email-driven)
- Engagement metrics (time on page, scroll depth)
- Enrollment and revenue attribution
- Email list growth
- Brevo automation performance
- Identify top-performing topics

### Quarterly

- Full campaign synthesis (all 12 weeks' data)
- Which learning objectives resonated most?
- Which platforms performed best?
- Which CTAs converted highest?
- Production friction patterns
- Recommendations for next quarter

---

## ANALYTICS TEMPLATE

### Weekly Tracking (Friday)

```
WEEK [#] — [ARTICLE TITLE]

Production:
- Days to publication: [#]
- Blockers: [if any]
- Asset readiness: [%]

Email (by end of week):
- Open rate: [%]
- CTR: [%]
- New list subscribers: [#]

Social Media (by end of week):
- Facebook engagement: [#] comments/shares
- Instagram engagement: [#] likes/comments
- LinkedIn engagement: [#] interactions

Blog Traffic (first 7 days):
- Pageviews: [#]
- Avg time on page: [mins]
- Scroll depth (75%+): [%]

Course Impact:
- Course page visits: [#]
- Enrollments: [#]
- Revenue: $[amount]

Notes:
- What worked: 
- What didn't:
- Next week's focus:
```

### Monthly Synthesis (End of Month)

```
MONTH [MONTH/YEAR]

Articles Published: [#/target]
Total Blog Views: [#]
Total Email Opens: [#]
Total Enrollments: [#]
Total Revenue: $[amount]

Top Performing Articles:
1. [Title] — [pageviews] views, [#] enrollments
2. [Title] — [pageviews] views, [#] enrollments
3. [Title] — [pageviews] views, [#] enrollments

Top Platform:
- Email: [#] CTR
- Blog (organic): [#] views
- Social: [#] engagement

Production Health:
- Avg days to publication: [#]
- Publishing adherence: [%]
- Zero blockers: Yes/No

Email List:
- New subscribers: [#]
- Growth rate: [%]

Insights:
- Which topics resonated most?
- Which CTAs converted best?
- What production friction appeared?
- What changed week-to-week?

Next Month:
- Adjust for: [any changes needed]
- Maintain: [what's working]
```

### Quarterly Review (End of Quarter)

```
QUARTER [Q#/YEAR]

Campaign Summary:
- Articles published: [#/12]
- Total views: [#]
- Total enrollments: [#]
- Total revenue: $[amount]
- Production velocity: [avg days]

Learning Objective Performance:
[Table showing each LO with views, enrollments, revenue]

Platform Performance:
- Email open rate: [%]
- Email CTR: [%]
- Blog organic traffic: [#]
- Social engagement: [#]

Phase Performance:
- Phase I (See Differently) — [views, enrollments, revenue]
- Phase II (Practice Differently) — [views, enrollments, revenue]
- Phase III (Become Different) — [views, enrollments, revenue]

Production:
- Adherence to schedule: [%]
- Avg production time: [days]
- Blockers encountered: [list]
- Friction points: [list]

Financial Summary:
- Revenue from publishing: $[amount]
- ROI (revenue ÷ production hours): [$/hour]
- Cost per enrollment: $[amount]

Key Findings:
1. [Most important insight]
2. [Second insight]
3. [Third insight]

Recommendations for Next Quarter:
- Continue: [what's working]
- Change: [what needs adjustment]
- Try: [experiments]
- Stop: [what isn't working]

Evidence-Based Changes (if any):
- [Decision]: [Evidence supporting it]
```

---

## What NOT to Measure

**Avoid these vanity metrics:**

- Raw likes or reactions
- Impressions (reach without engagement)
- Follower count
- Share count alone (engagement matters more)
- Email list size only (growth rate matters more)

These metrics go up regardless of quality. They don't tell you if anyone is learning.

**Focus instead on:**

- Depth of engagement (time, scroll, comments)
- Educational outcomes (did they learn?)
- Business outcomes (did they enroll?)
- Production efficiency (can we do this sustainably?)

---

## Decision Making from Analytics

### When Analytics Suggest Changes

**Evidence for change:** Two consecutive weeks/months showing problem

**Examples:**

- **Problem:** Low email CTR (below 15%) for 2 weeks
  - **Investigation:** Is CTA clear? Is subject line misleading? Is email content weaker?
  - **Action:** Test new CTA, new subject line, or refresh email template
  - **Decision Log:** Record what you changed and why

- **Problem:** High scroll depth (75%+) but zero comments
  - **Investigation:** Are readers not invited to comment? Is the topic not discussion-worthy?
  - **Action:** Add comment prompt to next article; try a different topic angle
  - **Decision Log:** Record the experiment

- **Problem:** Blog views declining over 3 weeks
  - **Investigation:** Are older articles getting found? Is new content not SEO-optimized?
  - **Action:** Review SEO on recent articles; compare to top-performing articles
  - **Decision Log:** What SEO changes did you make?

- **Problem:** Production time creeping above 10 days
  - **Investigation:** Where is the delay? Research? Review? Derivatives?
  - **Action:** Identify the bottleneck and solve it
  - **Decision Log:** What workflow change did you make?

### What NOT to Change Based on Analytics

- **Don't change curriculum** based on engagement alone. A hard topic may have lower initial engagement but higher long-term value.
- **Don't abandon an audience** because Week 1 numbers are low. Content compounds; give it 4 weeks before judging.
- **Don't change the system** based on one article. Use patterns across 3–4 articles before making structural changes.
- **Don't chase vanity metrics.** Likes mean nothing; enrollments mean everything.

---

## Dependencies

This document depends on:
- 02_CURRICULUM_BLUEPRINT.md (learning objectives being measured)
- 03_CONTENT_WORKFLOW.md (production process being tracked)
- 02A_CURRICULUM_DELIVERY_PLAN_Q3_2026.md (publication schedule)
- 05_DERIVATIVE_STANDARDS.md (platforms being measured)

This document informs:
- 08_DECISION_LOG.md (evidence for decisions)
- Campaign optimization and v1.1 planning

---

## Referenced By

This document guides:
- Weekly performance review (every Friday)
- Monthly synthesis (end of month)
- Quarterly strategy review (end of quarter)
- Evidence-based decision making
- Future publishing improvements

---

## Change Log

| Date | Version | Change | Reason | Author |
|------|---------|--------|--------|--------|
| 2026-07-10 | 1.0 | Initial publication | PENDING VALIDATION — to be tested during Q3 2026 campaign | Drew Freedman |

