# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T15:45:15Z**
- feed_generated_utc: 2026-11-09T15:45:16+00:00
- source_sha256: `e9d03c92ef91296c8f687da9745c69f1e605fbd87bf80b2cb3f0620a0b9b73a4`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T15:45+00:00, close=75381.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-09T15:00+00:00, close=74871.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-09T12:00+00:00, close=74345.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001486|-24.12|27.57|-23.26|6001038|0.67|
|AKE_USDT|0.004717|-11.94|-48.50|-11.08|9048636|2.12|
|TRUMPOFFICIAL_USDT|1.140000|-4.12|-33.56|-3.26|6374611|8.78|
|JCT_USDT|0.009458|-3.82|89.95|-2.96|57872320|4.22|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004717|0.004655|0.004717|1.14|N|Y/Y|N/Y|Y|N|
|JCT_USDT|0.009458|0.009032|0.009460|1.00|N|N/N|N/N|Y|N|
|ONE_USDT|0.001486|0.001470|0.001486|1.05|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.140000|1.113000|1.140000|0.35|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-09T15:45:00+00:00, last15m_closed_end=2026-11-09T15:45+00:00, prior8high=0.004890, depth_time=2026-11-09T15:45:10+00:00, book20_bid_proxy_usdt=46024, book20_ask_proxy_usdt=48343, funding_indicative=0.000050, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-11.94%, turnover=9048636. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-09T15:45:00+00:00, last15m_closed_end=2026-11-09T15:45+00:00, prior8high=0.011600, depth_time=2026-11-09T15:45:15+00:00, book20_bid_proxy_usdt=18342, book20_ask_proxy_usdt=69928, funding_indicative=0.000925, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.82%, turnover=57872320. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T15:45:00+00:00, last15m_closed_end=2026-11-09T15:45+00:00, prior8high=0.001538, depth_time=2026-11-09T15:45:06+00:00, book20_bid_proxy_usdt=24416, book20_ask_proxy_usdt=20535, funding_indicative=-0.000340, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-24.12%, turnover=6001038. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-09T15:45:00+00:00, last15m_closed_end=2026-11-09T15:45+00:00, prior8high=1.143000, depth_time=2026-11-09T15:45:12+00:00, book20_bid_proxy_usdt=2834615, book20_ask_proxy_usdt=2803453, funding_indicative=0.000020, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.12%, turnover=6374611. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
