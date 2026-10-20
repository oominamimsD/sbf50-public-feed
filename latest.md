# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T03:45:17Z**
- feed_generated_utc: 2026-10-20T03:45:19+00:00
- source_sha256: `b21dfaf2eebed174e3c489a7911d061a50868870b683804e327404a7ca7f26f3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T03:45+00:00, close=81984.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-20T03:00+00:00, close=81763.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T00:00+00:00, close=81903.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.123013|-2.35|299.50|-2.43|14229828|0.41|
|SAND_USDT|0.058010|-1.91|-6.57|-1.99|9043477|1.72|
|ZRO_USDT|1.870800|-1.64|-17.25|-1.72|7640198|0.53|
|NEAR_USDT|4.842000|-1.26|-12.74|-1.34|167832662|2.06|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|NEAR_USDT|4.842000|4.788000|4.843000|0.48|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.123013|0.122496|0.123013|1.00|N|Y/Y|N/N|Y|N|
|SAND_USDT|0.058010|0.057590|0.058020|0.06|N|Y/Y|N/Y|Y|N|
|ZRO_USDT|1.870800|1.847300|1.870800|0.65|N|Y/Y|N/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- NEAR_USDT: quote_utc=2026-10-20T03:44:59+00:00, last15m_closed_end=2026-10-20T03:45+00:00, prior8high=4.885000, depth_time=2026-10-20T03:45:16+00:00, book20_bid_proxy_usdt=3489047, book20_ask_proxy_usdt=1213395, funding_indicative=0.000055, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.26%, turnover=167832662. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-20T03:44:59+00:00, last15m_closed_end=2026-10-20T03:45+00:00, prior8high=0.128625, depth_time=2026-10-20T03:45:09+00:00, book20_bid_proxy_usdt=17637, book20_ask_proxy_usdt=16513, funding_indicative=-0.000197, next_funding_utc=2026-10-20T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.35%, turnover=14229828. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-20T03:44:59+00:00, last15m_closed_end=2026-10-20T03:45+00:00, prior8high=0.058600, depth_time=2026-10-20T03:45:11+00:00, book20_bid_proxy_usdt=595854, book20_ask_proxy_usdt=747339, funding_indicative=-0.002111, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.91%, turnover=9043477. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-20T03:44:59+00:00, last15m_closed_end=2026-10-20T03:45+00:00, prior8high=1.883500, depth_time=2026-10-20T03:45:11+00:00, book20_bid_proxy_usdt=33789, book20_ask_proxy_usdt=48985, funding_indicative=0.000050, next_funding_utc=2026-10-20T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.64%, turnover=7640198. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
