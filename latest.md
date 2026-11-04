# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T10:15:14Z**
- feed_generated_utc: 2026-11-04T10:15:15+00:00
- source_sha256: `98e9ebe1dc31a77a89435037e05567c0db8b87f0baee596a2c79ddd06d1a5417`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1182; contracts: 1174; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T10:15+00:00, close=78521.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T10:00+00:00, close=78377.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T08:00+00:00, close=78117.1, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.033610|-37.53|-29.27|-38.63|10716598|8.92|
|AKE_USDT|0.002862|-31.13|-86.45|-32.23|12457468|6.99|
|TRUMPOFFICIAL_USDT|1.485000|-7.64|-12.02|-8.74|10534584|6.73|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.033610|0.032150|0.033600|2.66|N|Y/Y|Y/N|N|N|
|AKE_USDT|0.002862|0.002863|0.002862|2.35|Y|Y/Y|Y/Y|N|Y|
|TRUMPOFFICIAL_USDT|1.485000|1.463000|1.485000|0.87|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T10:14:59+00:00, last15m_closed_end=2026-11-04T10:15+00:00, prior8high=0.036480, depth_time=2026-11-04T10:15:08+00:00, book20_bid_proxy_usdt=35194, book20_ask_proxy_usdt=25127, funding_indicative=0.000053, next_funding_utc=2026-11-04T12:00:00+00:00, funding_cycle_h=4, 24h_change=-37.53%, turnover=10716598. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T10:14:59+00:00, last15m_closed_end=2026-11-04T10:15+00:00, prior8high=0.003107, depth_time=2026-11-04T10:15:10+00:00, book20_bid_proxy_usdt=60989, book20_ask_proxy_usdt=81478, funding_indicative=0.000050, next_funding_utc=2026-11-04T12:00:00+00:00, funding_cycle_h=4, 24h_change=-31.13%, turnover=12457468. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T10:15:00+00:00, last15m_closed_end=2026-11-04T10:15+00:00, prior8high=1.526000, depth_time=2026-11-04T10:15:13+00:00, book20_bid_proxy_usdt=2497514, book20_ask_proxy_usdt=2671016, funding_indicative=-0.000087, next_funding_utc=2026-11-04T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.64%, turnover=10534584. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
