# ImplementationPlan.md

## Purpose

This document defines the phased implementation of the Alto Multimodal Trail advocacy website so that the work can be managed in source control and executed incrementally.

This plan is based on the agreed design direction captured in `SiteDesign.md`.

---

## Planning assumptions

### Platform
- GitHub Pages
- Jekyll
- Markdown content pages
- minimal shared layouts/includes
- custom CSS

### Implementation philosophy
- launch lean
- prioritize pages that answer the most important user questions
- avoid building empty or thin pages too early
- expand structure only when the content justifies it
- keep the site easy to maintain by non-specialists

### Primary goal of the MVP
Launch a credible, navigable, static advocacy site that explains the proposal, addresses concerns, presents evidence, and provides a clear path to action.

---

## High-level phases

- Phase 0 — Foundation and project setup
- Phase 1 — MVP information architecture and core pages
- Phase 2 — Evidence, advocacy, and expansion pages
- Phase 3 — Media/support maturity and editorial hardening
- Phase 4 — Continuous improvement and content operations

---

# Phase 0 — Foundation and project setup

## Goal
Create the repository, base static site structure, and shared site shell.

## Deliverables
- repository created and initialized
- GitHub Pages/Jekyll setup working locally and in GitHub
- base folder structure created
- `_config.yml` created
- `Gemfile` created
- base layout created
- header include created
- footer include created
- breadcrumbs include created
- base stylesheet created
- top navigation wired
- footer navigation wired

## Suggested repo structure

```text
alto-multimodal-trail/
├─ README.md
├─ Gemfile
├─ _config.yml
├─ index.md
├─ assets/
│  ├─ css/
│  │  └─ site.css
│  ├─ images/
│  └─ docs/
├─ _layouts/
│  ├─ default.html
│  └─ page.html
├─ _includes/
│  ├─ header.html
│  ├─ footer.html
│  └─ breadcrumbs.html
├─ the-case/
├─ issues-and-solutions/
├─ evidence/
├─ updates/
├─ get-involved/
├─ faq.md
├─ media-kit.md
├─ contact.md
├─ accessibility.md
└─ privacy.md
```

## Acceptance criteria
- site builds locally
- site publishes correctly on GitHub Pages
- global navigation is visible and functional
- footer navigation is visible and functional
- base page template is reusable
- content pages can be added with simple Markdown front matter

---

# Phase 1 — MVP information architecture and core pages

## Goal
Launch the smallest credible version of the website.

## MVP scope

### Main navigation
- Home
- The Case
- Issues & Solutions
- Evidence
- Updates
- Get Involved

### Utility links
- FAQ
- Contact
- Privacy

### MVP pages
1. Home
2. The Case landing page
3. What Is Proposed?
4. Why It Matters
5. Issues & Solutions landing page
6. Concerns
7. How the Trail Helps
8. Evidence landing page
9. Research
10. Updates landing page
11. Timeline
12. Get Involved landing page
13. Take Action
14. FAQ
15. Contact
16. Privacy

## Deliverables
- all MVP pages created as Markdown pages
- navigation labels finalized in templates
- homepage content blocks implemented
- breadcrumbs on interior pages
- initial calls to action implemented
- responsive navigation verified

## Page goals in this phase

### Home
- orient first-time visitors
- present the idea quickly
- route users to learn, verify, or act

### The Case pages
- explain the proposal
- explain why it matters

### Issues & Solutions pages
- acknowledge concerns
- explain where the trail concept may help

### Evidence pages
- provide proof layer and source-backed context

### Updates pages
- establish current relevance through timeline/context

### Get Involved pages
- give visitors a clear action path

## Acceptance criteria
- users can understand the proposal within one visit
- users can find concerns and evidence quickly
- users can find at least one clear action path
- the homepage is directional, not overloaded
- the site feels complete even if some later pages do not exist yet

---

# Phase 2 — Evidence, advocacy, and expansion pages

## Goal
Add the deeper pages needed for reuse, campaigning, and stronger proof.

## Phase 2 pages
- The Case / Benefits
- The Case / Examples
- Issues & Solutions / Open Questions
- Evidence / Case Studies
- Evidence / Downloads
- Updates / Latest
- Updates / Events
- Get Involved / Contact Decision-Makers
- Get Involved / Stay Connected
- Media Kit
- Accessibility

## Deliverables
- additional section pages created
- evidence library expanded
- downloadable artifacts organized
- action pathways improved
- media support page added
- accessibility statement added

