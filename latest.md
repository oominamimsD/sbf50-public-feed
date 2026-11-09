# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T23:30:16Z**
- feed_generated_utc: 2026-11-09T23:30:17+00:00
- source_sha256: `4243fed818304c3625df6cfa448fb15bd533b8d2eb5eae9456da7e4eac8a9850`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T23:30+00:00, close=75251, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-09T23:00+00:00, close=75256.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-09T20:00+00:00, close=74856.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.003668|-25.09|-33.33|-24.77|9905790|2.71|
|ZEC_USDT|1164.840000|-4.96|-7.11|-4.64|2488274343|0.09|
|DOT_USDT|0.857000|-3.80|-8.25|-3.48|11355307|1.17|
|QNT_USDT|194.490000|-2.77|-3.93|-2.45|41869969|0.51|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.003668|0.004903|0.003670|13.44|Y|N/N|Y/N|Y|N|
|DOT_USDT|0.857000|0.853200|0.856700|0.31|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|194.490000|194.280000|194.500000|2.80|N|Y/Y|Y/N|Y|N|
|ZEC_USDT|1164.840000|1153.000000|1164.340000|1.23|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-09T23:30:01+00:00, last15m_closed_end=2026-11-09T23:30+00:00, prior8high=0.005150, depth_time=2026-11-09T23:30:07+00:00, book20_bid_proxy_usdt=40123, book20_ask_proxy_usdt=23224, funding_indicative=0.000050, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=4, 24h_change=-25.09%, turnover=9905790. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-09T23:30:01+00:00, last15m_closed_end=2026-11-09T23:30+00:00, prior8high=0.864800, depth_time=2026-11-09T23:30:12+00:00, book20_bid_proxy_usdt=451221, book20_ask_proxy_usdt=888725, funding_indicative=0.000073, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.80%, turnover=11355307. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-09T23:30:01+00:00, last15m_closed_end=2026-11-09T23:30+00:00, prior8high=197.070000, depth_time=2026-11-09T23:30:15+00:00, book20_bid_proxy_usdt=67724, book20_ask_proxy_usdt=82356, funding_indicative=0.000100, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.77%, turnover=41869969. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-09T23:30:01+00:00, last15m_closed_end=2026-11-09T23:30+00:00, prior8high=1184.660000, depth_time=2026-11-09T23:30:09+00:00, book20_bid_proxy_usdt=266467, book20_ask_proxy_usdt=165545, funding_indicative=0.000100, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.96%, turnover=2488274343. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
