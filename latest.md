# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T01:00:22Z**
- feed_generated_utc: 2026-11-09T01:00:24+00:00
- source_sha256: `863c5429aa20b8e246f8d56ac66125aa34b65f5ab912b2425f93c6253177dd5b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T01:00+00:00, close=75213.4, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-11-09T01:00+00:00, close=75213.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T00:00+00:00, close=74823.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|CLAUDIA_USDT|0.006665|-26.52|265.00|-25.48|10380987|4.50|
|ONE_USDT|0.001735|-8.25|49.02|-7.21|11494642|0.58|
|PUMPFUN_USDT|0.003600|-3.66|-14.65|-2.62|8302856|2.78|
|XRP_USDT|1.117600|-3.30|-10.58|-2.26|225725117|0.89|
|HYPE_USDT|74.987000|-3.15|-14.48|-2.11|37264071|0.13|
|LIT_USDT|3.102000|-2.86|-3.96|-1.82|11703500|0.32|
|AKE_USDT|0.005217|-2.61|-43.04|-1.57|13597256|1.91|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.005217|0.005147|0.005206|1.25|N|Y/Y|N/N|Y|N|
|CLAUDIA_USDT|0.006665|0.006330|0.006665|0.41|N|Y/Y|N/N|Y|N|
|HYPE_USDT|74.987000|74.227000|74.928000|0.32|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.102000|3.031200|3.098900|1.70|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001735|0.001693|0.001735|0.62|N|Y/Y|Y/N|Y|N|
|PUMPFUN_USDT|0.003600|0.003495|0.003599|0.79|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.117600|1.105100|1.116900|0.36|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-09T01:00:02+00:00, last15m_closed_end=2026-11-09T01:00+00:00, prior8high=0.005394, depth_time=2026-11-09T01:00:22+00:00, book20_bid_proxy_usdt=27691, book20_ask_proxy_usdt=27548, funding_indicative=0.000050, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.61%, turnover=13597256. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CLAUDIA_USDT: quote_utc=2026-11-09T01:00:02+00:00, last15m_closed_end=2026-11-09T01:00+00:00, prior8high=0.007371, depth_time=2026-11-09T01:00:07+00:00, book20_bid_proxy_usdt=479, book20_ask_proxy_usdt=359, funding_indicative=0.000128, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-26.52%, turnover=10380987. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-09T01:00:02+00:00, last15m_closed_end=2026-11-09T01:00+00:00, prior8high=75.837000, depth_time=2026-11-09T01:00:17+00:00, book20_bid_proxy_usdt=47114, book20_ask_proxy_usdt=81846, funding_indicative=0.000020, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.15%, turnover=37264071. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-09T01:00:02+00:00, last15m_closed_end=2026-11-09T01:00+00:00, prior8high=3.135200, depth_time=2026-11-09T01:00:19+00:00, book20_bid_proxy_usdt=23942, book20_ask_proxy_usdt=27126, funding_indicative=0.000050, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.86%, turnover=11703500. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T01:00:02+00:00, last15m_closed_end=2026-11-09T01:00+00:00, prior8high=0.001763, depth_time=2026-11-09T01:00:10+00:00, book20_bid_proxy_usdt=9722, book20_ask_proxy_usdt=8731, funding_indicative=-0.001065, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-8.25%, turnover=11494642. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-09T01:00:03+00:00, last15m_closed_end=2026-11-09T01:00+00:00, prior8high=0.003662, depth_time=2026-11-09T01:00:12+00:00, book20_bid_proxy_usdt=3073111, book20_ask_proxy_usdt=3323987, funding_indicative=0.000011, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.66%, turnover=8302856. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T01:00:02+00:00, last15m_closed_end=2026-11-09T01:00+00:00, prior8high=1.131800, depth_time=2026-11-09T01:00:15+00:00, book20_bid_proxy_usdt=1907560, book20_ask_proxy_usdt=1887423, funding_indicative=0.000056, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.30%, turnover=225725117. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
