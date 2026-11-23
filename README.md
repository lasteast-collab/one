# LASTEAST

A cinematic, streaming-style platform for discovering and launching apps, software and projects.

**Live site:** https://lasteast-one.netlify.app/  
**Repository:** https://github.com/lasteast-collab/one

## What's inside

Everything is in one self-contained file, `index.html`: HTML, CSS, JavaScript, the LASTEAST logo and all app artwork are embedded. There's no build step, backend or API key.

- Cinematic LASTEAST logo intro (can be skipped or turned off in Settings)
- Hero spotlight, horizontal app rows, app cards with hover previews
- Apps open full-screen inside LASTEAST, with a new-tab fallback
- Search (Ctrl + K), favorites, recently opened
- Admin mode (password protected): add, edit, reorder and delete apps and categories, choose the hero, export/import data
- Settings: theme, accent colour, intro options, JSON export/import, reset
- Data is saved in the browser (localStorage)

## Apps

| App | Category | Link |
|---|---|---|
| Lasteast Model | Design & Engineering | https://lasteast-model.netlify.app/ |
| Lasteast Pdf | AI & Technology | https://lasteast-pdf.netlify.app/ |
| Lasteast Cut | Design & Engineering | https://lasteast-cut.netlify.app/ |
| Lasteast Present | Education | https://lasteast-present.netlify.app/ |
| Lasteast Write | Education | https://lasteast-write.netlify.app/ |
| Lasteast Matrix | Education | — |
| Lasteast Partition | AI & Technology | — |

## Admin access

Visitors can browse, launch, search and favourite apps, and change their own display settings. Adding, editing and removing apps requires the admin password (profile menu → Admin login, or the "Admin" link in the footer). Only a SHA-256 hash of the password is stored in `index.html`.

Admin changes are saved in the admin's own browser. To publish them to everyone, use Export in admin mode and update `index.html`.

## Run locally

Open `index.html` in any modern browser.

## Deploy

The site is hosted on Netlify (project `lasteast-one`). Publish directory: the repository root. No build command.
