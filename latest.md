# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T17:45:16Z**
- feed_generated_utc: 2026-11-04T17:45:18+00:00
- source_sha256: `8a08e1a330bd6e2ffa4d58ed71db87b5268cb7ac53c0aaefd4deb0112ba307f5`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T17:45+00:00, close=80332.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T17:00+00:00, close=80491.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T16:00+00:00, close=80272.3, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.033850|-5.71|-24.92|-5.78|6059552|5.91|
|AKE_USDT|0.002703|-3.80|-86.54|-3.87|17726475|3.69|
|ZRO_USDT|1.820000|-2.39|6.30|-2.46|11531194|0.55|
|WLFI_USDT|0.046940|-1.79|-10.55|-1.86|6132175|2.13|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.033850|0.033090|0.033850|0.40|N|Y/Y|Y/Y|N|N|
|AKE_USDT|0.002703|0.002421|0.002703|1.19|N|Y/Y|Y/Y|N|N|
|WLFI_USDT|0.046940|0.046600|0.046940|5.23|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.820000|1.806800|1.820000|0.93|N|Y/N|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T17:45:00+00:00, last15m_closed_end=2026-11-04T17:45+00:00, prior8high=0.036400, depth_time=2026-11-04T17:45:05+00:00, book20_bid_proxy_usdt=49002, book20_ask_proxy_usdt=22547, funding_indicative=0.000053, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-5.71%, turnover=6059552. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T17:45:00+00:00, last15m_closed_end=2026-11-04T17:45+00:00, prior8high=0.003055, depth_time=2026-11-04T17:45:10+00:00, book20_bid_proxy_usdt=94884, book20_ask_proxy_usdt=43910, funding_indicative=-0.000310, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.80%, turnover=17726475. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLFI_USDT: quote_utc=2026-11-04T17:45:01+00:00, last15m_closed_end=2026-11-04T17:45+00:00, prior8high=0.049950, depth_time=2026-11-04T17:45:15+00:00, book20_bid_proxy_usdt=174086, book20_ask_proxy_usdt=304712, funding_indicative=0.000050, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.79%, turnover=6132175. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-04T17:45:01+00:00, last15m_closed_end=2026-11-04T17:45+00:00, prior8high=1.907500, depth_time=2026-11-04T17:45:13+00:00, book20_bid_proxy_usdt=28061, book20_ask_proxy_usdt=46589, funding_indicative=0.000050, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.39%, turnover=11531194. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
