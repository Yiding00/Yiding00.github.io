# Yiding Wang's Personal Homepage

Personal academic homepage for Yiding Wang, Ph.D. student at Xi'an Jiaotong University.

## About

This site is built with [Jekyll](https://jekyllrb.com/) and hosted on [GitHub Pages](https://pages.github.com/). It is based on the [Academic Pages](https://academicpages.github.io/) template, with a clean Google Scholar-inspired design.

## Site Structure

```
_pages/
  about.md          # Homepage (profile + research interests + selected publications)
  bio.md            # Education history
  publications.md   # Full publication list

_publications/      # Individual publication entries
  2023-EGCNTSD.md   # Neurocomputing
  2023-STDCDAE.md   # Pattern Recognition
  2024-TRDCDL.md    # IEEE TBME
  2026-IDECD-CT.md  # Medical Image Analysis

_sass/              # SCSS styles (Google Scholar-inspired theme)
_includes/          # Jekyll templates and partials
_layouts/           # Page layouts (archive, single)
images/             # Static images (avatar, favicon, etc.)
```

## Customization

- **Profile info**: Edit `_config.yml` (author section)
- **Navigation**: Edit `_data/navigation.yml`
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
