# Camino Henro

Prototype of the Camino Henro website (カミノ遍路): a pilgrimage on foot from Portugal to Japan, and the essays written along the way.

Live at https://caminohenro.com

## What is here

A working prototype of the approved design: a persistent header, one washi scroll per page, the fixed road behind it, and the photograph that appears when a scroll ends. Text and figures are samples, and the page asks search engines not to index it.

| File | Purpose |
| --- | --- |
| `index.html` | The whole prototype. Every page is a view inside this one file (`#essays`, `#finances`, and so on). |
| `404.html` | Shown for addresses that do not exist. |
| `assets/` | Photographs, the crest, icons and the share image. |
| `CNAME` | Tells GitHub Pages to serve the site at caminohenro.com. |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are. |

## Updating

Change a file and commit to `main`. GitHub Pages publishes the change in about a minute.

## What comes next

The full site (separate pages, essays written in Markdown, publishing from a phone) will replace this prototype in this repository.
