---
name: catalog-maker-guide-writer
description: Write one PDF Catalog Maker user guide page from a single screenshot of the app. Use this whenever the user hands over a screenshot of the Catalog Maker editor (or any of its panels, templates, blocks, or settings dialogs) and asks for a guide page, help doc, or user guide content for the feature it shows.
---

# Catalog Maker Guide Page Writer

**Job:** Given one screenshot of the PDF Catalog Maker app, write one guide page for the feature shown in it, and hand back the page plus an annotated copy of the screenshot.

This skill only covers PDF Catalog Maker. If the screenshot is clearly from a different RockCats app (Gallery, Lookbook, Collage), say so and stop — that's a different app with its own page template groups.

## Read these, in this order, before every job

1. **`catalog-maker-summary.png`** (repo root) — what the app is for and its capability list (Input / Editor: Page templates, Blocks, Product card template, Global settings / Output). Use it as the source of truth for what's a *real* Catalog Maker feature.
2. **`SKILL.md`** (repo root) — the general writing process: understand the app, pick the page type, check examples, verify against the screenshot instead of guessing, ask when unclear, write to template, handle the screenshot.
3. **`page-template.md`** (repo root) — the exact page structure, tables, and writing rules every page must follow. It's written for the Gallery App, but its page-type structures (especially Type 1: Guide page) and all its writing rules apply as-is; ignore its Gallery/Lookbook/Collage-specific Help Center grouping.
4. **`screenshots/examples/`** — reference examples only (one Guide page, one Help Center page, one FAQ page, one annotation example). Use these to match formatting and highlight style, not as content to copy.

If any of these four is missing or empty, stop and tell the user exactly which one, and don't write the page.

## Steps for each screenshot

1. **Look at the screenshot closely.** Read every visible panel title, label, toggle, dropdown, and button text — this is your primary source for what the feature is and what it's called, not any external design file.
2. **Identify the feature**, and sanity-check it against `catalog-maker-summary.png`'s capability list (Page templates: Cover, Product page, Back cover, Custom page; Blocks: Text, Shape, etc.; Product card template; Global settings: page size, colors, fonts; Output: PDF catalog, Flipbook catalog).
   - Can't tell which screen or feature the screenshot shows → stop and ask the user. Don't guess.
   - Shows a field, button, or behavior that isn't anywhere in `catalog-maker-summary.png`'s capability list → stop and ask the user to confirm it's real before writing about it. Never invent a field or behavior that isn't visibly in the screenshot or confirmed by the user.
3. **Write a Type 1: Guide page** following `page-template.md`'s structure exactly:
   - Title ("How to... [feature]"), quick index line, Goal, Where to see & edit, What you can do (one numbered row per feature/control visible, in the same order you'll badge them on the screenshot), Troubleshooting (only if errors are likely), Note (only if a rule applies to the whole page).
   - Apply every writing rule in `page-template.md` (verb-first, bold exact UI labels, US English, "and" not "&", one idea per line, etc.).
4. **Annotate a copy of the screenshot** — never the original — the same way as `screenshots/examples/screenshot-annotation-example.png`: blue `#2563EB` rounded highlight box per control, filled blue circle with a white number badge, one badge per "What you can do" row, same order as the table. Keep the output under 200 KB. Name the file lowercase-with-hyphens.
5. **Self-check**, max 2 rounds: does every table row match something actually visible in the screenshot? Does every label match the exact on-screen text? Do the badge numbers on the image match the row numbers in the table? Fix anything that doesn't, then stop — don't keep polishing past 2 rounds. If something's still unresolved after 2 rounds, hand over the page anyway and flag what's unresolved.
6. **Hand back** the finished page text and the annotated image together.

## Stop and ask the user when

- The screenshot doesn't make clear which screen or feature it's for (e.g. cropped too tight, ambiguous panel).
- The screenshot shows something not covered by `catalog-maker-summary.png`'s capability list.
- `catalog-maker-summary.png`, `SKILL.md`, `page-template.md`, or `screenshots/examples/` is missing.
- The screenshot is from a different app (Gallery, Lookbook, Collage) rather than Catalog Maker.
