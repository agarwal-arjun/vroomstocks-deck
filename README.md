# VroomStocks — Pitch Deck

An HTML presentation covering VroomStocks: customer journeys, product, early traction,
business model, roadmap, market and team, with a supporting appendix.

**Live deck:** https://agarwal-arjun.github.io/vroomstocks-deck/

**Product:** https://vroomstocks.com

## Contents

| # | Slide |
|---|---|
| 1 | Title |
| 2 | Vision — democratise investment analysis |
| 3 | The problem |
| 4 | Two customer journeys — stocks and Indian mutual funds |
| 5 | Product — discover, understand, value, monitor and test |
| 6 | Stock journey — screener, Visual comparisons and DCF |
| 7 | Watchlist, sample weekly email digest and live in-app notification |
| 8 | Full capability overview — 12 illustrated feature groups |
| 9 | Early traction — founding date and reported users |
| 10 | Business model — free core, paid capacity, enterprise discovery |
| 11 | Roadmap — newsletters & alert expansion, broker integration, VroomAI, algo trading, portfolio import/analysis/insights, enterprise APIs |
| 12 | Market — illustrative retail TAM / SAM / SOM scenarios |
| 13 | Competitive positioning — connected workflow at accessible pricing |
| 14 | Who we are — Arjun Agarwal & Krati Mittal |
| 15 | The ask — design-partner pilots & join us |
| 16 | Close |
| 17 | Appendix — full product screenshot gallery |
| 18 | Appendix — sourced competitor comparison |
| 19 | Appendix — data platform and diligence |

## Usage

Open `index.html` in any browser — no build step or runtime dependencies are needed.
Keep `assets/screenshots` alongside it; each gallery thumbnail opens its capture in
an in-page popup. Close it with Escape, the Close button, or a click outside the popup.
Keyboard focus stays inside the popup and returns to the thumbnail on close; deck
keyboard and swipe navigation pause while it is open.

| Key | Action |
|---|---|
| `←` `→` / `Space` | Previous / next slide |
| `Home` / `End` | First / last slide |
| `T` | Toggle light / dark theme |
| `P` | Print (one slide per page → PDF) |

Also supports click-to-jump dots, touch swipe on mobile, and deep links via `#<slide-number>`
(e.g. `index.html#12` opens the market slide). Numeric slide links follow the
current order; the competitor comparison is now `#18`, rather than `#10`.

## Product screenshots

The gallery contains 11 captures from the signed-in live application in October 2026,
plus a Visual comparison screenshot from the product's official guide. Slide 6
uses larger, clickable images for the stock research journey. Slide 7 pairs a
watchlist with a user-supplied weekly email digest and a freshly captured in-app
notification. These are separate examples, not a matched event sequence.

`assets/screenshots/email-digest-sample.png` is the unmodified user-supplied screenshot
of a weekly digest dated 5 October 2026, showing 14 updates across one alert.
It is not a newly generated or independently delivery-tested email. It is embedded
on slide 7 and opens in the same screenshot popup as website captures.

`assets/screenshots/notifications.png` shows the live top-right notification drawer in light theme,
captured on 11 October 2026 after the user signed in directly in a temporary browser.
The user's original dark-theme preference was restored after capture.
It displays a price-move notification. Only the empty lower portion of the drawer
was cropped; its content and colours were not altered. No credentials or authentication
state were saved by the capture script. The notification bell is hidden in the
signed-out, read-only workspace.

Slide 8 adds a full capability overview with 12 website/official-guide screenshots
and descriptions covering workspace, screeners, financials and ratios, Visual,
valuation, charts, options, funds, AI, earnings/filings, simulation and monitoring.
Each image illustrates its feature group rather than proving every listed function.
ProCharts is labelled beta; broker execution and the broader VroomAI roadmap are
not presented as shipped.

`assets/screenshots/visual-comparison.png` is the unmodified image from
https://vroomstocks.com/static/img/guide/24-visual.png, linked by
https://vroomstocks.com/learn/getting-started and retrieved on 11 October 2026.
It shows NVDA, AMD and AVGO financial-ratio comparisons. It is labelled as an official
guide capture, not a freshly captured signed-in session.

