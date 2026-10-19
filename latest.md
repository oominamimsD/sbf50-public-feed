# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T05:45:16Z**
- feed_generated_utc: 2026-10-19T05:45:18+00:00
- source_sha256: `1ba394460af0ccb118f80208f88820883308cebef62926bc992ee39a8ad6c7d2`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T05:45+00:00, close=82639.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-19T05:00+00:00, close=82748.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-19T04:00+00:00, close=82496.1, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.060260|-2.11|-49.47|-3.96|17784789|1.66|
|HBAR_USDT|0.084020|-2.05|-10.40|-3.90|50930763|1.19|
|TIA_USDT|0.612300|-0.90|4.00|-2.75|57830508|1.63|
|ICNT_USDT|0.177900|-0.83|67.83|-2.68|7501771|5.63|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|HBAR_USDT|0.084020|0.083810|0.084020|0.83|N|Y/Y|Y/Y|N|N|
|ICNT_USDT|0.177900|0.171100|0.177400|1.37|N|N/Y|N/N|N|N|
|STRK_USDT|0.060260|0.059440|0.060260|1.12|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.612300|0.604400|0.612300|1.42|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- HBAR_USDT: quote_utc=2026-10-19T05:44:59+00:00, last15m_closed_end=2026-10-19T05:45+00:00, prior8high=0.084640, depth_time=2026-10-19T05:45:10+00:00, book20_bid_proxy_usdt=749943, book20_ask_proxy_usdt=991610, funding_indicative=-0.000041, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.05%, turnover=50930763. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-19T05:44:59+00:00, last15m_closed_end=2026-10-19T05:45+00:00, prior8high=0.194500, depth_time=2026-10-19T05:45:16+00:00, book20_bid_proxy_usdt=157230, book20_ask_proxy_usdt=108635, funding_indicative=-0.000146, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.83%, turnover=7501771. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-19T05:44:59+00:00, last15m_closed_end=2026-10-19T05:45+00:00, prior8high=0.060780, depth_time=2026-10-19T05:45:07+00:00, book20_bid_proxy_usdt=811647, book20_ask_proxy_usdt=560054, funding_indicative=0.000050, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.11%, turnover=17784789. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-19T05:44:59+00:00, last15m_closed_end=2026-10-19T05:45+00:00, prior8high=0.617900, depth_time=2026-10-19T05:45:13+00:00, book20_bid_proxy_usdt=324568, book20_ask_proxy_usdt=289578, funding_indicative=-0.000001, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.90%, turnover=57830508. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
