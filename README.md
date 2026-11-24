# Talks

Slide decks made with reveal.js. Each folder is one talk.

## Making a new talk

1. Copy the `template` folder and rename the copy, e.g. `2027-03-ccr-seminar`
   (year-month-short-name keeps them in order; no spaces).
2. Edit the new folder's `index.html`: each `<section>` is one slide, written in Markdown.
3. To add a slide, copy a whole `<section>` block. Colors and fonts are in `theme.css`.
4. Add the talk to the list in the top-level `index.html`.
5. Commit and push in GitHub Desktop.

Live at: `https://YOUR-USERNAME.github.io/talks/FOLDER-NAME/`

## Presenting

| Key | Does |
|---|---|
| → / Space | Next slide |
| ← | Previous slide |
| F | Fullscreen |
| S | Speaker view (notes, timer, next slide) |
| Esc / O | Overview of all slides |

## Saving as PDF

Add `?print-pdf` to the link (e.g. `.../2027-03-ccr-seminar/?print-pdf`), open it in Chrome,
then Print → Save as PDF, Layout: Landscape, Margins: None, Background graphics: on.
