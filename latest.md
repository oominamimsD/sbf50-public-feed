# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T05:15:19Z**
- feed_generated_utc: 2026-11-11T05:15:20+00:00
- source_sha256: `b656b0ae43896225b4cbc711a5c28232911cc1ca17422dedf285327bb52f70fd`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T05:15+00:00, close=73714.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-11T05:00+00:00, close=73703.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-11T04:00+00:00, close=73740.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZEC_USDT|1009.180000|-7.69|-16.16|-8.42|2151156049|0.10|
|UNI_USDT|6.645000|-2.70|-9.62|-3.43|36237013|1.50|
|DASH_USDT|44.140000|-2.21|-4.33|-2.94|14556883|2.27|
|VVV_USDT|19.072000|-0.86|-14.70|-1.59|5336573|1.57|
|QNT_USDT|180.010000|-0.38|-7.88|-1.11|45259917|0.56|
|HBAR_USDT|0.065530|-0.38|-6.42|-1.11|7480797|1.53|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DASH_USDT|44.140000|43.290000|44.140000|0.83|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.065530|0.065520|0.065550|6.99|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|180.010000|179.480000|180.010000|0.69|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.645000|6.651000|6.645000|1.04|N|Y/Y|Y/Y|Y|N|
|VVV_USDT|19.072000|19.074000|19.072000|1.04|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1009.180000|1012.300000|1009.180000|1.02|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DASH_USDT: quote_utc=2026-11-11T05:15:00+00:00, last15m_closed_end=2026-11-11T05:15+00:00, prior8high=44.810000, depth_time=2026-11-11T05:15:11+00:00, book20_bid_proxy_usdt=567458, book20_ask_proxy_usdt=682462, funding_indicative=-0.000218, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.21%, turnover=14556883. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-11-11T05:15:00+00:00, last15m_closed_end=2026-11-11T05:15+00:00, prior8high=0.066370, depth_time=2026-11-11T05:15:15+00:00, book20_bid_proxy_usdt=683928, book20_ask_proxy_usdt=584152, funding_indicative=-0.000005, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.38%, turnover=7480797. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-11T05:15:00+00:00, last15m_closed_end=2026-11-11T05:15+00:00, prior8high=181.920000, depth_time=2026-11-11T05:15:15+00:00, book20_bid_proxy_usdt=56378, book20_ask_proxy_usdt=117543, funding_indicative=-0.000113, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.38%, turnover=45259917. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T05:15:00+00:00, last15m_closed_end=2026-11-11T05:15+00:00, prior8high=6.768000, depth_time=2026-11-11T05:15:08+00:00, book20_bid_proxy_usdt=2641278, book20_ask_proxy_usdt=4233463, funding_indicative=0.000044, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.70%, turnover=36237013. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-11T05:15:00+00:00, last15m_closed_end=2026-11-11T05:15+00:00, prior8high=19.529000, depth_time=2026-11-11T05:15:11+00:00, book20_bid_proxy_usdt=33378, book20_ask_proxy_usdt=17508, funding_indicative=0.000050, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.86%, turnover=5336573. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T05:15:00+00:00, last15m_closed_end=2026-11-11T05:15+00:00, prior8high=1038.490000, depth_time=2026-11-11T05:15:06+00:00, book20_bid_proxy_usdt=664184, book20_ask_proxy_usdt=269431, funding_indicative=0.000097, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-7.69%, turnover=2151156049. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
