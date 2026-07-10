# CLAUDE BUILD WORKFLOW
# Learn2Tape Publishing System Repository

**Repository:** `learn2tape-publishing-system`  
**Status:** Authorized for initial build  
**Owner:** Drew Freedman / Learn2Tape, LLC  
**Primary Builder:** Claude  
**Canonical Platform:** GitHub  
**Document Type:** Execution Workflow  
**Version:** 1.0  
**Created:** July 10, 2026  

---

# 1. PURPOSE

This workflow instructs Claude to build the `learn2tape-publishing-system` repository as the canonical operating backbone for Learn2Tape publishing.

The repository must preserve:

- the permanent publishing philosophy,
- the curriculum architecture,
- the production workflow,
- campaign delivery plans,
- canonical long-form educational content,
- platform derivatives,
- production decisions,
- analytics findings,
- and the institutional history of Learn2Tape publishing.

This is not a general marketing repository.

It is the single source of truth for Learn2Tape curriculum-driven publishing.

---

# 2. FOUNDATIONAL PRINCIPLES

Claude must operate according to these principles throughout the build.

## 2.1 Education First

> The purpose of the Learn2Tape Publishing System is to create enduring educational content that improves clinical practice, establishes professional trust, and naturally supports the growth of Learn2Tape. Marketing is the outcome of education, not its substitute.

The order is:

1. Education
2. Authority
3. Enrollment

## 2.2 Curriculum Before Campaign

Campaigns are temporary expressions of the curriculum.

The curriculum is permanent.

No campaign may redefine the curriculum merely to satisfy a marketing objective.

## 2.3 Curriculum Before Content

Learn2Tape defines learning objectives before producing articles, videos, social posts, emails, webinars, or other media.

Content is a delivery mechanism.

Curriculum is the educational foundation.

## 2.4 Canonical Creation

Every educational idea must have one canonical source.

For Campaign 001, the default canonical source is the approved long-form blog article.

All derivative assets must be created from the canonical article.

Never create competing canonical versions across email, Facebook, LinkedIn, Instagram, Brevo, WordPress, Canva, or other platforms.

## 2.5 The System Exists to Accelerate Publishing

> The Learn2Tape Publishing System exists to accelerate publishing, not delay it.

The system may be changed only when:

- production exposes a genuine deficiency,
- analytics reveal a measurable problem,
- or a new product cannot be supported by the existing system.

The system must not be changed because:

- a new idea feels more elegant,
- an alternative structure seems theoretically better,
- someone wants to add "one more thing,"
- or a working process feels imperfect.

## 2.6 Publish Before Perfect

> A published educational asset teaches. An unpublished perfect draft teaches no one.

When production reaches the editorial quality defined by the Editorial Charter, it should be published.

Future improvements belong in the next version—not in perpetual revision.

This complements Principle 2.5 perfectly:

- **Principle 2.5:** The system exists to accelerate publishing, not delay it.
- **Principle 2.6:** Once quality standards are met, publish rather than endlessly refine.

Together, they protect the institution from two common failure modes:

- endlessly redesigning the system, and
- endlessly polishing content that is already ready to help clinicians.

## 2.7 Real-World Validation Before Freeze

No canonical document is considered validated until it has been used during the complete production of Blog #1.

After Blog #1 is produced, distributed, and tracked:

- repair only genuine production failures,
- record decisions in the Decision Log,
- freeze Publishing System v1.0,
- and transition fully to production.

---

# 3. REPOSITORY AUTHORITY

GitHub is the canonical institutional source of truth for this project.

The following are distribution or execution platforms, not canonical repositories:

- WordPress
- Brevo
- Instagram
- Facebook
- LinkedIn
- Canva
- Adobe
- Google Drive
- local notes
- chat conversations

If content differs between GitHub and a distribution platform, GitHub governs unless an approved decision explicitly states otherwise.

Claude must never allow the canonical source to exist only inside a chat session.

---

# 4. REPOSITORY SAFETY RULES

Before making changes, Claude must:

1. Confirm the active local repository is the correct clone of:
   `learn2tape-publishing-system`
2. Display the repository root path.
3. Run:
   - `git status`
   - `git remote -v`
   - `git branch --show-current`
