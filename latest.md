# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T23:30:16Z**
- feed_generated_utc: 2026-10-27T23:30:19+00:00
- source_sha256: `c66f8dcf8d9e58ad177231724e010c0026277134cdec6384c9303f081f44f2dd`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T23:30+00:00, close=80909.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-27T23:00+00:00, close=80874.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-27T20:00+00:00, close=80778.5, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.053262|-16.23|-56.61|-16.70|44741204|0.56|
|ARB_USDT|0.166410|-1.24|-11.92|-1.71|15234835|0.60|
|SYN_USDT|0.179200|-1.21|-2.39|-1.68|5804741|5.58|
|NIL_USDT|0.091870|-0.88|3.38|-1.35|5603299|7.62|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.166410|0.165630|0.166410|2.43|N|Y/Y|Y/Y|N|N|
|NIL_USDT|0.091870|0.091090|0.091870|0.84|N|Y/Y|N/N|N|N|
|Q_USDT|0.053262|0.053262|0.053242|0.86|N|Y/Y|Y/Y|N|N|
|SYN_USDT|0.179200|0.178600|0.179200|1.56|N|Y/N|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-27T23:30:00+00:00, last15m_closed_end=2026-10-27T23:30+00:00, prior8high=0.169030, depth_time=2026-10-27T23:30:11+00:00, book20_bid_proxy_usdt=95118, book20_ask_proxy_usdt=62221, funding_indicative=-0.000022, next_funding_utc=2026-10-28T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.24%, turnover=15234835. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NIL_USDT: quote_utc=2026-10-27T23:30:00+00:00, last15m_closed_end=2026-10-27T23:30+00:00, prior8high=0.093310, depth_time=2026-10-27T23:30:14+00:00, book20_bid_proxy_usdt=2836, book20_ask_proxy_usdt=6586, funding_indicative=-0.000415, next_funding_utc=2026-10-28T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.88%, turnover=5603299. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-27T23:30:00+00:00, last15m_closed_end=2026-10-27T23:30+00:00, prior8high=0.055980, depth_time=2026-10-27T23:30:08+00:00, book20_bid_proxy_usdt=8098, book20_ask_proxy_usdt=4032, funding_indicative=-0.000041, next_funding_utc=2026-10-28T00:00:00+00:00, funding_cycle_h=4, 24h_change=-16.23%, turnover=44741204. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SYN_USDT: quote_utc=2026-10-27T23:30:00+00:00, last15m_closed_end=2026-10-27T23:30+00:00, prior8high=0.183400, depth_time=2026-10-27T23:30:09+00:00, book20_bid_proxy_usdt=102134, book20_ask_proxy_usdt=101544, funding_indicative=0.000050, next_funding_utc=2026-10-28T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.21%, turnover=5804741. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
