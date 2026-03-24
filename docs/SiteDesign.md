# SiteDesign.md

## Purpose

This document captures the agreed design direction for the Alto Multimodal Trail advocacy website so that the site can be developed consistently over time and the key decisions from early planning are not lost.

This document is intended to be stored in source control and updated deliberately as the design evolves.

---

## Design goals

The site should:

- explain the multimodal trail concept clearly and credibly
- support advocacy for considering a multimodal trail alongside the proposed Alto high-speed rail project
- help different audiences quickly find the information they need
- present evidence, concerns, and tradeoffs honestly
- convert interest into concrete action
- remain simple enough to launch as a maintainable GitHub Pages static site

---

## Core design principles

### 1. Organize by user questions, not content type
The site should be organized around what visitors are trying to understand or do, not around internal document types like reports, letters, visuals, or PDFs.

### 2. Keep the hierarchy shallow
The site should use a shallow, topic-based hierarchy that is easy to scan and navigate.

### 3. Treat concerns seriously
The site must not read like pure promotion. It should acknowledge legitimate concerns and distinguish between what is known, what is plausible, and what still requires study.

### 4. Separate persuasion from proof
The persuasive case should be readable and accessible, while detailed evidence and downloadable materials should live in dedicated support sections.

### 5. Build for an MVP first
The design should support a lean launch first, then expand later as content volume and campaign needs grow.

### 6. Embed visuals where they do explanatory work
Maps, figures, and visuals should generally be embedded into relevant pages rather than presented as a standalone top-level section.

### 7. Use plain-language labels
Navigation labels should be concise, readable, and audience-centered.

---

## The six core personas

The site design is based on six primary personas.

### 1. Public Decision-Maker
A federal, municipal, agency, or institutional actor who can influence whether the trail concept is considered, studied, supported, or integrated.

### 2. Technical Implementer
A planner, engineer, project development staffer, transportation official, environmental reviewer, or similar professional evaluating feasibility and interfaces.

### 3. Corridor Community Member
A resident, neighbourhood stakeholder, parent, nearby business owner, local trail user, or community association member affected by or interested in the corridor.

### 4. Supportive Advocate
An active transportation advocate, trail/cycling group member, environmental advocate, coalition partner, or civic supporter looking to advance the idea.

### 5. Skeptical Stakeholder
A concerned resident, cautious official, critic, property-rights oriented observer, or journalist pressure-testing the idea.

### 6. Media / Research Intermediary
A journalist, policy analyst, academic, public-interest researcher, or partner organization preparing a summary, briefing, or presentation.

---

## Persona matrix

| Persona | Role in the Alto ecosystem | Top questions | Top tasks | Needed content | Desired action |
|---|---|---|---|---|---|
| Public Decision-Maker | Can influence whether the trail concept is considered, studied, supported, or integrated | What is proposed? Why is it in the public interest? Is it credible enough to merit study? Does it help address broader project concerns? | Review quickly, assess credibility, brief others, compare with policy goals | Executive summary, one-pager, benefits case, issues-and-solutions framing, precedent summaries, clear asks | Support further study, request briefing, share internally |
| Technical Implementer | Evaluates feasibility, constraints, interfaces, and study paths | What is the physical concept? How might it interface with the corridor? What constraints are acknowledged? What still needs study? | Evaluate feasibility, test assumptions, identify gaps, compare examples | Scope diagrams, design principles, tradeoffs, case studies, corridor context, technical FAQ | Treat the proposal as credible input and engage on design/study questions |
| Corridor Community Member | Lives near, uses, or is affected by the corridor | What does this mean for my area? What are the benefits? What are the risks? How can I have a say? | Understand impacts, check local relevance, follow updates, decide whether to support | Plain-language explainer, local benefits, concerns page, timeline, engagement info, FAQ | Stay informed, attend events, contact officials, support or share |
| Supportive Advocate | Helps amplify, organize, and legitimize support | What is the strongest argument? What evidence can I cite? What can I share? What is the ask? | Reuse messaging, recruit support, brief others, circulate materials | Talking points, evidence summaries, downloadable briefs, action info, partner resources | Amplify, organize, advocate, recruit allies |
| Skeptical Stakeholder | Tests whether the proposal is overstated or incomplete | Is this spin? What does it not solve? What are the downsides? Are claims sourced? Are uncertainties acknowledged? | Pressure-test claims, verify facts, assess balance and honesty | Concerns page, tradeoffs/open questions, cited evidence, precise language | Move from dismissal to cautious engagement, or at least view the proposal as serious |
| Media / Research Intermediary | Translates the proposal for broader audiences | What is the proposal? What is Alto context? Who supports it? What are the key facts and dates? | Pull facts, cite sources, build summaries, find assets and contacts | Timeline, fact sheet, evidence library, downloadable assets, media kit, contact info | Cover it accurately, brief others, request interview/comment |

