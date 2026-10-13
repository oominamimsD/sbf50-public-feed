# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T20:45:16Z**
- feed_generated_utc: 2026-10-13T20:45:18+00:00
- source_sha256: `9e22fb58c703b2a2941af2969b71f475cf1c7b8bc23de330807a3c7c9c9a1632`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T20:45+00:00, close=83324.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-13T20:00+00:00, close=83253, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-13T20:00+00:00, close=83253, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|RLC_USDT|0.887200|-3.89|8.22|-3.81|5697832|1.13|
|CT_USDT|0.358540|-3.55|-3.51|-3.47|5795394|0.28|
|DOS_USDT|0.208800|-3.01|-3.10|-2.93|9338464|4.79|
|STRK_USDT|0.085030|-2.18|62.92|-2.10|42304565|1.18|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|CT_USDT|0.358540|0.351000|0.358540|0.57|N|Y/Y|N/N|N|N|
|DOS_USDT|0.208800|0.206400|0.208800|1.40|N|Y/Y|Y/Y|N|N|
|RLC_USDT|0.887200|0.878300|0.887200|0.48|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.085030|0.084500|0.085030|1.49|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- CT_USDT: quote_utc=2026-10-13T20:44:59+00:00, last15m_closed_end=2026-10-13T20:45+00:00, prior8high=0.361890, depth_time=2026-10-13T20:45:09+00:00, book20_bid_proxy_usdt=7005, book20_ask_proxy_usdt=8401, funding_indicative=0.000050, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.55%, turnover=5795394. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOS_USDT: quote_utc=2026-10-13T20:44:59+00:00, last15m_closed_end=2026-10-13T20:45+00:00, prior8high=0.214000, depth_time=2026-10-13T20:45:11+00:00, book20_bid_proxy_usdt=117840, book20_ask_proxy_usdt=90337, funding_indicative=-0.000139, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.01%, turnover=9338464. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-13T20:44:59+00:00, last15m_closed_end=2026-10-13T20:45+00:00, prior8high=0.908000, depth_time=2026-10-13T20:45:07+00:00, book20_bid_proxy_usdt=65772, book20_ask_proxy_usdt=64344, funding_indicative=-0.000498, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.89%, turnover=5697832. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-13T20:44:59+00:00, last15m_closed_end=2026-10-13T20:45+00:00, prior8high=0.089710, depth_time=2026-10-13T20:45:14+00:00, book20_bid_proxy_usdt=275274, book20_ask_proxy_usdt=214644, funding_indicative=0.000029, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.18%, turnover=42304565. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