The options image is a US AAPL example, not an NSE chain.
Fundamental charts could not be captured successfully because the live application
reported a market-mismatch error; no mockup was substituted.

## Product claims and scope

The narrative reflects the browser-rendered homepage, pricing page, getting-started
guide, options page and alerts page reviewed on 11 October 2026. This public-site
review is not a new end-to-end test of every authenticated feature.

- https://vroomstocks.com
- https://vroomstocks.com/pricing
- https://vroomstocks.com/learn/getting-started
- https://vroomstocks.com/research/options-charts
- https://vroomstocks.com/research/alerts

Financial ratios, Visual multi-company comparisons, segments/KPIs, period selection,
metric templates and saved views are called out explicitly. Q-Score is described as
quality less valuation expensiveness, not as a forecast of returns. Indian options
availability is qualified, and the deck distinguishes research/paper trading from
future broker execution.

Current AI summaries are not the planned VroomAI agent. Current mutual-fund CAS import
is not the broader cross-asset portfolio roadmap. Enterprise APIs and embedded research
are design-partner proposals, subject to rights, service readiness and commercial
validation. Infrastructure statements are team descriptions, not independent audit
results or absolute reliability guarantees.

## Notes on the numbers

Slide 9 reports the founder-provided May 2026 founding date and approximately 4,000
users as of 11 October 2026. The user-count definition was not supplied: do not relabel
it as registered, active or paying users. Activation, retention, paid conversion and
revenue are measurement needs, not invented results.

Slide 10 describes one-time access: ₹99/30 days or ₹999/365 days, GST included, with
no automatic renewal. The paid tier expands limits rather than locking the whole
product behind payment. Trial terms are deliberately omitted: the public pricing
page contains conflicting free-month and seven-day ₹1 descriptions. Published metric
counts also vary, so the deck avoids a blanket 50+/75+ claim.

Slide 12 is an explicitly hypothetical customer-based sizing model, not an official
market estimate. It replaces the earlier account/folio aggregation:

| Scenario | Assumed unique purchasers | Annual price | Gross collections including GST |
|---|---|---|---|
| TAM ceiling | 10 crore | ₹999 | ₹9,990 crore |
| SAM hypothesis | 1 crore | ₹999 | ₹999 crore |
| SOM scale case | 2–4 lakh | ₹999 | ₹19.98–39.96 crore |

The customer pools are unvalidated planning assumptions; no external source is claimed
for them. SAM is 10% of the assumed TAM; SOM is 2–4% of the assumed SAM. Each assumes
one annual-plan purchase per customer, without a price increase. These are gross
collections before refunds and operating costs, not recognised revenue or ARR.
No 3-year delivery forecast or enterprise revenue is included. Enterprise upside
requires separate paid-pilot, contract-value, licensing and cost evidence.
Unverified demographic statistics and analyst-to-investor ratios have been removed
from the problem slide instead of being presented as current sourced facts.

Slide 18 compares coverage, pricing, specific research/AI and portfolio/strategy
features, founding/launch milestones, funding, revenue and Users#. Source links and
expandable methodology are on-slide, checked 11 October 2026. On small screens, the
comparison table scrolls horizontally; focus it to use arrow keys without changing slides.

Funding figures are named historical rounds, not cumulative totals. Revenue includes
the reporting year and entity. Users# uses platform-stated user counts, not active-user
metrics: Tickertape states 6m+ "trusted users" and TradingView states 100m "traders".
These claims were observed on 11 October 2026; their definitions are not equivalent.
`NV` means not verified in the cited public sources, not zero or necessarily undisclosed.
VroomStocks' May 2026 founding date and ~4K users were founder-provided on 11 October
2026, as was the updated company filings, earnings calendar and earnings transcripts
feature description. Funding and revenue were not provided. Founding years, product launches
and rebrands are distinguished where known; Tickertape's conflicting histories are noted.
Pricing is not a like-for-like entitlement comparison: Trendlyne uses an official
help-page offer (checkout inaccessible), Fiscal.ai uses a disclosed affiliate's
September 2026 review (official page inaccessible), and TradingView is an India offer.
No traffic is substituted for user counts, and no estimated revenue or parent-company
metrics are substituted for standalone revenue.
