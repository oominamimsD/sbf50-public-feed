# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T02:15:16Z**
- feed_generated_utc: 2026-10-20T02:15:18+00:00
- source_sha256: `c414f67044543dba936c22f0bd6f25ee9e1082f917bbdeb4d4c3b4cae671dddc`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T02:15+00:00, close=81640.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-20T02:00+00:00, close=81765.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T00:00+00:00, close=81903.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|NEAR_USDT|4.800000|-2.12|-13.49|-1.79|168216187|2.08|
|SAND_USDT|0.057910|-2.07|-6.73|-1.74|9078002|1.73|
|ZRO_USDT|1.862600|-2.07|-17.62|-1.74|7609897|0.54|
|PUMPFUN_USDT|0.004394|-1.39|-17.23|-1.06|34361435|2.28|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|NEAR_USDT|4.800000|4.785000|4.801000|1.85|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004394|0.004327|0.004394|0.54|N|Y/N|N/N|Y|N|
|SAND_USDT|0.057910|0.057130|0.057910|5.37|N|Y/Y|N/Y|Y|N|
|ZRO_USDT|1.862600|1.833600|1.863500|1.57|N|Y/N|N/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- NEAR_USDT: quote_utc=2026-10-20T02:15:03+00:00, last15m_closed_end=2026-10-20T02:15+00:00, prior8high=4.912000, depth_time=2026-10-20T02:15:08+00:00, book20_bid_proxy_usdt=2368248, book20_ask_proxy_usdt=1177551, funding_indicative=0.000057, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.12%, turnover=168216187. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-20T02:15:03+00:00, last15m_closed_end=2026-10-20T02:15+00:00, prior8high=0.004486, depth_time=2026-10-20T02:15:15+00:00, book20_bid_proxy_usdt=858989, book20_ask_proxy_usdt=1108228, funding_indicative=0.000021, next_funding_utc=2026-10-20T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.39%, turnover=34361435. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-20T02:15:03+00:00, last15m_closed_end=2026-10-20T02:15+00:00, prior8high=0.059200, depth_time=2026-10-20T02:15:10+00:00, book20_bid_proxy_usdt=553404, book20_ask_proxy_usdt=517422, funding_indicative=-0.002327, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.07%, turnover=9078002. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-20T02:15:03+00:00, last15m_closed_end=2026-10-20T02:15+00:00, prior8high=1.919400, depth_time=2026-10-20T02:15:13+00:00, book20_bid_proxy_usdt=52818, book20_ask_proxy_usdt=48491, funding_indicative=0.000050, next_funding_utc=2026-10-20T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.07%, turnover=7609897. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
