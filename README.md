# noktalabs-web

Nokta Labs company site, www.noktalabs.com (GitHub Pages, `CNAME`). Plain HTML and CSS, no
build step, GitHub Pages from the repo root of `main`.

| File | What |
| --- | --- |
| `index.html` | The page. Copy from `strategy/site-copy.md` in the monorepo. |
| `404.html` | Shown for unknown paths. |
| `tokens.css` | Placeholder tokens; replace with a copy of `design/tokens.css` when it lands. |
| `styles.css` | Layout. Uses only the `--nl-*` tokens. |
| `favicon.svg`, `media/og.png` | Placeholders until `design/logos/` lands. |

Run locally: `python3 -m http.server 8080`
