# pawsby-website

Static site for [pawsby.app](https://pawsby.app), served by GitHub Pages (`CNAME`).

| Path | Page |
|---|---|
| `/` | Landing page — features, pricing, FAQ, roadmap, downloads |
| `/help/` | User guide |
| `/subscribe/` | Plan picker → Creem checkout |
| `/checkout/success/` | Post-checkout return page (noindex) |
| `/calendar/connected/` | OAuth return page that hands the calendar connection back to the app (noindex) |
| `/privacy/`, `/terms/` | Legal |
| `/delete-account/` | Account deletion request |
| `404.html` | Served by GitHub Pages for unknown paths |

Shared styles live in `css/pawsby.css`; pages add small page-local `<style>` blocks.
The pricing lists in `index.html` and `subscribe/index.html` are separate copies — update both.
Downloads link to `github.com/dlstjdj/pawsby-releases/releases/latest`.