4. Confirm the remote points to the correct GitHub repository.
5. Pull the latest changes before editing.
6. Refuse to work in an unrelated repository.
7. Never place Learn2Tape publishing files inside the Finding My Wei repository.
8. Never overwrite an existing canonical document without first reading it.
9. Never delete content unless explicitly authorized.
10. Never force-push.
11. Never rewrite published Git history.
12. Never commit secrets, passwords, API keys, patient information, private student data, or protected health information.

If the correct repository cannot be confirmed, stop repository modifications and report the exact problem.

---

# 5. TARGET REPOSITORY STRUCTURE

Claude must create the following initial structure.

```text
learn2tape-publishing-system/
│
├── README.md
├── REPOSITORY_PHILOSOPHY.md
├── CHANGELOG.md
├── ROADMAP.md
├── CONTRIBUTING.md
├── .gitignore
│
├── 00_PUBLISHING_SYSTEM/
│   ├── 00_PUBLISHING_FOUNDATION.md
│   ├── 01_EDITORIAL_CHARTER.md
│   ├── 02_CURRICULUM_BLUEPRINT.md
│   ├── 02A_CURRICULUM_DELIVERY_PLAN_Q3_2026.md
│   ├── 03_CONTENT_WORKFLOW.md
│   ├── 04_MASTER_ASSET_LIBRARY.md
│   ├── 05_DERIVATIVE_STANDARDS.md
│   ├── 06_ANALYTICS_SCORECARD.md
│   ├── 07_CONTENT_BACKLOG.md
│   ├── 08_DECISION_LOG.md
│   └── PUBLISHING_SYSTEM_v1.0_FROZEN.md
│
├── 01_CURRICULUM/
│   ├── LEARNING_OBJECTIVES/
│   ├── ASSESSMENTS/
│   └── REFERENCES/
│
├── 02_CAMPAIGNS/
│   └── CAMPAIGN_001_BECOME_THE_THERAPIST_PATIENTS_REMEMBER/
│       ├── README.md
│       ├── CAMPAIGN_BRIEF.md
│       ├── DELIVERY_STATUS.md
│       ├── 01_CANONICAL_ARTICLES/
│       ├── 02_INSTAGRAM_CAROUSELS/
│       ├── 03_FACEBOOK/
│       ├── 04_LINKEDIN/
│       ├── 05_INSTAGRAM_STORIES/
│       ├── 06_EMAIL/
│       ├── 07_BREVO/
│       ├── 08_MEDIA/
│       └── 09_ANALYTICS/
│
├── 03_ASSETS/
│   ├── BRAND/
│   ├── PHOTOGRAPHY/
│   ├── GRAPHICS/
│   ├── TESTIMONIALS/
│   ├── RESEARCH/
│   └── TEMPLATES/
│
├── 04_ANALYTICS/
│   ├── WEEKLY/
│   ├── MONTHLY/
│   └── CAMPAIGN_REPORTS/
│
├── 05_OPERATIONS/
│   ├── PUBLISHING_CHECKLISTS/
│   ├── BREVO/
│   ├── WORDPRESS/
│   └── SEO/
│
└── 06_ARCHIVE/
```

## 5.1 Freeze File Rule

`PUBLISHING_SYSTEM_v1.0_FROZEN.md` must be created initially as a clearly marked placeholder:

- Status: `PENDING VALIDATION`
- It must not declare the system frozen.
- It may be changed to `FROZEN` only after Blog #1 completes the full workflow.

---

# 6. STANDARD DOCUMENT METADATA

Every canonical governance and production document must begin with:

```markdown
# DOCUMENT TITLE

| Field | Value |
|-------|-------|
| **Title** | ... |
| **Version** | 1.0 |
| **Status** | ACTIVE |
| **Owner** | ... |
| **Created** | ... |
| **Last Updated** | ... |
| **Purpose** | ... |
| **Scope** | ... |
| **Dependencies** | ... |
| **Referenced By** | ... |
| **Review Cycle** | ... |
```

Each document must end with:

```markdown
---

## Change Log

| Date | Version | Change | Reason | Author |
|------|---------|--------|--------|--------|
| YYYY-MM-DD | 1.0 | Initial creation | ... | Drew Freedman |
```

