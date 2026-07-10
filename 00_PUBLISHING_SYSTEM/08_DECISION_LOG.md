# Document: Decision Log

| Field | Value |
|-------|-------|
| **Title** | Learn2Tape Decision Log |
| **Version** | 1.0 |
| **Status** | ACTIVE |
| **Owner** | Drew Freedman |
| **Created** | 2026-07-10 |
| **Last Updated** | 2026-07-10 |
| **Review Cycle** | Continuous; reviewed quarterly |

---

## Purpose

This document records intentional system changes to the Learn2Tape Publishing System, the evidence supporting them, and their impact.

The Decision Log prevents "Why did we stop doing X?" moments and preserves institutional reasoning for future decisions.

---

## Scope

This document records:
- Changes to governance documents
- Changes to production workflow
- Changes to curriculum or delivery plan
- Changes to tools or platforms
- Material business decisions affecting publishing

This document does NOT record:
- Routine production activities (publish Blog #5 on schedule)
- Regular analytics insights (weekly pageview reports)
- Content ideas (use 07_CONTENT_BACKLOG.md for that)
- Meeting notes or status updates

---

## Core Principle: Record Decisions, Not Activity

A decision log is not a diary of what happened this week. It's a record of intentional changes made to the system.

**Examples of what to record:**
- "We moved email send time from 8 AM to 9 AM because open rates increased 15%"
- "We simplified the Content Workflow by removing one review stage based on Blog #5 testing"
- "We shifted from 12-week campaigns to 16-week campaigns based on Q3 analytics"

**Examples of what NOT to record:**
- "Published Blog #7 on schedule"
- "Email list grew to 5,000 subscribers"
- "Carousel got 200 likes on Instagram"

---

## Decision Log Entry Template

```
## Decision [ID]

**Date:** YYYY-MM-DD

**Decision:**  
[Concise statement of what changed]

**Evidence:**  
- [Specific data or observation supporting this]
- [Quantified impact if available]
- [Research or past experience]

**Reason:**  
[Why this decision matters. Connect to the mission or success metrics.]

**Alternatives Considered:**  
- [Option A and why it wasn't chosen]
- [Option B and why it wasn't chosen]

**Affected Documents:**  
- [Which governance/production documents need updating]
- [Links to documents]

**Operational Impact:**  
- [What changes in daily/weekly work?]
- [Who is affected?]
- [Timeline for implementation]

**Success Metric:**  
[How will we know if this decision was good?]

**Authorized By:**  
Drew Freedman

**Review Trigger:**  
[When should we revisit this decision? Evidence threshold? Timeline?]
```

---

## Historical Decisions

### Foundation Decisions (Recorded July 10, 2026)

These foundational decisions established Learn2Tape Publishing System v1.0 and are recorded here for continuity.

#### Decision 001

**Date:** 2026-06-15 (Captured 2026-07-10)

**Decision:**  
Establish Learn2Tape as an educational institution publishing curriculum-driven content, not a marketing department publishing content to drive sales.

**Evidence:**
- Find ing My Wei established successful pattern: philosophy first, content second
- Market research shows therapists prefer authority-based education over sales-based messaging
- Drew's 25 years experience demonstrates education-first approach builds sustainable business

**Reason:**  
This distinction is foundational to the entire system. It determines how we think about content, which topics we publish, how we measure success, and how we position Learn2Tape. It's not a marketing tactic; it's the institution's operating model.

**Alternatives Considered:**
- Marketing-first approach (traditional CE provider model) — rejected as commoditized and unsustainable
- Product-first approach (push the course) — rejected as lacking trust-building

**Affected Documents:**
- 00_PUBLISHING_FOUNDATION.md
- 01_EDITORIAL_CHARTER.md
- 02_CURRICULUM_BLUEPRINT.md

**Operational Impact:**
- Every content decision measures "does this improve clinical practice?" first
- Revenue is a consequence of trust, not the primary goal
- Budget prioritizes content quality over ad spend

**Success Metric:**  
Over 12 weeks, publishing drives measurable trust-building (engagement depth, return readers, email subscriptions) independent of immediate enrollment

**Review Trigger:**  
If analytics show engagement without enrollment progression, revisit positioning

---

#### Decision 002

**Date:** 2026-06-20 (Captured 2026-07-10)

**Decision:**  
Separate the Learning Objective from the Blog. Use curriculum-first architecture: learning objective → canonical blog → all derivatives.

**Evidence:**
- Blog-first approach limited Finding My Wei expansion (difficult to create webinars, videos, etc. from existing blogs)
- Curriculum-first approach enabled multi-format teaching
- Every platform has different format requirements; centralized curriculum prevents duplicate work

**Reason:**  
This architectural decision determines how future products (webinars, videos, AI tutors, books) can reuse existing intellectual property. It prevents commoditizing Learn2Tape as a "blog platform" and enables expansion into other formats.

**Alternatives Considered:**
- Platform-agnostic content first — rejected as creating duplicate definitions
- One-format-at-a-time approach — rejected as inefficient

**Affected Documents:**
- 02_CURRICULUM_BLUEPRINT.md (defines learning objectives)
- 05_DERIVATIVE_STANDARDS.md (all formats map back to objectives)
- 03_CONTENT_WORKFLOW.md (workflow starts with objective, not topic)

**Operational Impact:**
- Every article begins with "which learning objective?" not "what topic?"
- Derivatives are created from canonical blog, not as independent efforts
- Content backlog is organized by learning objective

**Success Metric:**  
Within 18 months, can produce a YouTube video series, webinar, or book using the same curriculum without redesign

**Review Trigger:**  
After first non-blog product launch (webinar, video, book), audit whether this architecture held

---

#### Decision 003

**Date:** 2026-07-01 (Captured 2026-07-10)

**Decision:**  
Freeze the curriculum and publishing system after Blog #1 validation. No major changes until evidence proves they're needed.

**Evidence:**
- Finding My Wei: early system changes delayed launch; locking system accelerated production
- Perfect systems don't exist; real systems prove themselves through use
- Production data reveals friction theoretical design can't predict

**Reason:**  
This prevents endless refinement and forces focus on publishing. The best system is one that ships; the worst is the perfect one that never publishes.

**Alternatives Considered:**
- Iterative refinement model — rejected as creating perpetual "setup" mode
- Staged launch over 6 months — rejected as unnecessary

**Affected Documents:**
- CLAUDE_BUILD_WORKFLOW.md
- 02_CURRICULUM_BLUEPRINT.md
- 03_CONTENT_WORKFLOW.md

**Operational Impact:**
- After Blog #1, system is frozen
- Changes only allowed when evidence of genuine problem appears
- All improvements documented in Decision Log with evidence

**Success Metric:**  
After Blog #1, zero major workflow changes needed. Any changes are tactical (email send time adjustment) not architectural (redesign workflow)

**Review Trigger:**  
Blog #1 production exposes genuine friction requiring system change

---

### Production Decisions

#### Decision 004

**Date:** 2026-07-10

**Decision:**  
Revise canonical blog article length standard from 1,200–2,000 words (target: 1,400–1,800) to 700–1,000 words (target: ~800). Apply reader-behavior-first philosophy before Blog #1 publication.

**Evidence:**
- Blog #1 draft: 1,847 words attempted to teach three distinct concepts (clinical reasoning, assessment importance, movement vs. tissue damage)
- User feedback: "One Learning Objective = One Idea" — current length enables multi-idea teaching, which violates curriculum principle
- Reader behavior principle: online readers scan, pause, return later. Completion rates increase with shorter, focused articles
- Field observation: expert mentors deliver teaching content in 5-minute reads for clinical consumption
- Test case (Blog #1): Refactored to 795 words, single focus (clinical reasoning). Format aligns with curriculum principle.

**Reason:**  
This enforces the curriculum foundation: each learning objective teaches one belief shift. Longer articles create temptation to over-teach; shorter length forces discipline. Online readership patterns show higher completion for focused pieces under 1,000 words. Aligns with mentor-voice positioning: clinical wisdom shared briefly, not academic essays.

**Alternatives Considered:**
- Keep 1,200–2,000 word standard, split Blog #1 into three articles later — rejected because it delays Blog #1 publication and leaves governance misaligned with practice
- Increase length further for "depth" — rejected as undermining curriculum architecture and ignoring reader behavior data

**Affected Documents:**
- 05_DERIVATIVE_STANDARDS.md (line 73–79: canonical blog length section updated)
- LO01_CANONICAL_ARTICLE.md (refactored from 1,847 to 795 words, single-idea focus)
- 02A_CURRICULUM_DELIVERY_PLAN_Q3_2026.md (standard reflected in current campaign)

**Operational Impact:**
- All future blog articles targeted at ~800 words (maximum 1,200 only when topic genuinely demands extra depth, rare)
- Production guidance shifts from "teach comprehensively" to "teach one lesson well"
- Splits blog series assignments where single topics would exceed 1,000 words

**Success Metric:**  
- Blog #1 publishes at 795 words with complete teaching of LO1 (clinical reasoning foundation)
- Blog #1 engagement metrics exceed Blog #2+ baseline (completion rate, scroll depth, email CTR)
- Reader feedback confirms focus and clarity

**Authorized By:**  
Drew Freedman

**Review Trigger:**  
After Blog #1 and Blog #2 publish, compare engagement metrics (completion rate, scroll depth, time-on-page, email open/CTR). If the shorter format underperforms, revisit.

---

## Decision Log Review Cycle

### After Each Blog Publication

Quick review:
- Did the workflow work? (No blockers?)
- Did analytics confirm effectiveness?
- Should we record a decision?

### Monthly Review

Aggregate decisions:
- Any patterns in what changed?
- Are changes evidence-based or reactive?
- Any anticipated decisions?

### Quarterly Strategic Review

Deep review:
- Did decisions improve performance?
- Did decisions align with mission?
- Are there unintended consequences?
- Should any decisions be revisited?

---

## Template Decision Log Entry (Blank)

```
## Decision [ID]

**Date:** YYYY-MM-DD

**Decision:**  
[What changed?]

**Evidence:**  
- [Data point 1]
- [Data point 2]
- [Observation 3]

**Reason:**  
[Why does this matter?]

**Alternatives Considered:**  
- [What else could we have done?]
- [Why wasn't that chosen?]

**Affected Documents:**  
- [Which docs change?]
- [Links]

**Operational Impact:**  
- [What changes in workflow?]
- [Timeline]

**Success Metric:**  
[How do we know this was right?]

**Authorized By:**  
Drew Freedman

**Review Trigger:**  
[When should we check if this still makes sense?]
```

---

## What Belongs in the Decision Log

### ✅ Include These

- System changes (workflow, timing, process)
- Curriculum changes (new learning objective, modified approach)
- Significant platform changes (switched email provider, changed publishing schedule)
- Messaging/positioning changes (how we talk about Learn2Tape)
- Budget or resource allocation changes
- Decisions based on analytics findings
- Decisions based on production friction

### ❌ Don't Include These

- Weekly status updates
- Analytics reports (use 06_ANALYTICS_SCORECARD for that)
- Content ideas (use 07_CONTENT_BACKLOG for that)
- Routine tasks (email sent, article published)
- Meeting notes (document elsewhere, link if relevant)
- Personal preferences without evidence

---

## How Decisions Become Part of the System

### Step 1: Decision is Made
- Evidence is reviewed
- Reasoning is clear
- Impact is understood

### Step 2: Decision is Recorded
- Entry added to Decision Log
- Affected documents are updated
- Change is dated

### Step 3: System Updates
- Governance documents reflect decision
- Workflow is updated if needed
- Team is informed

### Step 4: Decision is Monitored
- Success metric is tracked
- Review trigger is set
- At trigger, decision is revisited

---

## Using the Decision Log for Future Decisions

When you're tempted to change something:

1. **Check the Decision Log:** Has this been revisited? What was decided before?
2. **Gather Evidence:** Data, patterns, friction—what backs up this change?
3. **Consider Alternatives:** What else could we do?
4. **Impact Assessment:** What changes? Who's affected?
5. **Document and Decide:** Record in Decision Log or move forward

The Decision Log prevents revisiting the same decision twice and ensures all changes are intentional.

---

## Dependencies

This document depends on:
- All governance and production documents (decisions affect them)
- 06_ANALYTICS_SCORECARD.md (provides evidence for decisions)
- 07_CONTENT_BACKLOG.md (tracks idea decisions)

This document informs:
- Future versions of governance documents
- Quarterly strategic planning
- System freeze/thaw decisions

---

## Referenced By

This document is consulted when:
- Proposing a system change
- Reviewing past decisions
- Planning v1.1 improvements
- Onboarding new team members

---

## Change Log

| Date | Version | Change | Reason | Author |
|------|---------|--------|--------|--------|
| 2026-07-10 | 1.0 | Initial publication | Foundation decisions recorded; log active for production phase | Drew Freedman |

