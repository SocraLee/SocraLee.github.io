# SocraLee.github.io

Personal academic homepage of **Yongkang Li** — live at <https://socralee.github.io>.

Built with [Jekyll](https://jekyllrb.com/), based on the [academicpages](https://github.com/academicpages/academicpages.github.io) template (a fork of the [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) theme, © 2016 Michael Rose, released under the MIT License — see LICENSE).

## Where to edit content

- Homepage: `_pages/about.md`
- CV page: `_pages/cv.md` (PDF lives in `assets/`)
- Research projects: `_pages/research.md`
- Blog posts: `_posts/` (filenames must follow `YYYY-MM-DD-title.md`, or Jekyll will skip them)
- Publications / Talks pages: `_pages/publications.md`, `_pages/talks.md` (currently stubs; enable their links in `_data/navigation.yml` when ready)
- Site-wide settings (name, bio, avatar, social links): `_config.yml`

## Run locally

```bash
bundle install
bundle exec jekyll serve
```

Then open <http://localhost:4000>.
