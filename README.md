# tangomike.app

The home page for Graham D.'s iPhone apps: Scales, Shoebox and Lovely Mail. Each app has its own site; this page
links out to them.

- `site/`: the static site. No build step, no scripts, strict CSP (`site/_headers`).
- `.github/workflows/site.yml`: deploys `site/` to the Cloudflare Pages project `tangomike-home` on pushes to main.

| App | Site | Source |
|---|---|---|
| Scales | scales.tangomike.app | grahamdeno/scales (`site/`) |
| Shoebox | inmyshoebox.com | grahamdeno/Shoebox |
| Lovely Mail | lovely.tangomike.app | grahamdeno/reelmail (`site/`) |

Support for every app: support@tangomike.app.
