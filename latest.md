# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T04:15:16Z**
- feed_generated_utc: 2026-11-11T04:15:17+00:00
- source_sha256: `52fedc6ffdafb3e7ff102ea48bf1c933138361975ef43be84453e6ef93745ddc`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T04:15+00:00, close=73685, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-11T04:00+00:00, close=73740.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-11T04:00+00:00, close=73740.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002655|-8.88|-36.11|-9.56|9720364|3.77|
|ZEC_USDT|1022.210000|-6.50|-15.08|-7.18|2146272599|0.10|
|DASH_USDT|44.080000|-2.34|-4.46|-3.02|14401899|2.27|
|UNI_USDT|6.690000|-2.04|-9.01|-2.72|35891349|1.50|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002655|0.002606|0.002655|1.33|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|44.080000|42.750000|44.090000|0.08|N|N/Y|Y/Y|Y|N|
|UNI_USDT|6.690000|6.626000|6.690000|0.48|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1022.210000|1007.730000|1022.510000|0.99|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-11T04:15:02+00:00, last15m_closed_end=2026-11-11T04:15+00:00, prior8high=0.003032, depth_time=2026-11-11T04:15:06+00:00, book20_bid_proxy_usdt=53540, book20_ask_proxy_usdt=54163, funding_indicative=0.000050, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=4, 24h_change=-8.88%, turnover=9720364. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-11T04:15:02+00:00, last15m_closed_end=2026-11-11T04:15+00:00, prior8high=44.810000, depth_time=2026-11-11T04:15:13+00:00, book20_bid_proxy_usdt=904997, book20_ask_proxy_usdt=577242, funding_indicative=-0.000112, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.34%, turnover=14401899. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T04:15:02+00:00, last15m_closed_end=2026-11-11T04:15+00:00, prior8high=6.768000, depth_time=2026-11-11T04:15:14+00:00, book20_bid_proxy_usdt=3258640, book20_ask_proxy_usdt=2000188, funding_indicative=0.000053, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.04%, turnover=35891349. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T04:15:02+00:00, last15m_closed_end=2026-11-11T04:15+00:00, prior8high=1038.490000, depth_time=2026-11-11T04:15:09+00:00, book20_bid_proxy_usdt=282234, book20_ask_proxy_usdt=486692, funding_indicative=0.000098, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.50%, turnover=2146272599. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
