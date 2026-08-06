# Mini Apps

A polished, privacy-conscious set of static dashboards for GitHub Pages.

## Included

- `index.html` — product-style launcher and privacy overview
- `wire.html` — technology news reader with search, filters, saved stories, cached fallback, and refresh status
- `ticker.html` — public quote watchlist with market status, mover summaries, sorting, cached fallback, and local-only preferences

## Publish

Upload all three HTML files to the repository root. GitHub Pages will use `index.html` as the homepage.

Recommended cleanup after confirming the new pages work:

- delete `News wire.html`
- delete `ticker app.html`

## Privacy

No brokerage credentials, holdings, balances, or transaction records are requested. Saved stories, watchlists, and appearance settings remain in the browser's local storage.

## Data note

The apps depend on third-party public RSS and quote endpoints. Those services can be delayed, rate-limited, or temporarily unavailable. Both apps now use cached browser data as a fallback when possible.
