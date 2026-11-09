# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T15:15:20Z**
- feed_generated_utc: 2026-11-09T15:15:21+00:00
- source_sha256: `38d9d246b19f7d9cd84b815adc38ede08fb7caca5d99405f892e2f985c025fa1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T15:15+00:00, close=74866.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-09T15:00+00:00, close=74871.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-09T12:00+00:00, close=74345.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001497|-23.51|28.59|-21.95|5907443|0.67|
|AKE_USDT|0.004697|-12.32|-48.72|-10.76|8788924|2.13|
|ASTER_USDT|0.641100|-5.69|-8.33|-4.13|5880057|3.12|
|ETH_USDT|2126.090000|-5.13|-6.16|-3.57|1685843404|0.05|
|XRP_USDT|1.097100|-5.07|-12.22|-3.51|289526401|0.91|
|TRUMPOFFICIAL_USDT|1.136000|-4.45|-33.79|-2.89|6323704|8.81|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004697|0.004671|0.004697|0.51|N|Y/Y|N/Y|Y|N|
|ASTER_USDT|0.641100|0.637900|0.641100|4.97|N|Y/Y|Y/Y|Y|N|
|ETH_USDT|2126.090000|2113.380000|2126.150000|2.17|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001497|0.001470|0.001497|0.36|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.136000|1.113000|1.136000|0.34|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.097100|1.090100|1.097100|1.53|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-09T15:14:59+00:00, last15m_closed_end=2026-11-09T15:15+00:00, prior8high=0.004890, depth_time=2026-11-09T15:15:09+00:00, book20_bid_proxy_usdt=62060, book20_ask_proxy_usdt=35128, funding_indicative=0.000050, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-12.32%, turnover=8788924. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ASTER_USDT: quote_utc=2026-11-09T15:14:59+00:00, last15m_closed_end=2026-11-09T15:15+00:00, prior8high=0.643700, depth_time=2026-11-09T15:15:10+00:00, book20_bid_proxy_usdt=803627, book20_ask_proxy_usdt=830652, funding_indicative=0.000050, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.69%, turnover=5880057. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETH_USDT: quote_utc=2026-11-09T15:15:02+00:00, last15m_closed_end=2026-11-09T15:15+00:00, prior8high=2137.760000, depth_time=2026-11-09T15:15:14+00:00, book20_bid_proxy_usdt=3162207, book20_ask_proxy_usdt=1811622, funding_indicative=0.000008, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.13%, turnover=1685843404. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T15:14:59+00:00, last15m_closed_end=2026-11-09T15:15+00:00, prior8high=0.001538, depth_time=2026-11-09T15:15:07+00:00, book20_bid_proxy_usdt=15152, book20_ask_proxy_usdt=18872, funding_indicative=-0.000223, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-23.51%, turnover=5907443. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-09T15:14:59+00:00, last15m_closed_end=2026-11-09T15:15+00:00, prior8high=1.143000, depth_time=2026-11-09T15:15:19+00:00, book20_bid_proxy_usdt=2169684, book20_ask_proxy_usdt=2834022, funding_indicative=0.000044, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.45%, turnover=6323704. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T15:15:02+00:00, last15m_closed_end=2026-11-09T15:15+00:00, prior8high=1.106800, depth_time=2026-11-09T15:15:17+00:00, book20_bid_proxy_usdt=2865115, book20_ask_proxy_usdt=3426209, funding_indicative=0.000078, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.07%, turnover=289526401. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
