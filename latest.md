# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T14:15:22Z**
- feed_generated_utc: 2026-11-04T14:15:23+00:00
- source_sha256: `3ad184dda7fc43cf5326c37a1808b83158c71115e03746974b0dcec8f9fd1fe9`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T14:15+00:00, close=78328.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T14:00+00:00, close=78338.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T12:00+00:00, close=78453.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.036630|-31.92|-22.91|-32.77|7701325|8.19|
|AKE_USDT|0.003197|-23.07|-84.86|-23.92|14451907|6.26|
|HOT_USDT|0.000469|-12.83|35.87|-13.68|5256411|4.26|
|TRUMPOFFICIAL_USDT|1.421000|-11.62|-15.81|-12.47|12912195|7.04|
|ZRO_USDT|1.821100|-3.85|8.03|-4.70|11414109|2.74|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.036630|0.032170|0.036560|2.67|N|Y/Y|Y/Y|N|N|
|AKE_USDT|0.003197|0.002758|0.003187|2.13|N|Y/Y|Y/Y|N|N|
|HOT_USDT|0.000469|0.000472|0.000470|2.80|Y|Y/Y|N/N|N|N|
|TRUMPOFFICIAL_USDT|1.421000|1.407000|1.421000|1.13|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.821100|1.841900|1.821100|6.76|Y|Y/N|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T14:15:02+00:00, last15m_closed_end=2026-11-04T14:15+00:00, prior8high=0.035300, depth_time=2026-11-04T14:15:08+00:00, book20_bid_proxy_usdt=49508, book20_ask_proxy_usdt=33498, funding_indicative=0.000053, next_funding_utc=2026-11-04T16:00:00+00:00, funding_cycle_h=4, 24h_change=-31.92%, turnover=7701325. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T14:15:02+00:00, last15m_closed_end=2026-11-04T14:15+00:00, prior8high=0.003257, depth_time=2026-11-04T14:15:12+00:00, book20_bid_proxy_usdt=36498, book20_ask_proxy_usdt=53928, funding_indicative=-0.000061, next_funding_utc=2026-11-04T16:00:00+00:00, funding_cycle_h=4, 24h_change=-23.07%, turnover=14451907. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HOT_USDT: quote_utc=2026-11-04T14:15:02+00:00, last15m_closed_end=2026-11-04T14:15+00:00, prior8high=0.000498, depth_time=2026-11-04T14:15:15+00:00, book20_bid_proxy_usdt=70664, book20_ask_proxy_usdt=75384, funding_indicative=-0.000222, next_funding_utc=2026-11-04T15:00:00+00:00, funding_cycle_h=1, 24h_change=-12.83%, turnover=5256411. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T14:15:03+00:00, last15m_closed_end=2026-11-04T14:15+00:00, prior8high=1.460000, depth_time=2026-11-04T14:15:18+00:00, book20_bid_proxy_usdt=2951428, book20_ask_proxy_usdt=2488022, funding_indicative=-0.000394, next_funding_utc=2026-11-04T16:00:00+00:00, funding_cycle_h=4, 24h_change=-11.62%, turnover=12912195. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-04T14:15:03+00:00, last15m_closed_end=2026-11-04T14:15+00:00, prior8high=1.890800, depth_time=2026-11-04T14:15:21+00:00, book20_bid_proxy_usdt=21364, book20_ask_proxy_usdt=59058, funding_indicative=0.000050, next_funding_utc=2026-11-04T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.85%, turnover=11414109. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
