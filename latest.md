# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T20:45:22Z**
- feed_generated_utc: 2026-10-14T20:45:23+00:00
- source_sha256: `e8b795f267119c8dabdcfa587be7c5551b85941f9b1f68b61bae80cb62e8c4f4`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T20:45+00:00, close=81711.8, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T20:00+00:00, close=81798.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-14T20:00+00:00, close=81798.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|2.238900|-5.88|81.09|-6.01|61230136|4.47|
|FET_USDT|0.195800|-3.97|-13.55|-4.10|10894567|5.10|
|S_USDT|0.053330|-2.66|33.86|-2.79|6493719|1.88|
|BAT_USDT|0.170800|-2.07|72.24|-2.20|32912873|0.58|
|AAVE_USDT|154.230000|-1.06|-10.20|-1.19|24747203|3.24|
|NEAR_USDT|4.793000|-0.99|-4.78|-1.12|179214445|2.09|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|154.230000|153.970000|154.250000|1.12|N|Y/Y|Y/Y|Y|N|
|BAT_USDT|0.170800|0.167120|0.170710|1.02|N|Y/Y|Y/N|Y|N|
|BTW_USDT|2.238900|2.065400|2.240200|0.35|N|Y/Y|N/N|Y|N|
|FET_USDT|0.195800|0.192700|0.195800|0.37|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.793000|4.765000|4.793000|0.70|N|Y/Y|Y/Y|Y|N|
|S_USDT|0.053330|0.052430|0.053340|0.54|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-14T20:45:03+00:00, last15m_closed_end=2026-10-14T20:45+00:00, prior8high=155.360000, depth_time=2026-10-14T20:45:17+00:00, book20_bid_proxy_usdt=213783, book20_ask_proxy_usdt=292704, funding_indicative=0.000056, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.06%, turnover=24747203. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-14T20:45:03+00:00, last15m_closed_end=2026-10-14T20:45+00:00, prior8high=0.172860, depth_time=2026-10-14T20:45:16+00:00, book20_bid_proxy_usdt=30851, book20_ask_proxy_usdt=24136, funding_indicative=0.000004, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.07%, turnover=32912873. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-14T20:45:02+00:00, last15m_closed_end=2026-10-14T20:45+00:00, prior8high=2.275500, depth_time=2026-10-14T20:45:08+00:00, book20_bid_proxy_usdt=7163, book20_ask_proxy_usdt=15237, funding_indicative=0.000038, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=4, 24h_change=-5.88%, turnover=61230136. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-14T20:45:03+00:00, last15m_closed_end=2026-10-14T20:45+00:00, prior8high=0.201900, depth_time=2026-10-14T20:45:09+00:00, book20_bid_proxy_usdt=1086131, book20_ask_proxy_usdt=945176, funding_indicative=0.000058, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.97%, turnover=10894567. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-14T20:45:02+00:00, last15m_closed_end=2026-10-14T20:45+00:00, prior8high=4.849000, depth_time=2026-10-14T20:45:21+00:00, book20_bid_proxy_usdt=985022, book20_ask_proxy_usdt=2258649, funding_indicative=0.000100, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.99%, turnover=179214445. target_RR/account_short_permission/settled_funding=UNKNOWN.
- S_USDT: quote_utc=2026-10-14T20:45:03+00:00, last15m_closed_end=2026-10-14T20:45+00:00, prior8high=0.053720, depth_time=2026-10-14T20:45:10+00:00, book20_bid_proxy_usdt=203857, book20_ask_proxy_usdt=157754, funding_indicative=-0.000100, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.66%, turnover=6493719. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
