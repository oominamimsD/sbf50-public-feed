# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T02:45:19Z**
- feed_generated_utc: 2026-10-21T02:45:21+00:00
- source_sha256: `e90bc400b46e09c71849f2f1962ce9659a2389fcf74db858cdfbfa24d69fd2d1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T02:45+00:00, close=82749.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-21T02:00+00:00, close=82965.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T00:00+00:00, close=82984.8, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.187180|-13.25|5.52|-13.44|10442514|0.53|
|XMR_USDT|576.820000|-6.99|9.26|-7.18|20132909|0.17|
|Q_USDT|0.118207|-3.70|187.41|-3.89|5065420|2.96|
|AGT_USDT|0.063399|-1.90|291.90|-2.09|7144615|3.32|
|TIA_USDT|0.615000|-1.23|6.53|-1.42|49853659|3.25|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.063399|0.061689|0.063399|0.26|N|Y/Y|Y/Y|N|N|
|BAT_USDT|0.187180|0.186500|0.187180|0.37|N|Y/Y|N/N|N|N|
|Q_USDT|0.118207|0.119210|0.118149|2.18|Y|Y/Y|N/N|N|N|
|TIA_USDT|0.615000|0.605800|0.615000|0.58|N|Y/Y|Y/Y|N|N|
|XMR_USDT|576.820000|572.610000|576.820000|0.35|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-21T02:45:02+00:00, last15m_closed_end=2026-10-21T02:45+00:00, prior8high=0.069341, depth_time=2026-10-21T02:45:16+00:00, book20_bid_proxy_usdt=8397, book20_ask_proxy_usdt=6593, funding_indicative=0.000047, next_funding_utc=2026-10-21T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.90%, turnover=7144615. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T02:45:02+00:00, last15m_closed_end=2026-10-21T02:45+00:00, prior8high=0.194200, depth_time=2026-10-21T02:45:07+00:00, book20_bid_proxy_usdt=26692, book20_ask_proxy_usdt=61509, funding_indicative=0.000055, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-13.25%, turnover=10442514. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-21T02:45:02+00:00, last15m_closed_end=2026-10-21T02:45+00:00, prior8high=0.123452, depth_time=2026-10-21T02:45:13+00:00, book20_bid_proxy_usdt=16405, book20_ask_proxy_usdt=17964, funding_indicative=-0.000145, next_funding_utc=2026-10-21T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.70%, turnover=5065420. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T02:45:02+00:00, last15m_closed_end=2026-10-21T02:45+00:00, prior8high=0.619700, depth_time=2026-10-21T02:45:18+00:00, book20_bid_proxy_usdt=192738, book20_ask_proxy_usdt=210040, funding_indicative=-0.000038, next_funding_utc=2026-10-21T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.23%, turnover=49853659. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-21T02:45:02+00:00, last15m_closed_end=2026-10-21T02:45+00:00, prior8high=601.630000, depth_time=2026-10-21T02:45:10+00:00, book20_bid_proxy_usdt=17708, book20_ask_proxy_usdt=11708, funding_indicative=0.000100, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.99%, turnover=20132909. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
