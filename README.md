# Janeesh Kaur Bansal

Personal academic website for Janeesh Kaur Bansal, a computational biologist and PhD researcher working on malaria genomics.

The site is based on the [Researcher Jekyll theme](https://github.com/ankitsultana/researcher), a clean, single-column, monospace resume template. The design and structure have been adapted for this research profile and are deployed with GitHub Pages.

Live site: [janeeshbansal.github.io](https://janeeshbansal.github.io/)

## Site structure

- `index.md` - homepage and research overview
- `publications.md` - research themes and publication information
- `teaching.md` - teaching experience and modules
- `conferences-and-courses.md` - conferences and training
- `resume.md` - education, skills, and experience
- `contact.md` - contact and professional links
- `_config.yml` - site title, navigation, profile image, and footer settings
- `_sass/` and `css/` - theme styling
- `images/` - profile and site images
- `files/` - downloadable research files and papers

## Editing the site

Most content is written in Markdown. Edit the relevant page, commit the changes, and push them to the `master` branch:

```bash
git add .
git commit -m "Update website"
git push origin master
```

GitHub Pages will rebuild the site automatically after the push.

To update the navigation, edit the `nav` section in `_config.yml`. To change the link color, update `$accent` in `_sass/vars.scss`. The profile image is configured with `profile_picture` in `_config.yml`.

## Run locally

Install Ruby, Bundler, and the GitHub Pages dependencies, then run:

```bash
bundle install
bundle exec jekyll serve
```

Open [http://localhost:4000](http://localhost:4000) to preview the site. Jekyll will rebuild the site as files change.

## Original theme

- Theme: [ankitsultana/researcher](https://github.com/ankitsultana/researcher)
- Demo: [ankitsultana.com/researcher](http://ankitsultana.com/researcher)
- Original theme license: [GNU GPL v3](https://github.com/bk2dcradle/researcher/blob/gh-pages/LICENSE)