Status values must use a controlled vocabulary:

- `DRAFT`
- `IN REVIEW`
- `APPROVED`
- `ACTIVE`
- `PENDING VALIDATION`
- `FROZEN`
- `SUPERSEDED`
- `ARCHIVED`

---

# 7. DO NOT CREATE UNLESS EXPLICITLY AUTHORIZED

Claude is very good at creating useful documents. Sometimes too good.

The following documents should **NOT** be created unless Drew explicitly authorizes them:

❌ Additional governance documents
❌ Strategy documents
❌ Vision documents
❌ Manifestos
❌ Personas
❌ Marketing plans
❌ Social media strategies
❌ Brand books
❌ AI prompt libraries
❌ Meeting notes
❌ SOPs outside the approved workflow
❌ Duplicate workflows
❌ Alternate repository structures

**If a proposed document is not listed in the approved repository architecture, assume it should not be created.**

This keeps the repository lean and focused on production, not system design.

---

# 8. BUILD SEQUENCE

Claude must build the repository in the following order.

Do not jump ahead.

Do not create speculative files outside this order.

---

## PHASE 1 — Repository Initialization

### Actions

1. Validate repository identity and remote.
2. Pull latest changes.
3. Inspect existing files.
4. Create the approved folder structure.
5. Create:
   - `README.md`
   - `REPOSITORY_PHILOSOPHY.md`
   - `CHANGELOG.md`
   - `ROADMAP.md`
   - `CONTRIBUTING.md`
   - `.gitignore`
   - `CLAUDE_BUILD_WORKFLOW.md` (this file, in repository root)
6. Create placeholder files only where needed to preserve empty directories.
7. Commit and push.

### Commit

```text
chore: initialize Learn2Tape publishing repository
```

### Completion Gate

Phase 1 is complete only when:

- the repository structure exists,
- the README explains the repository,
- the remote is correct,
- the working tree is clean,
- and the commit is pushed successfully.

---

## PHASE 2 — Ingest Existing Governance Documents

Claude must not recreate documents that already exist elsewhere without first obtaining and reviewing the existing source text.

The expected Session 1 documents are:

- `00_PUBLISHING_FOUNDATION.md`
- `01_EDITORIAL_CHARTER.md`
- `03_CONTENT_WORKFLOW.md`

The expected cornerstone document is:

- `02_CURRICULUM_BLUEPRINT.md`

The expected production documents are:

- `02A_CURRICULUM_DELIVERY_PLAN_Q3_2026.md`
- `04_MASTER_ASSET_LIBRARY.md`

### Actions

1. Locate the most complete approved version of each document.
2. Verify that each matches the current institutional decisions.
3. Normalize metadata without changing substantive meaning.
4. Correct obvious formatting problems.
5. Preserve approved language.
6. Mark each document:
   - `APPROVED` if already accepted by Drew,
   - `PENDING VALIDATION` if it must still be tested through Blog #1.
7. Record ingestion in `CHANGELOG.md`.
8. Commit and push.

### Commit

```text
docs: add publishing governance and curriculum foundation
```

### Completion Gate

Do not advance until all six documents are:

- present,
- readable,
- internally consistent,
- linked from the README,
- and committed to GitHub.

---

## PHASE 3 — Build the Final Production Infrastructure

Create the final infrastructure documents:

1. `05_DERIVATIVE_STANDARDS.md`
2. `06_ANALYTICS_SCORECARD.md`
3. `07_CONTENT_BACKLOG.md`
4. `08_DECISION_LOG.md`

These are the final infrastructure documents before production.

### Prohibition

After this phase, Claude must not propose additional governance documents unless production reveals a genuine need.

### Commit

```text
docs: complete Learn2Tape publishing production system
```

---

# 9. REPOSITORY SUCCESS CRITERIA

Repository build is complete when ALL of the following are true:

