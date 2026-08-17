# Changelog

User-visible changes to Ayman Vault. This is a product changelog, not a commit log — it describes
what changed for you, not how it was built.

Ayman Vault is in **Early Public Preview**. Versions before 2.12.0 were private development builds
and are summarized rather than listed in detail.

---

## 2.12.0 — Early Public Preview — 2026-08-17

_The first public build._

### Added

- **Command palette (Ctrl+K)** — search your whole vault and jump to any result from anywhere in
  the app, without leaving the page you were on.
- **Quick capture** — write a thought in the command palette and save it straight to your Inbox as
  an unfiled note. Typing alone never creates anything; capture is always a deliberate action.
- **Inbox** — a single place for everything you have not filed into a project or an area yet. A
  note leaves the Inbox as soon as you give it a project or an area.
- **Archive** — move projects, areas, notes, prompts, and resources out of your active workspace
  without deleting them. Archived items keep all their content and links, disappear from lists and
  search, and can be restored at any time.
- **Areas** — ongoing topics and domains, replacing the previous "Subjects" naming throughout the
  interface.
- **Note types** — ordinary, daily, and quick-capture notes.

### Improved

- **Search is now a real search engine.** Results are ranked by relevance instead of by date, so
  the best match comes first. Matches are shown as highlighted snippets so you can see *why* a
  result matched.
- **Arabic search works properly.** Searching `احمد` now finds `أحمد`, and diacritics, tatweel,
  alef maqsura, ta marbuta and Arabic-Indic digits no longer break matching. Mixed Arabic and
  English queries work in the same search box.
- **Search-as-you-type** — partial words match as you type.
- **Sort by relevance or by date** — your choice, on the search page.
- **Rebuild search index** — a manual repair action in Settings, if search results ever look out
  of date.
- Navigation reorganized around the PARA structure: Inbox, Projects, Areas, Resources, Archive.

### Privacy and safety

- Archived content is excluded from search results and from the dashboard, not just from lists.
- Local file paths are never included in search results or in the search index.
- Backup validation extended to cover the new data, so a restored backup is checked before it is
  applied.
- Quick capture writes through the normal note path, so it gets the same validation as any other
  note.

### Known limitations

See the Known limitations section in the README. In short: Arabic word prefixes are not stripped
during search, "archived" means two different things for projects, Ctrl+K does not open while you
are typing in a text field, installers are unsigned, and there is no confirmation message after a
quick capture.

---

## Earlier development (private builds)

Ayman Vault was developed privately before this public preview. Summarized by theme:

- **Core vault** — projects, notes, prompts, resources, and areas, with linking between them,
  tagging, filtering, bulk actions, and Markdown/TXT import and export.
- **Local paths and files** — safe handling of project folders, document references on areas, and
  screenshot references on projects. Full filesystem paths are deliberately kept out of the normal
  interface.
- **AI (optional)** — local AI tasks through LM Studio, and a small number of optional cloud AI
  tasks for projects. Every AI action shows the exact content it will use before running, AI is off
  by default, and nothing runs in the background.
- **Reminders** — local reminders with overdue and upcoming views and an in-app due banner. In-app
  only; nothing runs while the application is closed.
- **Arabic and RTL** — full Arabic interface with right-to-left layout, alongside English.
- **Themes** — a dark and a light theme, with dark as the default.
- **Backup and restore** — copy your database somewhere safe, and restore from any previous backup.
