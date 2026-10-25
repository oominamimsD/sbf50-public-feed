# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T20:00:15Z**
- feed_generated_utc: 2026-10-25T20:00:18+00:00
- source_sha256: `fd57c7727554f44a8cc646ac76911d53abef62429993b3d1d881c632c1687520`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T20:00+00:00, close=80530.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-25T20:00+00:00, close=80530.1, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-10-25T20:00+00:00, close=80530.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.036290|-5.59|197.45|-5.51|20441590|2.76|
|XMR_USDT|596.190000|-1.99|2.35|-1.91|6838233|0.17|
|USELESS_USDT|0.169050|-1.86|19.52|-1.78|5200292|1.18|
|T_USDT|0.005365|-1.61|14.10|-1.53|8465582|3.73|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|IRYS_USDT|0.036290|0.035650|0.036260|0.64|N|Y/Y|Y/Y|Y|N|
|T_USDT|0.005365|0.005328|0.005365|0.62|N|Y/Y|N/N|Y|N|
|USELESS_USDT|0.169050|0.166550|0.169050|0.62|N|Y/Y|N/N|Y|N|
|XMR_USDT|596.190000|594.720000|596.190000|1.63|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- IRYS_USDT: quote_utc=2026-10-25T20:00:01+00:00, last15m_closed_end=2026-10-25T20:00+00:00, prior8high=0.037780, depth_time=2026-10-25T20:00:07+00:00, book20_bid_proxy_usdt=74130, book20_ask_proxy_usdt=68685, funding_indicative=-0.000018, next_funding_utc=2026-10-25T21:00:00+00:00, funding_cycle_h=1, 24h_change=-5.59%, turnover=20441590. target_RR/account_short_permission/settled_funding=UNKNOWN.
- T_USDT: quote_utc=2026-10-25T20:00:01+00:00, last15m_closed_end=2026-10-25T20:00+00:00, prior8high=0.005560, depth_time=2026-10-25T20:00:14+00:00, book20_bid_proxy_usdt=62548, book20_ask_proxy_usdt=132433, funding_indicative=-0.002554, next_funding_utc=2026-10-25T21:00:00+00:00, funding_cycle_h=1, 24h_change=-1.61%, turnover=8465582. target_RR/account_short_permission/settled_funding=UNKNOWN.
- USELESS_USDT: quote_utc=2026-10-25T20:00:01+00:00, last15m_closed_end=2026-10-25T20:00+00:00, prior8high=0.169980, depth_time=2026-10-25T20:00:12+00:00, book20_bid_proxy_usdt=16183, book20_ask_proxy_usdt=23909, funding_indicative=0.000144, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.86%, turnover=5200292. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-25T20:00:01+00:00, last15m_closed_end=2026-10-25T20:00+00:00, prior8high=605.330000, depth_time=2026-10-25T20:00:09+00:00, book20_bid_proxy_usdt=34398, book20_ask_proxy_usdt=24170, funding_indicative=0.000100, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.99%, turnover=6838233. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
