# Lumadose website

The public website for Lumadose, a private GLP-1 medication log for iPhone. GitHub Pages serves it at https://manish-raana.github.io/lumadose/.

| Page | URL |
|---|---|
| Home | https://manish-raana.github.io/lumadose/ |
| Privacy policy | https://manish-raana.github.io/lumadose/privacy/ |
| Support | https://manish-raana.github.io/lumadose/support/ |

The app links to the privacy policy and support pages, and the App Store listing uses the same two URLs, so keep those paths as they are.

## How it's built
- Plain HTML with one stylesheet, `assets/style.css`, in the app's colours, with light and dark modes.
- No scripts, cookies or analytics, and nothing loaded from other sites.
- `.nojekyll` tells Pages to serve the files exactly as they are.

## Publishing
Pages serves the `main` branch from the root. Push to `main` and the site updates within a few minutes.

These files are copied from the `site/` folder of the app's own repository, which also keeps the privacy policy in Markdown. Change both together.
