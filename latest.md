# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T21:30:17Z**
- feed_generated_utc: 2026-10-25T21:30:20+00:00
- source_sha256: `1863c4a151648d47e192b29a4b44337e911db7f99d7a0d0c5c18ff59b44d7e5c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T21:30+00:00, close=80489, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-25T21:00+00:00, close=80457, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-25T20:00+00:00, close=80530.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.035970|-6.42|194.83|-6.28|20321838|5.56|
|DASH_USDT|51.620000|-1.50|7.81|-1.36|14169600|1.94|
|USELESS_USDT|0.170020|-1.47|20.20|-1.33|5082981|1.18|
|T_USDT|0.005313|-1.30|12.99|-1.16|8533530|5.65|
|XMR_USDT|600.000000|-1.19|3.00|-1.05|6602609|0.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DASH_USDT|51.620000|51.490000|51.610000|1.87|N|Y/N|N/N|Y|N|
|IRYS_USDT|0.035970|0.035580|0.035970|0.32|N|Y/Y|Y/Y|Y|N|
|T_USDT|0.005313|0.005255|0.005313|0.30|N|Y/Y|N/N|Y|N|
|USELESS_USDT|0.170020|0.167500|0.170020|0.30|N|Y/Y|N/N|Y|N|
|XMR_USDT|600.000000|594.720000|600.000000|0.84|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DASH_USDT: quote_utc=2026-10-25T21:30:01+00:00, last15m_closed_end=2026-10-25T21:30+00:00, prior8high=52.300000, depth_time=2026-10-25T21:30:04+00:00, book20_bid_proxy_usdt=624554, book20_ask_proxy_usdt=442474, funding_indicative=0.000100, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.50%, turnover=14169600. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T21:30:01+00:00, last15m_closed_end=2026-10-25T21:30+00:00, prior8high=0.036760, depth_time=2026-10-25T21:30:07+00:00, book20_bid_proxy_usdt=45819, book20_ask_proxy_usdt=65509, funding_indicative=-0.000023, next_funding_utc=2026-10-25T22:00:00+00:00, funding_cycle_h=1, 24h_change=-6.42%, turnover=20321838. target_RR/account_short_permission/settled_funding=UNKNOWN.
- T_USDT: quote_utc=2026-10-25T21:30:01+00:00, last15m_closed_end=2026-10-25T21:30+00:00, prior8high=0.005412, depth_time=2026-10-25T21:30:14+00:00, book20_bid_proxy_usdt=94756, book20_ask_proxy_usdt=135296, funding_indicative=-0.003274, next_funding_utc=2026-10-25T22:00:00+00:00, funding_cycle_h=1, 24h_change=-1.30%, turnover=8533530. target_RR/account_short_permission/settled_funding=UNKNOWN.
- USELESS_USDT: quote_utc=2026-10-25T21:30:01+00:00, last15m_closed_end=2026-10-25T21:30+00:00, prior8high=0.170810, depth_time=2026-10-25T21:30:12+00:00, book20_bid_proxy_usdt=28812, book20_ask_proxy_usdt=29906, funding_indicative=0.000129, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.47%, turnover=5082981. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-25T21:30:01+00:00, last15m_closed_end=2026-10-25T21:30+00:00, prior8high=605.460000, depth_time=2026-10-25T21:30:16+00:00, book20_bid_proxy_usdt=25743, book20_ask_proxy_usdt=19840, funding_indicative=0.000100, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.19%, turnover=6602609. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
