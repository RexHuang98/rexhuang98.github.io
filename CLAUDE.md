# rexhuang98.github.io

Personal academic site of Yunqi Huang (UCL PhD, soft robotics / EIT tactile skin), built on the al-folio Jekyll theme.
Template demo content (blog, projects, books, teaching, CV page) has been removed; live pages are About (`_pages/about.md`), Publications and News.
See `README.md` for where content lives.

- Deploy: push to `main` → `.github/workflows/deploy.yml` builds and publishes to `gh-pages`.
- Local build: `bundle exec jekyll build` (ImageMagick is installed; Docker is not).
- News item: new file `_news/announcement_N.md` with `layout: post`, `date:`, `inline: true`, `related_posts: false`.
- Publications: `_bibliography/papers.bib`; `scholar.last_name/first_name` in `_config.yml` bolds the owner's name.
- Theme code (`_layouts`, `_includes`, `_sass`, `_plugins`, `assets/js`) is unchanged al-folio; avoid editing unless needed.
- Format with `npx prettier . --write` before committing.
