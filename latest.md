# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T23:45:18Z**
- feed_generated_utc: 2026-10-14T23:45:20+00:00
- source_sha256: `810deee775d3c4f780b6a40d99b7a405fedfac39f340acb42a17571352e33399`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T23:45+00:00, close=81563.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T23:00+00:00, close=81624.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-14T20:00+00:00, close=81798.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|FET_USDT|0.197100|-3.33|-12.98|-3.29|10811100|5.08|
|BAT_USDT|0.170740|-2.10|72.18|-2.06|25145709|0.59|
|S_USDT|0.053820|-1.77|35.09|-1.73|5323982|1.86|
|AAVE_USDT|154.070000|-1.16|-10.29|-1.12|26629505|0.65|
|LDO_USDT|0.401500|-1.05|-6.05|-1.01|5134308|2.49|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|154.070000|152.860000|154.090000|0.46|N|Y/Y|Y/Y|Y|N|
|BAT_USDT|0.170740|0.167970|0.170740|0.59|N|Y/Y|Y/N|Y|N|
|FET_USDT|0.197100|0.196400|0.197100|0.16|N|Y/Y|Y/Y|Y|N|
|LDO_USDT|0.401500|0.398100|0.401500|0.44|N|Y/Y|Y/Y|Y|N|
|S_USDT|0.053820|0.052410|0.053820|0.29|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-14T23:45:00+00:00, last15m_closed_end=2026-10-14T23:45+00:00, prior8high=154.420000, depth_time=2026-10-14T23:45:15+00:00, book20_bid_proxy_usdt=301435, book20_ask_proxy_usdt=312254, funding_indicative=0.000072, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.16%, turnover=26629505. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-14T23:45:00+00:00, last15m_closed_end=2026-10-14T23:45+00:00, prior8high=0.171730, depth_time=2026-10-14T23:45:09+00:00, book20_bid_proxy_usdt=30356, book20_ask_proxy_usdt=31973, funding_indicative=0.000058, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.10%, turnover=25145709. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-14T23:45:00+00:00, last15m_closed_end=2026-10-14T23:45+00:00, prior8high=0.198600, depth_time=2026-10-14T23:45:03+00:00, book20_bid_proxy_usdt=1039886, book20_ask_proxy_usdt=1106141, funding_indicative=0.000064, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.33%, turnover=10811100. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LDO_USDT: quote_utc=2026-10-14T23:45:00+00:00, last15m_closed_end=2026-10-14T23:45+00:00, prior8high=0.402400, depth_time=2026-10-14T23:45:18+00:00, book20_bid_proxy_usdt=575169, book20_ask_proxy_usdt=468932, funding_indicative=-0.000070, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.05%, turnover=5134308. target_RR/account_short_permission/settled_funding=UNKNOWN.
- S_USDT: quote_utc=2026-10-14T23:45:00+00:00, last15m_closed_end=2026-10-14T23:45+00:00, prior8high=0.053880, depth_time=2026-10-14T23:45:12+00:00, book20_bid_proxy_usdt=164676, book20_ask_proxy_usdt=192600, funding_indicative=-0.000099, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.77%, turnover=5323982. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
