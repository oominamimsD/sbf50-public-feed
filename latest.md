# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T11:15:17Z**
- feed_generated_utc: 2026-10-16T11:15:19+00:00
- source_sha256: `75352d4029c5c23cc20bf65c56dc2537449933aec4f95498341daecf5295767e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T11:15+00:00, close=82627.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-16T11:00+00:00, close=82175.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-16T08:00+00:00, close=82258.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZEREBRO_USDT|0.041889|-18.33|52.56|-18.62|5250552|5.73|
|STRK_USDT|0.078700|-18.32|30.81|-18.61|40054874|1.27|
|BTW_USDT|1.737600|-8.90|25.16|-9.19|21281956|1.73|
|AKE_USDT|0.030026|-4.99|3.45|-5.28|19236724|0.33|
|NIL_USDT|0.083030|-4.43|-4.11|-4.72|5695473|1.20|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.030026|0.029790|0.030022|0.63|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.737600|1.816900|1.737600|2.88|Y|Y/Y|Y/Y|Y|Y|
|NIL_USDT|0.083030|0.081680|0.083030|0.96|N|Y/Y|Y/N|Y|N|
|STRK_USDT|0.078700|0.076230|0.078700|1.78|N|Y/Y|Y/Y|Y|N|
|ZEREBRO_USDT|0.041889|0.045600|0.041878|3.87|Y|N/N|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-16T11:14:59+00:00, last15m_closed_end=2026-10-16T11:15+00:00, prior8high=0.031827, depth_time=2026-10-16T11:15:14+00:00, book20_bid_proxy_usdt=18456, book20_ask_proxy_usdt=12143, funding_indicative=0.000050, next_funding_utc=2026-10-16T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.99%, turnover=19236724. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-16T11:14:59+00:00, last15m_closed_end=2026-10-16T11:15+00:00, prior8high=2.088200, depth_time=2026-10-16T11:15:11+00:00, book20_bid_proxy_usdt=6330, book20_ask_proxy_usdt=4285, funding_indicative=-0.000749, next_funding_utc=2026-10-16T12:00:00+00:00, funding_cycle_h=4, 24h_change=-8.90%, turnover=21281956. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NIL_USDT: quote_utc=2026-10-16T11:14:59+00:00, last15m_closed_end=2026-10-16T11:15+00:00, prior8high=0.084570, depth_time=2026-10-16T11:15:16+00:00, book20_bid_proxy_usdt=21042, book20_ask_proxy_usdt=39882, funding_indicative=0.000050, next_funding_utc=2026-10-16T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.43%, turnover=5695473. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-16T11:14:59+00:00, last15m_closed_end=2026-10-16T11:15+00:00, prior8high=0.079390, depth_time=2026-10-16T11:15:09+00:00, book20_bid_proxy_usdt=264535, book20_ask_proxy_usdt=228684, funding_indicative=0.000017, next_funding_utc=2026-10-16T12:00:00+00:00, funding_cycle_h=4, 24h_change=-18.32%, turnover=40054874. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEREBRO_USDT: quote_utc=2026-10-16T11:14:59+00:00, last15m_closed_end=2026-10-16T11:15+00:00, prior8high=0.055777, depth_time=2026-10-16T11:15:07+00:00, book20_bid_proxy_usdt=6888, book20_ask_proxy_usdt=15096, funding_indicative=0.000050, next_funding_utc=2026-10-16T12:00:00+00:00, funding_cycle_h=4, 24h_change=-18.33%, turnover=5250552. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
