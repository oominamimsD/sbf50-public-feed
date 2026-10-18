# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T23:00:16Z**
- feed_generated_utc: 2026-10-18T23:00:18+00:00
- source_sha256: `1f827460f586ec63e558c19d3cfb08b257460111ebff8e0056ec995d2bb6f016`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T23:00+00:00, close=81727.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-18T23:00+00:00, close=81727.3, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-18T20:00+00:00, close=80844.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.061954|-8.25|250.31|-8.97|10175604|3.23|
|STRK_USDT|0.059870|-2.74|-49.80|-3.46|15959179|1.67|
|SAND_USDT|0.057960|-1.36|-12.76|-2.08|34578427|1.73|
|TIA_USDT|0.610500|-1.19|3.70|-1.91|52606594|1.64|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.061954|0.061280|0.061954|0.57|N|Y/Y|N/N|Y|N|
|SAND_USDT|0.057960|0.056220|0.057960|1.09|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.059870|0.058490|0.059870|0.39|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.610500|0.586400|0.610500|0.60|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-18T22:59:59+00:00, last15m_closed_end=2026-10-18T23:00+00:00, prior8high=0.065678, depth_time=2026-10-18T23:00:07+00:00, book20_bid_proxy_usdt=2678, book20_ask_proxy_usdt=4299, funding_indicative=0.000230, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=4, 24h_change=-8.25%, turnover=10175604. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-18T22:59:59+00:00, last15m_closed_end=2026-10-18T23:00+00:00, prior8high=0.058220, depth_time=2026-10-18T23:00:11+00:00, book20_bid_proxy_usdt=722328, book20_ask_proxy_usdt=828925, funding_indicative=-0.002348, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.36%, turnover=34578427. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T22:59:59+00:00, last15m_closed_end=2026-10-18T23:00+00:00, prior8high=0.061020, depth_time=2026-10-18T23:00:10+00:00, book20_bid_proxy_usdt=676081, book20_ask_proxy_usdt=357489, funding_indicative=0.000050, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.74%, turnover=15959179. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-18T22:59:59+00:00, last15m_closed_end=2026-10-18T23:00+00:00, prior8high=0.612300, depth_time=2026-10-18T23:00:14+00:00, book20_bid_proxy_usdt=219431, book20_ask_proxy_usdt=205750, funding_indicative=0.000001, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.19%, turnover=52606594. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
