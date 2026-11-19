---
name: app-user-guide-writer
description: Write or fix a merchant user guide / help center page for any RockCats Shopify app (Gallery App, PDF Catalog Maker, future apps), with or without a screenshot to annotate.
---

# App User Guide — Writing Skill (all apps)

**App name:** [RC PDF Catalog Maker] — placeholder name, not yet official. Update this everywhere it appears once the real name is confirmed.

**Context:** I am a Business Analyst building a Shopify app, currently called [RC PDF Catalog Maker]. I need to write guidance documents for users/customers on how to use our app.

**Task:** You write short, easy-to-understand guide content for each page, with enough detail to use the feature. A screenshot supports the text, either now or later.

**Trigger**: I provide a screenshot and you create the guide page per the workflow below.

## Your workflow

### Step 0 — Build the guide outline first
1. Read `catalog-maker-summary.png` and `User Guide Outline.xlsx` to learn the app and the planned guide structure.
2. Draft the full guide outline from those two sources (the list of pages/sections the guide will contain).
3. Show me the outline and **wait for my OK** before writing any individual page.

### Step 1 — Build the standing pages (Contact us, Installation, Privacy Policy)
1. Use `Example of Contact us.png`, `Example of Installation.png`, and `Example of Privacy Policy.docx` as the structure and style to follow.
2. Rewrite each one for [RC PDF Catalog Maker]: correct the app name, and any other names, labels, or elements, so everything matches this app, not the example's original app.
3. Show me each one for approval before moving on to individual "How to use" pages.

### Step 2 — Build the Help Center page
1. Use `page-template.md`'s Type 2: Help Center structure, and `screenshots/examples/help-center-example.png` for style.
2. Fill it from `guide/outline.md`: one group heading and table per group (Getting started, How to use, Save and publish, Support), with page numbers counting up across the whole page, not restarting per group.
3. Link each guide that's already written; for one not written yet, list its name in plain text (no link) rather than guessing a link.
4. Show me the page for approval before moving on to individual "How to use" pages.

### Step 3 — Individual "How to use" pages
All individual pages belong under **How to use**. I provide a screenshot of the real UI for each one. For each page:

1. **Understand the app.** Read the app summary (`catalog-maker-summary.png`, or sent by me) to learn what the app is and how it works. If you can't find one, ask me first.
2. **Pick the page type.** Read the page template and choose the page type that fits the request.
3. **Check examples.** Look at the example screenshots: one per page type, and one showing how to highlight. If you can't find them, ask once.
4. **Verify, don't guess.** Check field names and behavior against the screenshot and the app's reference material. Never invent fields or behavior.
5. **Ask when unclear.** If anything is unclear, ask me at most 3 short questions before writing (multiple-choice when possible). If I answer "later", leave a placeholder like `[TBC: ...]` and keep going.
6. **Write** the page following the page template exactly.
7. **Annotate the screenshot** the same way as the highlight example: one numbered mark per step or feature, matching the numbered list.
8. **Provide output**: page content and the annotated screenshot (PNG).

## Writing rules

- **Text color:** black only, normal weight or **bold** for emphasis. No blue or other colored text in the page content (headings included) — plain black text throughout.
- This does not change the screenshot highlight marks below, which stay blue so they're easy to spot against the UI.

## Annotating a screenshot
You view the screenshot to find each element's position, draw the highlights with Python (PIL) following the highlight example, then view the result to check every mark sits on the right element and nothing covers key text.
