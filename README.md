# nimroddickler.github.io

Personal site powered by [Hydejack](https://hydejack.com/) and hosted on [GitHub Pages](https://pages.github.com/).

**Live site:** https://nimroddickler.github.io/

## Local development

```bash
bundle install
bundle exec jekyll serve
```

Open http://localhost:4000/

## Deploy

Pushes to `master` trigger the GitHub Actions workflow in `.github/workflows/jekyll.yml`, which builds the site and deploys to GitHub Pages.

## Customize

- Site settings: `_config.yml`
- Author profile: `_data/authors.yml`
- About page: `about.md`
- New posts: add markdown files under `_posts/` (or `example/_posts/` for the sample section)
