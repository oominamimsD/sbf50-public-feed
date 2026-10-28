# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T13:15:37Z**
- feed_generated_utc: 2026-10-28T13:15:43+00:00
- source_sha256: `16bc3f703255c907c32bc491fe01d051f0a4b4856d34056c9b6ff9c7ca798405`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.09 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T13:15+00:00, close=80694.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-28T13:00+00:00, close=80708.1, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T12:00+00:00, close=81305.7, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.053330|-16.12|-56.55|-16.32|18500103|1.88|
|BEAT_USDT|0.080100|-12.06|7.21|-12.26|14973357|3.74|
|AKE_USDT|0.019541|-7.49|-37.14|-7.69|6624551|3.07|
|ENA_USDT|0.198850|-6.54|4.72|-6.74|75842704|1.01|
|INJ_USDT|7.818000|-4.56|-9.09|-4.76|24395381|1.28|
|ARB_USDT|0.164820|-2.18|-12.77|-2.38|16288460|0.61|
|DASH_USDT|53.150000|-1.88|6.42|-2.08|15935095|1.88|
|UNI_USDT|7.030000|-1.80|-3.31|-2.00|13917916|1.42|
|WLD_USDT|0.429200|-1.55|-23.73|-1.75|64390007|2.33|
|ADA_USDT|0.202400|-1.55|-8.58|-1.75|34940720|4.94|
|PUMPFUN_USDT|0.004238|-1.09|-6.05|-1.29|16107085|2.36|
|OP_USDT|0.110250|-0.96|-16.02|-1.16|5836053|0.91|
|HBAR_USDT|0.075400|-0.94|-9.54|-1.14|9433307|1.33|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ADA_USDT|0.202400|0.202700|0.202400|6.58|Y|Y/Y|N/N|N|N|
|AKE_USDT|0.019541|0.019542|0.019541|0.97|N|Y/Y|Y/Y|N|N|
|ARB_USDT|0.164820|0.164190|0.164830|3.56|N|Y/Y|Y/Y|N|N|
|BEAT_USDT|0.080100|0.074400|0.080070|0.54|N|Y/Y|Y/N|N|N|
|DASH_USDT|53.150000|53.220000|53.150000|1.08|N|Y/Y|N/N|N|N|
|ENA_USDT|0.198850|0.198290|0.198850|1.57|N|Y/Y|Y/N|N|N|
|HBAR_USDT|0.075400|0.075140|0.075400|0.55|N|Y/Y|Y/Y|N|N|
|INJ_USDT|7.818000|7.808000|7.818000|2.10|N|Y/Y|N/N|N|N|
|OP_USDT|0.110250|0.110110|0.110250|0.83|N|Y/Y|N/N|N|N|
|PUMPFUN_USDT|0.004238|0.004221|0.004238|1.78|N|Y/Y|N/N|N|N|
|Q_USDT|0.053330|0.053250|0.053330|0.81|N|Y/Y|Y/Y|N|N|
|UNI_USDT|7.030000|7.004000|7.030000|0.75|N|Y/Y|N/N|N|N|
|WLD_USDT|0.429200|0.425300|0.429200|1.07|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- ADA_USDT: quote_utc=2026-10-28T13:15:00+00:00, last15m_closed_end=2026-10-28T13:15+00:00, prior8high=0.207700, depth_time=2026-10-28T13:15:29+00:00, book20_bid_proxy_usdt=6673428, book20_ask_proxy_usdt=5974156, funding_indicative=-0.000057, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.55%, turnover=34940720. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-10-28T13:15:00+00:00, last15m_closed_end=2026-10-28T13:15+00:00, prior8high=0.020235, depth_time=2026-10-28T13:15:12+00:00, book20_bid_proxy_usdt=10430, book20_ask_proxy_usdt=4459, funding_indicative=0.000050, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.49%, turnover=6624551. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-28T13:15:00+00:00, last15m_closed_end=2026-10-28T13:15+00:00, prior8high=0.169040, depth_time=2026-10-28T13:15:20+00:00, book20_bid_proxy_usdt=88332, book20_ask_proxy_usdt=94357, funding_indicative=-0.000059, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.18%, turnover=16288460. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-28T13:15:00+00:00, last15m_closed_end=2026-10-28T13:15+00:00, prior8high=0.086050, depth_time=2026-10-28T13:15:10+00:00, book20_bid_proxy_usdt=13588, book20_ask_proxy_usdt=7788, funding_indicative=0.000050, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-12.06%, turnover=14973357. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-28T13:15:00+00:00, last15m_closed_end=2026-10-28T13:15+00:00, prior8high=53.830000, depth_time=2026-10-28T13:15:22+00:00, book20_bid_proxy_usdt=982769, book20_ask_proxy_usdt=773449, funding_indicative=0.000100, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.88%, turnover=15935095. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-28T13:15:00+00:00, last15m_closed_end=2026-10-28T13:15+00:00, prior8high=0.206740, depth_time=2026-10-28T13:15:15+00:00, book20_bid_proxy_usdt=167515, book20_ask_proxy_usdt=131585, funding_indicative=-0.000027, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.54%, turnover=75842704. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-28T13:15:00+00:00, last15m_closed_end=2026-10-28T13:15+00:00, prior8high=0.076630, depth_time=2026-10-28T13:15:34+00:00, book20_bid_proxy_usdt=1176159, book20_ask_proxy_usdt=1312950, funding_indicative=0.000027, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.94%, turnover=9433307. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-28T13:15:00+00:00, last15m_closed_end=2026-10-28T13:15+00:00, prior8high=7.964000, depth_time=2026-10-28T13:15:16+00:00, book20_bid_proxy_usdt=481466, book20_ask_proxy_usdt=289800, funding_indicative=0.000192, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.56%, turnover=24395381. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-28T13:15:01+00:00, last15m_closed_end=2026-10-28T13:15+00:00, prior8high=0.113020, depth_time=2026-10-28T13:15:33+00:00, book20_bid_proxy_usdt=160275, book20_ask_proxy_usdt=122507, funding_indicative=-0.000049, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.96%, turnover=5836053. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-28T13:15:00+00:00, last15m_closed_end=2026-10-28T13:15+00:00, prior8high=0.004344, depth_time=2026-10-28T13:15:31+00:00, book20_bid_proxy_usdt=2361583, book20_ask_proxy_usdt=2961388, funding_indicative=0.000007, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.09%, turnover=16107085. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-28T13:15:00+00:00, last15m_closed_end=2026-10-28T13:15+00:00, prior8high=0.058150, depth_time=2026-10-28T13:15:06+00:00, book20_bid_proxy_usdt=34192, book20_ask_proxy_usdt=64305, funding_indicative=-0.000692, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-16.12%, turnover=18500103. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-28T13:15:00+00:00, last15m_closed_end=2026-10-28T13:15+00:00, prior8high=7.188000, depth_time=2026-10-28T13:15:24+00:00, book20_bid_proxy_usdt=2428817, book20_ask_proxy_usdt=2649948, funding_indicative=0.000100, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.80%, turnover=13917916. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-28T13:15:00+00:00, last15m_closed_end=2026-10-28T13:15+00:00, prior8high=0.438400, depth_time=2026-10-28T13:15:27+00:00, book20_bid_proxy_usdt=3501524, book20_ask_proxy_usdt=3343449, funding_indicative=-0.000089, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.55%, turnover=64390007. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
