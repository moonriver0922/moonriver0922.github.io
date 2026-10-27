# Guosheng Wang — Academic Homepage

Personal academic homepage for Guosheng Wang, a Ph.D. candidate in the Department of Computing at The Hong Kong Polytechnic University.

Live site: <https://moonriver0922.github.io>

The page is static HTML and CSS. `.nojekyll` tells GitHub Pages to serve the repository root as-is from `master`, so the homepage is `index.html` rather than a Jekyll theme.

## Visual language

The layout follows a dark single-column academic page: `#222436` background, light text, a large name, and numbered publications. Body type is [Inter](https://fonts.google.com/specimen/Inter) (OFL), with IBM Plex Sans and system-ui as fallbacks. BBC Reith is not shipped.

## Local preview

From the repository root:

```bash
python3 -m http.server 8000
```

Open <http://127.0.0.1:8000/>.

## Content notes

- Visible email is obfuscated. Google Scholar and ORCID are the profiles already recorded for this site.
- No CV file is in the repository, so the header does not link to one.
- `google98c34d4d07a86a79.html` is the Google Search Console verification file.
