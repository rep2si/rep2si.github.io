# rep2si.github.io

Generates [the rep2si website](https://rep2si.github.io/).

Any edits should happen directly in the `*.qmd` and `_quarto.yml` files. The html pages are stored in `docs`, but these should never be edited directly. Instead, they should be generated with quarto.

The pages are deployed automatically using [github pages](https://pages.github.com/).

## Typical workflow

1. Make changes to `*.qmd` and `_quarto.yml` (on a new branch, as usual).
2. Ensure you have the latest version of quarto installed: `brew install --cask quarto`
3. Generate the content of `_site` by running `quarto render`
4. Push changes and create a new pull request as usual

## Directory structure and style guide

This repo does not follow the [conventions outlined on sharepoint](https://lsecloud.sharepoint.com/sites/Methodology-Rep2SI/SitePages/Conventions.aspx), since these are not adequate for a quarto website.

## Renv

This repository does not use [renv](https://rstudio.github.io/renv/).
