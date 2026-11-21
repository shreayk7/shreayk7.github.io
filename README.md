# Shreay Kacheria: portfolio

My portfolio site: business analytics at Purdue, looking for data analyst roles.
Live at **https://shreayk7.github.io**

Plain HTML and CSS in one folder. No framework, no build step, no trackers, no cookies.
Edit a file on GitHub (pencil icon), commit, and the site updates within a few minutes.

## What's where

| File | What it is |
|---|---|
| `index.html` | Home: intro, four case studies, contact |
| `about.html` | Story, a to-scale timeline, experience, education, skills, recognition |
| `cloud-migration.html`, `ai-in-education.html`, `bank-credit.html`, `logistics-forecasting.html` | One page per case study |
| `404.html` | Shown for any address that doesn't exist |
| `site.css` | All styles. Colors and sizes are at the top, under `:root` |
| `favicon.svg`, `favicon-32.png`, `apple-touch-icon.png` | Browser and phone icons |
| `og-card.png` | The preview image shown when the link is shared |

## Add the headshot

1. Upload the photo to this repo as `shreay.jpg` (portrait, about 800 × 1000 px).
2. In `index.html` and `about.html`, find the comment that starts with `Photo:` and delete the `<!--` and `-->` around the `<figure>` line.
3. In the same two files, add `has-photo` to the section's class: `class="hero has-photo"` on the home page and `class="page-head about-intro has-photo"` on the About page.

The photo shows in black and white with a yellow block behind it. To keep it in color, delete the `filter:` line under `.portrait img` in `site.css`.

## The "today" line

The yellow line on the About page timeline moves to the current date by itself (a short script at the bottom of `about.html`). Without JavaScript it stays at November 2026.

## Design notes

- **Black, white and one yellow.** Yellow works like a highlighter: it marks results, the page you're on, and today on the timeline. Mumbai's taxis are black and yellow; Purdue's colors are black and gold.
- **One typeface.** Archivo, using its width axis: wide for names and headings, condensed for numbers.
- **Every number is real.** Figures come from my own work. Charts are drawn only from those numbers, and diagrams that show a method or setup say so in their captions.

## Credits and license

- Written from scratch, not from a template, so there is no template author to credit.
- Typeface: [Archivo](https://github.com/Omnibus-Type/Archivo) by Omnibus-Type, SIL Open Font License 1.1, served by [jsDelivr](https://www.jsdelivr.com/) from the [Fontsource](https://fontsource.org/fonts/archivo) package.
- Code (HTML structure, CSS, script): MIT, see `LICENSE`.
- Text, photos and project content: © 2026 Shreay Kacheria, all rights reserved.
