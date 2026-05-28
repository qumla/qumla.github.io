# QuMLa Homepage Editing Map

Main pages:

- Home: `_pages/about.md`
- Publications: `_pages/publications.md` and `_bibliography/papers.bib`
- Members: `_pages/members.md`
- News/Notice: `_pages/news.md` and `_news/`

Images:

- Main logo: `assets/img/qumla-full.png`
- Navbar/fav icon: `assets/img/qumla-only-logo.svg`
- Profile image placeholder: `assets/img/profile-placeholder.svg`

To use your real profile photo, add the image to `assets/img/` and update the image path in `_pages/members.md`.

Text styling:

- Markdown like `**bold**` and `*italic*` works in normal Markdown paragraphs.
- Inside raw HTML blocks such as `<div>...</div>`, use HTML tags like `<strong>bold</strong>` and `<em>italic</em>`.
- Site-wide accent color, section-heading color, and visible bold/italic styling are controlled in `_includes/header.liquid`.

Site-wide settings:

- Group name, description, footer, and deployment URL: `_config.yml`

Deployment:

- Pushing to `main` triggers `.github/workflows/deploy.yml`.
- The live site is `https://qumla.github.io`.
