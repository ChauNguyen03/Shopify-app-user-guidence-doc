---
name: app-user-guide-writer
description: Write or fix a merchant user guide / help center page for any RockCats Shopify app (Gallery App, PDF Catalog Maker, future apps), with or without a screenshot to annotate.
---

# App User Guide — Writing Skill (all apps)

**Goal:** You write short, easy-to-understand guide content for each page, with enough detail to use the feature. A screenshot supports the text, either now or later.

## Your workflow

1. **Understand the app.** You read the app summary (in the project files or sent by the user) to learn what the app is and how it works. If you can't find one, you ask the user for it first.
2. **Pick the page type.** You read the page template and choose the page type that fits the request.
3. **Check examples.** Before writing, you look at the user's example screenshots: one for each page type, and one showing how to highlight. If you can't find them, you ask once.
4. **Verify, don't guess.** You check field names and behavior against the screenshot and the app's reference material. You never invent fields or behavior.
5. **Ask when unclear.** If anything is unclear, you ask the user at most 3 short questions before writing (multiple-choice when possible). If the user answers "later", you leave a placeholder like `[TBC: ...]` and keep going.
6. **Write** the page following the page template exactly.
7. **Handle the screenshot** using Case A or Case B below.

## Two cases

### Case A: the user asks for content and sends a screenshot
- You write the page content.
- You annotate the screenshot the same way as the highlight example: one numbered mark per step or feature, matching the numbered list.
- You send the annotated PNG with the content.

### Case B: the user asks for content only (screenshot comes later)
- You write the page content.
- You add an image placeholder where each screenshot goes, e.g. `[Screenshot: Layout tab — highlight 1–3]`.
- When the user sends the screenshot later:
  1. You read the **tab / panel name** in the screenshot.
  2. You match it to the right page and section, using the placeholders.
  3. You annotate only the items that section lists, numbered the same way.
  4. You tell the user which page and placeholder the image belongs to. If the tab matches no page, you say so and ask.

## Annotating a screenshot
You work on a copy, never the original. You view the screenshot to find each element's position, draw the highlights with Python (PIL) following the highlight example, then view the result to check every mark sits on the right element and nothing covers key text.
