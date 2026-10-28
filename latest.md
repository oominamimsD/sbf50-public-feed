# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T03:00:18Z**
- feed_generated_utc: 2026-10-28T03:00:21+00:00
- source_sha256: `d37d980480bba08b81f502a576bb14c5478f34e0d91c8803686f08e103eb1ee7`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T03:00+00:00, close=80917.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-28T03:00+00:00, close=80917.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T00:00+00:00, close=80868.4, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.022615|-23.50|-27.26|-23.97|5594000|4.42|
|Q_USDT|0.054391|-17.57|-55.69|-18.04|35708402|0.18|
|NIL_USDT|0.085120|-6.43|-4.20|-6.90|5856944|8.22|
|INJ_USDT|7.922000|-0.90|-7.88|-1.37|24282484|1.26|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.022615|0.021438|0.022615|0.61|N|Y/Y|Y/Y|N|N|
|INJ_USDT|7.922000|7.947000|7.922000|0.85|N|Y/N|N/N|N|N|
|NIL_USDT|0.085120|0.084190|0.085120|0.33|N|Y/Y|N/N|N|N|
|Q_USDT|0.054391|0.052383|0.054391|0.57|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-28T03:00:01+00:00, last15m_closed_end=2026-10-28T03:00+00:00, prior8high=0.023654, depth_time=2026-10-28T03:00:09+00:00, book20_bid_proxy_usdt=3033, book20_ask_proxy_usdt=4942, funding_indicative=0.000050, next_funding_utc=2026-10-28T04:00:00+00:00, funding_cycle_h=4, 24h_change=-23.50%, turnover=5594000. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-28T03:00:01+00:00, last15m_closed_end=2026-10-28T03:00+00:00, prior8high=8.060000, depth_time=2026-10-28T03:00:17+00:00, book20_bid_proxy_usdt=316150, book20_ask_proxy_usdt=308271, funding_indicative=0.000201, next_funding_utc=2026-10-28T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.90%, turnover=24282484. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NIL_USDT: quote_utc=2026-10-28T03:00:01+00:00, last15m_closed_end=2026-10-28T03:00+00:00, prior8high=0.089130, depth_time=2026-10-28T03:00:14+00:00, book20_bid_proxy_usdt=10732, book20_ask_proxy_usdt=4068, funding_indicative=-0.000157, next_funding_utc=2026-10-28T04:00:00+00:00, funding_cycle_h=4, 24h_change=-6.43%, turnover=5856944. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-28T03:00:00+00:00, last15m_closed_end=2026-10-28T03:00+00:00, prior8high=0.055511, depth_time=2026-10-28T03:00:12+00:00, book20_bid_proxy_usdt=27722, book20_ask_proxy_usdt=26846, funding_indicative=-0.000069, next_funding_utc=2026-10-28T04:00:00+00:00, funding_cycle_h=4, 24h_change=-17.57%, turnover=35708402. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
