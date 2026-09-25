# Start here

## Day-to-day → [`my/`](my/) or the workspace file

Open **[`Derek-Career.code-workspace`](Derek-Career.code-workspace)** (File → Open Workspace from File…).

That puts **⭐ My career** first. Engine is a second root only when you need it.

| Need | Path |
|------|------|
| **CVs** | [`my/output/resumes/YY-MM-DD/`](my/output/resumes/YY-MM-DD/) — `DD-{Company}-Resume.pdf` |
| Reports | [`my/reports/`](my/reports/) |
| Tracker | [`my/data/applications.md`](my/data/applications.md) |
| Master CV | [`my/cv.md`](my/cv.md) |

## Why root still has ~200 engine files on disk

Those `*.mjs` / `templates/` / `tests/` files **are** career-ops. Physically moving them breaks scanning, PDFs, and updates.

This folder’s **Explorer hide-list** (`.vscode/settings.json`) conceals that noise so the sidebar shows `my/`, `START_HERE.md`, and a few docs — not 128 scripts.

Show everything again: Explorer → filter menu → disable exclude, or edit `.vscode/settings.json`.
