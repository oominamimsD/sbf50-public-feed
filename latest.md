# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T22:30:20Z**
- feed_generated_utc: 2026-10-25T22:30:22+00:00
- source_sha256: `e5c75ee2abb831f889c65bd40b0261adb27922ba3fb7a451fd01bbd43ac57db1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T22:30+00:00, close=80463.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-25T22:00+00:00, close=80235.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-25T20:00+00:00, close=80530.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.006744|-3.27|265.92|-3.09|9678953|2.97|
|IRYS_USDT|0.037460|-2.54|207.04|-2.36|20087990|2.67|
|USELESS_USDT|0.168910|-2.12|19.42|-1.94|5127793|1.18|
|XMR_USDT|594.720000|-2.06|2.09|-1.88|6682893|0.17|
|DASH_USDT|51.640000|-1.46|7.85|-1.28|14220630|1.94|
|PEPE_USDT|0.000004|-1.19|12.68|-1.01|74414398|0.23|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DASH_USDT|51.640000|51.310000|51.640000|1.50|N|Y/Y|N/N|Y|N|
|IRYS_USDT|0.037460|0.035580|0.037480|0.76|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.006744|0.006816|0.006744|1.06|N|N/N|N/N|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|1.02|N|Y/Y|Y/Y|Y|N|
|USELESS_USDT|0.168910|0.167580|0.168910|1.90|N|Y/Y|N/N|Y|N|
|XMR_USDT|594.720000|594.140000|594.720000|2.35|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DASH_USDT: quote_utc=2026-10-25T22:30:00+00:00, last15m_closed_end=2026-10-25T22:30+00:00, prior8high=52.260000, depth_time=2026-10-25T22:30:15+00:00, book20_bid_proxy_usdt=392710, book20_ask_proxy_usdt=508129, funding_indicative=0.000100, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.46%, turnover=14220630. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T22:30:03+00:00, last15m_closed_end=2026-10-25T22:30+00:00, prior8high=0.037530, depth_time=2026-10-25T22:30:09+00:00, book20_bid_proxy_usdt=64708, book20_ask_proxy_usdt=56502, funding_indicative=-0.000161, next_funding_utc=2026-10-25T23:00:00+00:00, funding_cycle_h=1, 24h_change=-2.54%, turnover=20087990. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-10-25T22:30:03+00:00, last15m_closed_end=2026-10-25T22:30+00:00, prior8high=0.006991, depth_time=2026-10-25T22:30:07+00:00, book20_bid_proxy_usdt=42180, book20_ask_proxy_usdt=52911, funding_indicative=0.000221, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.27%, turnover=9678953. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-25T22:30:00+00:00, last15m_closed_end=2026-10-25T22:30+00:00, prior8high=0.000004, depth_time=2026-10-25T22:30:19+00:00, book20_bid_proxy_usdt=60520, book20_ask_proxy_usdt=199720, funding_indicative=0.000048, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.19%, turnover=74414398. target_RR/account_short_permission/settled_funding=UNKNOWN.
- USELESS_USDT: quote_utc=2026-10-25T22:30:00+00:00, last15m_closed_end=2026-10-25T22:30+00:00, prior8high=0.171640, depth_time=2026-10-25T22:30:12+00:00, book20_bid_proxy_usdt=10315, book20_ask_proxy_usdt=15847, funding_indicative=0.000060, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.12%, turnover=5127793. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-25T22:30:03+00:00, last15m_closed_end=2026-10-25T22:30+00:00, prior8high=605.460000, depth_time=2026-10-25T22:30:10+00:00, book20_bid_proxy_usdt=12889, book20_ask_proxy_usdt=18857, funding_indicative=0.000100, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.06%, turnover=6682893. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
