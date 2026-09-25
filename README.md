# Federal Recompete Capture Brief

Static offer page for a paid research product aimed at federal capture teams: a brief of federal contract awards that may be coming up for recompete, with every award cited back to USAspending.gov.

**Live site:** https://mattbusel.github.io/federal-recompete-capture-brief/ (the root page is a placeholder; offer pages sit under per-audience paths and are shared by direct link)

## What the offer page shows

- A free sample of three real Department of Defense awards (NAICS 334111), each with award ID, agency, value and a link to its USAspending API record.
- One paid tier: a 10-award capture brief as PDF plus CSV with source links, $49 via Gumroad checkout.
- A plain caveat on the page: recompete status still needs verification.

## What is in this repo

| Path | What it is |
|---|---|
| `index.html` | Placeholder root: "use the private link you were sent" |
| `federal-capture-teams/index.html` | The offer page for federal capture teams |
| `.nojekyll` | Tells GitHub Pages to serve the files as-is |

Plain HTML with inline CSS. The page includes a small click-tracking hook (`track()`), but its endpoint is empty, so it sends nothing.

## Deploy

GitHub Pages serves the `gh-pages` branch from the root. Push to `gh-pages` and the site redeploys. To add a page for another audience, copy `federal-capture-teams/` to a new folder and change the sample and copy.
