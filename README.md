# AIHARA SEKAI TECHNOLOGY

Corporate website for **AIHARA SEKAI TECHNOLOGY** — an independent technology company building software, mobile applications, interactive entertainment, and IT infrastructure.

Live site: https://hasan000amin.github.io/aihara-technologies/

## Design

Japanese Futuristic Minimalism. Obsidian Black `#111318`, Graphite `#252A32`, Deep Charcoal `#191C22`, Metallic Silver `#D9DCE1`, Warm Ivory `#F4F3EF`, Steel Blue `#8C9BAA`.

## Structure

Multi-page static site with PJAX navigation (History API + fetch, no hash routing, no framework):

| File | Page |
| --- | --- |
| `index.html` | Home |
| `company.html` | Company |
| `capabilities.html` | Capabilities |
| `work.html` | Selected Works |
| `technology.html` | Technology |
| `contact.html` | Contact |

Each page is a complete standalone HTML file, so it opens directly and refreshes cleanly on GitHub Pages. Clicking the navigation fetches the target page and swaps content without a full reload; URLs stay clean (e.g. `/company`). English is the default language, with an Indonesian (ID) toggle.

## Deploy

This repo is served by GitHub Pages from the `main` branch root. No build step is required; copy the HTML files to any static host to deploy.
