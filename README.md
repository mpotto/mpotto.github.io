# mpotto.github.io

Personal website of Mateus Piovezan Otto, served by GitHub Pages at
<https://mpotto.github.io>.

The site is a few hand-written HTML layouts, one stylesheet, and YAML data
files. GitHub Pages builds it with Jekyll on every push to `master`; there is
no theme and nothing to install unless you want a local preview.

## Editing content

| What | Where |
| --- | --- |
| About paragraph | `index.md` |
| Name, affiliation, email, profile links | `_config.yml`, `author` block |
| Papers (home-page highlights and the full list) | `_data/publications.yml`; `highlight: true` puts a paper on the home page |
| Teaching page | `_data/teaching.yml` |
| Top menu | `_data/navigation.yml` |
| Photo | `images/profile.jpg`, 4:5 portrait, about 880 px wide |
| Colours and type | `assets/css/style.css` |

The CV entry in the top menu points at `files/cv.pdf`; put the PDF there.
A page can use LaTeX math by adding `math: true` to its front matter.

## Local preview

```sh
bundle install
bundle exec jekyll serve
```

Then open <http://localhost:4000>.
