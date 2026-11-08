# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T12:15:27Z**
- feed_generated_utc: 2026-11-08T12:15:28+00:00
- source_sha256: `23cba2b6a2b540e9c572c831aae28eb4a4918fa93adbaef34669d3082f444e4a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T12:15+00:00, close=75927.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T12:00+00:00, close=75944.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-08T12:00+00:00, close=75944.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IDOL_USDT|0.030578|-8.16|74.52|-8.42|16224965|6.20|
|ONE_USDT|0.001904|-6.51|62.16|-6.77|25263315|0.53|
|TIA_USDT|0.424900|-3.78|-13.30|-4.04|6723340|2.35|
|ENA_USDT|0.154330|-2.43|-20.45|-2.69|29322716|0.65|
|WLD_USDT|0.327700|-2.35|-18.96|-2.61|22558291|3.05|
|AAVE_USDT|130.330000|-1.43|-3.82|-1.69|9623159|0.77|
|LINK_USDT|10.755000|-0.82|-7.05|-1.08|62159698|0.93|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|130.330000|129.850000|130.330000|1.01|N|Y/Y|Y/N|Y|N|
|ENA_USDT|0.154330|0.152210|0.154330|0.55|N|Y/Y|Y/Y|Y|N|
|IDOL_USDT|0.030578|0.027111|0.030578|1.38|N|Y/N|N/N|Y|N|
|LINK_USDT|10.755000|10.718000|10.755000|1.45|N|N/Y|Y/Y|Y|N|
|ONE_USDT|0.001904|0.001872|0.001904|0.36|N|Y/Y|N/N|Y|N|
|TIA_USDT|0.424900|0.422800|0.424900|1.01|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.327700|0.326800|0.327700|1.14|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-08T12:15:00+00:00, last15m_closed_end=2026-11-08T12:15+00:00, prior8high=131.250000, depth_time=2026-11-08T12:15:17+00:00, book20_bid_proxy_usdt=401359, book20_ask_proxy_usdt=824673, funding_indicative=0.000055, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.43%, turnover=9623159. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-08T12:15:00+00:00, last15m_closed_end=2026-11-08T12:15+00:00, prior8high=0.155490, depth_time=2026-11-08T12:15:17+00:00, book20_bid_proxy_usdt=142068, book20_ask_proxy_usdt=256740, funding_indicative=0.000015, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.43%, turnover=29322716. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-08T12:15:00+00:00, last15m_closed_end=2026-11-08T12:15+00:00, prior8high=0.033952, depth_time=2026-11-08T12:15:09+00:00, book20_bid_proxy_usdt=3392, book20_ask_proxy_usdt=5151, funding_indicative=0.000503, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.16%, turnover=16224965. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-08T12:15:00+00:00, last15m_closed_end=2026-11-08T12:15+00:00, prior8high=10.807000, depth_time=2026-11-08T12:15:22+00:00, book20_bid_proxy_usdt=1096444, book20_ask_proxy_usdt=529511, funding_indicative=0.000023, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.82%, turnover=62159698. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T12:15:00+00:00, last15m_closed_end=2026-11-08T12:15+00:00, prior8high=0.002169, depth_time=2026-11-08T12:15:12+00:00, book20_bid_proxy_usdt=30364, book20_ask_proxy_usdt=7837, funding_indicative=-0.001264, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.51%, turnover=25263315. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T12:15:00+00:00, last15m_closed_end=2026-11-08T12:15+00:00, prior8high=0.427700, depth_time=2026-11-08T12:15:15+00:00, book20_bid_proxy_usdt=334113, book20_ask_proxy_usdt=306304, funding_indicative=-0.000024, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.78%, turnover=6723340. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T12:15:00+00:00, last15m_closed_end=2026-11-08T12:15+00:00, prior8high=0.330100, depth_time=2026-11-08T12:15:20+00:00, book20_bid_proxy_usdt=3787430, book20_ask_proxy_usdt=3353949, funding_indicative=-0.000024, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.35%, turnover=22558291. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
