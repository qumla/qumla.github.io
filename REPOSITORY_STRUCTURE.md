# Repository Structure

This repository is intentionally kept small. It keeps only the source files needed for the QuMLa homepage and the GitHub Pages deployment.

## Main Content

- `_pages/`: top-level website pages.
  - `about.md`: home page at `/`.
  - `publications.md`: publications tab at `/publications/`.
  - `members.md`: members tab at `/members/`.
  - `news.md`: News/Notice tab at `/news/`.
  - `notice.md`: hidden compatibility page at `/notice/`.
  - `404.md`: missing-page fallback.
- `_news/`: short dated news items shown on the home page and News/Notice page.
- `_bibliography/papers.bib`: BibTeX source for the publications page.

## Site Settings

- `_config.yml`: Jekyll and al-folio configuration.
- `_data/socials.yml`: optional public contact/social links.
- `Gemfile` and `Gemfile.lock`: Ruby/Jekyll dependencies used by GitHub Actions.
- `.ruby-version`: Ruby version used for deployment.

## Assets

- `assets/img/qumla-full.png`: main QuMLa logo used on the home page.
- `assets/img/qumla-only-logo.svg`: navbar home button and site icon.
- `assets/img/profile-placeholder.svg`: temporary profile image placeholder.

Add future public images under `assets/img/`.

## Deployment

- `.github/workflows/deploy.yml`: builds the site and deploys it to GitHub Pages on every push to `main`.

The live site is served from:

<https://wookshin26.github.io>

## Codex Skills

- `.codex/skills/update-publications/SKILL.md`: reusable workflow for refreshing `_bibliography/papers.bib` and the publications tab from the Google Scholar profile.

## Documentation

- `README.md`: short project overview.
- `SITE_EDITING.md`: quick content-editing map.
- `REPOSITORY_STRUCTURE.md`: this file.
- `LICENSE`: license inherited from the al-folio starter/theme.

## Removed Template Material

The original al-folio template includes demos, tests, Docker files, preview screenshots, sample posts, sample projects, sample CV data, and contributor automation. Those were removed because they are not part of this research group homepage.
