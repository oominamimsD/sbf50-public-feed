# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T06:00:37Z**
- feed_generated_utc: 2026-10-20T06:00:40+00:00
- source_sha256: `9fce6b63a3c20dfc9d61b35b66e37f7b6d1b49de859848d94bc41a1949208ac1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T06:00+00:00, close=81684.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-20T06:00+00:00, close=81684.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T04:00+00:00, close=82099.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.112573|-8.93|265.60|-8.65|9287347|0.27|
|CT_USDT|0.305930|-8.23|-10.58|-7.95|5416131|6.54|
|BTW_USDT|1.774700|-7.22|1.07|-6.94|29905889|1.69|
|SAND_USDT|0.056870|-4.51|-8.40|-4.23|8141434|1.76|
|NEAR_USDT|4.782000|-2.48|-13.82|-2.20|166217440|2.09|
|PUMPFUN_USDT|0.004381|-2.25|-17.47|-1.97|29729602|2.28|
|TAO_USDT|264.790000|-1.95|-7.50|-1.67|52290152|1.13|
|QNT_USDT|192.520000|-1.62|-15.70|-1.34|81168008|2.08|
|SEI_USDT|0.059940|-1.60|-9.68|-1.32|6804331|1.67|
|FILECOIN_USDT|1.008400|-1.46|-13.24|-1.18|8593278|0.99|
|STRK_USDT|0.056410|-1.43|-37.78|-1.15|19885826|1.77|
|AVAX_USDT|9.551000|-1.41|-10.57|-1.13|130742679|2.09|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AVAX_USDT|9.551000|9.547000|9.552000|1.48|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.774700|1.675200|1.774600|1.71|N|Y/Y|Y/Y|Y|N|
|CT_USDT|0.305930|0.302430|0.305930|0.43|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|1.008400|1.006000|1.008400|0.67|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.782000|4.765000|4.781000|0.92|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004381|0.004383|0.004381|0.84|N|Y/N|N/N|Y|N|
|QNT_USDT|192.520000|192.910000|192.490000|1.70|Y|Y/Y|N/Y|Y|N|
|Q_USDT|0.112573|0.112868|0.112553|2.69|Y|Y/Y|N/N|Y|N|
|SAND_USDT|0.056870|0.056650|0.056870|0.39|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.059940|0.059930|0.059940|0.97|N|Y/N|Y/Y|Y|N|
|STRK_USDT|0.056410|0.055750|0.056410|1.12|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|264.790000|264.470000|264.790000|1.42|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AVAX_USDT: quote_utc=2026-10-20T06:00:00+00:00, last15m_closed_end=2026-10-20T06:00+00:00, prior8high=9.635000, depth_time=2026-10-20T06:00:36+00:00, book20_bid_proxy_usdt=919672, book20_ask_proxy_usdt=1065210, funding_indicative=-0.000017, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.41%, turnover=130742679. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-20T06:00:00+00:00, last15m_closed_end=2026-10-20T06:00+00:00, prior8high=1.942600, depth_time=2026-10-20T06:00:14+00:00, book20_bid_proxy_usdt=7633, book20_ask_proxy_usdt=8002, funding_indicative=-0.003598, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-7.22%, turnover=29905889. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CT_USDT: quote_utc=2026-10-20T06:00:00+00:00, last15m_closed_end=2026-10-20T06:00+00:00, prior8high=0.333240, depth_time=2026-10-20T06:00:10+00:00, book20_bid_proxy_usdt=10540, book20_ask_proxy_usdt=8972, funding_indicative=-0.002585, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-8.23%, turnover=5416131. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-20T06:00:01+00:00, last15m_closed_end=2026-10-20T06:00+00:00, prior8high=1.027100, depth_time=2026-10-20T06:00:29+00:00, book20_bid_proxy_usdt=477878, book20_ask_proxy_usdt=827916, funding_indicative=-0.000085, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.46%, turnover=8593278. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-20T06:00:00+00:00, last15m_closed_end=2026-10-20T06:00+00:00, prior8high=4.872000, depth_time=2026-10-20T06:00:19+00:00, book20_bid_proxy_usdt=2113978, book20_ask_proxy_usdt=1608617, funding_indicative=0.000000, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.48%, turnover=166217440. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-20T06:00:00+00:00, last15m_closed_end=2026-10-20T06:00+00:00, prior8high=0.004489, depth_time=2026-10-20T06:00:22+00:00, book20_bid_proxy_usdt=1091024, book20_ask_proxy_usdt=1152724, funding_indicative=0.000050, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.25%, turnover=29729602. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-20T06:00:00+00:00, last15m_closed_end=2026-10-20T06:00+00:00, prior8high=198.680000, depth_time=2026-10-20T06:00:26+00:00, book20_bid_proxy_usdt=76923, book20_ask_proxy_usdt=88985, funding_indicative=0.000002, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.62%, turnover=81168008. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-20T06:00:00+00:00, last15m_closed_end=2026-10-20T06:00+00:00, prior8high=0.133766, depth_time=2026-10-20T06:00:08+00:00, book20_bid_proxy_usdt=19793, book20_ask_proxy_usdt=14442, funding_indicative=-0.000260, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-8.93%, turnover=9287347. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-20T06:00:01+00:00, last15m_closed_end=2026-10-20T06:00+00:00, prior8high=0.058160, depth_time=2026-10-20T06:00:17+00:00, book20_bid_proxy_usdt=765706, book20_ask_proxy_usdt=1039807, funding_indicative=-0.001773, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.51%, turnover=8141434. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-20T06:00:01+00:00, last15m_closed_end=2026-10-20T06:00+00:00, prior8high=0.061300, depth_time=2026-10-20T06:00:28+00:00, book20_bid_proxy_usdt=190545, book20_ask_proxy_usdt=213738, funding_indicative=0.000046, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.60%, turnover=6804331. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-20T06:00:00+00:00, last15m_closed_end=2026-10-20T06:00+00:00, prior8high=0.058290, depth_time=2026-10-20T06:00:33+00:00, book20_bid_proxy_usdt=556916, book20_ask_proxy_usdt=696437, funding_indicative=0.000022, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.43%, turnover=19885826. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-20T06:00:00+00:00, last15m_closed_end=2026-10-20T06:00+00:00, prior8high=269.360000, depth_time=2026-10-20T06:00:24+00:00, book20_bid_proxy_usdt=88150, book20_ask_proxy_usdt=84635, funding_indicative=0.000047, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.95%, turnover=52290152. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
