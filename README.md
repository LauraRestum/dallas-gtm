# Dallas GTM Deck

Envision Dallas Go-to-Market strategy presentation.

- `index.html` — the deck (self-contained, ~10 MB). This is what Vercel serves at the root URL. It also carries the companion brief in its side panel.
- The two `Envision Dallas GTM Deck ... .html` files are the original exports; `index.html` is a copy of the "Print, Standalone" export (the fully self-contained one) with a small fix to hide a harmless error banner.
- `Dallas_GTM_Companion_Brief_print.html` — the print source for the companion brief (14 letter-size pages, generated from the panel content). Print it from Chrome at 8.5x11 with backgrounds on and zero margins to reproduce the PDF.
- `Dallas_GTM_Companion_Brief_v2.pdf` — the exported companion brief.

## Deploy on Vercel

Import this repo in Vercel with the **main** branch, framework preset "Other", no build command, output directory left empty. It deploys as a static site and serves `index.html`.

Last content update: July 13, 2026 — five new marketplace video examples added to the Made in America section: a new "social feed" slide (SIG Sauer, Regulator Marine, Core Products — how the campaign video gets reshared to social) and two quick-win examples (Lost Dutchman Leather, Fastway Moto) on the low-hanging fruit slide.
