# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T12:15:20Z**
- feed_generated_utc: 2026-10-19T12:15:22+00:00
- source_sha256: `4301e887627f104a0f5b7440a938978e615dd51004332aae99a888d6c9b8a32e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T12:15+00:00, close=82477.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-19T12:00+00:00, close=82317.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-19T12:00+00:00, close=82317.9, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|2.006700|-12.95|19.29|-14.60|20936954|0.50|
|STRK_USDT|0.058350|-5.21|-51.07|-6.86|18011063|1.71|
|HBAR_USDT|0.083600|-2.54|-10.85|-4.19|40620165|1.20|
|TIA_USDT|0.608900|-1.45|3.43|-3.10|49200217|1.64|
|SEI_USDT|0.059920|-0.53|-15.47|-2.18|9141701|1.67|
|XAUT_USDT|4160.280000|0.30|-0.69|-1.35|92464035|0.07|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|2.006700|2.005000|2.003400|2.32|Y|Y/Y|Y/Y|N|Y|
|HBAR_USDT|0.083600|0.082730|0.083610|1.69|N|Y/Y|Y/Y|N|N|
|SEI_USDT|0.059920|0.059210|0.059920|2.46|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.058350|0.057600|0.058360|2.00|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.608900|0.602400|0.608900|0.74|N|Y/Y|Y/Y|N|N|
|XAUT_USDT|4160.280000|4157.400000|4160.280000|0.85|N|Y/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-19T12:15:02+00:00, last15m_closed_end=2026-10-19T12:15+00:00, prior8high=2.239100, depth_time=2026-10-19T12:15:07+00:00, book20_bid_proxy_usdt=14222, book20_ask_proxy_usdt=17846, funding_indicative=-0.000726, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=4, 24h_change=-12.95%, turnover=20936954. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-19T12:15:02+00:00, last15m_closed_end=2026-10-19T12:15+00:00, prior8high=0.084230, depth_time=2026-10-19T12:15:12+00:00, book20_bid_proxy_usdt=330966, book20_ask_proxy_usdt=647857, funding_indicative=-0.000002, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.54%, turnover=40620165. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-19T12:15:02+00:00, last15m_closed_end=2026-10-19T12:15+00:00, prior8high=0.060440, depth_time=2026-10-19T12:15:17+00:00, book20_bid_proxy_usdt=207975, book20_ask_proxy_usdt=243638, funding_indicative=0.000024, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.53%, turnover=9141701. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-19T12:15:02+00:00, last15m_closed_end=2026-10-19T12:15+00:00, prior8high=0.060310, depth_time=2026-10-19T12:15:10+00:00, book20_bid_proxy_usdt=752995, book20_ask_proxy_usdt=546010, funding_indicative=0.000050, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.21%, turnover=18011063. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-19T12:15:02+00:00, last15m_closed_end=2026-10-19T12:15+00:00, prior8high=0.614900, depth_time=2026-10-19T12:15:14+00:00, book20_bid_proxy_usdt=172418, book20_ask_proxy_usdt=264267, funding_indicative=0.000009, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.45%, turnover=49200217. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAUT_USDT: quote_utc=2026-10-19T12:15:02+00:00, last15m_closed_end=2026-10-19T12:15+00:00, prior8high=4169.510000, depth_time=2026-10-19T12:15:20+00:00, book20_bid_proxy_usdt=157880, book20_ask_proxy_usdt=127787, funding_indicative=-0.000010, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=4, 24h_change=0.30%, turnover=92464035. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
