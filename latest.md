# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T17:15:22Z**
- feed_generated_utc: 2026-11-04T17:15:23+00:00
- source_sha256: `0c9a7c91074f94aceb2d7197fe719d1e122dbef8585690a0502f168086c809b8`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T17:15+00:00, close=80258.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T17:00+00:00, close=80491.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T16:00+00:00, close=80272.3, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.035700|-5.75|-40.40|-5.74|6880100|0.97|
|TRUMPOFFICIAL_USDT|1.355000|-4.84|-20.71|-4.83|18266321|7.39|
|WLD_USDT|0.374100|-4.59|-13.56|-4.58|69729980|2.67|
|AGT_USDT|0.034470|-3.98|-23.55|-3.97|5966408|5.80|
|ZRO_USDT|1.819600|-2.41|6.28|-2.40|11316221|0.55|
|WLFI_USDT|0.046850|-1.98|-10.72|-1.97|5774636|2.13|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.034470|0.033650|0.034400|0.89|N|Y/Y|Y/Y|N|N|
|BTW_USDT|1.035700|1.034600|1.036400|0.69|N|N/N|N/N|N|N|
|TRUMPOFFICIAL_USDT|1.355000|1.385000|1.355000|4.03|Y|Y/Y|Y/Y|N|Y|
|WLD_USDT|0.374100|0.388500|0.373400|6.35|Y|N/N|N/N|N|N|
|WLFI_USDT|0.046850|0.046600|0.046840|4.06|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.819600|1.845600|1.819600|1.25|N|Y/N|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T17:15:03+00:00, last15m_closed_end=2026-11-04T17:15+00:00, prior8high=0.036850, depth_time=2026-11-04T17:15:15+00:00, book20_bid_proxy_usdt=30061, book20_ask_proxy_usdt=21018, funding_indicative=0.000053, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.98%, turnover=5966408. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-04T17:15:03+00:00, last15m_closed_end=2026-11-04T17:15+00:00, prior8high=1.107800, depth_time=2026-11-04T17:15:08+00:00, book20_bid_proxy_usdt=15320, book20_ask_proxy_usdt=35583, funding_indicative=0.000050, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-5.75%, turnover=6880100. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T17:15:03+00:00, last15m_closed_end=2026-11-04T17:15+00:00, prior8high=1.465000, depth_time=2026-11-04T17:15:10+00:00, book20_bid_proxy_usdt=2621345, book20_ask_proxy_usdt=1408380, funding_indicative=-0.000463, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.84%, turnover=18266321. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-04T17:15:03+00:00, last15m_closed_end=2026-11-04T17:15+00:00, prior8high=0.401900, depth_time=2026-11-04T17:15:13+00:00, book20_bid_proxy_usdt=2079140, book20_ask_proxy_usdt=1573695, funding_indicative=-0.000060, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.59%, turnover=69729980. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLFI_USDT: quote_utc=2026-11-04T17:15:03+00:00, last15m_closed_end=2026-11-04T17:15+00:00, prior8high=0.050060, depth_time=2026-11-04T17:15:21+00:00, book20_bid_proxy_usdt=336589, book20_ask_proxy_usdt=444551, funding_indicative=0.000050, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.98%, turnover=5774636. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-04T17:15:03+00:00, last15m_closed_end=2026-11-04T17:15+00:00, prior8high=1.925500, depth_time=2026-11-04T17:15:18+00:00, book20_bid_proxy_usdt=18362, book20_ask_proxy_usdt=67782, funding_indicative=0.000050, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.41%, turnover=11316221. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
