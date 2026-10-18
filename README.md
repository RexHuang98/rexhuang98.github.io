# rexhuang98.github.io

Personal academic website of Yunqi Huang (黄允祺): https://rexhuang98.github.io/

Built with [Jekyll](https://jekyllrb.com/) and the [al-folio](https://github.com/alshedivat/al-folio) theme (MIT license, see `LICENSE`).
Pushing to `main` deploys the site via GitHub Actions (`.github/workflows/deploy.yml`).

## Where things live

| What               | File                                              |
| ------------------ | ------------------------------------------------- |
| Bio / home page    | `_pages/about.md`                                 |
| Profile photo      | `assets/img/prof_pic.jpg`                         |
| News items         | `_news/*.md` (one file per item)                  |
| Publications       | `_bibliography/papers.bib` (`selected={true}` shows on home page) |
| Email, Scholar, CV | `_data/socials.yml`, CV file at `assets/pdf/cv_pdf.pdf` |
| Co-author links    | `_data/coauthors.yml`                             |
| Site settings      | `_config.yml`                                     |

Google Scholar citation counts in `_data/citations.yml` are refreshed by `.github/workflows/update-citations.yml`.

## Local preview

```bash
bundle install
bundle exec jekyll serve   # http://localhost:4000
```
