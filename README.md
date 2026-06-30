# jamespan.org three-site static package

This package contains three standalone static sites:

1. `jamespan.org/` — root domain / www domain hub.
2. `pro.jamespan.org/` — professional CV site for James Pan.
3. `pmm.jamespan.org/` — Page MaMa creative localization site.

Each folder includes `index.html`, `style.css`, `assets/`, `CNAME`, `robots.txt`, and `sitemap.xml`.

## DNS / GitHub Pages notes

For GitHub Pages, each subdomain is usually deployed from its own repository or Pages source with its own `CNAME` file. DNS should point:

- `jamespan.org` and `www.jamespan.org` to the root site host.
- `pro.jamespan.org` to the Professional CV site host.
- `pmm.jamespan.org` to the Page MaMa site host.

The Professional CV page is written from the uploaded Profile.pdf content and intentionally avoids embedding third-party profile widgets or external profile data.
