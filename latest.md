# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T12:45:18Z**
- feed_generated_utc: 2026-10-16T12:45:20+00:00
- source_sha256: `f62808700c94b35b415b3eb0d08076a910790fc280626dc2bf337350db2c920b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T12:45+00:00, close=82241.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-16T12:00+00:00, close=82599.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-16T12:00+00:00, close=82599.5, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZEREBRO_USDT|0.040088|-21.84|46.00|-21.68|5075943|2.99|
|STRK_USDT|0.075700|-21.44|25.83|-21.28|40937207|3.96|
|BTW_USDT|1.694600|-11.15|22.06|-10.99|22413679|0.59|
|AKE_USDT|0.029608|-6.31|2.01|-6.15|18321393|0.34|
|NIL_USDT|0.082330|-5.23|-4.91|-5.07|5442898|2.43|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.029608|0.029345|0.029608|0.39|N|Y/Y|N/N|N|N|
|BTW_USDT|1.694600|1.611400|1.694700|0.97|N|Y/Y|Y/Y|N|N|
|NIL_USDT|0.082330|0.081930|0.082330|1.24|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.075700|0.075950|0.075700|1.96|Y|Y/Y|Y/Y|N|Y|
|ZEREBRO_USDT|0.040088|0.037647|0.040088|1.00|N|Y/N|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-16T12:44:59+00:00, last15m_closed_end=2026-10-16T12:45+00:00, prior8high=0.030310, depth_time=2026-10-16T12:45:15+00:00, book20_bid_proxy_usdt=17825, book20_ask_proxy_usdt=13817, funding_indicative=0.000050, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.31%, turnover=18321393. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-16T12:44:59+00:00, last15m_closed_end=2026-10-16T12:45+00:00, prior8high=1.924700, depth_time=2026-10-16T12:45:13+00:00, book20_bid_proxy_usdt=8834, book20_ask_proxy_usdt=12078, funding_indicative=-0.000640, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-11.15%, turnover=22413679. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NIL_USDT: quote_utc=2026-10-16T12:44:59+00:00, last15m_closed_end=2026-10-16T12:45+00:00, prior8high=0.084050, depth_time=2026-10-16T12:45:17+00:00, book20_bid_proxy_usdt=24506, book20_ask_proxy_usdt=22076, funding_indicative=0.000044, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.23%, turnover=5442898. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-16T12:44:59+00:00, last15m_closed_end=2026-10-16T12:45+00:00, prior8high=0.080420, depth_time=2026-10-16T12:45:10+00:00, book20_bid_proxy_usdt=210498, book20_ask_proxy_usdt=329992, funding_indicative=-0.000008, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-21.44%, turnover=40937207. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEREBRO_USDT: quote_utc=2026-10-16T12:44:59+00:00, last15m_closed_end=2026-10-16T12:45+00:00, prior8high=0.052390, depth_time=2026-10-16T12:45:08+00:00, book20_bid_proxy_usdt=6187, book20_ask_proxy_usdt=4397, funding_indicative=0.000050, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-21.84%, turnover=5075943. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
