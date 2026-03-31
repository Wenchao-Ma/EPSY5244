# Survey Data Analysis Book

This repository contains a Quarto book for EPSY 5244 survey data analysis.

## Structure

- `index.qmd`: Landing page
- `01-intro-to-r.qmd`: Intro to R
- `02-post-survey-data-preparation.qmd`: Post-survey data preparation
- `03-psychometric-analysis.qmd`: Placeholder chapter
- `04-statistical-analysis.qmd`: Placeholder chapter
- `05-open-ended-question-analysis.qmd`: Placeholder chapter

## Local Build

1. Install Quarto: <https://quarto.org/docs/get-started/>
2. In this folder, run:

```bash
quarto render
```

The rendered book is written to `_book/`.

## Publish to GitHub Pages

1. Create a new GitHub repository.
2. Push this folder to the `main` branch.
3. In GitHub, go to **Settings > Pages**.
4. Set **Build and deployment** to **GitHub Actions**.
5. Push to `main` (or run the workflow manually).

The workflow file is in `.github/workflows/publish.yml`.
