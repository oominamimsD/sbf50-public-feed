# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T21:15:23Z**
- feed_generated_utc: 2026-11-08T21:15:25+00:00
- source_sha256: `cbb6e717b209b895458f9b1c474b030698bd8e23d729f721c51e71c36aa099ba`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T21:15+00:00, close=75708.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-08T21:00+00:00, close=75718.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-08T20:00+00:00, close=75894.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001675|-14.44|43.84|-14.01|14449559|0.60|
|ZEC_USDT|1238.210000|-2.55|0.02|-2.12|1476205071|0.08|
|NEAR_USDT|3.610000|-2.45|-16.64|-2.02|31503162|2.77|
|TRUMPOFFICIAL_USDT|1.168000|-1.76|-31.93|-1.33|5001219|8.56|
|HYPE_USDT|76.138000|-1.66|-13.17|-1.23|22982801|0.13|
|ARB_USDT|0.167300|-1.53|0.67|-1.10|18033799|0.60|
|ONDO_USDT|0.356700|-1.46|-12.22|-1.03|7349302|2.80|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.167300|0.166560|0.167300|0.95|N|Y/Y|N/N|Y|N|
|HYPE_USDT|76.138000|76.273000|76.147000|3.10|Y|Y/Y|Y/Y|Y|Y|
|NEAR_USDT|3.610000|3.611000|3.610000|1.50|Y|Y/Y|Y/Y|Y|Y|
|ONDO_USDT|0.356700|0.357800|0.356700|3.93|Y|Y/Y|Y/Y|Y|Y|
|ONE_USDT|0.001675|0.001668|0.001675|1.28|N|Y/Y|N/N|Y|N|
|TRUMPOFFICIAL_USDT|1.168000|1.166000|1.168000|0.86|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1238.210000|1240.690000|1238.090000|1.40|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-11-08T21:15:02+00:00, last15m_closed_end=2026-11-08T21:15+00:00, prior8high=0.168160, depth_time=2026-11-08T21:15:20+00:00, book20_bid_proxy_usdt=56572, book20_ask_proxy_usdt=88481, funding_indicative=-0.000006, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.53%, turnover=18033799. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-08T21:15:01+00:00, last15m_closed_end=2026-11-08T21:15+00:00, prior8high=77.158000, depth_time=2026-11-08T21:15:17+00:00, book20_bid_proxy_usdt=83438, book20_ask_proxy_usdt=162093, funding_indicative=0.000050, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.66%, turnover=22982801. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-08T21:15:01+00:00, last15m_closed_end=2026-11-08T21:15+00:00, prior8high=3.666000, depth_time=2026-11-08T21:15:09+00:00, book20_bid_proxy_usdt=3711688, book20_ask_proxy_usdt=3398651, funding_indicative=0.000100, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.45%, turnover=31503162. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-08T21:15:02+00:00, last15m_closed_end=2026-11-08T21:15+00:00, prior8high=0.361200, depth_time=2026-11-08T21:15:20+00:00, book20_bid_proxy_usdt=2043175, book20_ask_proxy_usdt=1881424, funding_indicative=0.000050, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.46%, turnover=7349302. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T21:15:01+00:00, last15m_closed_end=2026-11-08T21:15+00:00, prior8high=0.001808, depth_time=2026-11-08T21:15:07+00:00, book20_bid_proxy_usdt=13508, book20_ask_proxy_usdt=11158, funding_indicative=-0.000100, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=4, 24h_change=-14.44%, turnover=14449559. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-08T21:15:02+00:00, last15m_closed_end=2026-11-08T21:15+00:00, prior8high=1.179000, depth_time=2026-11-08T21:15:15+00:00, book20_bid_proxy_usdt=2118250, book20_ask_proxy_usdt=2152306, funding_indicative=-0.000107, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.76%, turnover=5001219. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-08T21:15:01+00:00, last15m_closed_end=2026-11-08T21:15+00:00, prior8high=1268.660000, depth_time=2026-11-08T21:15:09+00:00, book20_bid_proxy_usdt=163190, book20_ask_proxy_usdt=206311, funding_indicative=0.000043, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.55%, turnover=1476205071. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