---

## Persona matrix tied to site sections and page priorities

| Persona | Primary site sections | Secondary site sections | First pages they should find | Page priority / emphasis |
|---|---|---|---|---|
| Public Decision-Maker | The Case, Issues & Solutions, Evidence | Updates, Get Involved | Home, What Is Proposed?, Why It Matters, How the Trail Helps, Research | Very high on concise summaries, evidence-backed claims, and a clear ask |
| Technical Implementer | The Case, Issues & Solutions, Evidence | FAQ, Updates | What Is Proposed?, How the Trail Helps, Open Questions, Case Studies, Research | Very high on scope clarity, precedents, and acknowledged constraints |
| Corridor Community Member | Home, The Case, Issues & Solutions, Updates | Get Involved, FAQ | Home, Why It Matters, Concerns, Timeline, Events | Very high on plain language, local relevance, clarity, and trust |
| Supportive Advocate | Get Involved, Evidence, The Case | Updates, Media Kit | Take Action, Contact Decision-Makers, Why It Matters, Downloads, Statements/updates | Very high on shareable content, talking points, and downloadable materials |
| Skeptical Stakeholder | Issues & Solutions, Evidence | FAQ, The Case | Concerns, Open Questions, Research, Case Studies | Very high on honesty, citations, nuance, and non-hype language |
| Media / Research Intermediary | Updates, Evidence, Media Kit | Contact, The Case | Latest, Timeline, fact-summary content, Downloads, Media Kit, Contact | Very high on dates, sources, downloadable assets, and quick orientation |

---

## Final information architecture

### Main navigation

- Home
- The Case
- Issues & Solutions
- Evidence
- Updates
- Get Involved

### Utility links

- FAQ
- Media Kit
- Contact

### Footer-only links

- Accessibility
- Privacy

### Primary header CTA

- Take Action

---

## Final sitemap

### Home
- URL: `/`
- Purpose: orient first-time visitors, explain the idea quickly, and route users to the right next step

### The Case
- URL: `/the-case/`
- Purpose: present the persuasive public-interest case for the idea
- Subpages:
  - What Is Proposed?
  - Why It Matters
  - Benefits
  - Examples

### Issues & Solutions
- URL: `/issues-and-solutions/`
- Purpose: build credibility by addressing concerns directly and honestly
- Subpages:
  - Concerns
  - How the Trail Helps
  - Open Questions

### Evidence
- URL: `/evidence/`
- Purpose: back up the site’s claims with sources, examples, and downloadable material
- Subpages:
  - Research
  - Case Studies
  - Downloads

### Updates
- URL: `/updates/`
- Purpose: show the site is current and the campaign is active
- Subpages:
  - Latest
  - Timeline
  - Events

### Get Involved
- URL: `/get-involved/`
- Purpose: turn support into action
- Subpages:
  - Take Action
  - Contact Decision-Makers
  - Stay Connected

