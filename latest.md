# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T08:15:16Z**
- feed_generated_utc: 2026-11-04T08:15:18+00:00
- source_sha256: `90abd7d21a202abc462159c5870bad87815c73d3b96658d41d2196ddd4a4891a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1182; contracts: 1174; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T08:15+00:00, close=78404.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T08:00+00:00, close=78117.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T08:00+00:00, close=78117.1, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.036040|-33.02|-24.15|-33.97|10572124|2.77|
|AKE_USDT|0.003032|-27.04|-85.64|-27.99|11932938|6.59|
|TRUMPOFFICIAL_USDT|1.517000|-5.65|-10.13|-6.60|9410145|6.59|
|Q_USDT|0.027970|-0.70|-56.01|-1.65|7312883|7.15|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.036040|0.035540|0.036040|1.40|N|Y/Y|Y/N|N|N|
|AKE_USDT|0.003032|0.003039|0.003031|1.01|N|Y/Y|Y/Y|N|N|
|Q_USDT|0.027970|0.027690|0.027970|1.78|N|Y/Y|Y/Y|N|N|
|TRUMPOFFICIAL_USDT|1.517000|1.502000|1.517000|3.76|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T08:15:00+00:00, last15m_closed_end=2026-11-04T08:15+00:00, prior8high=0.038670, depth_time=2026-11-04T08:15:07+00:00, book20_bid_proxy_usdt=28053, book20_ask_proxy_usdt=33731, funding_indicative=0.000074, next_funding_utc=2026-11-04T12:00:00+00:00, funding_cycle_h=4, 24h_change=-33.02%, turnover=10572124. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T08:15:00+00:00, last15m_closed_end=2026-11-04T08:15+00:00, prior8high=0.003323, depth_time=2026-11-04T08:15:09+00:00, book20_bid_proxy_usdt=42664, book20_ask_proxy_usdt=52108, funding_indicative=0.000050, next_funding_utc=2026-11-04T12:00:00+00:00, funding_cycle_h=4, 24h_change=-27.04%, turnover=11932938. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-11-04T08:15:00+00:00, last15m_closed_end=2026-11-04T08:15+00:00, prior8high=0.028570, depth_time=2026-11-04T08:15:15+00:00, book20_bid_proxy_usdt=42154, book20_ask_proxy_usdt=47105, funding_indicative=-0.000422, next_funding_utc=2026-11-04T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.70%, turnover=7312883. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T08:15:00+00:00, last15m_closed_end=2026-11-04T08:15+00:00, prior8high=1.531000, depth_time=2026-11-04T08:15:11+00:00, book20_bid_proxy_usdt=1477502, book20_ask_proxy_usdt=1024591, funding_indicative=-0.000049, next_funding_utc=2026-11-04T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.65%, turnover=9410145. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
