# noktalabs-web

Nokta Labs company site, www.nokta-labs.com (GitHub Pages, `CNAME`). Plain HTML and CSS, no
build step, GitHub Pages from the repo root of `main`.

| File | What |
| --- | --- |
| `index.html` | The page. Copy from `strategy/site-copy.md` in the monorepo. |
| `404.html` | Shown for unknown paths. |
| `tokens.css` | Copy of `design/tokens.css`. Do not edit here. |
| `styles.css` | Layout and the `@font-face` rules. Uses only the `--nl-*` tokens. Rules: `design/DESIGN.md`. |
| `fonts/`, `LICENSES/` | Instrument Sans, self-hosted, SIL OFL 1.1. |
| `favicon.*`, `favicon-96.png`, `apple-touch-icon.png`, `icon-512.png` | Copies of `design/logos/favicon/`. |
| `media/` | Wordmark (copy of `design/logos/nokta-labs-wordmark.svg`) and the `og.png` link preview. |

Run locally: `python3 -m http.server 8080`

Update design files (from the monorepo root):

    cp design/tokens.css web/noktalabs-web/tokens.css
    cp design/logos/favicon/* web/noktalabs-web/
    cp design/logos/nokta-labs-wordmark.svg web/noktalabs-web/media/
