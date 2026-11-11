# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T03:30:16Z**
- feed_generated_utc: 2026-11-11T03:30:17+00:00
- source_sha256: `fa1ac1555d7729abdee7bafe83a54a3fe9de12d465396c1a61c213e339795c7d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T03:30+00:00, close=73748.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-11T03:00+00:00, close=73615.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-11T00:00+00:00, close=73762.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|PIEVERSE_USDT|1.748700|-13.69|48.77|-14.47|5070627|6.29|
|AKE_USDT|0.002635|-9.57|-36.59|-10.35|10415456|7.60|
|ZEC_USDT|1033.690000|-5.45|-14.13|-6.23|2188633747|0.10|
|UNI_USDT|6.735000|-1.39|-8.40|-2.17|35057615|1.49|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002635|0.002606|0.002632|0.87|N|Y/Y|Y/Y|Y|N|
|PIEVERSE_USDT|1.748700|1.682600|1.748700|1.24|N|Y/Y|N/N|Y|N|
|UNI_USDT|6.735000|6.626000|6.735000|0.73|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1033.690000|1007.730000|1033.260000|0.86|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-11T03:30:01+00:00, last15m_closed_end=2026-11-11T03:30+00:00, prior8high=0.003032, depth_time=2026-11-11T03:30:09+00:00, book20_bid_proxy_usdt=55394, book20_ask_proxy_usdt=40368, funding_indicative=0.000050, next_funding_utc=2026-11-11T04:00:00+00:00, funding_cycle_h=4, 24h_change=-9.57%, turnover=10415456. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PIEVERSE_USDT: quote_utc=2026-11-11T03:30:01+00:00, last15m_closed_end=2026-11-11T03:30+00:00, prior8high=1.853200, depth_time=2026-11-11T03:30:07+00:00, book20_bid_proxy_usdt=12986, book20_ask_proxy_usdt=14312, funding_indicative=0.000122, next_funding_utc=2026-11-11T04:00:00+00:00, funding_cycle_h=4, 24h_change=-13.69%, turnover=5070627. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T03:30:01+00:00, last15m_closed_end=2026-11-11T03:30+00:00, prior8high=6.820000, depth_time=2026-11-11T03:30:14+00:00, book20_bid_proxy_usdt=2978684, book20_ask_proxy_usdt=1668423, funding_indicative=0.000029, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.39%, turnover=35057615. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T03:30:01+00:00, last15m_closed_end=2026-11-11T03:30+00:00, prior8high=1042.760000, depth_time=2026-11-11T03:30:13+00:00, book20_bid_proxy_usdt=341822, book20_ask_proxy_usdt=320934, funding_indicative=0.000100, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.45%, turnover=2188633747. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
