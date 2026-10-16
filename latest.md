# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T11:45:17Z**
- feed_generated_utc: 2026-10-16T11:45:18+00:00
- source_sha256: `edd987feb2b3bf5364b40b9229ccd1a653cbe76056b13e662d25151d940c44f7`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T11:45+00:00, close=82660, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-16T11:00+00:00, close=82175.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-16T08:00+00:00, close=82258.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZEREBRO_USDT|0.041854|-18.40|52.43|-18.74|5460526|6.91|
|STRK_USDT|0.079830|-17.15|32.69|-17.49|41103034|1.25|
|BTW_USDT|1.647200|-13.64|18.64|-13.98|22441410|2.43|
|AKE_USDT|0.029634|-6.23|2.10|-6.57|19381387|0.34|
|NIL_USDT|0.082440|-5.11|-4.79|-5.45|5726845|4.86|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.029634|0.029661|0.029634|0.60|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.647200|1.632500|1.648100|1.90|N|Y/Y|Y/Y|Y|N|
|NIL_USDT|0.082440|0.081680|0.082420|0.80|N|Y/Y|Y/N|Y|N|
|STRK_USDT|0.079830|0.075950|0.079830|1.96|N|Y/Y|Y/Y|Y|N|
|ZEREBRO_USDT|0.041854|0.038826|0.041854|3.98|N|N/N|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-16T11:44:59+00:00, last15m_closed_end=2026-10-16T11:45+00:00, prior8high=0.030391, depth_time=2026-10-16T11:45:14+00:00, book20_bid_proxy_usdt=15485, book20_ask_proxy_usdt=12835, funding_indicative=0.000050, next_funding_utc=2026-10-16T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.23%, turnover=19381387. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-16T11:44:59+00:00, last15m_closed_end=2026-10-16T11:45+00:00, prior8high=2.028200, depth_time=2026-10-16T11:45:11+00:00, book20_bid_proxy_usdt=8451, book20_ask_proxy_usdt=9625, funding_indicative=-0.000790, next_funding_utc=2026-10-16T12:00:00+00:00, funding_cycle_h=4, 24h_change=-13.64%, turnover=22441410. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NIL_USDT: quote_utc=2026-10-16T11:44:59+00:00, last15m_closed_end=2026-10-16T11:45+00:00, prior8high=0.084570, depth_time=2026-10-16T11:45:15+00:00, book20_bid_proxy_usdt=36632, book20_ask_proxy_usdt=15550, funding_indicative=0.000050, next_funding_utc=2026-10-16T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.11%, turnover=5726845. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-16T11:44:59+00:00, last15m_closed_end=2026-10-16T11:45+00:00, prior8high=0.080030, depth_time=2026-10-16T11:45:09+00:00, book20_bid_proxy_usdt=264276, book20_ask_proxy_usdt=233018, funding_indicative=-0.000004, next_funding_utc=2026-10-16T12:00:00+00:00, funding_cycle_h=4, 24h_change=-17.15%, turnover=41103034. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEREBRO_USDT: quote_utc=2026-10-16T11:44:59+00:00, last15m_closed_end=2026-10-16T11:45+00:00, prior8high=0.055777, depth_time=2026-10-16T11:45:07+00:00, book20_bid_proxy_usdt=26218, book20_ask_proxy_usdt=8165, funding_indicative=0.000050, next_funding_utc=2026-10-16T12:00:00+00:00, funding_cycle_h=4, 24h_change=-18.40%, turnover=5460526. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
