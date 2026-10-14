# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T09:45:24Z**
- feed_generated_utc: 2026-10-14T09:45:26+00:00
- source_sha256: `dc05d3f1e7eee7961ed0c3661868a9285a70708c0593aa7535732713ab8bd798`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T09:45+00:00, close=83268.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T09:00+00:00, close=83400.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-14T08:00+00:00, close=83540.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.078680|-9.49|50.75|-9.32|30524380|1.27|
|TIA_USDT|0.546200|-5.38|14.67|-5.21|39094060|5.49|
|W_USDT|0.015973|-4.93|10.06|-4.76|6946526|3.76|
|UNI_USDT|7.342000|-3.03|-15.26|-2.86|19649510|1.36|
|DOT_USDT|1.134000|-1.97|-5.61|-1.80|20691010|0.88|
|RENDER_USDT|1.955000|-1.61|-8.21|-1.44|10502832|5.11|
|ICP_USDT|3.068000|-1.41|-9.81|-1.24|10088323|3.26|
|XLM_USDT|0.188370|-1.36|-11.84|-1.19|10319846|0.53|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOT_USDT|1.134000|1.134200|1.134000|2.60|Y|Y/Y|Y/Y|N|Y|
|ICP_USDT|3.068000|3.067000|3.068000|2.93|N|Y/Y|Y/Y|N|N|
|RENDER_USDT|1.955000|1.955000|1.955000|1.92|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.078680|0.078250|0.078650|0.87|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.546200|0.547900|0.546400|1.68|Y|Y/Y|Y/N|N|N|
|UNI_USDT|7.342000|7.339000|7.343000|0.75|N|Y/Y|Y/Y|N|N|
|W_USDT|0.015973|0.016037|0.015953|3.00|Y|Y/Y|Y/Y|N|Y|
|XLM_USDT|0.188370|0.188470|0.188370|1.42|Y|Y/Y|Y/Y|N|Y|

## Detailed time markers and risk references (NOT executable limits)
- DOT_USDT: quote_utc=2026-10-14T09:45:02+00:00, last15m_closed_end=2026-10-14T09:45+00:00, prior8high=1.164200, depth_time=2026-10-14T09:45:15+00:00, book20_bid_proxy_usdt=252730, book20_ask_proxy_usdt=287029, funding_indicative=0.000000, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.97%, turnover=20691010. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-14T09:45:02+00:00, last15m_closed_end=2026-10-14T09:45+00:00, prior8high=3.139000, depth_time=2026-10-14T09:45:21+00:00, book20_bid_proxy_usdt=1137812, book20_ask_proxy_usdt=711834, funding_indicative=0.000090, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.41%, turnover=10088323. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RENDER_USDT: quote_utc=2026-10-14T09:45:02+00:00, last15m_closed_end=2026-10-14T09:45+00:00, prior8high=2.037000, depth_time=2026-10-14T09:45:19+00:00, book20_bid_proxy_usdt=1922134, book20_ask_proxy_usdt=1564720, funding_indicative=0.000017, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.61%, turnover=10502832. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T09:45:02+00:00, last15m_closed_end=2026-10-14T09:45+00:00, prior8high=0.083790, depth_time=2026-10-14T09:45:07+00:00, book20_bid_proxy_usdt=195205, book20_ask_proxy_usdt=393620, funding_indicative=0.000050, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-9.49%, turnover=30524380. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-14T09:45:02+00:00, last15m_closed_end=2026-10-14T09:45+00:00, prior8high=0.564000, depth_time=2026-10-14T09:45:09+00:00, book20_bid_proxy_usdt=121310, book20_ask_proxy_usdt=185878, funding_indicative=0.000000, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.38%, turnover=39094060. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-14T09:45:02+00:00, last15m_closed_end=2026-10-14T09:45+00:00, prior8high=7.502000, depth_time=2026-10-14T09:45:14+00:00, book20_bid_proxy_usdt=1249434, book20_ask_proxy_usdt=1521577, funding_indicative=0.000100, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.03%, turnover=19649510. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-14T09:45:02+00:00, last15m_closed_end=2026-10-14T09:45+00:00, prior8high=0.016686, depth_time=2026-10-14T09:45:12+00:00, book20_bid_proxy_usdt=43052, book20_ask_proxy_usdt=46661, funding_indicative=-0.000367, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.93%, turnover=6946526. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-10-14T09:45:02+00:00, last15m_closed_end=2026-10-14T09:45+00:00, prior8high=0.192050, depth_time=2026-10-14T09:45:22+00:00, book20_bid_proxy_usdt=186646, book20_ask_proxy_usdt=165730, funding_indicative=-0.000079, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.36%, turnover=10319846. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
