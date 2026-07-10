# Contributing to Learn2Tape Publishing System

Thank you for contributing to Learn2Tape's institutional publishing system.

This document explains how to work with this repository and maintain its integrity.

---

## Guiding Principles

Before contributing, understand the principles that govern this repository:

1. **Curriculum Before Content** — All publishing decisions serve the 12 core learning objectives
2. **Education Before Authority** — Content is educational first; business outcomes follow
3. **One Source of Truth** — GitHub is canonical; all changes happen here
4. **Production Over Perfection** — Published work is favored over endless refinement
5. **Evidence-Based Changes** — System changes only proceed with evidence of need

---

## Types of Contributions

### Content Production (Blog Articles, Derivatives, Assets)

If you're producing an article or creating supporting assets:

1. **Start with the Curriculum Delivery Plan**
   - Find your assigned learning objective
   - Review the required research, stories, images, and assets

2. **Follow the Content Workflow**
   - See [03_CONTENT_WORKFLOW.md](00_PUBLISHING_SYSTEM/03_CONTENT_WORKFLOW.md)
   - Each phase has quality gates; don't skip them

3. **Use the Master Asset Library**
   - See [04_MASTER_ASSET_LIBRARY.md](00_PUBLISHING_SYSTEM/04_MASTER_ASSET_LIBRARY.md)
   - Reference existing assets before creating new ones

4. **Create in the Appropriate Campaign Folder**
   - `02_CAMPAIGNS/CAMPAIGN_001_BECOME_THE_THERAPIST_PATIENTS_REMEMBER/`
   - Follow the file naming standard (LO##_TOPIC_ASSET_TYPE_v1.0)

5. **Commit Clearly**
   - Use a descriptive message: `content: add LO03 canonical article`
   - Never mix unrelated changes in one commit

### Documentation Changes

If you're updating governance or infrastructure documents:

1. **Read the entire document first**
   - Understand the context and intent

2. **Make only evidence-based changes**
   - If it's governance, do we have evidence this needs updating?
   - If it's operational, has production revealed the need?

3. **Preserve metadata**
   - Update Version, Last Updated, Change Log
   - Don't remove historical information

4. **Commit with clear reasoning**
   - `docs: update 03_CONTENT_WORKFLOW based on Blog #1 learnings`
   - Include the evidence in the commit message

### Bug Fixes and Corrections

If you find an error:

1. **Verify the issue** — Read the relevant section fully
2. **Fix it** — Correct the error with minimal changes
3. **Document it** — Update the Change Log with the correction
4. **Commit it** — Use a patch version: `docs: fix broken link in Editorial Charter`

### Suggestions for System Improvement

If you notice something that could be better:

**First, ask:** Is this evidence of a genuine problem, or is this a preference?

- **Genuine problem:** Something breaks production or prevents us from publishing
- **Preference:** An alternative structure that seems more elegant

Only evidence-based improvements are accepted.

If you have evidence:

1. **Document the problem** — What is the actual friction?
2. **Propose the fix** — What change would resolve it?
3. **Show the impact** — How would this improve publishing?
4. **Open a discussion** — Don't make unilateral changes to governance

---

## Repository Structure

### Do Not Create

❌ Additional governance documents (without explicit authorization)  
❌ Strategy or vision documents  
❌ Marketing plans or social media strategies  
❌ Personas or competitor analyses  
❌ Meeting notes or status updates  
❌ Duplicate workflows or alternate processes  

If a document is not in the approved repository architecture, it should not be created.

### Do Create (When Authorized)

✅ Content (articles, derivatives, assets)  
✅ Analytics entries and reports  
✅ Backlog items  
✅ Decision log entries  
✅ Campaign folders and supporting materials  

---

## Git Workflow

### Branch Naming

Use descriptive branch names:

```text
content/lo##-short-description
campaign/campaign-id-short-description
docs/short-description
fix/short-description
```

Examples:
```text
content/lo01-clinical-reasoning
campaign/campaign-001-phase1-content
docs/add-analytics-scorecard
fix/broken-link-editorial-charter
```

### Commits

Each commit should:

- Represent one logical unit of work
- Use clear, present-tense language
- Avoid mixing unrelated changes

Examples:
```text
content: add LO01 canonical article and derivatives
docs: add 05_DERIVATIVE_STANDARDS.md
fix: correct curriculum phase descriptions in Blueprint
```

### Pull Requests

If working on a branch:

1. Write a clear title: `Add LO02 canonical article`
2. Describe what changed and why
3. Reference any related decisions or issues
4. Request review if needed

### Pushing to Main

After your work is complete and reviewed:

```bash
git checkout main
git pull origin main
git merge <your-branch>
git push origin main
```

Never force-push to main.

---

## Quality Standards

### Content Quality

All published content must:

- Meet Editorial Charter standards
- Follow the required structure (Situation → Common Mistake → Better Approach → Why It Works → Clinical Takeaway → Continue Learning)
- Pass clinical review
- Pass editorial review
- Include proper SEO metadata
- Have images with alt text
- Link internally (2–3 related articles)

### Documentation Quality

All governance and operational documents must:

- Include complete metadata (version, status, owner, dates)
- Have a clear purpose statement
- Include dependencies and what references them
- Maintain consistent voice and terminology
- Include a change log
- Pass the repository quality checklist (see below)

### Repository Quality Checklist

Before committing, verify:

- [ ] Correct repository (learn2tape-publishing-system, not Finding My Wei)
- [ ] Correct branch (main or feature branch)
- [ ] No broken internal links
- [ ] No placeholder text presented as complete work
- [ ] Metadata is accurate and consistent
- [ ] Status values use controlled vocabulary
- [ ] File naming follows standard (LO##_TOPIC_TYPE_v1.0)
- [ ] No fabricated research, testimonials, or analytics
- [ ] No unsupported clinical claims
- [ ] No personal data or protected information
- [ ] No accidental changes to unrelated files

---

## Clinical Integrity

### What We Require

- Distinguish evidence from clinical observation
- Avoid diagnosing readers or patients
- Avoid guaranteed outcome claims
- Cite the original or most authoritative source
- Preserve contraindications and safety boundaries
- Anonymize clinical stories; exclude protected health information

### What We Never Do

- Invent student outcomes
- Invent patient cases and present them as real
- Fabricate research citations
- Make claims unsupported by evidence
- Oversimplify complex clinical concepts
- Misrepresent author credentials or expertise

---

## Questions?

If you're unsure about:

- **Workflow:** See [03_CONTENT_WORKFLOW.md](00_PUBLISHING_SYSTEM/03_CONTENT_WORKFLOW.md)
- **Standards:** See [01_EDITORIAL_CHARTER.md](00_PUBLISHING_SYSTEM/01_EDITORIAL_CHARTER.md)
- **Production:** See [02A_CURRICULUM_DELIVERY_PLAN_Q3_2026.md](00_PUBLISHING_SYSTEM/02A_CURRICULUM_DELIVERY_PLAN_Q3_2026.md)
- **Assets:** See [04_MASTER_ASSET_LIBRARY.md](00_PUBLISHING_SYSTEM/04_MASTER_ASSET_LIBRARY.md)
- **Philosophy:** See [REPOSITORY_PHILOSOPHY.md](REPOSITORY_PHILOSOPHY.md)

When in doubt, ask before making changes.

---

## Respect for Process

This repository exists because process matters.

The governance documents, workflows, and standards aren't restrictions; they're the foundation of institutional capability.

Contributions that honor the process—and the principles behind it—strengthen the entire system.

Thank you for being part of it.

