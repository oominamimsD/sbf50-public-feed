# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T06:15:19Z**
- feed_generated_utc: 2026-11-06T06:15:21+00:00
- source_sha256: `2e72fea260406bc5bb38677bc52eec4bbd32424313627d03d5fe26bb23dc1a54`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T06:15+00:00, close=75441.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-06T06:00+00:00, close=75669.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T04:00+00:00, close=75880.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|XRP_USDT|1.189500|-4.42|-9.16|-3.67|441286703|0.84|
|FLUID_USDT|2.421000|-4.38|17.29|-3.63|6225303|4.13|
|ELSA_USDT|0.077600|-4.37|3.88|-3.62|5790423|6.44|
|XPL_USDT|0.056530|-3.49|-28.37|-2.74|12413680|1.77|
|QNT_USDT|188.180000|-1.89|-5.31|-1.14|37408904|1.59|
|BCH_USDT|274.010000|-1.83|-4.95|-1.08|6944896|2.55|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BCH_USDT|274.010000|273.600000|274.010000|0.35|N|Y/Y|Y/Y|Y|N|
|ELSA_USDT|0.077600|0.076350|0.077600|0.58|N|Y/Y|Y/N|Y|N|
|FLUID_USDT|2.421000|2.409000|2.421000|5.85|N|Y/Y|N/N|Y|N|
|QNT_USDT|188.180000|188.630000|188.180000|2.84|Y|Y/Y|Y/Y|Y|Y|
|XPL_USDT|0.056530|0.056480|0.056530|2.88|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.189500|1.194200|1.189500|2.74|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- BCH_USDT: quote_utc=2026-11-06T06:15:00+00:00, last15m_closed_end=2026-11-06T06:15+00:00, prior8high=277.120000, depth_time=2026-11-06T06:15:18+00:00, book20_bid_proxy_usdt=49266, book20_ask_proxy_usdt=65728, funding_indicative=0.000100, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.83%, turnover=6944896. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ELSA_USDT: quote_utc=2026-11-06T06:14:59+00:00, last15m_closed_end=2026-11-06T06:15+00:00, prior8high=0.078430, depth_time=2026-11-06T06:15:11+00:00, book20_bid_proxy_usdt=27323, book20_ask_proxy_usdt=20701, funding_indicative=0.000067, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.37%, turnover=5790423. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FLUID_USDT: quote_utc=2026-11-06T06:15:00+00:00, last15m_closed_end=2026-11-06T06:15+00:00, prior8high=2.456000, depth_time=2026-11-06T06:15:09+00:00, book20_bid_proxy_usdt=289101, book20_ask_proxy_usdt=172285, funding_indicative=0.000381, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.38%, turnover=6225303. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-06T06:15:00+00:00, last15m_closed_end=2026-11-06T06:15+00:00, prior8high=191.280000, depth_time=2026-11-06T06:15:16+00:00, book20_bid_proxy_usdt=66298, book20_ask_proxy_usdt=83136, funding_indicative=-0.000001, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.89%, turnover=37408904. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-06T06:15:00+00:00, last15m_closed_end=2026-11-06T06:15+00:00, prior8high=0.057540, depth_time=2026-11-06T06:15:14+00:00, book20_bid_proxy_usdt=534189, book20_ask_proxy_usdt=386011, funding_indicative=0.000050, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.49%, turnover=12413680. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-06T06:14:59+00:00, last15m_closed_end=2026-11-06T06:15+00:00, prior8high=1.207300, depth_time=2026-11-06T06:15:07+00:00, book20_bid_proxy_usdt=3400337, book20_ask_proxy_usdt=3826695, funding_indicative=0.000100, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.42%, turnover=441286703. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
