# Screenshots

Images used by the public README live in this folder.

**The six primary public screenshots are captured.** They were taken from a dedicated demo vault,
not from a real one. See [SHOTLIST.md](SHOTLIST.md) for what each one shows and what is still
optional.

| File | Shows |
|---|---|
| `dashboard-dark-en.png` | Dashboard, dark theme, English |
| `search-ar-sqlalchemy.png` | Arabic + English search with relevance highlighting |
| `command-palette.png` | Ctrl+K command palette with search results and Quick Capture |
| `inbox-mixed.png` | Inbox with unfiled notes and the file-into controls |
| `dashboard-dark-ar.png` | Arabic RTL interface, dark theme |
| `dashboard-light-ar.png` | Arabic RTL interface, light theme |

---

## Safety checklist

Run through this **before adding any file here** — it applies to every future screenshot too, not
just the first six. Every screenshot must come from a clean demo vault, never from a real one.

### The vault in the shot

- [ ] It is the **demo vault**, not your real one — no real project, note, area, prompt, or resource content
- [ ] No file paths, folder names, or anything containing a Windows username
- [ ] No email addresses
- [ ] No real URLs pointing at private repositories or internal sites

### The AI surfaces

- [ ] The AI settings page is **not** in the shot — it shows provider configuration and API-key state
- [ ] No AI preview or output panel containing real content
- [ ] If AI appears at all, it shows the default disabled state

### Everything around the window

- [ ] No taskbar, no system tray, no notifications from other applications
- [ ] No other application windows visible behind or beside it
- [ ] No browser tabs, bookmarks, or profile avatars
- [ ] Nothing identifying the machine or the account

### The image itself

- [ ] Cropped to the application window
- [ ] PNG, readable at normal zoom
- [ ] Filename matches the one in [SHOTLIST.md](SHOTLIST.md)
- [ ] Opened and looked at once more, at full size, before committing

---

## After adding a screenshot

Replace the matching row in the root `README.md` screenshots table with the image, for example:

```markdown
### Dashboard
![Ayman Vault dashboard](screenshots/dashboard.png)
```

The README contains a comment with this same snippet next to the table.