### Utility pages
- FAQ
- Media Kit
- Contact
- Accessibility
- Privacy

---

## Homepage content model

The homepage should be directional rather than encyclopedic.

### Recommended homepage sections

1. Hero
   - short statement of the proposal
   - primary CTA: Learn the Case
   - secondary CTA: Take Action

2. Why this matters
   - 3 short benefit cards or summary points

3. Concerns, taken seriously
   - short credibility block linking to Issues & Solutions

4. Evidence
   - quick links to Research, Case Studies, and Downloads

5. What’s happening now
   - latest development
   - next engagement moment
   - latest statement/brief

6. Take action
   - 2–3 concrete actions only

---

## Navigation and wayfinding guidance

### Header
- site title/logo on the left
- main nav in a consistent position
- Take Action button highlighted on the right

### Breadcrumbs
Use breadcrumbs on interior pages to show location in the hierarchy.

Example:

`Home > Issues & Solutions > How the Trail Helps`

### Section landing pages
Each major section should have a landing page with:
- a brief introduction
- summary cards to the most important subpages
- one clear CTA

---

## Content model guidance

### What belongs on persuasive pages
- plain-language explanation
- structured arguments
- embedded visuals where useful
- concise summaries and next-step links

### What belongs on evidence pages
- source-backed summaries
- case studies
- downloadable artifacts
- dates and context

### What belongs on action pages
- clear asks
- simple instructions
- contact or sign-up pathways
- partner/support information

---

## Visual and media guidance

### Agreed decision
Do not create a standalone main section called “Maps, Figures, and Visuals.”

### Rationale
Visitors look for information by topic and task, not by media type.

### Implementation guidance
- embed maps where geographic understanding is needed
- embed figures where they explain a point
- keep reusable assets in Media Kit or Downloads where appropriate

---

## Tone and editorial guidance

The site should sound:
- credible
- calm
- civic-minded
- evidence-aware
- honest about tradeoffs
- persuasive without hype

Avoid:
- exaggeration
- overclaiming
- dismissive treatment of concerns
- vague calls to action

---

## GitHub Pages implementation guidance

### Platform choice
Use GitHub Pages with Jekyll and Markdown.

### Implementation stance
Start with a lean structure and only add complexity when content volume justifies it.

### Lean MVP structure
- Markdown content pages
- `_config.yml`
- minimal layouts/includes
- custom stylesheet
- no JavaScript unless it is clearly needed

---

## MVP repository structure (agreed lean version)

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
│  ├─ index.md
│  ├─ what-is-proposed.md
│  └─ why-it-matters.md
├─ issues-and-solutions/
│  ├─ index.md
│  ├─ concerns.md
│  └─ how-the-trail-helps.md
├─ evidence/
│  ├─ index.md
│  └─ research.md
├─ updates/
│  ├─ index.md
│  └─ timeline.md
├─ get-involved/
│  ├─ index.md
│  └─ take-action.md
├─ faq.md
├─ media-kit.md
├─ contact.md
├─ accessibility.md
└─ privacy.md
```

---

## Page-building priority

### Highest priority pages
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

### Phase 2 expansion pages
- Benefits
- Examples
- Open Questions
- Case Studies
- Downloads
- Latest
- Events
- Contact Decision-Makers
- Stay Connected
- Media Kit
- Accessibility

---

## Open future documents recommended

The following documents are recommended for source control as the project grows:

- `ImplementationPlan.md` — phased implementation plan for the site
- `ContentPlan.md` — page-by-page copy plan, ownership, and status
- `StyleGuide.md` — voice, terminology, and component-level writing patterns if the site grows in complexity

---

## Change management guidance

When updating this document:
- preserve earlier decisions unless there is a deliberate reason to change them
- record why a major IA or persona decision changed
- keep this document aligned with `ImplementationPlan.md`
- update the sitemap and page priority sections when pages are added or removed

