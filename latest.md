# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T10:00:29Z**
- feed_generated_utc: 2026-10-23T10:00:31+00:00
- source_sha256: `75ce56b3e786e2e009e661ae3e3c2f880016bc758233578bccf2fb96489aa342`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T10:00+00:00, close=81630.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-23T10:00+00:00, close=81630.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T08:00+00:00, close=81544.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.004097|-11.08|106.39|-11.06|7947267|9.76|
|LIT_USDT|3.378800|-6.51|9.29|-6.49|9626884|0.30|
|STRK_USDT|0.051600|-5.07|-46.45|-5.05|12482678|1.94|
|TIA_USDT|0.550600|-3.13|-8.61|-3.11|25815600|1.82|
|QNT_USDT|184.830000|-3.08|-11.10|-3.06|49961867|2.16|
|SILVER_USDT|53.970000|-2.33|-5.54|-2.31|339822912|1.85|
|PUMPFUN_USDT|0.004578|-2.15|1.14|-2.13|36539862|2.19|
|ARB_USDT|0.180360|-1.78|-5.04|-1.76|26148121|0.56|
|OP_USDT|0.118090|-1.46|-14.96|-1.44|6350390|1.69|
|HBAR_USDT|0.079230|-1.09|-5.17|-1.07|20032605|1.26|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.180360|0.179350|0.180360|1.29|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.079230|0.079040|0.079230|1.14|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.004097|0.004082|0.004097|1.21|N|Y/Y|N/N|Y|N|
|LIT_USDT|3.378800|3.369300|3.378800|0.46|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.118090|0.117700|0.118090|1.00|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004578|0.004556|0.004578|2.11|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|184.830000|183.630000|184.850000|1.87|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|53.970000|53.870000|53.970000|0.67|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.051600|0.051730|0.051600|1.45|Y|Y/Y|Y/Y|Y|Y|
|TIA_USDT|0.550600|0.548100|0.550600|0.49|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-23T09:59:59+00:00, last15m_closed_end=2026-10-23T10:00+00:00, prior8high=0.182430, depth_time=2026-10-23T10:00:23+00:00, book20_bid_proxy_usdt=74876, book20_ask_proxy_usdt=61429, funding_indicative=-0.000018, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.78%, turnover=26148121. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-23T09:59:59+00:00, last15m_closed_end=2026-10-23T10:00+00:00, prior8high=0.080470, depth_time=2026-10-23T10:00:27+00:00, book20_bid_proxy_usdt=629534, book20_ask_proxy_usdt=525650, funding_indicative=0.000038, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.09%, turnover=20032605. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-10-23T09:59:59+00:00, last15m_closed_end=2026-10-23T10:00+00:00, prior8high=0.004279, depth_time=2026-10-23T10:00:07+00:00, book20_bid_proxy_usdt=61710, book20_ask_proxy_usdt=48344, funding_indicative=0.000077, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-11.08%, turnover=7947267. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T09:59:59+00:00, last15m_closed_end=2026-10-23T10:00+00:00, prior8high=3.441600, depth_time=2026-10-23T10:00:08+00:00, book20_bid_proxy_usdt=22217, book20_ask_proxy_usdt=22447, funding_indicative=0.000050, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.51%, turnover=9626884. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-23T09:59:59+00:00, last15m_closed_end=2026-10-23T10:00+00:00, prior8high=0.120000, depth_time=2026-10-23T10:00:26+00:00, book20_bid_proxy_usdt=111704, book20_ask_proxy_usdt=88419, funding_indicative=0.000003, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.46%, turnover=6350390. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-23T09:59:59+00:00, last15m_closed_end=2026-10-23T10:00+00:00, prior8high=0.004660, depth_time=2026-10-23T10:00:21+00:00, book20_bid_proxy_usdt=1231316, book20_ask_proxy_usdt=2110156, funding_indicative=0.000000, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.15%, turnover=36539862. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-23T09:59:59+00:00, last15m_closed_end=2026-10-23T10:00+00:00, prior8high=189.310000, depth_time=2026-10-23T10:00:16+00:00, book20_bid_proxy_usdt=107532, book20_ask_proxy_usdt=126067, funding_indicative=-0.000165, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.08%, turnover=49961867. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T09:59:59+00:00, last15m_closed_end=2026-10-23T10:00+00:00, prior8high=54.210000, depth_time=2026-10-23T10:00:19+00:00, book20_bid_proxy_usdt=40789549, book20_ask_proxy_usdt=39000333, funding_indicative=0.000090, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.33%, turnover=339822912. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T09:59:59+00:00, last15m_closed_end=2026-10-23T10:00+00:00, prior8high=0.053440, depth_time=2026-10-23T10:00:11+00:00, book20_bid_proxy_usdt=509640, book20_ask_proxy_usdt=661035, funding_indicative=0.000017, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.07%, turnover=12482678. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T09:59:59+00:00, last15m_closed_end=2026-10-23T10:00+00:00, prior8high=0.560000, depth_time=2026-10-23T10:00:14+00:00, book20_bid_proxy_usdt=410774, book20_ask_proxy_usdt=461891, funding_indicative=0.000007, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.13%, turnover=25815600. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
