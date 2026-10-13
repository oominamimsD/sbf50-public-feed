# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T21:45:15Z**
- feed_generated_utc: 2026-10-13T21:45:18+00:00
- source_sha256: `d33f3104af158ea28cdf4bb4d3435c5b59130be1a7cfdf332e7b1e096156efba`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T21:45+00:00, close=83424.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-13T21:00+00:00, close=83379.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-13T20:00+00:00, close=83253, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DOS_USDT|0.208600|-3.11|-3.20|-3.14|8624232|4.79|
|RLC_USDT|0.895300|-3.02|9.20|-3.05|5529036|2.23|
|CT_USDT|0.361930|-2.64|-2.60|-2.67|5724449|0.55|
|STRK_USDT|0.085000|-2.22|62.86|-2.25|41571631|1.18|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|CT_USDT|0.361930|0.351000|0.361930|0.23|N|N/Y|N/N|N|N|
|DOS_USDT|0.208600|0.207500|0.208700|0.65|N|Y/Y|Y/Y|N|N|
|RLC_USDT|0.895300|0.878300|0.895300|0.39|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.085000|0.083530|0.085000|0.15|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- CT_USDT: quote_utc=2026-10-13T21:45:01+00:00, last15m_closed_end=2026-10-13T21:45+00:00, prior8high=0.367810, depth_time=2026-10-13T21:45:09+00:00, book20_bid_proxy_usdt=14146, book20_ask_proxy_usdt=12027, funding_indicative=0.000050, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.64%, turnover=5724449. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOS_USDT: quote_utc=2026-10-13T21:45:01+00:00, last15m_closed_end=2026-10-13T21:45+00:00, prior8high=0.214000, depth_time=2026-10-13T21:45:07+00:00, book20_bid_proxy_usdt=96193, book20_ask_proxy_usdt=86097, funding_indicative=-0.000308, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.11%, turnover=8624232. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-13T21:45:01+00:00, last15m_closed_end=2026-10-13T21:45+00:00, prior8high=0.897400, depth_time=2026-10-13T21:45:09+00:00, book20_bid_proxy_usdt=58685, book20_ask_proxy_usdt=42321, funding_indicative=-0.000459, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.02%, turnover=5529036. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-13T21:45:01+00:00, last15m_closed_end=2026-10-13T21:45+00:00, prior8high=0.087750, depth_time=2026-10-13T21:45:15+00:00, book20_bid_proxy_usdt=141723, book20_ask_proxy_usdt=206994, funding_indicative=0.000012, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.22%, turnover=41571631. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