✓ Repository structure exists as specified  
✓ Repository Philosophy is published  
✓ README is complete and links all documents  
✓ CHANGELOG documents version history  
✓ ROADMAP outlines next phases  
✓ CONTRIBUTING guide is present  
✓ .gitignore is configured  
✓ 6 governance + production documents are ingested and marked APPROVED or PENDING VALIDATION  
✓ 4 remaining infrastructure documents are complete  
✓ Campaign 001 folder structure is initialized  
✓ All internal links validate and resolve  
✓ All metadata is consistent (version, status, dates)  
✓ No placeholder text remains  
✓ Working tree is clean  
✓ All changes are committed  
✓ All changes are pushed to GitHub  
✓ Remote verification passes  

### When Success Criteria are Met:

```
Infrastructure is complete. The next authorized action is Blog #1 production.
```

Claude must not recommend more infrastructure unless a documented production problem requires it.

---

# 10. DOCUMENT-SPECIFIC BUILD REQUIREMENTS

## 10.1 02A_CURRICULUM_DELIVERY_PLAN_Q3_2026.md

This document is the quarterly command center for delivering the permanent curriculum.

It must include:

- campaign name,
- quarter and date range,
- curriculum phase,
- learning objective ID,
- canonical article title,
- educational outcome,
- belief shift,
- emotional outcome,
- clinical competency,
- professional competency,
- assessment prompt,
- primary educational CTA,
- email journey stage,
- Brevo segment assignment,
- required research,
- required story,
- required testimonial,
- required image assets,
- derivative requirements,
- production owner,
- target approval date,
- target publication date,
- production status,
- analytics focus,
- post-publication notes.

### Required Phases

1. `SEE DIFFERENTLY`
2. `PRACTICE DIFFERENTLY`
3. `BECOME DIFFERENT`

### Required Capstones

- Phase I capstone: learner can articulate how clinical thinking has shifted.
- Phase II capstone: learner recognizes a developing professional identity.
- Phase III capstone: learner understands why certification matters beyond the certificate.

### Date Discipline

Use exact publication dates.

Do not label a Q3 plan with dates outside July 1 through September 30, 2026 without explicitly documenting the exception.

If the full 12-week arc extends beyond Q3, label the file and plan accurately rather than forcing incorrect dates.

---

## 10.2 04_MASTER_ASSET_LIBRARY.md

Organize this document by learning objective, not merely by asset type.

For each learning objective include:

- objective ID and title,
- readiness score,
- research sources,
- evidence summary,
- Drew stories,
- student testimonials,
- patient or clinician scenarios,
- statistics,
- images available,
- images required,
- quotes,
- FAQs,
- objections,
- gaps,
- next acquisition action,
- source location,
- rights or permission status.

### Asset Readiness Score

Use this model:

| Category | Weight |
|---|---:|
| Research/evidence | 25% |
| Clinical example or Drew story | 20% |
| Practical teaching framework | 20% |
| Image/media readiness | 15% |
| Testimonial/social proof | 10% |
| Assessment prompt | 10% |

Score each objective from 0–100%.

### Readiness Meaning

- `90–100%`: Ready for production
- `75–89%`: Ready with minor gaps
- `50–74%`: Needs asset collection
- `<50%`: Not approved for production

Blog #1 must reach at least 90% readiness before drafting begins.

---

## 10.3 05_DERIVATIVE_STANDARDS.md

This document must define exact specifications for:

- canonical blog article,
- Instagram carousel,
- Facebook post,
- LinkedIn post or article,
- Instagram Story,
- newsletter email,
- Brevo sequence use,
- feature image,
- accessibility text,
- SEO metadata.

Every derivative must preserve:

- the same learning objective,
- the same belief shift,
- the same clinical conclusion,
- the same evidence boundaries,
- and the appropriate educational CTA.

Platform adaptation may change length, framing, and format.

It may not change the underlying lesson.

### Minimum Format Standards

#### Canonical Blog

- 1,200–2,000 words unless the topic requires otherwise
- Uses:
  1. The Situation
  2. The Common Mistake
  3. The Better Approach
  4. Why It Works
  5. Clinical Takeaway
  6. Continue Learning
- Includes citations where factual or research claims are made
- Includes SEO title, slug, meta description, internal links, and image alt text

#### Instagram Carousel

- 5 slides
- 1080 × 1350 px
- Slide 1: hook
- Slides 2–4: instruction
- Slide 5: educational CTA
- No crowded text
- No unsupported outcome claims

