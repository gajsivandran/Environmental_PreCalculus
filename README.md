# Precalculus for Environmental Science

A bookdown textbook preparing students for the *Environmental Calculus* sequence (UW QSci 291), using the same environmental-science lens.

Companion volume to:
- [Environmental Calculus](https://gajsivandran.github.io/Environmental_Calculus/)
- [Environmental Calculus 2](https://gajsivandran.github.io/Environmental_Calculus2/)

## Building the book

```r
bookdown::render_book('index.Rmd', 'bookdown::bs4_book')
```

## Status

**Work in progress — scaffolding stage.** Content chapters 1–10 are stubbed with learning objectives and section headers; full content is being drafted chapter by chapter. Workbook chapters (Part II) and full back-matter practice problems will be added in a later phase.

## Structure

- `index.Rmd` — front matter / "Why Precalculus?"
- `01`–`10-*.Rmd` — content chapters
- `20-equation-sheet.Rmd` — precalculus equation sheet
- `21`–`23-*.Rmd` — midterm and final exam review material
- `style.css`, `toc.css`, `_output.yml`, `_accessibility-head.html` — shared theme, matched to the Environmental Calculus books
