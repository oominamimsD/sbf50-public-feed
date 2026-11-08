# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T23:15:17Z**
- feed_generated_utc: 2026-11-08T23:15:18+00:00
- source_sha256: `7f23d9f43875c4a21a149b4b7851dea45dbfa028b04208d201b9676a78eb9e76`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T23:15+00:00, close=75171.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-08T23:00+00:00, close=74432.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-08T20:00+00:00, close=75894.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001745|-10.88|49.83|-9.75|12488405|0.57|
|DASH_USDT|45.740000|-4.32|-5.88|-3.19|14585072|2.19|
|ZEC_USDT|1219.630000|-4.01|-1.47|-2.88|1616301103|0.08|
|HYPE_USDT|75.206000|-2.87|-14.23|-1.74|35150684|0.13|
|LIT_USDT|3.108700|-2.65|-3.75|-1.52|10370144|0.32|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DASH_USDT|45.740000|44.290000|45.740000|3.10|N|Y/Y|N/N|Y|N|
|HYPE_USDT|75.206000|73.578000|75.179000|1.35|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.108700|3.007700|3.107700|4.49|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001745|0.001607|0.001742|1.17|N|Y/Y|N/N|Y|N|
|ZEC_USDT|1219.630000|1178.000000|1219.250000|2.00|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DASH_USDT: quote_utc=2026-11-08T23:15:02+00:00, last15m_closed_end=2026-11-08T23:15+00:00, prior8high=47.350000, depth_time=2026-11-08T23:15:09+00:00, book20_bid_proxy_usdt=283342, book20_ask_proxy_usdt=586607, funding_indicative=0.000068, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.32%, turnover=14585072. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-08T23:15:01+00:00, last15m_closed_end=2026-11-08T23:15+00:00, prior8high=76.390000, depth_time=2026-11-08T23:15:14+00:00, book20_bid_proxy_usdt=99383, book20_ask_proxy_usdt=62301, funding_indicative=0.000048, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.87%, turnover=35150684. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-08T23:15:01+00:00, last15m_closed_end=2026-11-08T23:15+00:00, prior8high=3.181400, depth_time=2026-11-08T23:15:16+00:00, book20_bid_proxy_usdt=25631, book20_ask_proxy_usdt=23043, funding_indicative=0.000050, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.65%, turnover=10370144. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T23:15:01+00:00, last15m_closed_end=2026-11-08T23:15+00:00, prior8high=0.001733, depth_time=2026-11-08T23:15:07+00:00, book20_bid_proxy_usdt=8093, book20_ask_proxy_usdt=11428, funding_indicative=-0.000390, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=4, 24h_change=-10.88%, turnover=12488405. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-08T23:15:01+00:00, last15m_closed_end=2026-11-08T23:15+00:00, prior8high=1247.630000, depth_time=2026-11-08T23:15:11+00:00, book20_bid_proxy_usdt=582201, book20_ask_proxy_usdt=1561727, funding_indicative=0.000006, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.01%, turnover=1616301103. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
