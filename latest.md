# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T06:45:33Z**
- feed_generated_utc: 2026-10-31T06:45:35+00:00
- source_sha256: `63443d925b885d4529dbe6dc3add740d6882b4fb4919bc3c4114f55a00e6ac4c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T06:45+00:00, close=77307.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T06:00+00:00, close=77232.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-31T04:00+00:00, close=77131.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.012333|-34.81|-64.75|-34.46|6945548|4.86|
|Q_USDT|0.032240|-32.09|-72.75|-31.74|19753259|9.28|
|BEAT_USDT|0.097410|-7.36|34.19|-7.01|8637875|3.08|
|EVAA_USDT|1.187800|-7.35|126.29|-7.00|6170206|2.52|
|BTW_USDT|1.138300|-5.10|-33.13|-4.75|9600534|3.52|
|HYPE_USDT|88.557000|-4.10|12.94|-3.75|109485924|0.11|
|TRX_USDT|0.324560|-3.26|-1.45|-2.91|6771842|0.31|
|WLD_USDT|0.400200|-2.84|-24.83|-2.49|48767349|2.50|
|DASH_USDT|47.930000|-2.26|-10.99|-1.91|15006492|2.09|
|FET_USDT|0.163700|-1.74|-12.60|-1.39|6547843|6.11|
|PEPE_USDT|0.000005|-1.65|2.38|-1.30|132688001|0.40|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.012333|0.010838|0.012390|1.53|N|Y/Y|Y/Y|Y|N|
|BEAT_USDT|0.097410|0.096280|0.097360|0.94|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.138300|1.108600|1.138300|0.74|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|47.930000|47.920000|47.940000|9.96|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.187800|1.141300|1.187800|2.31|N|N/N|N/N|Y|N|
|FET_USDT|0.163700|0.162200|0.163700|0.87|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|88.557000|88.038000|88.558000|4.66|N|Y/Y|N/N|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|0.89|N|Y/Y|N/N|Y|N|
|Q_USDT|0.032240|0.027250|0.032210|0.64|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.324560|0.322650|0.324560|0.90|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.400200|0.392600|0.400200|0.48|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T06:45:03+00:00, last15m_closed_end=2026-10-31T06:45+00:00, prior8high=0.011974, depth_time=2026-10-31T06:45:08+00:00, book20_bid_proxy_usdt=3899, book20_ask_proxy_usdt=6887, funding_indicative=-0.000145, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-34.81%, turnover=6945548. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-31T06:45:03+00:00, last15m_closed_end=2026-10-31T06:45+00:00, prior8high=0.100100, depth_time=2026-10-31T06:45:12+00:00, book20_bid_proxy_usdt=17918, book20_ask_proxy_usdt=13878, funding_indicative=0.000149, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-7.36%, turnover=8637875. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T06:45:03+00:00, last15m_closed_end=2026-10-31T06:45+00:00, prior8high=1.176300, depth_time=2026-10-31T06:45:18+00:00, book20_bid_proxy_usdt=20329, book20_ask_proxy_usdt=14904, funding_indicative=-0.000453, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.10%, turnover=9600534. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-31T06:45:03+00:00, last15m_closed_end=2026-10-31T06:45+00:00, prior8high=48.240000, depth_time=2026-10-31T06:45:23+00:00, book20_bid_proxy_usdt=744130, book20_ask_proxy_usdt=755432, funding_indicative=0.000077, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.26%, turnover=15006492. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-31T06:45:03+00:00, last15m_closed_end=2026-10-31T06:45+00:00, prior8high=1.242000, depth_time=2026-10-31T06:45:14+00:00, book20_bid_proxy_usdt=6553, book20_ask_proxy_usdt=5552, funding_indicative=0.000206, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-7.35%, turnover=6170206. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T06:45:03+00:00, last15m_closed_end=2026-10-31T06:45+00:00, prior8high=0.163800, depth_time=2026-10-31T06:45:26+00:00, book20_bid_proxy_usdt=1257900, book20_ask_proxy_usdt=696079, funding_indicative=0.000100, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.74%, turnover=6547843. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T06:45:03+00:00, last15m_closed_end=2026-10-31T06:45+00:00, prior8high=89.191000, depth_time=2026-10-31T06:45:20+00:00, book20_bid_proxy_usdt=159235, book20_ask_proxy_usdt=136396, funding_indicative=0.000050, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.10%, turnover=109485924. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-31T06:45:03+00:00, last15m_closed_end=2026-10-31T06:45+00:00, prior8high=0.000005, depth_time=2026-10-31T06:45:32+00:00, book20_bid_proxy_usdt=32369, book20_ask_proxy_usdt=34928, funding_indicative=-0.000010, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.65%, turnover=132688001. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T06:45:03+00:00, last15m_closed_end=2026-10-31T06:45+00:00, prior8high=0.032360, depth_time=2026-10-31T06:45:11+00:00, book20_bid_proxy_usdt=54123, book20_ask_proxy_usdt=39500, funding_indicative=-0.000747, next_funding_utc=2026-10-31T07:00:00+00:00, funding_cycle_h=1, 24h_change=-32.09%, turnover=19753259. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T06:45:03+00:00, last15m_closed_end=2026-10-31T06:45+00:00, prior8high=0.326690, depth_time=2026-10-31T06:45:22+00:00, book20_bid_proxy_usdt=493082, book20_ask_proxy_usdt=83839, funding_indicative=-0.000748, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.26%, turnover=6771842. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T06:45:03+00:00, last15m_closed_end=2026-10-31T06:45+00:00, prior8high=0.400200, depth_time=2026-10-31T06:45:24+00:00, book20_bid_proxy_usdt=2715811, book20_ask_proxy_usdt=2946729, funding_indicative=0.000100, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.84%, turnover=48767349. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