## Why these come later
These pages are useful, but should only be added when there is enough content to make them substantive.

## Acceptance criteria
- each added page contains meaningful content and not just placeholders
- evidence pages contain actual sources, summaries, or downloads
- action pages contain concrete instructions and contact paths
- Media Kit has enough material to be useful

---

# Phase 3 — Media/support maturity and editorial hardening

## Goal
Strengthen the quality, consistency, and operational usefulness of the site.

## Deliverables
- Media Kit expanded with fact sheet and approved descriptions
- Downloads organized by type and date
- FAQ expanded based on real repeated questions
- page templates refined for consistency
- tone and terminology audited for alignment
- metadata/descriptions improved for sharing and search snippets

## Optional additions in this phase
- structured content status tracking
- visual asset library inside `assets/`
- style guidance for repeated page patterns
- better card/grid patterns for section landing pages

## Acceptance criteria
- the site supports journalists and partner organizations effectively
- messaging is consistent across pages
- there is a repeatable pattern for updates and downloads

---

# Phase 4 — Continuous improvement and content operations

## Goal
Keep the site current, trustworthy, and maintainable over time.

## Ongoing work
- publish updates as project conditions change
- revise timeline as milestones occur
- add or retire downloads as needed
- update FAQs based on public questions
- refine wording when strategy shifts
- maintain accuracy and dated context on evidence pages

## Operating guidance
- prefer small, deliberate content updates over big rewrites
- keep `SiteDesign.md` and this document aligned
- avoid adding pages that cannot be maintained
- archive outdated material rather than leaving it ambiguous

---

## Suggested work breakdown by implementation stream

### Stream A — Site shell and templates
- `_config.yml`
- layouts
- includes
- nav
- footer
- breadcrumbs
- CSS foundation

### Stream B — Core content pages
- homepage
- core explanatory pages
- concerns and evidence pages
- action pages

### Stream C — Evidence and downloadable artifacts
- research summaries
- case studies
- briefs
- decks
- letters
- submissions

### Stream D — Content operations
- update cadence
- editorial review
- page status tracking
- QA/checklist discipline

---

## Suggested page implementation order

### First build order
1. README.md
2. Gemfile
3. `_config.yml`
4. base layout and includes
5. `assets/css/site.css`
6. `index.md`
7. `the-case/index.md`
8. `the-case/what-is-proposed.md`
9. `the-case/why-it-matters.md`
10. `issues-and-solutions/index.md`
11. `issues-and-solutions/concerns.md`
12. `issues-and-solutions/how-the-trail-helps.md`
13. `evidence/index.md`
14. `evidence/research.md`
15. `updates/index.md`
16. `updates/timeline.md`
17. `get-involved/index.md`
18. `get-involved/take-action.md`
19. `faq.md`
20. `contact.md`
21. `privacy.md`

### Second build order
1. `the-case/benefits.md`
2. `the-case/examples.md`
3. `issues-and-solutions/open-questions.md`
4. `evidence/case-studies.md`
5. `evidence/downloads.md`
6. `updates/latest.md`
7. `updates/events.md`
8. `get-involved/contact-decision-makers.md`
9. `get-involved/stay-connected.md`
10. `media-kit.md`
11. `accessibility.md`

---

## Definition of done for each page

A page should be considered done when:
- the purpose of the page is clear
- the content matches its persona and role in the IA
- the page has a clear next step or CTA where appropriate
- headings are scannable
- links are working
- metadata/front matter is complete
- the page does not depend on placeholder text to make sense
- visuals, if used, support the page’s argument directly

---

## Risks to avoid

- overbuilding the site before content exists
- creating too many thin pages
- hiding key information behind vague labels
- making the homepage too dense
- mixing persuasive claims with unsupported evidence
- creating content-type silos that weaken information scent
- neglecting updates after launch

---

## Recommended companion documents

To support implementation, the following companion documents are recommended:

- `SiteDesign.md` — agreed design direction and IA
- `ContentPlan.md` — page copy plan, ownership, and status
- `ChangeLog.md` — major site/content changes over time if needed

---

## Change management guidance

When updating this plan:
- preserve the phased approach unless there is a deliberate reason to change it
- record why scope moved between phases
- keep implementation phases aligned with actual repository structure
- update the page lists when new pages are added or retired
- keep this document aligned with `SiteDesign.md`

