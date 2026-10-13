# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T20:00:15Z**
- feed_generated_utc: 2026-10-13T20:00:18+00:00
- source_sha256: `aab12c03f7179cb8dbd0ec01ad7edbb1529277f48a1f475fac9697f2cd8cada7`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T20:00+00:00, close=83253, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-13T20:00+00:00, close=83253, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-13T20:00+00:00, close=83253, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|CT_USDT|0.353940|-4.79|-4.75|-4.63|5871415|1.13|
|RLC_USDT|0.894900|-3.06|9.16|-2.90|5795322|2.24|
|DOS_USDT|0.210100|-2.41|-2.50|-2.25|9523301|9.52|
|STRK_USDT|0.085750|-1.35|64.30|-1.19|45277753|1.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|CT_USDT|0.353940|0.351440|0.353860|0.61|N|Y/Y|N/N|N|N|
|DOS_USDT|0.210100|0.206400|0.210100|0.55|N|Y/Y|Y/Y|N|N|
|RLC_USDT|0.894900|0.874600|0.894900|0.29|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.085750|0.083140|0.085750|0.66|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- CT_USDT: quote_utc=2026-10-13T19:59:59+00:00, last15m_closed_end=2026-10-13T20:00+00:00, prior8high=0.372120, depth_time=2026-10-13T20:00:08+00:00, book20_bid_proxy_usdt=7731, book20_ask_proxy_usdt=9103, funding_indicative=0.000050, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.79%, turnover=5871415. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOS_USDT: quote_utc=2026-10-13T19:59:59+00:00, last15m_closed_end=2026-10-13T20:00+00:00, prior8high=0.214000, depth_time=2026-10-13T20:00:12+00:00, book20_bid_proxy_usdt=105244, book20_ask_proxy_usdt=80585, funding_indicative=-0.000112, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.41%, turnover=9523301. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-13T19:59:59+00:00, last15m_closed_end=2026-10-13T20:00+00:00, prior8high=0.908000, depth_time=2026-10-13T20:00:09+00:00, book20_bid_proxy_usdt=61172, book20_ask_proxy_usdt=80831, funding_indicative=-0.000556, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.06%, turnover=5795322. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-13T19:59:59+00:00, last15m_closed_end=2026-10-13T20:00+00:00, prior8high=0.089710, depth_time=2026-10-13T20:00:13+00:00, book20_bid_proxy_usdt=150492, book20_ask_proxy_usdt=242635, funding_indicative=0.000050, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.35%, turnover=45277753. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
