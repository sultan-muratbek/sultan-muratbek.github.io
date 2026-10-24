# sultan-muratbek.github.io

Personal academic homepage, built with Jekyll and served by GitHub Pages.

## Updating content

| What | Where |
| --- | --- |
| Bio, research experience, teaching, education | `_pages/about.md` |
| News items | `_data/news.yml` |
| Publications (home page and CV) | `_data/publications.yml` |
| CV (web page) | `_pages/cv.md` |
| CV (PDF, linked from the home page) | `files/SultanMuratbek-CV.pdf` |
| Photo | `images/sultan-muratbek.jpg` |
| Coursework | `_pages/markdown.md` |
| Section pages for students | `_teaching/*.md` |
| Top navigation | `_data/navigation.yml` |
| Name, email, social links, Google Scholar | `_config.yml` (`author:`) |
| Styling | `assets/css/academic.css` |
| Page layout | `_layouts/academic.html` |

## Local preview

```bash
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000.
