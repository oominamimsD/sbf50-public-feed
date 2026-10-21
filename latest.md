# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T13:00:30Z**
- feed_generated_utc: 2026-10-21T13:00:32+00:00
- source_sha256: `f53939067c7bca87c5988ceb32bd0e74fd244b70a3281a32af8d1005157c9382`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1206; contracts: 1198; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T13:00+00:00, close=83471.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T13:00+00:00, close=83471.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T12:00+00:00, close=83464, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.045468|-28.59|181.06|-29.66|6482697|9.01|
|BAT_USDT|0.179910|-16.61|1.42|-17.68|10421835|1.11|
|BTW_USDT|1.579800|-14.58|-19.08|-15.65|24086229|0.64|
|AKE_USDT|0.027080|-12.90|8.03|-13.97|8892744|2.21|
|BR_USDT|0.616590|-8.23|42.39|-9.30|19478165|3.57|
|TIA_USDT|0.624100|-2.62|8.10|-3.69|42942577|1.60|
|INJ_USDT|8.707000|-2.23|11.10|-3.30|67750794|1.15|
|SILVER_USDT|57.590000|-0.62|-3.03|-1.69|216770395|1.74|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.045468|0.044727|0.045468|0.32|N|Y/Y|Y/Y|N|N|
|AKE_USDT|0.027080|0.028134|0.027135|5.95|Y|Y/Y|Y/N|N|N|
|BAT_USDT|0.179910|0.180140|0.179900|0.69|N|Y/Y|Y/Y|N|N|
|BR_USDT|0.616590|0.572580|0.616770|0.99|N|N/Y|N/N|N|N|
|BTW_USDT|1.579800|1.562500|1.579600|0.99|N|Y/Y|Y/Y|N|N|
|INJ_USDT|8.707000|8.712000|8.707000|0.39|N|Y/Y|N/N|N|N|
|SILVER_USDT|57.590000|57.450000|57.610000|0.48|N|N/N|N/N|N|N|
|TIA_USDT|0.624100|0.615000|0.624100|0.86|N|N/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-21T13:00:01+00:00, last15m_closed_end=2026-10-21T13:00+00:00, prior8high=0.048022, depth_time=2026-10-21T13:00:08+00:00, book20_bid_proxy_usdt=9375, book20_ask_proxy_usdt=5573, funding_indicative=0.000047, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-28.59%, turnover=6482697. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-10-21T13:00:01+00:00, last15m_closed_end=2026-10-21T13:00+00:00, prior8high=0.036629, depth_time=2026-10-21T13:00:17+00:00, book20_bid_proxy_usdt=12304, book20_ask_proxy_usdt=12421, funding_indicative=0.000050, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-12.90%, turnover=8892744. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T13:00:01+00:00, last15m_closed_end=2026-10-21T13:00+00:00, prior8high=0.182860, depth_time=2026-10-21T13:00:11+00:00, book20_bid_proxy_usdt=26852, book20_ask_proxy_usdt=21614, funding_indicative=-0.000167, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=-16.61%, turnover=10421835. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T13:00:01+00:00, last15m_closed_end=2026-10-21T13:00+00:00, prior8high=0.619000, depth_time=2026-10-21T13:00:19+00:00, book20_bid_proxy_usdt=4266, book20_ask_proxy_usdt=5199, funding_indicative=-0.000029, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.23%, turnover=19478165. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-21T13:00:01+00:00, last15m_closed_end=2026-10-21T13:00+00:00, prior8high=1.787000, depth_time=2026-10-21T13:00:14+00:00, book20_bid_proxy_usdt=11403, book20_ask_proxy_usdt=8407, funding_indicative=-0.005286, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-14.58%, turnover=24086229. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-21T13:00:01+00:00, last15m_closed_end=2026-10-21T13:00+00:00, prior8high=8.871000, depth_time=2026-10-21T13:00:24+00:00, book20_bid_proxy_usdt=253424, book20_ask_proxy_usdt=202968, funding_indicative=0.000098, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.23%, turnover=67750794. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-21T13:00:01+00:00, last15m_closed_end=2026-10-21T13:00+00:00, prior8high=57.860000, depth_time=2026-10-21T13:00:28+00:00, book20_bid_proxy_usdt=39343804, book20_ask_proxy_usdt=28095398, funding_indicative=0.000046, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-0.62%, turnover=216770395. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T13:00:01+00:00, last15m_closed_end=2026-10-21T13:00+00:00, prior8high=0.626700, depth_time=2026-10-21T13:00:22+00:00, book20_bid_proxy_usdt=192596, book20_ask_proxy_usdt=238722, funding_indicative=-0.000078, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.62%, turnover=42942577. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
