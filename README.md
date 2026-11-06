# Andrew Givens' website

This repository contains the source files for my personal website, published with GitHub Pages and built with [Quarto](https://quarto.org/).

## Site pages

- `index.qmd` is the homepage.
- `projects.qmd` lists selected projects and collaborators.
- `dnd-challenge-ratings.qmd` is the D&D challenge-rating project write-up.
- `tutorial.qmd` is a tutorial about using pull requests when working alone.
- `about.qmd` is the About page.
- `docs/` contains the rendered site files.

## Rebuild the site

Install Quarto, then run this command from the repository folder:

```bash
quarto render
```

Commit both the Quarto source files and the updated `docs/` output when publishing a change.
