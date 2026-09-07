# JaneeshBansal.github.io

Personal academic website for Janeesh Kaur Bansal, built on the [Researcher](https://github.com/ankitsultana/researcher) Jekyll theme.

## Structure

* `_config.yml` — site title, nav, and footer settings.
* `index.md`, `research.md`, `skills.md`, `cv.md`, `beyond-research.md` — page content, each a plain markdown file with `layout: default`.
* `_layouts/default.html` — page shell (nav, footer, meta tags).
* `_sass/`, `css/main.scss` — styling. Accent colour is set in `_sass/vars.scss`.

To add a new page, drop a markdown file in the repo root with `layout: default` and add it to `nav` in `_config.yml`.

## Local development

```
bundle install
bundle exec jekyll serve
```

## Deployment

Pushes to `master` are built and deployed automatically via the GitHub Actions workflow in `.github/workflows/pages.yml`.
