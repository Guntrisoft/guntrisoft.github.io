# guntrisoft.github.io
Peter Guntrip's CV

[Website](https://guntrisoft.github.io)

## Project structure (quick orientation)

- `_config.yml` stores site-wide metadata (name, title, contact links) that templates render.
- `index.md` contains the profile narrative and highlights shown in the main content area.
- `_layouts/default.html` is the top-level page layout that assembles header, profile, experience, education, and references sections.
- `_includes/` contains reusable partials:
  - section partials such as `contacts.html`, `profile.html`, `experience.html`, `education.html`, `references.html`
  - many role-specific entries under `_includes/experience/`
  - SVG symbol definitions under `_includes/svg/`
  - `styles.css` for all styling, inlined via `_includes/head.html`

## Local development

This is a Jekyll-style static site. If you have Ruby/Jekyll installed, a typical workflow is:

1. Run `bundle install`
2. Run `bundle exec jekyll serve`
3. Open the local URL printed by Jekyll (usually `http://127.0.0.1:4000`)
