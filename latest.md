# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T10:15:16Z**
- feed_generated_utc: 2026-10-28T10:15:19+00:00
- source_sha256: `607b4e74f6b254780c3fa652d3e7a23d40e8641e6f93e14f898e54bc0eaab8b9`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T10:15+00:00, close=81476.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-28T10:00+00:00, close=81515.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T08:00+00:00, close=81049, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.057600|-9.41|-53.07|-10.58|23002011|1.73|
|BEAT_USDT|0.084790|-6.91|13.49|-8.08|15188857|7.07|
|AKE_USDT|0.020268|-4.05|-34.81|-5.22|6082120|5.43|
|DASH_USDT|53.840000|-0.60|7.80|-1.77|15350461|1.86|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.020268|0.020071|0.020264|1.94|N|Y/Y|Y/Y|N|N|
|BEAT_USDT|0.084790|0.085830|0.084710|2.36|Y|Y/N|N/N|N|N|
|DASH_USDT|53.840000|53.960000|53.840000|7.85|Y|Y/Y|N/N|N|N|
|Q_USDT|0.057600|0.056930|0.057610|0.91|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-28T10:15:03+00:00, last15m_closed_end=2026-10-28T10:15+00:00, prior8high=0.021104, depth_time=2026-10-28T10:15:10+00:00, book20_bid_proxy_usdt=32304, book20_ask_proxy_usdt=3587, funding_indicative=0.000050, next_funding_utc=2026-10-28T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.05%, turnover=6082120. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-28T10:15:03+00:00, last15m_closed_end=2026-10-28T10:15+00:00, prior8high=0.108740, depth_time=2026-10-28T10:15:11+00:00, book20_bid_proxy_usdt=8496, book20_ask_proxy_usdt=8003, funding_indicative=0.000050, next_funding_utc=2026-10-28T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.91%, turnover=15188857. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-28T10:15:03+00:00, last15m_closed_end=2026-10-28T10:15+00:00, prior8high=54.470000, depth_time=2026-10-28T10:15:16+00:00, book20_bid_proxy_usdt=940083, book20_ask_proxy_usdt=629891, funding_indicative=0.000100, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.60%, turnover=15350461. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-28T10:15:02+00:00, last15m_closed_end=2026-10-28T10:15+00:00, prior8high=0.061020, depth_time=2026-10-28T10:15:09+00:00, book20_bid_proxy_usdt=14583, book20_ask_proxy_usdt=23452, funding_indicative=-0.000372, next_funding_utc=2026-10-28T12:00:00+00:00, funding_cycle_h=4, 24h_change=-9.41%, turnover=23002011. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
