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
4. **Where to see & edit** (Heading 1): a 2-column table, same column headers as **What you can do**.

   | Where | Preview |
   |---|---|
   | In the Design editor, under **More settings**, open **[Panel]**. | *(screenshot: panel highlighted, box only, no number)* |

5. **What you can do** (Heading 1): a 2-column table.

   | Steps (N) | Preview |
   |---|---|
   | **1. Step name** — in **[location]**, pick a setting:<br>&nbsp;&nbsp;▸ **Sub-option**<br>&nbsp;&nbsp;▸ **Sub-option** | *(one screenshot for this step: the editor panel and its storefront result, side by side, with a short caption underneath)* |
   | **2. Step name** — Short description, only if the name isn't clear. | *(its own screenshot + caption)* |

6. **Troubleshooting** (Heading 1): only add this section when the user explicitly asks for it — never on your own, even if a screenshot shows a visible warning or error.

   | Case | Issue | Solution |
   |---|---|---|
   | **Short case name** | One line + issue screenshot | One line + fix screenshot |

7. **Note** (optional): one line at the end for a rule that applies to the whole page. Include a link to the docs site (https://documentations.rockcats.site/e/en/apps/rc-ctalog-maker) when it helps the reader find other individual pages.

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

## Rules

### A. Content

**1. Page file setup**
- Write the page name in H2 (`## Page name:`).
- Write the short description as a normal paragraph.
- Add a `---` divider after them.
- Write the page title in H1 (`#`).
- Use [App Name] as the app name.
- Deliver the page's content and its highlighted screenshot together, in the same pass — never hand over a plain, unhighlighted screenshot and add the highlighting later as a follow-up.

**2. Wording**
- Start with a verb ("Set…", "Click…"), not "You can…".
- Use plain words, no jargon.
- Explain only what the name doesn't say.
- Use US English ("color", not "colour").
- Use "and" instead of "&" in sentences.
- Start with a capital letter and end with a full stop.

**3. Length and structure**
- Keep one idea per line.
- Put rules and limits in a sub-point.
- Keep the main line under 10 words.
- **Break each item onto its own line, with a short explanation, only when its logic isn't obvious** (e.g. a Match dropdown with All/Any: **All** — every condition must match / **Any** — at least one must match). Skip the explanation — and skip breaking it out at all — when the screenshot already makes it obvious (e.g. a **Text** or **Color** field needs no line of its own).
- **If a list has more than 3 items, group them onto one line** instead of breaking each one out (e.g. "Set **Columns**, **Rows**, **Space between cards**, and **Card style**" rather than 4 separate lines) — unless one of those items needs its own explanation, in which case pull just that one out onto its own line and group the rest.
- Skip text the screenshot already shows.

**4. UI labels and page numbers**
- Bold the exact UI labels (e.g. **Browse files**).
- Put page numbers only in the Help Center **Page #** column.

**5. Steps table**
- **Steps (N)** in the column header is the number of steps in this table.
- One row per step, each with its own screenshot (not one shared screenshot for the whole table).
- Sub-options go as indented bullets under the step, not as separate rows.
- Add a description only when the step name doesn't explain itself.

### B. Screenshot

**1. Style**
- Highlight in blue `#2563EB`.
- Use a blue circle badge with a white number and white 2px outline.
- Draw a rounded box around each field.

**2. Numbering**
- Box the "Where to see & edit" image, with no number.
- Number each feature to match its table row.
- Number badges top to bottom, as they appear on screen.
- Give the same number to controls that do the same action.

**3. Combining images**
- Join screens in a flow with a blue arrow.
- Put two places side by side with a grey dashed divider.
- Use the blue labels as the caption, with no extra caption.
- Keep image labels short (e.g. "Fix: redraw blocks").

**4. Errors**
- Mark errors in red and fixes in blue.

**5. Privacy and files**
- Blur store names, URLs, themes, folders, and the app's internal name.
- Keep each image under 200 KB.
- Name files in lowercase with hyphens (e.g. `filters-callouts.png`).
