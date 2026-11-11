# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T06:30:32Z**
- feed_generated_utc: 2026-11-11T06:30:33+00:00
- source_sha256: `e64dccd70bea67b6f434b4a948605e6fcbbe364cd8dfbca8b362a9a222329953`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T06:30+00:00, close=73785.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-11T06:00+00:00, close=73895.6, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-11-11T04:00+00:00, close=73740.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|INIT_USDT|0.221730|-11.64|64.87|-12.46|66237332|1.35|
|AKE_USDT|0.002658|-8.78|-36.04|-9.60|9406463|3.76|
|ZEC_USDT|1004.670000|-8.11|-16.54|-8.93|2176335641|0.10|
|UNI_USDT|6.506000|-4.74|-11.51|-5.56|38264310|1.54|
|DASH_USDT|44.060000|-2.39|-4.50|-3.21|15230316|2.27|
|VVV_USDT|19.020000|-1.13|-14.94|-1.95|5371614|0.53|
|ARB_USDT|0.159620|-1.09|-0.16|-1.91|31669098|0.63|
|DOT_USDT|0.835800|-0.70|-11.33|-1.52|8177377|1.20|
|QNT_USDT|179.500000|-0.66|-8.14|-1.48|45740266|0.56|
|HBAR_USDT|0.065520|-0.39|-6.44|-1.21|5801814|1.53|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002658|0.002625|0.002658|1.92|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.159620|0.160160|0.159620|1.72|Y|Y/Y|Y/Y|Y|Y|
|DASH_USDT|44.060000|43.650000|44.060000|1.48|N|N/N|Y/Y|Y|N|
|DOT_USDT|0.835800|0.839400|0.835500|4.31|Y|Y/Y|Y/Y|Y|Y|
|HBAR_USDT|0.065520|0.065430|0.065520|8.23|N|Y/Y|Y/Y|Y|N|
|INIT_USDT|0.221730|0.234900|0.221730|0.76|N|N/N|N/N|Y|N|
|QNT_USDT|179.500000|179.480000|179.500000|0.86|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.506000|6.616000|6.506000|6.35|Y|Y/Y|Y/Y|Y|Y|
|VVV_USDT|19.020000|19.006000|19.020000|0.92|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1004.670000|1002.510000|1003.570000|0.92|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-11T06:30:01+00:00, last15m_closed_end=2026-11-11T06:30+00:00, prior8high=0.002864, depth_time=2026-11-11T06:30:10+00:00, book20_bid_proxy_usdt=46041, book20_ask_proxy_usdt=46750, funding_indicative=0.000050, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=4, 24h_change=-8.78%, turnover=9406463. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-11T06:30:01+00:00, last15m_closed_end=2026-11-11T06:30+00:00, prior8high=0.164540, depth_time=2026-11-11T06:30:22+00:00, book20_bid_proxy_usdt=29946, book20_ask_proxy_usdt=118064, funding_indicative=-0.000038, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.09%, turnover=31669098. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-11T06:30:01+00:00, last15m_closed_end=2026-11-11T06:30+00:00, prior8high=45.400000, depth_time=2026-11-11T06:30:18+00:00, book20_bid_proxy_usdt=859331, book20_ask_proxy_usdt=631513, funding_indicative=-0.000221, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.39%, turnover=15230316. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-11T06:30:01+00:00, last15m_closed_end=2026-11-11T06:30+00:00, prior8high=0.849100, depth_time=2026-11-11T06:30:23+00:00, book20_bid_proxy_usdt=565780, book20_ask_proxy_usdt=596393, funding_indicative=0.000024, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.70%, turnover=8177377. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-11-11T06:30:01+00:00, last15m_closed_end=2026-11-11T06:30+00:00, prior8high=0.065940, depth_time=2026-11-11T06:30:28+00:00, book20_bid_proxy_usdt=892123, book20_ask_proxy_usdt=660437, funding_indicative=-0.000015, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.39%, turnover=5801814. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INIT_USDT: quote_utc=2026-11-11T06:30:01+00:00, last15m_closed_end=2026-11-11T06:30+00:00, prior8high=0.299550, depth_time=2026-11-11T06:30:08+00:00, book20_bid_proxy_usdt=12999, book20_ask_proxy_usdt=11415, funding_indicative=-0.016692, next_funding_utc=2026-11-11T07:00:00+00:00, funding_cycle_h=1, 24h_change=-11.64%, turnover=66237332. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-11T06:30:01+00:00, last15m_closed_end=2026-11-11T06:30+00:00, prior8high=181.050000, depth_time=2026-11-11T06:30:28+00:00, book20_bid_proxy_usdt=126928, book20_ask_proxy_usdt=58304, funding_indicative=-0.000110, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.66%, turnover=45740266. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T06:30:01+00:00, last15m_closed_end=2026-11-11T06:30+00:00, prior8high=6.722000, depth_time=2026-11-11T06:30:16+00:00, book20_bid_proxy_usdt=2392560, book20_ask_proxy_usdt=1866213, funding_indicative=0.000003, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.74%, turnover=38264310. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-11T06:30:01+00:00, last15m_closed_end=2026-11-11T06:30+00:00, prior8high=19.311000, depth_time=2026-11-11T06:30:20+00:00, book20_bid_proxy_usdt=107670, book20_ask_proxy_usdt=21062, funding_indicative=0.000050, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.13%, turnover=5371614. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T06:30:01+00:00, last15m_closed_end=2026-11-11T06:30+00:00, prior8high=1027.770000, depth_time=2026-11-11T06:30:13+00:00, book20_bid_proxy_usdt=296867, book20_ask_proxy_usdt=200424, funding_indicative=0.000080, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-8.11%, turnover=2176335641. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
