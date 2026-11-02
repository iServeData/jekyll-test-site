# jekyll-test-site

A small [Jekyll](https://jekyllrb.com/) site for learning GitHub Pages: one default layout, a
navigation include built from each page's `nav_order`, a Home page and an About page. GitHub Pages
builds it from `main` and serves it under `/jekyll-test-site`.

## Files

| File | What it does |
| --- | --- |
| `_config.yml` | Site title, description, `baseurl` and `url` |
| `_layouts/default.html` | The page frame every page uses |
| `_includes/nav.html` | Navigation links, sorted by `nav_order` |
| `index.html`, `about.html` | The pages |

## Run it locally

```sh
gem install bundler jekyll
jekyll serve --baseurl ""      # then open http://127.0.0.1:4000/
```

See [CONTRIBUTING.md](CONTRIBUTING.md) to suggest changes. MIT licensed, see [LICENSE](LICENSE).
