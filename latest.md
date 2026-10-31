# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T04:15:29Z**
- feed_generated_utc: 2026-10-31T04:15:31+00:00
- source_sha256: `8df0f623b1e827956c08138ac35e98bec0fc56c28ca99d77b5db25f7dba0a1b5`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T04:15+00:00, close=77170.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-31T04:00+00:00, close=77131.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-31T04:00+00:00, close=77131.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.011523|-39.09|-67.07|-38.57|6467222|2.60|
|BEAT_USDT|0.099740|-5.14|37.40|-4.62|8712532|1.00|
|EVAA_USDT|1.222200|-4.67|132.84|-4.15|6405433|2.46|
|HYPE_USDT|89.228000|-3.37|13.80|-2.85|111201309|0.11|
|PEPE_USDT|0.000005|-3.25|0.70|-2.73|138025026|0.20|
|LIT_USDT|2.747600|-2.71|-17.34|-2.19|5530984|0.36|
|BTW_USDT|1.167400|-2.67|-31.42|-2.15|9648850|0.86|
|TRX_USDT|0.326640|-2.64|-0.81|-2.12|7204657|0.92|
|DASH_USDT|48.240000|-1.63|-10.41|-1.11|16028578|2.07|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.011523|0.011264|0.011523|0.93|N|Y/Y|Y/Y|Y|N|
|BEAT_USDT|0.099740|0.096210|0.099740|0.97|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.167400|1.114700|1.167400|1.03|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|48.240000|48.330000|48.240000|1.03|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.222200|1.121600|1.222200|0.64|N|N/N|N/N|Y|N|
|HYPE_USDT|89.228000|89.108000|89.228000|0.45|N|Y/Y|N/N|Y|N|
|LIT_USDT|2.747600|2.742400|2.747600|0.37|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|0.89|N|Y/Y|N/N|Y|N|
|TRX_USDT|0.326640|0.324100|0.326770|0.10|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T04:15:00+00:00, last15m_closed_end=2026-10-31T04:15+00:00, prior8high=0.012397, depth_time=2026-10-31T04:15:08+00:00, book20_bid_proxy_usdt=6043, book20_ask_proxy_usdt=8156, funding_indicative=-0.000135, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-39.09%, turnover=6467222. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-31T04:15:00+00:00, last15m_closed_end=2026-10-31T04:15+00:00, prior8high=0.101470, depth_time=2026-10-31T04:15:10+00:00, book20_bid_proxy_usdt=14484, book20_ask_proxy_usdt=6535, funding_indicative=0.000159, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.14%, turnover=8712532. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T04:15:00+00:00, last15m_closed_end=2026-10-31T04:15+00:00, prior8high=1.291900, depth_time=2026-10-31T04:15:22+00:00, book20_bid_proxy_usdt=15229, book20_ask_proxy_usdt=9433, funding_indicative=-0.000249, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.67%, turnover=9648850. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-31T04:15:00+00:00, last15m_closed_end=2026-10-31T04:15+00:00, prior8high=48.970000, depth_time=2026-10-31T04:15:25+00:00, book20_bid_proxy_usdt=746850, book20_ask_proxy_usdt=752153, funding_indicative=0.000070, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.63%, turnover=16028578. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-31T04:15:00+00:00, last15m_closed_end=2026-10-31T04:15+00:00, prior8high=1.292600, depth_time=2026-10-31T04:15:12+00:00, book20_bid_proxy_usdt=6839, book20_ask_proxy_usdt=5682, funding_indicative=0.000189, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.67%, turnover=6405433. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T04:15:00+00:00, last15m_closed_end=2026-10-31T04:15+00:00, prior8high=90.160000, depth_time=2026-10-31T04:15:15+00:00, book20_bid_proxy_usdt=338266, book20_ask_proxy_usdt=135480, funding_indicative=0.000050, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.37%, turnover=111201309. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-31T04:15:00+00:00, last15m_closed_end=2026-10-31T04:15+00:00, prior8high=2.792700, depth_time=2026-10-31T04:15:20+00:00, book20_bid_proxy_usdt=31492, book20_ask_proxy_usdt=21937, funding_indicative=0.000050, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.71%, turnover=5530984. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-31T04:15:00+00:00, last15m_closed_end=2026-10-31T04:15+00:00, prior8high=0.000005, depth_time=2026-10-31T04:15:17+00:00, book20_bid_proxy_usdt=22309, book20_ask_proxy_usdt=28844, funding_indicative=-0.000211, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.25%, turnover=138025026. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T04:15:00+00:00, last15m_closed_end=2026-10-31T04:15+00:00, prior8high=0.327950, depth_time=2026-10-31T04:15:25+00:00, book20_bid_proxy_usdt=35286, book20_ask_proxy_usdt=30307, funding_indicative=-0.001536, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.64%, turnover=7204657. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
