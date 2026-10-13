# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T22:45:13Z**
- feed_generated_utc: 2026-10-13T22:45:15+00:00
- source_sha256: `425751e63def3ca3e3335e8020185cee9598a0d05b1dceb19990e5c7740331c1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T22:45+00:00, close=83485, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-13T22:00+00:00, close=83487.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-13T20:00+00:00, close=83253, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|RLC_USDT|0.894900|-3.06|9.16|-3.17|5386477|1.12|
|STRK_USDT|0.084600|-2.68|62.10|-2.79|40811385|2.36|
|CT_USDT|0.364130|-2.05|-2.01|-2.16|5548465|1.37|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|CT_USDT|0.364130|0.354740|0.364130|0.74|N|Y/Y|N/N|N|N|
|RLC_USDT|0.894900|0.882500|0.894900|0.08|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.084600|0.082530|0.084600|0.87|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- CT_USDT: quote_utc=2026-10-13T22:44:59+00:00, last15m_closed_end=2026-10-13T22:45+00:00, prior8high=0.367810, depth_time=2026-10-13T22:45:12+00:00, book20_bid_proxy_usdt=11274, book20_ask_proxy_usdt=8207, funding_indicative=0.000050, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.05%, turnover=5548465. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-13T22:44:59+00:00, last15m_closed_end=2026-10-13T22:45+00:00, prior8high=0.903000, depth_time=2026-10-13T22:45:07+00:00, book20_bid_proxy_usdt=72611, book20_ask_proxy_usdt=79754, funding_indicative=-0.000448, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.06%, turnover=5386477. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-13T22:44:59+00:00, last15m_closed_end=2026-10-13T22:45+00:00, prior8high=0.085880, depth_time=2026-10-13T22:45:09+00:00, book20_bid_proxy_usdt=124218, book20_ask_proxy_usdt=352836, funding_indicative=0.000011, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.68%, turnover=40811385. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