#### Facebook

- Native platform post
- Conversational, mentor-led tone
- May be shortened from the blog
- Must retain the practical teaching point
- Link to canonical article when appropriate

#### LinkedIn

- Professional and research-aware
- Connects clinical reasoning to professional development
- Avoids consumer-marketing language

#### Instagram Story

- 3–5 frames
- 1080 × 1920 px
- One clear takeaway
- Optional poll, reflection, or assessment question
- Link back to canonical source when available

#### Newsletter

- 300–600 words
- One learning point
- One primary CTA
- Links to the canonical article
- Must not reproduce the full article

---

## 10.4 06_ANALYTICS_SCORECARD.md

Track:

### Production Health

- days from topic approval to publication,
- asset readiness at production start,
- number of revisions,
- missed gates,
- publication consistency.

### Educational Engagement

- assessment question responses,
- saves,
- shares,
- replies,
- meaningful comments,
- newsletter clicks,
- time on article,
- scroll depth when available.

### Business Outcomes

- course-page visits,
- checkout starts,
- enrollments,
- revenue attributable to article or campaign,
- Brevo segment performance.

### Required KPI

> Production Velocity = calendar days from approved topic to published canonical article.

Target:

- 10 days or fewer.

Do not treat likes or impressions as primary success metrics.

---

## 10.5 07_CONTENT_BACKLOG.md

Each entry must include:

- ID,
- proposed topic,
- why it matters,
- learning objective,
- curriculum phase,
- source,
- evidence availability,
- story availability,
- urgency,
- status,
- date added,
- notes.

Approved statuses:

- `CAPTURED`
- `RESEARCHING`
- `READY`
- `SCHEDULED`
- `IN PRODUCTION`
- `PUBLISHED`
- `DEFERRED`
- `REJECTED`

---

## 10.6 08_DECISION_LOG.md

Every entry must include:

- decision ID,
- date,
- decision,
- evidence,
- reason,
- alternatives considered,
- affected documents,
- operational impact,
- authorized by,
- review trigger.

The log must record decisions, not routine activity.

Do not use it as a diary.

---

# 11. CAMPAIGN 001 INITIALIZATION

Create:

`02_CAMPAIGNS/CAMPAIGN_001_BECOME_THE_THERAPIST_PATIENTS_REMEMBER/`

The campaign README must include:

- campaign purpose,
- curriculum phases,
- learning objectives included,
- audience,
- channels,
- core CTA logic,
- Brevo segment use,
- production schedule,
- success definition,
- status.

## Campaign 001 Success Definition

The campaign proves that the system can repeatedly deliver curriculum-driven content.

Track:

- canonical articles completed,
- derivatives completed,
- newsletters sent,
- Brevo distributions completed,
- production velocity,
- analytics entries completed,
- system friction identified.

Do not define the publishing system as successful solely by revenue.

Revenue is a business outcome, not the only validation of operational reproducibility.

---

# 12. BLOG #1 PROOF-OF-CONCEPT

## Canonical Title

`Tape Doesn't Fail: Clinical Reasoning Does`

Use punctuation that reads naturally. Avoid excessive ellipses and em dashes.

## Required Production Path

```text
Approved Learning Objective
        ↓
Asset Readiness Review
        ↓
Research Plan
        ↓
Canonical Blog Draft
        ↓
Clinical Review
        ↓
Editorial Review
        ↓
SEO Package
        ↓
Media Selection
        ↓
Instagram Carousel
        ↓
Facebook Post
        ↓
LinkedIn Version
        ↓
Instagram Story
        ↓
Newsletter Email
        ↓
Brevo Assignment
        ↓
Schedule
        ↓
Publish
        ↓
Analytics Entry
        ↓
Decision Log, only if warranted
```

## Blog #1 Folder Structure

```text
01_CANONICAL_ARTICLES/
└── LO01_TAPE_DOESNT_FAIL/
    ├── README.md
    ├── LO01_CANONICAL_ARTICLE.md
    ├── LO01_RESEARCH_NOTES.md
    ├── LO01_EDITORIAL_REVIEW.md
    ├── LO01_SEO_METADATA.md
    └── LO01_PUBLICATION_RECORD.md
```

