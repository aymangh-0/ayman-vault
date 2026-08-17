# Screenshot shot list

A practical plan for the public README images. Read the safety checklist in
[README.md](README.md) first — it is the part that matters.

All shots are taken from a **clean demo vault**, never from a real one.

> **Status: the six primary shots are done and wired into the public README.**
>
> | Shot | File | Status |
> |---|---|---|
> | Dashboard | `dashboard-dark-en.png` | ✅ captured |
> | Search with Arabic highlighting | `search-ar-sqlalchemy.png` | ✅ captured |
> | Command palette + Quick Capture | `command-palette.png` | ✅ captured |
> | Inbox | `inbox-mixed.png` | ✅ captured |
> | Arabic RTL | `dashboard-dark-ar.png` | ✅ captured |
> | Arabic RTL, light theme | `dashboard-light-ar.png` | ✅ captured |
> | Projects | — | optional, not captured |
> | Notes and Areas | — | optional, not captured |
>
> The remaining entries below are kept as **optional future shots**. The demo-content guidance and
> the "must never appear" rules still apply to anything added later.

---

## Demo content to create first

Small and believable beats large and impressive. A vault that is obviously staged looks worse than
a modest one. Aim for roughly this, all of it invented:

| Kind | How many | Suggested content |
|---|---|---|
| Projects | 3 | one Active with a tech stack and a short description, one Paused, one Completed |
| Areas | 2 | e.g. *Data Analysis* and *Backend Development* |
| Notes | 5–6 | two linked to a project, two linked to an area, two left unfiled for the Inbox shot |
| Prompts | 2 | one general, one linked to a project |
| Resources | 2 | one URL, one folder reference |
| Reminders | 1–2 | one upcoming, optionally one overdue |

**One note must be written in Arabic** — it carries the search and RTL shots. Something ordinary
and technical works best, for example a note about ‏قاعدة البيانات‏ that also mentions an English
term like `SQLAlchemy`, so a single search can show mixed-language matching.

Nothing in any of this should reference a real client, employer, or person.

---

## Shots, in capture order

Capture 1–6 in the **dark theme in English** first, since that is the default and the majority of
the README. Then re-shoot the two variants at the end.

### 1. `dashboard.png` — Dashboard
**Needs:** the demo content above, so the counts and *Recently updated* look alive.
**Shows:** the overall shape of the app in one image. This is the first thing a visitor sees.

### 2. `projects.png` — Projects
**Needs:** the three projects, with the status filter visible.
**Shows:** status and type badges, filtering, the card layout.

### 3. `notes-areas.png` — Notes and Areas
**Needs:** notes linked to both a project and an area.
**Shows:** that content is organized by relationship, not just piled into one list.
Either the Notes list showing its project/area labels, or an Area detail page with its related
notes and resources — whichever reads more clearly at README width.

### 4. `search-arabic.png` — Search with Arabic highlighting ⭐
**Needs:** the Arabic demo note. Search for the word written **without** its hamza, so the result
highlights the original spelling that includes it.
**Shows:** the single most distinctive feature — Arabic-aware matching with a highlighted snippet
and relevance ranking. Worth the extra effort to get right.
**Tip:** make sure the highlight is clearly visible in the crop; that is the whole point of the shot.

### 5. `inbox.png` — Inbox
**Needs:** the two unfiled notes.
**Shows:** the *File into Project / Area* controls, so the PARA idea is visible rather than
explained.

### 6. `command-palette.png` — Ctrl+K command palette ⭐
**Needs:** the palette open over a normal page, with a few characters typed so both search results
**and** the capture row are visible at once.
**Shows:** search and quick capture in one image. The capture row must be readable — it is what
makes this different from a search box.

### 7. `dark-light.png` — Themes
**Needs:** the same screen in both themes.
**Shows:** that the light theme is a real design, not an inverted dark one. Either two crops side
by side in one image, or split into `dark-theme.png` and `light-theme.png`.

### 8. `arabic-rtl.png` — Arabic interface ⭐
**Needs:** switch the language to Arabic in Settings, then capture a content-rich screen —
Dashboard or Notes — so the mirrored layout is obvious.
**Shows:** that Arabic is a fully mirrored interface, not translated labels on a left-to-right
layout. Check that the sidebar has moved to the right edge before capturing.

---

## Must never appear in any shot

Short version of the checklist, worth re-reading between captures:

- Real vault content of any kind
- File paths, folder names, or a Windows username
- Email addresses
- The AI settings page, any API-key field, or any AI output containing real content
- Taskbar, tray, notifications, or other application windows
- Anything identifying the machine or the account

---

## When done

1. Save each file into this folder using the exact filenames above
2. Replace the matching row in the root `README.md` table with the image
3. Look at the README rendered, at full size, before committing
