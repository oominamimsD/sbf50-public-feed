# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T02:30:18Z**
- feed_generated_utc: 2026-11-11T02:30:19+00:00
- source_sha256: `99faafd474d9babde66077585159eed0b7534b9db9b447cb251164d0b5106d17`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T02:30+00:00, close=73332.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-11T02:00+00:00, close=73573.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-11T00:00+00:00, close=73762.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|PIEVERSE_USDT|1.725800|-14.82|46.82|-15.02|5092439|3.48|
|ZEC_USDT|1020.800000|-6.63|-15.20|-6.83|2207098532|0.10|
|DASH_USDT|43.110000|-4.49|-6.56|-4.69|14165745|2.32|
|UNI_USDT|6.671000|-2.32|-9.27|-2.52|35895218|3.00|
|VVV_USDT|19.059000|-0.93|-14.76|-1.13|5403104|0.53|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DASH_USDT|43.110000|42.890000|43.110000|1.43|N|Y/Y|Y/Y|Y|N|
|PIEVERSE_USDT|1.725800|1.682600|1.725800|2.37|N|Y/Y|N/N|Y|N|
|UNI_USDT|6.671000|6.646000|6.671000|2.33|N|Y/Y|Y/Y|Y|N|
|VVV_USDT|19.059000|19.043000|19.059000|0.93|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1020.800000|1008.110000|1020.780000|1.56|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DASH_USDT: quote_utc=2026-11-11T02:30:01+00:00, last15m_closed_end=2026-11-11T02:30+00:00, prior8high=44.600000, depth_time=2026-11-11T02:30:13+00:00, book20_bid_proxy_usdt=617413, book20_ask_proxy_usdt=522116, funding_indicative=-0.000188, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.49%, turnover=14165745. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PIEVERSE_USDT: quote_utc=2026-11-11T02:30:01+00:00, last15m_closed_end=2026-11-11T02:30+00:00, prior8high=1.870000, depth_time=2026-11-11T02:30:07+00:00, book20_bid_proxy_usdt=22138, book20_ask_proxy_usdt=18545, funding_indicative=0.000100, next_funding_utc=2026-11-11T04:00:00+00:00, funding_cycle_h=4, 24h_change=-14.82%, turnover=5092439. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T02:30:01+00:00, last15m_closed_end=2026-11-11T02:30+00:00, prior8high=6.820000, depth_time=2026-11-11T02:30:14+00:00, book20_bid_proxy_usdt=2492308, book20_ask_proxy_usdt=1983854, funding_indicative=-0.000003, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.32%, turnover=35895218. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-11T02:30:01+00:00, last15m_closed_end=2026-11-11T02:30+00:00, prior8high=19.688000, depth_time=2026-11-11T02:30:16+00:00, book20_bid_proxy_usdt=30501, book20_ask_proxy_usdt=18438, funding_indicative=0.000001, next_funding_utc=2026-11-11T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.93%, turnover=5403104. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T02:30:01+00:00, last15m_closed_end=2026-11-11T02:30+00:00, prior8high=1049.410000, depth_time=2026-11-11T02:30:10+00:00, book20_bid_proxy_usdt=375572, book20_ask_proxy_usdt=162581, funding_indicative=0.000098, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.63%, turnover=2207098532. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
