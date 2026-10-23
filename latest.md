# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T12:00:39Z**
- feed_generated_utc: 2026-10-23T12:00:42+00:00
- source_sha256: `1d9859d1ce7311f7003b0df601c9683cc4abde5b204803c305699b636b39f8fb`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T12:00+00:00, close=81696.6, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-23T12:00+00:00, close=81696.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T12:00+00:00, close=81696.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.004195|-16.26|111.33|-16.31|6378813|9.52|
|MAGMA_USDT|0.438010|-12.75|85.24|-12.80|6980488|0.46|
|LIT_USDT|3.395900|-6.71|9.84|-6.76|8338687|0.29|
|QNT_USDT|182.950000|-5.16|-12.00|-5.21|52276411|0.55|
|TIA_USDT|0.547400|-4.91|-9.14|-4.96|24549845|3.65|
|STRK_USDT|0.052710|-4.05|-45.29|-4.10|12012510|3.79|
|SILVER_USDT|54.000000|-2.28|-5.49|-2.33|335433483|1.85|
|ARB_USDT|0.180370|-1.95|-5.03|-2.00|24041759|0.56|
|OP_USDT|0.118030|-1.54|-15.00|-1.59|5947605|1.69|
|PUMPFUN_USDT|0.004637|-1.36|2.45|-1.41|39621219|2.16|
|ZRO_USDT|1.783000|-1.08|-16.04|-1.13|6048207|3.93|
|HBAR_USDT|0.079500|-1.00|-4.84|-1.05|20116257|1.26|
|INJ_USDT|7.974000|-0.96|-0.43|-1.01|24679618|1.25|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.180370|0.179250|0.180370|1.10|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.079500|0.078710|0.079500|0.58|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.974000|7.944000|7.974000|1.30|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.004195|0.004042|0.004195|1.02|N|Y/Y|N/N|Y|N|
|LIT_USDT|3.395900|3.349800|3.395900|0.43|N|Y/Y|Y/Y|Y|N|
|MAGMA_USDT|0.438010|0.431000|0.438010|0.71|N|Y/Y|N/N|Y|N|
|OP_USDT|0.118030|0.116880|0.118040|1.44|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004637|0.004525|0.004637|1.75|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|182.950000|181.170000|182.950000|1.51|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|54.000000|53.890000|54.000000|1.98|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.052710|0.051150|0.052710|1.86|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.547400|0.545700|0.547400|2.11|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.783000|1.773200|1.783000|0.62|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-23T12:00:00+00:00, last15m_closed_end=2026-10-23T12:00+00:00, prior8high=0.181560, depth_time=2026-10-23T12:00:26+00:00, book20_bid_proxy_usdt=71910, book20_ask_proxy_usdt=56377, funding_indicative=-0.000015, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.95%, turnover=24041759. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-23T12:00:00+00:00, last15m_closed_end=2026-10-23T12:00+00:00, prior8high=0.079640, depth_time=2026-10-23T12:00:34+00:00, book20_bid_proxy_usdt=624828, book20_ask_proxy_usdt=1237793, funding_indicative=0.000049, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.00%, turnover=20116257. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-23T12:00:00+00:00, last15m_closed_end=2026-10-23T12:00+00:00, prior8high=8.068000, depth_time=2026-10-23T12:00:37+00:00, book20_bid_proxy_usdt=249113, book20_ask_proxy_usdt=252496, funding_indicative=0.000216, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.96%, turnover=24679618. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-10-23T12:00:00+00:00, last15m_closed_end=2026-10-23T12:00+00:00, prior8high=0.004254, depth_time=2026-10-23T12:00:06+00:00, book20_bid_proxy_usdt=48878, book20_ask_proxy_usdt=37000, funding_indicative=0.000101, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-16.26%, turnover=6378813. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T12:00:00+00:00, last15m_closed_end=2026-10-23T12:00+00:00, prior8high=3.401300, depth_time=2026-10-23T12:00:09+00:00, book20_bid_proxy_usdt=25004, book20_ask_proxy_usdt=24248, funding_indicative=0.000050, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.71%, turnover=8338687. target_RR/account_short_permission/settled_funding=UNKNOWN.
- MAGMA_USDT: quote_utc=2026-10-23T11:59:59+00:00, last15m_closed_end=2026-10-23T12:00+00:00, prior8high=0.512000, depth_time=2026-10-23T12:00:10+00:00, book20_bid_proxy_usdt=4200, book20_ask_proxy_usdt=2795, funding_indicative=0.000050, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-12.75%, turnover=6980488. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-23T12:00:00+00:00, last15m_closed_end=2026-10-23T12:00+00:00, prior8high=0.118640, depth_time=2026-10-23T12:00:28+00:00, book20_bid_proxy_usdt=93386, book20_ask_proxy_usdt=82197, funding_indicative=0.000034, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.54%, turnover=5947605. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-23T12:00:00+00:00, last15m_closed_end=2026-10-23T12:00+00:00, prior8high=0.004656, depth_time=2026-10-23T12:00:31+00:00, book20_bid_proxy_usdt=2508336, book20_ask_proxy_usdt=1530797, funding_indicative=0.000016, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.36%, turnover=39621219. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-23T12:00:00+00:00, last15m_closed_end=2026-10-23T12:00+00:00, prior8high=185.530000, depth_time=2026-10-23T12:00:16+00:00, book20_bid_proxy_usdt=89228, book20_ask_proxy_usdt=99665, funding_indicative=-0.000176, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.16%, turnover=52276411. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T11:59:59+00:00, last15m_closed_end=2026-10-23T12:00+00:00, prior8high=54.210000, depth_time=2026-10-23T12:00:23+00:00, book20_bid_proxy_usdt=37164916, book20_ask_proxy_usdt=37018530, funding_indicative=0.000014, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.28%, turnover=335433483. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T12:00:00+00:00, last15m_closed_end=2026-10-23T12:00+00:00, prior8high=0.051990, depth_time=2026-10-23T12:00:21+00:00, book20_bid_proxy_usdt=630688, book20_ask_proxy_usdt=489925, funding_indicative=0.000037, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.05%, turnover=12012510. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T12:00:00+00:00, last15m_closed_end=2026-10-23T12:00+00:00, prior8high=0.552300, depth_time=2026-10-23T12:00:18+00:00, book20_bid_proxy_usdt=357443, book20_ask_proxy_usdt=424524, funding_indicative=0.000013, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.91%, turnover=24549845. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-23T12:00:00+00:00, last15m_closed_end=2026-10-23T12:00+00:00, prior8high=1.807200, depth_time=2026-10-23T12:00:34+00:00, book20_bid_proxy_usdt=61082, book20_ask_proxy_usdt=50970, funding_indicative=0.000033, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.08%, turnover=6048207. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
