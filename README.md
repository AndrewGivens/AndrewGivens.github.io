# Andrew Givens' website

This repository contains the source files for my personal website, published with GitHub Pages and built with [Quarto](https://quarto.org/).

**Visit the live website:** [andrewgivens.github.io](https://andrewgivens.github.io/)

## Featured projects

- [D&D challenge-rating blog post](https://andrewgivens.github.io/dnd-challenge-ratings.html) · [code repository](https://github.com/AndrewGivens/dnd-challenge-rating-analysis)
- [NFL Combine project site](https://andrewgivens.github.io/stat330-nfl-combine/) · [code repository](https://github.com/AndrewGivens/stat330-nfl-combine)  
  **Contributors:** Andrew Givens and Andrew Walker.
- [STAT 386 Pandas Foundations repository](https://github.com/AndrewGivens/stat-386-pandas-foundations)

See the [Projects page](https://andrewgivens.github.io/projects.html) for descriptions and more links.

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
