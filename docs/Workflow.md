# Workflow

## Immediate next steps

### 1. Open the local site in your browser

After `bundle exec jekyll serve`, Jekyll usually prints a local URL in the terminal, typically:

```text
http://127.0.0.1:4000/
```

Open that and click through the main pages:

- Home
- The Case
- Issues & Solutions
- Evidence
- Updates
- Get Involved
- FAQ
- Contact
- Privacy

What you are checking right now is:

- header renders
- footer renders
- navigation links work
- breadcrumbs appear on interior pages
- no broken layouts
- no missing assets/CSS

### 2. Fix any obvious skeleton issues first

Before writing a lot of content, confirm:

- nav labels are correct
- URLs are correct
- page titles look right
- Markdown content is rendering properly
- spacing/typography is acceptable for a first pass

If anything is broken, fix the shell now while the site is still small.

## After the skeleton is verified

### 3. Start implementing the MVP content in the agreed order

Use the build order from `ContentPlan.md` and `ImplementationPlan.md`.

Go in this sequence:

1. `index.md`
2. `the-case/index.md`
3. `the-case/what-is-proposed.md`
4. `the-case/why-it-matters.md`
5. `issues-and-solutions/index.md`
6. `issues-and-solutions/concerns.md`
7. `issues-and-solutions/how-the-trail-helps.md`
8. `evidence/index.md`
9. `evidence/research.md`
10. `updates/index.md`
11. `updates/timeline.md`
12. `get-involved/index.md`
13. `get-involved/take-action.md`
14. `faq.md`
15. `contact.md`
16. `privacy.md`

That gives you a usable MVP without waiting for every page to be perfect.

## Recommended working pattern in VS Code

For each page:

### A. Open the corresponding entry in `ContentPlan.md`

Use that as the brief:

- purpose
- primary persona
- key messages
- required content blocks
- CTA
- dependencies

### B. Draft the page in Markdown

Start with:

- page title
- short summary/standfirst
- 3–5 major sections
- CTA at the bottom

### C. Refresh browser and inspect

Look for:

- scanability
- heading structure
- link clarity
- whether the page actually serves its persona

### D. Commit page-by-page or section-by-section

That will keep source control clean.

## What I would do first

Start with these three pages before anything else:

1. **Home**  
   Because it sets the tone and validates the overall IA.

2. **What Is Proposed?**  
   Because that is the core explanatory page and will reduce ambiguity everywhere else.

3. **Why It Matters**  
   Because it begins to make the case and will likely feed copy into several other pages.

## Practical checkpoint after that first trio

Once those three pages are drafted, review:

- Does the proposition feel clear?
- Does the tone feel credible rather than over-advocacy-heavy?
- Is the navigation still the right shape?
- Are you happy with the visual hierarchy?

That is your first meaningful design/content milestone.

## Suggested source-control approach

At this stage, make commits like:

- `Initialize Jekyll site skeleton`
- `Draft homepage MVP content`
- `Draft The Case landing page`
- `Draft What Is Proposed page`
- `Draft Why It Matters page`

That will make rollback and review much easier.

## My recommendation for your very next action

Open `index.md` and start drafting the homepage using the content brief from `ContentPlan.md`.

A good practical sequence is:

1. draft homepage headline + subhead
2. add the homepage section headings
3. fill each section with placeholder or first-pass copy
4. preview in browser
5. refine structure before polishing wording