Associated derivatives must use the same `LO01` identifier.

## Production Rule

Do not mark Blog #1 complete until:

- every required derivative exists,
- the article is published,
- the newsletter is distributed,
- Brevo assignment is documented,
- analytics tracking is initialized,
- and the publication record includes live URLs or distribution references.

---

# 13. FILE NAMING STANDARD

Use:

```text
LO##_SHORT_TOPIC_DESCRIPTION_ASSET_TYPE_VERSION.ext
```

Examples:

```text
LO01_TAPE_DOESNT_FAIL_CANONICAL_v1.0.md
LO01_TAPE_DOESNT_FAIL_CAROUSEL_SLIDE_01_v1.0.png
LO01_TAPE_DOESNT_FAIL_FACEBOOK_v1.0.md
LO01_TAPE_DOESNT_FAIL_LINKEDIN_v1.0.md
LO01_TAPE_DOESNT_FAIL_EMAIL_v1.0.md
LO01_TAPE_DOESNT_FAIL_STORY_01_v1.0.png
```

Rules:

- uppercase learning-objective prefix,
- words separated by underscores,
- no spaces,
- no vague names such as `final`, `final2`, or `new`,
- versions use `vMAJOR.MINOR`,
- dates use `YYYY-MM-DD`.

---

# 14. BRANCHING AND COMMIT DISCIPLINE

## Default Branch

Use the repository's existing default branch.

Do not rename branches without authorization.

## Working Branches

For substantial additions, use:

```text
docs/<short-description>
campaign/<campaign-id>-<short-description>
content/lo##-<short-description>
fix/<short-description>
```

Examples:

```text
docs/session-2-production-layer
content/lo01-clinical-reasoning
```

## Commit Principles

Each commit must:

- represent one logical unit,
- use clear language,
- avoid mixing unrelated changes,
- leave the repository usable,
- and be pushed after verification.

Recommended commit sequence:

```text
chore: initialize Learn2Tape publishing repository
docs: add governance and curriculum foundation
docs: add Q3 curriculum delivery plan
docs: add objective-based master asset library
docs: define derivative production standards
docs: add analytics backlog and decision operations
campaign: initialize Campaign 001
content: add LO01 research and canonical article
content: add LO01 social and email derivatives
ops: record LO01 publication and analytics setup
docs: freeze Learn2Tape Publishing System v1.0
```

---

# 15. QUALITY ASSURANCE

Before every commit, Claude must run a repository review.

## Required Checks

- correct repository,
- correct branch,
- clean file hierarchy,
- no duplicate canonical documents,
- no broken relative links,
- no placeholder text presented as complete,
- metadata present,
- status values valid,
- file naming compliant,
- dates accurate,
- no private data,
- no unsupported clinical claims,
- no fabricated testimonials,
- no fabricated citations,
- no fabricated analytics,
- no inconsistent learning-objective IDs,
- no accidental changes to unrelated files.

## Final Session Review

At the end of each build session, report:

1. Files created
2. Files modified
3. Decisions made
4. Open gaps
5. Validation status
6. Commit hash
7. Push status
8. Exact next production action

Do not end with speculative system improvements.

---

# 16. CLINICAL AND EVIDENCE INTEGRITY

Claude must:

- distinguish evidence from clinical observation,
- avoid diagnosing readers or patients,
- avoid guaranteed outcome claims,
- avoid false precision,
- preserve contraindications and safety boundaries,
- cite the original or most authoritative available source,
- never invent student outcomes,
- never invent patient cases and present them as real,
- anonymize clinical stories,
- exclude protected health information,
- flag claims that require Drew's clinical confirmation,
- and defer to Drew on Learn2Tape-specific teaching doctrine where documentation is incomplete.

Clinical accuracy overrides persuasion.

---

# 17. CLAUDE OPERATING BEHAVIOR

Claude must behave as an institutional builder and production operator.

Claude should:

- read before writing,
- preserve approved decisions,
- make bounded assumptions,
- state assumptions in the relevant document,
- execute the approved build order,
- commit completed work,
- keep the repository clean,
- and prioritize production after infrastructure is complete.

