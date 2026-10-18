# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T17:00:18Z**
- feed_generated_utc: 2026-10-18T17:00:19+00:00
- source_sha256: `23d9c7a45c436e0ffdc7ed975b75ffb56c4000d389d96821d17c9bcdbac11684`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T17:00+00:00, close=81040.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-18T17:00+00:00, close=81040.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-18T16:00+00:00, close=81137.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|2.208700|-5.94|31.29|-5.83|26904468|1.36|
|BAT_USDT|0.172650|-3.11|3.60|-3.00|9951528|0.58|
|AGT_USDT|0.067080|-3.07|279.30|-2.96|10754323|0.30|
|PUMPFUN_USDT|0.004125|-2.64|-28.57|-2.53|29126830|2.42|
|XPL_USDT|0.075710|-1.58|-15.17|-1.47|6315051|1.32|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.067080|0.062242|0.067080|0.66|N|Y/Y|N/N|Y|N|
|BAT_USDT|0.172650|0.172360|0.172650|0.81|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|2.208700|2.189300|2.208700|1.05|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004125|0.004108|0.004125|1.74|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.075710|0.075430|0.075710|0.28|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-18T17:00:01+00:00, last15m_closed_end=2026-10-18T17:00+00:00, prior8high=0.073701, depth_time=2026-10-18T17:00:13+00:00, book20_bid_proxy_usdt=4042, book20_ask_proxy_usdt=2079, funding_indicative=0.000214, next_funding_utc=2026-10-18T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.07%, turnover=10754323. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-18T17:00:01+00:00, last15m_closed_end=2026-10-18T17:00+00:00, prior8high=0.180190, depth_time=2026-10-18T17:00:10+00:00, book20_bid_proxy_usdt=28399, book20_ask_proxy_usdt=24019, funding_indicative=-0.000022, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.11%, turnover=9951528. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-18T17:00:01+00:00, last15m_closed_end=2026-10-18T17:00+00:00, prior8high=2.405100, depth_time=2026-10-18T17:00:08+00:00, book20_bid_proxy_usdt=9712, book20_ask_proxy_usdt=9721, funding_indicative=-0.000410, next_funding_utc=2026-10-18T20:00:00+00:00, funding_cycle_h=4, 24h_change=-5.94%, turnover=26904468. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T17:00:01+00:00, last15m_closed_end=2026-10-18T17:00+00:00, prior8high=0.004252, depth_time=2026-10-18T17:00:15+00:00, book20_bid_proxy_usdt=2056175, book20_ask_proxy_usdt=2004996, funding_indicative=0.000046, next_funding_utc=2026-10-18T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.64%, turnover=29126830. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-10-18T17:00:01+00:00, last15m_closed_end=2026-10-18T17:00+00:00, prior8high=0.077170, depth_time=2026-10-18T17:00:17+00:00, book20_bid_proxy_usdt=320812, book20_ask_proxy_usdt=495136, funding_indicative=0.000016, next_funding_utc=2026-10-18T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.58%, turnover=6315051. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
