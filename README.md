# Guosheng Wang — Academic Homepage

Personal academic homepage for Guosheng Wang, a Ph.D. student in the Department of Computing at The Hong Kong Polytechnic University.

Live site target:

- <https://moonriver0922.github.io>

This site is built with Jekyll and adapted from [academic-homepage](https://github.com/luost26/academic-homepage).

## Content files

- `_data/profile.yml` — name, affiliation, biography, contact details, education
- `_data/authors.yml` — author-name formatting in publication lists
- `_data/navigation.yml` — navbar pages
- `_data/display.yml` — homepage sections
- `_publications/` — one Markdown file per publication
- `assets/images/photos/portrait.jpg` — Google Scholar profile photo

## Local preview

Install Ruby, Bundler, and the dependencies in `Gemfile`, then run:

```bash
bundle install
bundle exec jekyll serve
```

Open the local URL shown by Jekyll.

## GitHub Pages deployment

This draft is configured as a user-site deployment with:

```yaml
baseurl: ""
```

For the existing `moonriver0922.github.io` repository, GitHub Pages serves the root of the `master` branch at the default GitHub Pages domain. The site does not rely on a custom-domain `CNAME` file. If the site is deployed as a project site under a different repository name, change `baseurl` in `_config.yml` to that repository path.

## Research profile

- Google Scholar: <https://scholar.google.com/citations?user=TTUUXAEAAAAJ&hl=en>
- ORCID: <https://orcid.org/0009-0004-3200-4871>
