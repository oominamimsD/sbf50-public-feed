# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T20:30:21Z**
- feed_generated_utc: 2026-10-14T20:30:23+00:00
- source_sha256: `4b799eff95a4930ec41361cd4dd04ce91ad56fc368613b1f6f86d9a0794db264`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T20:30+00:00, close=81865.2, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T20:00+00:00, close=81798.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-14T20:00+00:00, close=81798.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|2.220800|-6.64|79.63|-6.96|61107408|5.85|
|FET_USDT|0.196000|-3.87|-13.46|-4.19|10826126|5.10|
|BAT_USDT|0.170130|-2.45|71.57|-2.77|32804078|1.76|
|S_USDT|0.053590|-2.19|34.51|-2.51|6472102|1.87|
|NEAR_USDT|4.801000|-0.82|-4.62|-1.14|178039172|4.17|
|COPPER_USDT|6.624000|-0.74|-0.91|-1.06|6411227|3.02|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BAT_USDT|0.170130|0.167120|0.170130|2.15|N|Y/Y|Y/N|Y|N|
|BTW_USDT|2.220800|2.065400|2.220800|0.37|N|Y/Y|N/N|Y|N|
|COPPER_USDT|6.624000|6.606000|6.624000|0.03|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.196000|0.192700|0.196000|0.20|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.801000|4.765000|4.801000|0.40|N|Y/Y|Y/Y|Y|N|
|S_USDT|0.053590|0.052430|0.053590|0.97|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BAT_USDT: quote_utc=2026-10-14T20:29:59+00:00, last15m_closed_end=2026-10-14T20:30+00:00, prior8high=0.173100, depth_time=2026-10-14T20:30:13+00:00, book20_bid_proxy_usdt=36618, book20_ask_proxy_usdt=25624, funding_indicative=0.000001, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.45%, turnover=32804078. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-14T20:29:59+00:00, last15m_closed_end=2026-10-14T20:30+00:00, prior8high=2.275500, depth_time=2026-10-14T20:30:07+00:00, book20_bid_proxy_usdt=8009, book20_ask_proxy_usdt=25176, funding_indicative=0.000030, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=4, 24h_change=-6.64%, turnover=61107408. target_RR/account_short_permission/settled_funding=UNKNOWN.
- COPPER_USDT: quote_utc=2026-10-14T20:30:00+00:00, last15m_closed_end=2026-10-14T20:30+00:00, prior8high=6.644000, depth_time=2026-10-14T20:30:19+00:00, book20_bid_proxy_usdt=920246, book20_ask_proxy_usdt=979069, funding_indicative=0.000000, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.74%, turnover=6411227. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-14T20:29:59+00:00, last15m_closed_end=2026-10-14T20:30+00:00, prior8high=0.203600, depth_time=2026-10-14T20:30:10+00:00, book20_bid_proxy_usdt=1147076, book20_ask_proxy_usdt=1235690, funding_indicative=0.000059, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.87%, turnover=10826126. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-14T20:29:59+00:00, last15m_closed_end=2026-10-14T20:30+00:00, prior8high=4.849000, depth_time=2026-10-14T20:30:17+00:00, book20_bid_proxy_usdt=1364779, book20_ask_proxy_usdt=1744711, funding_indicative=0.000100, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.82%, turnover=178039172. target_RR/account_short_permission/settled_funding=UNKNOWN.
- S_USDT: quote_utc=2026-10-14T20:29:59+00:00, last15m_closed_end=2026-10-14T20:30+00:00, prior8high=0.053720, depth_time=2026-10-14T20:30:15+00:00, book20_bid_proxy_usdt=168096, book20_ask_proxy_usdt=148166, funding_indicative=-0.000100, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.19%, turnover=6472102. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
