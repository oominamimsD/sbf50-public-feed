# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-01T05:45:32Z**
- feed_generated_utc: 2026-11-01T05:45:34+00:00
- source_sha256: `8d8dc1df9150f0bb4aaff27793ed760e9e29b02874cb65c27c317a86ccf4c90d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-01T05:45+00:00, close=77775.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-01T05:00+00:00, close=77770.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-01T04:00+00:00, close=77753.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LSK_USDT|0.241670|-18.39|43.91|-18.66|30779779|2.48|
|XPL_USDT|0.073150|-10.03|1.30|-10.30|5264426|1.37|
|BLESS_USDT|0.009621|-8.92|18.58|-9.19|6567340|6.23|
|AKE_USDT|0.010266|-7.82|-64.87|-8.09|11770757|3.89|
|ENA_USDT|0.187730|-3.23|0.50|-3.50|43250978|0.53|
|ZEC_USDT|1243.870000|-3.16|8.61|-3.43|959322651|0.08|
|NEAR_USDT|4.374000|-2.27|-0.63|-2.54|53248244|2.29|
|XLM_USDT|0.168890|-1.65|0.28|-1.92|20365424|0.59|
|BEAT_USDT|0.097010|-1.55|44.76|-1.82|6106092|1.03|
|WLD_USDT|0.398700|-1.40|-13.70|-1.67|30738907|2.51|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.010266|0.008789|0.010266|1.49|N|Y/Y|Y/Y|Y|N|
|BEAT_USDT|0.097010|0.096720|0.097010|0.87|N|Y/Y|N/N|Y|N|
|BLESS_USDT|0.009621|0.009345|0.009617|0.52|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.187730|0.185670|0.187730|1.20|N|Y/Y|Y/Y|Y|N|
|LSK_USDT|0.241670|0.228320|0.241170|0.58|N|Y/Y|N/N|Y|N|
|NEAR_USDT|4.374000|4.379000|4.373000|3.25|Y|Y/Y|N/N|Y|N|
|WLD_USDT|0.398700|0.398200|0.398800|0.81|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.168890|0.167510|0.168890|1.02|N|Y/Y|Y/N|Y|N|
|XPL_USDT|0.073150|0.069100|0.073160|5.75|N|Y/Y|N/N|Y|N|
|ZEC_USDT|1243.870000|1238.800000|1244.060000|0.74|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-01T05:45:03+00:00, last15m_closed_end=2026-11-01T05:45+00:00, prior8high=0.009975, depth_time=2026-11-01T05:45:17+00:00, book20_bid_proxy_usdt=9278, book20_ask_proxy_usdt=4295, funding_indicative=-0.003040, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-7.82%, turnover=11770757. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-11-01T05:45:00+00:00, last15m_closed_end=2026-11-01T05:45+00:00, prior8high=0.099240, depth_time=2026-11-01T05:45:28+00:00, book20_bid_proxy_usdt=15097, book20_ask_proxy_usdt=14260, funding_indicative=0.000225, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.55%, turnover=6106092. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-11-01T05:45:03+00:00, last15m_closed_end=2026-11-01T05:45+00:00, prior8high=0.009822, depth_time=2026-11-01T05:45:13+00:00, book20_bid_proxy_usdt=22017, book20_ask_proxy_usdt=14008, funding_indicative=0.000050, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-8.92%, turnover=6567340. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-01T05:45:03+00:00, last15m_closed_end=2026-11-01T05:45+00:00, prior8high=0.189100, depth_time=2026-11-01T05:45:18+00:00, book20_bid_proxy_usdt=149472, book20_ask_proxy_usdt=122299, funding_indicative=0.000008, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.23%, turnover=43250978. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LSK_USDT: quote_utc=2026-11-01T05:45:03+00:00, last15m_closed_end=2026-11-01T05:45+00:00, prior8high=0.247730, depth_time=2026-11-01T05:45:09+00:00, book20_bid_proxy_usdt=6282, book20_ask_proxy_usdt=8674, funding_indicative=-0.002450, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-18.39%, turnover=30779779. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-01T05:45:03+00:00, last15m_closed_end=2026-11-01T05:45+00:00, prior8high=4.431000, depth_time=2026-11-01T05:45:22+00:00, book20_bid_proxy_usdt=3069285, book20_ask_proxy_usdt=3945849, funding_indicative=0.000100, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.27%, turnover=53248244. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-01T05:45:03+00:00, last15m_closed_end=2026-11-01T05:45+00:00, prior8high=0.401200, depth_time=2026-11-01T05:45:31+00:00, book20_bid_proxy_usdt=3699526, book20_ask_proxy_usdt=2984475, funding_indicative=0.000062, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.40%, turnover=30738907. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-01T05:45:00+00:00, last15m_closed_end=2026-11-01T05:45+00:00, prior8high=0.169260, depth_time=2026-11-01T05:45:26+00:00, book20_bid_proxy_usdt=133499, book20_ask_proxy_usdt=179563, funding_indicative=0.000080, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.65%, turnover=20365424. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-01T05:45:00+00:00, last15m_closed_end=2026-11-01T05:45+00:00, prior8high=0.086230, depth_time=2026-11-01T05:45:11+00:00, book20_bid_proxy_usdt=477929, book20_ask_proxy_usdt=307971, funding_indicative=0.000050, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-10.03%, turnover=5264426. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-01T05:45:03+00:00, last15m_closed_end=2026-11-01T05:45+00:00, prior8high=1251.980000, depth_time=2026-11-01T05:45:20+00:00, book20_bid_proxy_usdt=668580, book20_ask_proxy_usdt=419176, funding_indicative=-0.000133, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.16%, turnover=959322651. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
