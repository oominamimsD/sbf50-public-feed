# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T01:15:20Z**
- feed_generated_utc: 2026-11-11T01:15:22+00:00
- source_sha256: `589afad5fb1db1074d56218edb9d8cc6e44aeea8ccfb885a212cb3e00400cbdb`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T01:15+00:00, close=73376.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-11T01:00+00:00, close=73513.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-11T00:00+00:00, close=73762.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|INIT_USDT|0.199120|-20.65|48.06|-20.91|57585203|5.03|
|PIEVERSE_USDT|1.830200|-9.66|55.70|-9.92|5102353|1.09|
|ZEC_USDT|1025.350000|-6.21|-14.82|-6.47|2158717742|0.10|
|DASH_USDT|43.180000|-4.34|-6.41|-4.60|14090869|2.31|
|JCT_USDT|0.005128|-2.78|22.73|-3.04|18631017|1.95|
|UNI_USDT|6.699000|-1.91|-8.89|-2.17|34378775|1.49|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DASH_USDT|43.180000|42.400000|43.180000|0.61|N|Y/Y|Y/Y|Y|N|
|INIT_USDT|0.199120|0.190280|0.199120|1.92|N|Y/Y|N/N|Y|N|
|JCT_USDT|0.005128|0.004964|0.005128|1.29|N|Y/Y|Y/Y|Y|N|
|PIEVERSE_USDT|1.830200|1.808000|1.830200|1.17|N|Y/Y|N/N|Y|N|
|UNI_USDT|6.699000|6.611000|6.699000|4.08|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1025.350000|1030.550000|1025.340000|1.37|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- DASH_USDT: quote_utc=2026-11-11T01:15:00+00:00, last15m_closed_end=2026-11-11T01:15+00:00, prior8high=43.660000, depth_time=2026-11-11T01:15:15+00:00, book20_bid_proxy_usdt=931324, book20_ask_proxy_usdt=633757, funding_indicative=-0.000196, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.34%, turnover=14090869. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INIT_USDT: quote_utc=2026-11-11T01:15:00+00:00, last15m_closed_end=2026-11-11T01:15+00:00, prior8high=0.226550, depth_time=2026-11-11T01:15:07+00:00, book20_bid_proxy_usdt=6884, book20_ask_proxy_usdt=4134, funding_indicative=-0.011669, next_funding_utc=2026-11-11T02:00:00+00:00, funding_cycle_h=1, 24h_change=-20.65%, turnover=57585203. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-11T01:15:00+00:00, last15m_closed_end=2026-11-11T01:15+00:00, prior8high=0.005318, depth_time=2026-11-11T01:15:17+00:00, book20_bid_proxy_usdt=48104, book20_ask_proxy_usdt=43071, funding_indicative=0.000394, next_funding_utc=2026-11-11T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.78%, turnover=18631017. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PIEVERSE_USDT: quote_utc=2026-11-11T01:15:00+00:00, last15m_closed_end=2026-11-11T01:15+00:00, prior8high=1.870000, depth_time=2026-11-11T01:15:08+00:00, book20_bid_proxy_usdt=10766, book20_ask_proxy_usdt=11987, funding_indicative=0.000066, next_funding_utc=2026-11-11T04:00:00+00:00, funding_cycle_h=4, 24h_change=-9.66%, turnover=5102353. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T01:15:00+00:00, last15m_closed_end=2026-11-11T01:15+00:00, prior8high=6.740000, depth_time=2026-11-11T01:15:19+00:00, book20_bid_proxy_usdt=2768189, book20_ask_proxy_usdt=2098221, funding_indicative=0.000001, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.91%, turnover=34378775. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T01:15:00+00:00, last15m_closed_end=2026-11-11T01:15+00:00, prior8high=1049.410000, depth_time=2026-11-11T01:15:12+00:00, book20_bid_proxy_usdt=702806, book20_ask_proxy_usdt=349461, funding_indicative=0.000067, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.21%, turnover=2158717742. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
