# lunodzo.github.io

Personal academic website of Lunodzo J. Mwinuka, live at <https://lunodzo.github.io>.
Built with Jekyll on the [Academic Pages](https://github.com/academicpages/academicpages.github.io) template.

## Updating content

| What | Where |
|------|-------|
| Publications (DOI / arXiv / article links are generated automatically) | `_data/publications.yml` |
| Projects | `_data/projects.yml` |
| Home page | `_pages/about.html` |
| Teaching | `_pages/teaching.html` |
| News posts | `_posts/YYYY-MM-DD-title.md` |
| Sidebar profile, links, photo | `_config.yml` (`author:`), photo in `images/` |
| Menu | `_data/navigation.yml` |
| Styling | `_sass/_custom.scss` |

## Run locally

```bash
bundle install
bundle exec jekyll serve -l -H localhost
```
