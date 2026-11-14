# Sangjun Han (한상준) — CV

**English:** https://sjhan91.github.io/ · **한국어:** https://sjhan91.github.io/ko/

AI Researcher at LG AI Research (Data Intelligence Lab), working on time-series foundation models (EXAONE Forecast), multimodal forecasting, physical simulators, time-series causal discovery, and symbolic music generation.

## Files

| File | Purpose |
|---|---|
| `index.html` | The CV (English). **The only file to edit** — Korean text lives in `data-ko="…"` attributes. |
| `ko/index.html` | Korean page, generated from `index.html`. Do not edit by hand. |
| `build_ko.py` | Regenerates `ko/index.html`, `cv.pdf` and `ko/cv.pdf`: run `python3 build_ko.py` after every edit to `index.html` (needs Chrome/Chromium; set `CHROME=/path` if it is not found). |
| `cv.pdf`, `ko/cv.pdf` | Generated PDFs (A4, every section expanded) downloaded by the **PDF** button. |
| `robots.txt`, `sitemap.xml` | For search engines. Update `<lastmod>` in `sitemap.xml` when the content changes. |
| `sj.han.web.jpg` | Profile photo (also used as the link-preview image). |

## Publishing (GitHub Pages)

1. Name the repository **`sjhan91.github.io`** so the site is served at the root URL above.
2. Settings → Pages → Deploy from branch → `main` / `(root)`.
3. Google Search Console → add the property `https://sjhan91.github.io/`, verify it, submit `sitemap.xml`, and use "Request indexing" for both pages.

The **PDF** button in the sidebar downloads `cv.pdf` (English) or `ko/cv.pdf` (Korean). Their layout comes from the `@media print` rules in `index.html`.
