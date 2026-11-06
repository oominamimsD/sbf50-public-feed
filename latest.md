# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T03:30:23Z**
- feed_generated_utc: 2026-11-06T03:30:24+00:00
- source_sha256: `6b14a07dbf16e5725991a0324566bdee4ad3d51cdeea46308020fe99ca85412e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T03:30+00:00, close=75946.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-06T03:00+00:00, close=76162.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T00:00+00:00, close=76050.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ELSA_USDT|0.077830|-4.09|4.19|-4.01|6974204|5.14|
|FLUID_USDT|2.430000|-4.02|17.73|-3.94|6911778|4.12|
|JCT_USDT|0.002866|-3.30|-50.18|-3.22|12258573|3.49|
|XRP_USDT|1.208700|-2.88|-7.69|-2.80|423465816|0.83|
|XPL_USDT|0.057160|-2.42|-27.58|-2.34|12531449|1.75|
|ZRO_USDT|1.593500|-1.76|-9.68|-1.68|7159093|0.63|
|HYPE_USDT|77.522000|-1.49|-17.47|-1.41|86089523|0.13|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ELSA_USDT|0.077830|0.077650|0.077830|0.81|N|Y/Y|N/N|Y|N|
|FLUID_USDT|2.430000|2.394000|2.430000|0.60|N|Y/Y|N/N|Y|N|
|HYPE_USDT|77.522000|77.111000|77.520000|1.17|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.002866|0.002706|0.002866|2.14|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.057160|0.056870|0.057160|0.79|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.208700|1.211600|1.208700|2.05|Y|Y/Y|Y/Y|Y|Y|
|ZRO_USDT|1.593500|1.590700|1.593500|0.49|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ELSA_USDT: quote_utc=2026-11-06T03:29:59+00:00, last15m_closed_end=2026-11-06T03:30+00:00, prior8high=0.082580, depth_time=2026-11-06T03:30:06+00:00, book20_bid_proxy_usdt=17165, book20_ask_proxy_usdt=24659, funding_indicative=0.000050, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.09%, turnover=6974204. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FLUID_USDT: quote_utc=2026-11-06T03:29:59+00:00, last15m_closed_end=2026-11-06T03:30+00:00, prior8high=2.468000, depth_time=2026-11-06T03:30:07+00:00, book20_bid_proxy_usdt=242405, book20_ask_proxy_usdt=150514, funding_indicative=0.000169, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.02%, turnover=6911778. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-06T03:30:00+00:00, last15m_closed_end=2026-11-06T03:30+00:00, prior8high=78.260000, depth_time=2026-11-06T03:30:21+00:00, book20_bid_proxy_usdt=264531, book20_ask_proxy_usdt=79636, funding_indicative=0.000050, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.49%, turnover=86089523. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-06T03:30:00+00:00, last15m_closed_end=2026-11-06T03:30+00:00, prior8high=0.003382, depth_time=2026-11-06T03:30:12+00:00, book20_bid_proxy_usdt=60333, book20_ask_proxy_usdt=90822, funding_indicative=0.000109, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.30%, turnover=12258573. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-06T03:30:00+00:00, last15m_closed_end=2026-11-06T03:30+00:00, prior8high=0.058050, depth_time=2026-11-06T03:30:17+00:00, book20_bid_proxy_usdt=372810, book20_ask_proxy_usdt=422930, funding_indicative=0.000050, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.42%, turnover=12531449. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-06T03:29:59+00:00, last15m_closed_end=2026-11-06T03:30+00:00, prior8high=1.222500, depth_time=2026-11-06T03:30:14+00:00, book20_bid_proxy_usdt=4028633, book20_ask_proxy_usdt=2491862, funding_indicative=0.000100, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.88%, turnover=423465816. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-06T03:30:00+00:00, last15m_closed_end=2026-11-06T03:30+00:00, prior8high=1.616700, depth_time=2026-11-06T03:30:20+00:00, book20_bid_proxy_usdt=97754, book20_ask_proxy_usdt=62806, funding_indicative=0.000050, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.76%, turnover=7159093. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
