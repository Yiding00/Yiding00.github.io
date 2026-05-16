# Personal Academic Homepage

A clean single-page academic homepage built with Jekyll.

## About

This site is built with [Jekyll](https://jekyllrb.com/) and hosted on [GitHub Pages](https://pages.github.com/). It is based on the [Academic Pages](https://academicpages.github.io/) template.

## Site Structure

```
_pages/
  about.md            # Single homepage (profile + research interests + publications)

_publications/        # Publication entries (rendered on homepage)

_sass/                # SCSS styles
_includes/            # Jekyll templates and partials
_layouts/             # Page layouts
images/               # Static images (avatar, favicon, etc.)
```

## Customization

- **Profile info**: Edit `_config.yml` (author section)
- **Homepage content**: Edit `_pages/about.md`
- **Publications**: Add/edit files in `_publications/`
- **Styles**: Edit SCSS files in `_sass/`

## Local Development

```bash
bundle install
bundle exec jekyll serve -l -H localhost
```

Then open `http://localhost:4000` in your browser.

## License

This site uses the [Academic Pages](https://github.com/academicpages/academicpages.github.io) template, which is based on [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) by Michael Rose, released under the MIT License.
