# Academic Coaching — Best Practices Playbook

A single-page, interactive playbook for the Academic Coaching team. It collects the principles, scenario plays, tools, and troubleshooting steps that coaches use day to day.

**Live site:** https://fiorellamendez.github.io/coaching-playbook
*(adjust if your repo is named something else)*

## What's inside

- **Section A — Core Principles** — the five beliefs that underpin every coaching session.
- **Section B — Scenario Plays** — the 10 situations coaches face most, each with The Situation / What Good Coaches Do / Sample Language / Red Flags.
- **Section C — Tools & Resources** — a guiding-questions toolkit and a session-flow checklist. (App-specific cards coming later.)
- **Section D — Troubleshooting Quick Reference** — a one-table summary for mid-session.

## How it's built

The entire playbook is one self-contained file, `index.html`. React and Babel load from a CDN, so there is **no build step and no tooling** — the page just runs in the browser. Hosting is GitHub Pages (branch `main`, root folder).

> Note: this site is **public** (anyone with the link can view it). It contains coaching guidance and unattributed coach quotes — no student data. A `noindex` tag keeps it out of search results, but it is not access-restricted.

## How to update it

1. Get the new `index.html` (Fiorella generates this with Claude).
2. Replace the file in this repo:
   - **Web:** Add file → Upload files → drop in the new `index.html` → Commit changes, **or**
   - **Terminal:**
     ```bash
     cd ~/Desktop/coaching-playbook
     git add index.html && git commit -m "Update playbook" && git push
     ```
3. Wait 1–2 minutes for GitHub Pages to rebuild, then hard-refresh with **Cmd+Shift+R**.

The URL never changes, so bookmarks stay valid.

## Files

- `index.html` — the playbook (this is the only file the site needs).
- `README.md` — this file.

## Maintainer

Fiorella Mendez