Claude must not:

- redesign the architecture after approval,
- create unnecessary governance layers,
- inflate documents to appear comprehensive,
- repeat the same principle across multiple files without purpose,
- generate marketing claims unsupported by evidence,
- substitute generic CE-industry language for Drew's mentor voice,
- or keep asking what to build after the roadmap has been approved.

When uncertainty does not block safe execution, choose the least-complex option and document the assumption.

---

# 18. STOP CONDITION FOR INFRASTRUCTURE

Infrastructure work ends when all of the following exist and are internally consistent:

- Publishing Foundation ✓
- Editorial Charter ✓
- Curriculum Blueprint ✓
- Curriculum Delivery Plan ✓
- Content Workflow ✓
- Master Asset Library ✓
- Derivative Standards (in progress)
- Analytics Scorecard (in progress)
- Content Backlog (in progress)
- Decision Log (in progress)
- Campaign 001 structure (in progress)

At that point Claude must state:

> **Infrastructure is complete. The next authorized action is Blog #1 production.**

Claude must not recommend more infrastructure unless a documented production problem requires it.

---

# 19. FREEZE PROCEDURE

After Blog #1 completes the entire production and distribution workflow:

1. Review all friction noted during production.
2. Classify each item:
   - genuine system failure,
   - execution error,
   - preference,
   - future enhancement.
3. Correct genuine system failures only.
4. Record every approved correction in `08_DECISION_LOG.md`.
5. Update canonical document versions where necessary.
6. Complete `PUBLISHING_SYSTEM_v1.0_FROZEN.md`.
7. Update:
   - README
   - CHANGELOG
   - ROADMAP
8. Commit and push.

### Freeze Commit

```text
docs: freeze Learn2Tape Publishing System v1.0
```

After freeze:

- governance is stable,
- production continues,
- changes require evidence,
- and future improvements are versioned.

---

# 20. INITIAL EXECUTION PROMPT FOR CLAUDE

Copy the following prompt into Claude after giving it access to the repository:

```text
You are authorized to build the canonical GitHub repository for the Learn2Tape Publishing System.

Repository:
learn2tape-publishing-system

Your governing workflow is:
CLAUDE_BUILD_WORKFLOW.md (in repository root)

Begin by reading the entire workflow. Then perform repository preflight:

1. Confirm the local repository root.
2. Confirm git remote origin.
3. Confirm current branch.
4. Run git status.
5. Pull the latest changes.
6. Inventory all existing files.

Do not write or modify files until repository identity is verified.

Then execute the workflow in its approved order.

Important constraints:

- GitHub is the canonical source of truth.
- This repository must remain separate from Finding My Wei.
- Curriculum comes before campaign.
- Education comes before authority; authority comes before enrollment.
- The system exists to accelerate publishing, not delay it.
- Do not invent additional governance documents.
- Do not overwrite existing approved documents without reading them.
- Do not fabricate research, testimonials, analytics, or clinical outcomes.
- Commit and push each completed logical phase.
- Report commit hashes and push status.
- Stop infrastructure work when the defined stop condition is reached.
- The next action after infrastructure completion is Blog #1:
  "Tape Doesn't Fail: Clinical Reasoning Does."

At the end of each phase, provide:
- files created,
- files modified,
- decisions made,
- unresolved gaps,
- validation status,
- commit hash,
- push status,
- next authorized action.

Begin with repository preflight now.
```

---

# 21. DEFINITION OF DONE

The repository build is complete when:

- the structure is present,
- canonical governance documents are ingested,
- production documents are complete,
- Campaign 001 is initialized,
- all relative links work,
- all documents use controlled metadata,
- the repository is committed and pushed,
- the working tree is clean,
- and Claude explicitly transitions from infrastructure to Blog #1 production.

The publishing system itself is not frozen until Blog #1 has validated it end-to-end.

---

# 22. FINAL DIRECTIVE

Build only what improves Learn2Tape's ability to:

- teach better,
- publish faster,
- preserve institutional knowledge,
- maintain clinical integrity,
- and convert earned trust into sustainable enrollment.

Once the infrastructure is sufficient, stop building the machine and use it.
