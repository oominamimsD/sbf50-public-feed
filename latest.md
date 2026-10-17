# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T03:45:30Z**
- feed_generated_utc: 2026-10-17T03:45:32+00:00
- source_sha256: `8d87816a007f794c3df8adbc19d5d052221b71027ccf74cd50a35fe41d52080f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T03:45+00:00, close=81568.5, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-17T03:00+00:00, close=81449.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-17T00:00+00:00, close=81578.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZRO_USDT|1.979000|-5.82|-2.83|-6.12|15490447|3.54|
|RIVER_USDT|1.084000|-3.73|-8.29|-4.03|5244032|9.22|
|STRK_USDT|0.071950|-2.70|-4.46|-3.00|22370539|1.39|
|ARB_USDT|0.190110|-2.47|5.14|-2.77|33428047|0.53|
|ZEC_USDT|1159.140000|-2.43|-4.86|-2.73|1407474255|0.09|
|FET_USDT|0.195900|-1.85|-9.72|-2.15|11656580|5.11|
|TAO_USDT|277.110000|-1.25|0.88|-1.55|79934087|1.08|
|APT_USDT|0.847700|-0.98|5.89|-1.28|12670741|1.18|
|AVAX_USDT|10.011000|-0.71|-1.77|-1.01|123961068|1.00|
|AAVE_USDT|156.150000|-0.71|-8.06|-1.01|30151522|0.64|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|156.150000|154.410000|156.150000|1.08|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.847700|0.833600|0.847700|1.63|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.190110|0.187590|0.190110|0.64|N|Y/Y|N/N|Y|N|
|AVAX_USDT|10.011000|9.881000|10.011000|1.57|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.195900|0.194100|0.195700|0.60|N|Y/Y|Y/Y|Y|N|
|RIVER_USDT|1.084000|1.074000|1.084000|0.29|N|Y/Y|N/N|Y|N|
|STRK_USDT|0.071950|0.069640|0.071950|1.17|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|277.110000|273.080000|277.110000|2.91|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1159.140000|1140.370000|1159.200000|1.67|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.979000|1.943800|1.979000|1.49|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-17T03:45:00+00:00, last15m_closed_end=2026-10-17T03:45+00:00, prior8high=155.840000, depth_time=2026-10-17T03:45:28+00:00, book20_bid_proxy_usdt=307897, book20_ask_proxy_usdt=325497, funding_indicative=0.000057, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.71%, turnover=30151522. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-17T03:45:00+00:00, last15m_closed_end=2026-10-17T03:45+00:00, prior8high=0.848700, depth_time=2026-10-17T03:45:24+00:00, book20_bid_proxy_usdt=158270, book20_ask_proxy_usdt=144265, funding_indicative=0.000065, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.98%, turnover=12670741. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-17T03:45:00+00:00, last15m_closed_end=2026-10-17T03:45+00:00, prior8high=0.190730, depth_time=2026-10-17T03:45:15+00:00, book20_bid_proxy_usdt=40328, book20_ask_proxy_usdt=60322, funding_indicative=-0.000065, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.47%, turnover=33428047. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-17T03:45:00+00:00, last15m_closed_end=2026-10-17T03:45+00:00, prior8high=10.000000, depth_time=2026-10-17T03:45:27+00:00, book20_bid_proxy_usdt=696326, book20_ask_proxy_usdt=567746, funding_indicative=0.000090, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.71%, turnover=123961068. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-17T03:45:00+00:00, last15m_closed_end=2026-10-17T03:45+00:00, prior8high=0.196500, depth_time=2026-10-17T03:45:18+00:00, book20_bid_proxy_usdt=1655374, book20_ask_proxy_usdt=1220137, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.85%, turnover=11656580. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RIVER_USDT: quote_utc=2026-10-17T03:45:00+00:00, last15m_closed_end=2026-10-17T03:45+00:00, prior8high=1.091000, depth_time=2026-10-17T03:45:10+00:00, book20_bid_proxy_usdt=445658, book20_ask_proxy_usdt=365714, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.73%, turnover=5244032. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-17T03:45:00+00:00, last15m_closed_end=2026-10-17T03:45+00:00, prior8high=0.074750, depth_time=2026-10-17T03:45:12+00:00, book20_bid_proxy_usdt=263391, book20_ask_proxy_usdt=258370, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.70%, turnover=22370539. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-17T03:45:00+00:00, last15m_closed_end=2026-10-17T03:45+00:00, prior8high=275.840000, depth_time=2026-10-17T03:45:22+00:00, book20_bid_proxy_usdt=85112, book20_ask_proxy_usdt=55627, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.25%, turnover=79934087. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-17T03:45:00+00:00, last15m_closed_end=2026-10-17T03:45+00:00, prior8high=1157.920000, depth_time=2026-10-17T03:45:17+00:00, book20_bid_proxy_usdt=348083, book20_ask_proxy_usdt=332048, funding_indicative=0.000058, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.43%, turnover=1407474255. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-17T03:45:00+00:00, last15m_closed_end=2026-10-17T03:45+00:00, prior8high=1.972200, depth_time=2026-10-17T03:45:07+00:00, book20_bid_proxy_usdt=40270, book20_ask_proxy_usdt=49413, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.82%, turnover=15490447. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
