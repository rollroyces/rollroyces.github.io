# rollroyces.github.io

Personal site for Royce — ML × bioinformatics engineer.

Hosted on GitHub Pages at <https://rollroyces.github.io>.

## Structure

- `_config.yml` — Jekyll config
- `_layouts/default.html` — custom layout (sticky header, sticky "open to roles" pill, footer)
- `assets/css/main.css` — dark-theme stylesheet (cyan + emerald + violet accents)
- `index.md` — homepage content (hero, roles, featured work, selected work, writing, contact)

The Minima theme is kept in `_config.yml` for backward compatibility but the
page uses `_layouts/default.html`, which does not depend on any Minima
includes.

## Local preview

```bash
bundle install
bundle exec jekyll serve
# → http://127.0.0.1:4000
```

## Updating

Edit `index.md` and push to `main`. GitHub Pages rebuilds automatically.