# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T13:15:31Z**
- feed_generated_utc: 2026-10-20T13:15:34+00:00
- source_sha256: `9cb96b55c00f4755433720bd87f2366a0850490fac12f76e11629326d520bf92`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1201; contracts: 1193; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T13:15+00:00, close=81375.1, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-20T13:00+00:00, close=81577.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T12:00+00:00, close=81467.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.068775|-20.98|312.76|-20.32|8594463|2.33|
|ZRO_USDT|1.794200|-5.66|-20.64|-5.00|7982772|2.23|
|NEAR_USDT|4.668000|-4.81|-15.87|-4.15|163706595|2.14|
|ARB_USDT|0.187680|-4.06|-0.41|-3.40|95978177|1.07|
|SAND_USDT|0.057060|-3.51|-8.10|-2.85|5342544|1.75|
|BTW_USDT|1.711800|-2.29|-2.50|-1.63|35919994|1.17|
|UNI_USDT|7.128000|-2.19|-3.90|-1.53|9630301|1.40|
|AKE_USDT|0.030131|-2.06|27.99|-1.40|6565935|2.33|
|TAO_USDT|263.300000|-1.86|-8.03|-1.20|59622669|1.14|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.068775|0.066520|0.068775|0.65|N|Y/Y|Y/N|Y|N|
|AKE_USDT|0.030131|0.029686|0.030119|0.44|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.187680|0.187860|0.187680|1.74|Y|Y/Y|Y/N|Y|N|
|BTW_USDT|1.711800|1.675000|1.712100|0.26|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.668000|4.630000|4.668000|1.18|N|Y/Y|Y/Y|Y|N|
|SAND_USDT|0.057060|0.056510|0.057060|1.79|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|263.300000|262.590000|263.300000|1.18|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|7.128000|7.106000|7.128000|3.41|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.794200|1.861100|1.795100|14.65|Y|Y/N|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T13:15:01+00:00, last15m_closed_end=2026-10-20T13:15+00:00, prior8high=0.070454, depth_time=2026-10-20T13:15:09+00:00, book20_bid_proxy_usdt=5031, book20_ask_proxy_usdt=9528, funding_indicative=0.000059, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=4, 24h_change=-20.98%, turnover=8594463. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-10-20T13:15:01+00:00, last15m_closed_end=2026-10-20T13:15+00:00, prior8high=0.031085, depth_time=2026-10-20T13:15:27+00:00, book20_bid_proxy_usdt=14338, book20_ask_proxy_usdt=14078, funding_indicative=0.000050, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.06%, turnover=6565935. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-20T13:15:01+00:00, last15m_closed_end=2026-10-20T13:15+00:00, prior8high=0.190320, depth_time=2026-10-20T13:15:17+00:00, book20_bid_proxy_usdt=81838, book20_ask_proxy_usdt=110351, funding_indicative=0.000076, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.06%, turnover=95978177. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-20T13:15:01+00:00, last15m_closed_end=2026-10-20T13:15+00:00, prior8high=1.878700, depth_time=2026-10-20T13:15:22+00:00, book20_bid_proxy_usdt=17100, book20_ask_proxy_usdt=7534, funding_indicative=-0.003212, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.29%, turnover=35919994. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-20T13:15:01+00:00, last15m_closed_end=2026-10-20T13:15+00:00, prior8high=4.728000, depth_time=2026-10-20T13:15:15+00:00, book20_bid_proxy_usdt=3753727, book20_ask_proxy_usdt=4591695, funding_indicative=-0.000005, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.81%, turnover=163706595. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-20T13:15:01+00:00, last15m_closed_end=2026-10-20T13:15+00:00, prior8high=0.057080, depth_time=2026-10-20T13:15:17+00:00, book20_bid_proxy_usdt=978515, book20_ask_proxy_usdt=748751, funding_indicative=-0.001778, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.51%, turnover=5342544. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-20T13:15:01+00:00, last15m_closed_end=2026-10-20T13:15+00:00, prior8high=265.610000, depth_time=2026-10-20T13:15:30+00:00, book20_bid_proxy_usdt=159423, book20_ask_proxy_usdt=63692, funding_indicative=0.000039, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.86%, turnover=59622669. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-20T13:15:01+00:00, last15m_closed_end=2026-10-20T13:15+00:00, prior8high=7.197000, depth_time=2026-10-20T13:15:24+00:00, book20_bid_proxy_usdt=1455579, book20_ask_proxy_usdt=1671199, funding_indicative=0.000006, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.19%, turnover=9630301. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-20T13:15:01+00:00, last15m_closed_end=2026-10-20T13:15+00:00, prior8high=1.918500, depth_time=2026-10-20T13:15:12+00:00, book20_bid_proxy_usdt=27466, book20_ask_proxy_usdt=45767, funding_indicative=0.000022, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.66%, turnover=7982772. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
