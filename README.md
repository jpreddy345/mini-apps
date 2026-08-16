# Mini Apps

A polished, privacy-conscious set of static dashboards for GitHub Pages.

## Included

- `index.html` — product-style launcher and privacy overview
- `wire.html` — technology news reader with search, filters, saved stories, cached fallback, and refresh status
- `ticker.html` — public quote watchlist with market status, mover summaries, sorting, cached fallback, and local-only preferences
- `alphaveda.html` — high-beta NSE/BSE portfolio guardrail engine: market-regime data grounding, position-sizing and drawdown circuit-breakers, invalidation/risk-reward checks, STCG/LTCG-aware tax estimates, and a structured JSON action plan. Advisory only — it never places, routes, or executes an order.

## Publish

Upload the HTML files to the repository root. GitHub Pages will use `index.html` as the homepage.

Recommended cleanup after confirming the new pages work:

- delete `News wire.html`
- delete `ticker app.html`

## Privacy

No brokerage credentials, balances, or transaction records are requested. Saved stories, watchlists, manually entered portfolio positions, and appearance settings remain in the browser's local storage and are never transmitted anywhere.

## Data note

`wire.html` and `ticker.html` depend on third-party public RSS and quote endpoints. Those services can be delayed, rate-limited, or temporarily unavailable, so both use cached browser data as a fallback when possible. `alphaveda.html` fetches nothing — all prices, macro inputs, and holdings are entered by hand, so its output is only as fresh and accurate as what you type in.
