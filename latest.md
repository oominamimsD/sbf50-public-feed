# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T01:30:33Z**
- feed_generated_utc: 2026-11-09T01:30:34+00:00
- source_sha256: `af49571ef6c826aa467c1201755607064a616028749aa1e867abdcc0ae5c2401`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T01:30+00:00, close=74733.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-09T01:00+00:00, close=75213.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T00:00+00:00, close=74823.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|CLAUDIA_USDT|0.006522|-21.79|257.17|-20.06|10411126|3.06|
|ONE_USDT|0.001719|-12.22|47.59|-10.49|11536377|0.58|
|HOT_USDT|0.000399|-7.21|10.84|-5.48|6241273|2.51|
|ETH_USDT|2124.750000|-5.19|-6.22|-3.46|1145946070|0.05|
|DASH_USDT|45.530000|-4.76|-6.31|-3.03|15290537|2.20|
|PUMPFUN_USDT|0.003560|-4.73|-15.59|-3.00|8528908|2.81|
|HYPE_USDT|74.197000|-4.17|-15.38|-2.44|39383009|0.14|
|AKE_USDT|0.005135|-4.14|-43.94|-2.41|13681491|5.84|
|XRP_USDT|1.109100|-4.04|-11.26|-2.31|229809249|0.90|
|LIT_USDT|3.084100|-3.42|-4.51|-1.69|12076274|0.33|
|DOT_USDT|0.865600|-2.83|-8.59|-1.10|7097441|1.16|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.005135|0.005115|0.005149|0.34|N|Y/Y|N/N|Y|N|
|CLAUDIA_USDT|0.006522|0.006328|0.006515|0.41|N|Y/Y|N/N|Y|N|
|DASH_USDT|45.530000|45.020000|45.530000|0.94|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.865600|0.857600|0.865800|0.22|N|Y/Y|Y/Y|Y|N|
|ETH_USDT|2124.750000|2116.420000|2125.250000|0.88|N|Y/Y|Y/Y|Y|N|
|HOT_USDT|0.000399|0.000397|0.000399|0.37|N|Y/N|N/N|Y|N|
|HYPE_USDT|74.197000|74.227000|74.197000|2.63|Y|Y/Y|Y/Y|Y|Y|
|LIT_USDT|3.084100|3.031200|3.083500|0.18|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001719|0.001698|0.001719|0.30|N|Y/Y|Y/N|Y|N|
|PUMPFUN_USDT|0.003560|0.003495|0.003564|1.40|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.109100|1.105100|1.109100|0.75|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-09T01:30:02+00:00, last15m_closed_end=2026-11-09T01:30+00:00, prior8high=0.005339, depth_time=2026-11-09T01:30:24+00:00, book20_bid_proxy_usdt=41234, book20_ask_proxy_usdt=31937, funding_indicative=0.000050, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.14%, turnover=13681491. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CLAUDIA_USDT: quote_utc=2026-11-09T01:30:02+00:00, last15m_closed_end=2026-11-09T01:30+00:00, prior8high=0.007371, depth_time=2026-11-09T01:30:07+00:00, book20_bid_proxy_usdt=194, book20_ask_proxy_usdt=92, funding_indicative=0.000128, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-21.79%, turnover=10411126. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-09T01:30:02+00:00, last15m_closed_end=2026-11-09T01:30+00:00, prior8high=46.370000, depth_time=2026-11-09T01:30:17+00:00, book20_bid_proxy_usdt=579609, book20_ask_proxy_usdt=479123, funding_indicative=0.000002, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.76%, turnover=15290537. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-09T01:30:02+00:00, last15m_closed_end=2026-11-09T01:30+00:00, prior8high=0.877300, depth_time=2026-11-09T01:30:30+00:00, book20_bid_proxy_usdt=246051, book20_ask_proxy_usdt=810624, funding_indicative=0.000059, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.83%, turnover=7097441. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETH_USDT: quote_utc=2026-11-09T01:30:02+00:00, last15m_closed_end=2026-11-09T01:30+00:00, prior8high=2166.980000, depth_time=2026-11-09T01:30:16+00:00, book20_bid_proxy_usdt=3689480, book20_ask_proxy_usdt=4908150, funding_indicative=-0.000075, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.19%, turnover=1145946070. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HOT_USDT: quote_utc=2026-11-09T01:30:02+00:00, last15m_closed_end=2026-11-09T01:30+00:00, prior8high=0.000411, depth_time=2026-11-09T01:30:11+00:00, book20_bid_proxy_usdt=63495, book20_ask_proxy_usdt=87578, funding_indicative=-0.000626, next_funding_utc=2026-11-09T02:00:00+00:00, funding_cycle_h=1, 24h_change=-7.21%, turnover=6241273. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-09T01:30:02+00:00, last15m_closed_end=2026-11-09T01:30+00:00, prior8high=75.837000, depth_time=2026-11-09T01:30:22+00:00, book20_bid_proxy_usdt=85081, book20_ask_proxy_usdt=96567, funding_indicative=0.000013, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.17%, turnover=39383009. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-09T01:30:02+00:00, last15m_closed_end=2026-11-09T01:30+00:00, prior8high=3.135200, depth_time=2026-11-09T01:30:29+00:00, book20_bid_proxy_usdt=19671, book20_ask_proxy_usdt=24156, funding_indicative=0.000050, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.42%, turnover=12076274. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T01:30:02+00:00, last15m_closed_end=2026-11-09T01:30+00:00, prior8high=0.001763, depth_time=2026-11-09T01:30:09+00:00, book20_bid_proxy_usdt=4515, book20_ask_proxy_usdt=12536, funding_indicative=-0.001067, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-12.22%, turnover=11536377. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-09T01:30:02+00:00, last15m_closed_end=2026-11-09T01:30+00:00, prior8high=0.003662, depth_time=2026-11-09T01:30:20+00:00, book20_bid_proxy_usdt=2715472, book20_ask_proxy_usdt=4379699, funding_indicative=0.000024, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.73%, turnover=8528908. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T01:30:02+00:00, last15m_closed_end=2026-11-09T01:30+00:00, prior8high=1.131800, depth_time=2026-11-09T01:30:27+00:00, book20_bid_proxy_usdt=3499881, book20_ask_proxy_usdt=3870200, funding_indicative=0.000040, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.04%, turnover=229809249. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
