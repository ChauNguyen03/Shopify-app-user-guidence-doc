# Gallery App User Guide — Page Template

There are 3 page types. Pick the type first, then follow its format.

| Type | Use for | Example |
|---|---|---|
| **1. Guide page** | How to use one feature or panel | How to set up video on gallery |
| **2. Help Center page** | The hub that lists and links all guides | Gallery App Help Center |
| **3. FAQ page** | Quick answers to common questions | FAQs Frequently asked questions |

---

## Type 1: Guide page

1. **Page title**: lists the features covered, e.g. "How to set up video on gallery". No "?" on "How to..." titles.
2. **Quick index** (small text under the title): short feature names, comma-separated, e.g. *Mute, Autoplay, Video view on click, Show play/pause icon*
3. **Goal** (Heading 1): one sentence on what the merchant accomplishes. If the page has 2+ purposes, put each on its own line. Don't number them.
4. **Where to see & edit** (Heading 1): a 2-column table, no header row.

   | | |
   |---|---|
   | In the Design editor, under **More settings**, open **[Panel]**. | *(screenshot: panel highlighted, no number)* |

5. **What you can do** (Heading 1): a 3-column table.

   | Feature | Editor | Preview |
   |---|---|---|
   | **1. Feature name** | *(one screenshot for all rows, numbered 1, 2, 3…)* | *(storefront result, optional)* |
   | **2. Feature name** — Short description, only if the name isn't clear. | | |
   | **3. Feature name** — Choose how…: Option A, Option B, or Option C. | | |

   - One row per feature, numbered in the same order as the screenshot badges.
   - The Editor and Preview cells can be merged across all rows, with one screenshot each.
   - Add a description only when the feature name doesn't explain itself.

6. **Troubleshooting** (Heading 1, optional): only when merchants are likely to hit errors.

   | Case | Issue | Solution |
   |---|---|---|
   | **Short case name** | One line + issue screenshot | One line + fix screenshot |

7. **Note** (optional): one line at the end for a rule that applies to the whole page.

---

## Type 2: Help Center page

1. **Page title**: Gallery App Help Center
2. **Intro line**: one sentence, e.g. "Step-by-step guides to set up and customize your galleries, Lookbooks, and collages." No Goal heading.
3. **One Heading 1 + one table per group**: Getting started, Gallery, Lookbook, Collage, All gallery types. If a group is split into sub-sections, each sub-section title is also Heading 1 (e.g. "How to use — Product pages") — every heading on the page is the same level, nothing smaller.

   | Page # | Guide | What you'll learn |
   |---|---|---|
   | 1 | [Short guide name](link) | One short line. |

   - **Page #** counts up across all groups (Getting started 1–3, Gallery 4–13, …), not restarting per table or sub-section.
   - **Guide** is a link to the page, with a short name (not the full "How to…" title).

---

## Type 3: FAQ page

1. **Page title**: FAQs Frequently asked questions
2. **Group headings** (H2): named by topic, e.g. Getting started, Layout.
3. **Questions** (H3): numbered across the whole page (1, 2, 3…), not restarting per group.
   - If a question applies to one gallery type only, start it with the type in brackets, e.g. "(Lookbook) In the List card style, how do I change the space between items?"
4. **Each answer** uses this format:

**N. Question in plain words?**

One-line answer naming the setting in bold.
- **Option:** what it does. *(bullets only when there are 2+ options)*

**Go to:** Design editor → Panel → **Setting** *(or a link to a page)*

**Learn more:** [Guide page title](link)

---

## Writing rules (all page types)

- Verb-first ("Set...", "Click...", "Choose..."), not "You can..."
- One idea per line. Put rules and limits in a sub-point (e.g. "• Not available with the Slider layout.")
- Explain only what the name doesn't already say
- Keep every line short: plain words, no jargon, aim for under ~10 words on the main line
- Each description starts with a capital letter and ends with a full stop
- Use the exact UI labels from the app, in bold (e.g. **Continue to editor**, **Browse files**)
- US English ("color", not "colour")
- Use "and" instead of "&" in sentences
- Page numbers belong only in the Help Center **Page #** column, never in guide or FAQ text

## Naming

- App name: [App Name]

## Screenshot annotation

- **Highlight color:** blue `RGB(37, 99, 235)` / `#2563EB`
- **Step badge:** filled blue circle, white number, white 2px outline
- **Highlight box:** rounded rectangle around the field to focus on
- **Where to see & edit image:** box only, no number
- **What you can do image:** number each feature on the screenshot to match its row in the table
- **Flow across screens:** combine into one image, with a blue arrow between screens
- **Two different places:** combine side by side with a grey dashed divider and a blue label on each
- **Errors (Troubleshooting):** red boxes and red labels; fixes use blue
- **Labels on images:** short, e.g. "Before: blocks drawn wrong", "Fix: delete error blocks and draw new ones"
- **Privacy:** blur store names, store URLs, theme names, real folders, and the app's internal name in the Shopify sidebar
- **File size:** keep each image under **200 KB** (the CMS rejects larger files even though it shows 5 MB)
- **File names:** lowercase with hyphens, no spaces (e.g. `filters-callouts.png`)
