# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T22:15:12Z**
- feed_generated_utc: 2026-10-13T22:15:15+00:00
- source_sha256: `bbd5b4d2323e5a1b31806e662e6ac421aa9c87d47a95f71dd41f138e063be3e7`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T22:15+00:00, close=83384.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-13T22:00+00:00, close=83487.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-13T20:00+00:00, close=83253, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.083140|-4.35|59.30|-4.34|40271546|1.20|
|CT_USDT|0.360280|-3.08|-3.04|-3.07|5536474|1.39|
|RLC_USDT|0.895300|-3.02|9.20|-3.01|5355431|1.11|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|CT_USDT|0.360280|0.352570|0.360280|1.05|N|Y/Y|N/N|N|N|
|RLC_USDT|0.895300|0.878300|0.895300|0.38|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.083140|0.083530|0.083140|1.95|Y|Y/Y|Y/Y|N|Y|

## Detailed time markers and risk references (NOT executable limits)
- CT_USDT: quote_utc=2026-10-13T22:15:02+00:00, last15m_closed_end=2026-10-13T22:15+00:00, prior8high=0.367810, depth_time=2026-10-13T22:15:09+00:00, book20_bid_proxy_usdt=12912, book20_ask_proxy_usdt=12127, funding_indicative=0.000050, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.08%, turnover=5536474. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-13T22:15:02+00:00, last15m_closed_end=2026-10-13T22:15+00:00, prior8high=0.901800, depth_time=2026-10-13T22:15:10+00:00, book20_bid_proxy_usdt=68098, book20_ask_proxy_usdt=121421, funding_indicative=-0.000481, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.02%, turnover=5355431. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-13T22:15:02+00:00, last15m_closed_end=2026-10-13T22:15+00:00, prior8high=0.085920, depth_time=2026-10-13T22:15:06+00:00, book20_bid_proxy_usdt=179417, book20_ask_proxy_usdt=181949, funding_indicative=0.000005, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.35%, turnover=40271546. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
