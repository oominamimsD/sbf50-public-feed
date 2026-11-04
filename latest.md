# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T01:00:36Z**
- feed_generated_utc: 2026-11-04T01:00:39+00:00
- source_sha256: `55be5891d85a4b9a18e9b85b63e99937cae1e102d202a8e21a8376a1153a24f8`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T01:00+00:00, close=77225.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-04T01:00+00:00, close=77225.9, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T00:00+00:00, close=77441.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.003873|-5.74|-81.66|-5.17|13298947|5.17|
|TRUMPOFFICIAL_USDT|1.519000|-5.41|-10.01|-4.84|6356729|6.58|
|HYPE_USDT|84.000000|-3.83|5.71|-3.26|66509222|0.12|
|XPL_USDT|0.061980|-3.23|-16.03|-2.66|7199625|1.61|
|XLM_USDT|0.160730|-2.46|-5.01|-1.89|33509944|0.62|
|TIA_USDT|0.429700|-2.31|-19.84|-1.74|12404048|2.33|
|LINK_USDT|10.921000|-2.08|-4.62|-1.51|160562727|0.92|
|QNT_USDT|190.940000|-1.94|-3.51|-1.37|59390211|0.52|
|AAVE_USDT|126.020000|-1.86|-5.01|-1.29|21252764|0.79|
|OP_USDT|0.108490|-1.75|-2.54|-1.18|8934652|0.92|
|DASH_USDT|45.460000|-1.60|-16.07|-1.03|10251204|2.20|
|AVAX_USDT|8.438000|-1.58|-4.68|-1.01|18784862|1.18|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|126.020000|125.180000|126.020000|10.39|N|Y/Y|Y/Y|Y|N|
|AKE_USDT|0.003873|0.003829|0.003873|0.55|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.438000|8.378000|8.441000|2.04|N|Y/Y|Y/N|Y|N|
|DASH_USDT|45.460000|45.100000|45.460000|1.99|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|84.000000|83.134000|84.019000|2.23|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|10.921000|10.828000|10.919000|2.26|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.108490|0.107070|0.108490|1.13|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|190.940000|189.360000|190.940000|1.98|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.429700|0.423400|0.429700|0.46|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.519000|1.533000|1.519000|8.40|Y|Y/Y|Y/Y|Y|Y|
|XLM_USDT|0.160730|0.158870|0.160720|1.82|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.061980|0.061340|0.062000|2.98|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-04T01:00:03+00:00, last15m_closed_end=2026-11-04T01:00+00:00, prior8high=128.110000, depth_time=2026-11-04T01:00:28+00:00, book20_bid_proxy_usdt=335070, book20_ask_proxy_usdt=350236, funding_indicative=0.000100, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.86%, turnover=21252764. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T01:00:03+00:00, last15m_closed_end=2026-11-04T01:00+00:00, prior8high=0.004047, depth_time=2026-11-04T01:00:08+00:00, book20_bid_proxy_usdt=38585, book20_ask_proxy_usdt=32882, funding_indicative=-0.000774, next_funding_utc=2026-11-04T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.74%, turnover=13298947. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-11-04T01:00:03+00:00, last15m_closed_end=2026-11-04T01:00+00:00, prior8high=8.594000, depth_time=2026-11-04T01:00:35+00:00, book20_bid_proxy_usdt=937467, book20_ask_proxy_usdt=815510, funding_indicative=0.000100, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.58%, turnover=18784862. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-04T01:00:03+00:00, last15m_closed_end=2026-11-04T01:00+00:00, prior8high=46.700000, depth_time=2026-11-04T01:00:33+00:00, book20_bid_proxy_usdt=513892, book20_ask_proxy_usdt=612880, funding_indicative=0.000100, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.60%, turnover=10251204. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-04T01:00:03+00:00, last15m_closed_end=2026-11-04T01:00+00:00, prior8high=85.946000, depth_time=2026-11-04T01:00:14+00:00, book20_bid_proxy_usdt=89678, book20_ask_proxy_usdt=57789, funding_indicative=0.000050, next_funding_utc=2026-11-04T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.83%, turnover=66509222. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-04T01:00:03+00:00, last15m_closed_end=2026-11-04T01:00+00:00, prior8high=11.152000, depth_time=2026-11-04T01:00:24+00:00, book20_bid_proxy_usdt=323815, book20_ask_proxy_usdt=307168, funding_indicative=0.000100, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.08%, turnover=160562727. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-04T01:00:03+00:00, last15m_closed_end=2026-11-04T01:00+00:00, prior8high=0.110510, depth_time=2026-11-04T01:00:31+00:00, book20_bid_proxy_usdt=68327, book20_ask_proxy_usdt=123138, funding_indicative=0.000100, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.75%, turnover=8934652. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-04T01:00:03+00:00, last15m_closed_end=2026-11-04T01:00+00:00, prior8high=193.440000, depth_time=2026-11-04T01:00:26+00:00, book20_bid_proxy_usdt=56808, book20_ask_proxy_usdt=60157, funding_indicative=-0.000013, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.94%, turnover=59390211. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-04T01:00:03+00:00, last15m_closed_end=2026-11-04T01:00+00:00, prior8high=0.439200, depth_time=2026-11-04T01:00:21+00:00, book20_bid_proxy_usdt=260896, book20_ask_proxy_usdt=271222, funding_indicative=-0.000016, next_funding_utc=2026-11-04T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.31%, turnover=12404048. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T01:00:03+00:00, last15m_closed_end=2026-11-04T01:00+00:00, prior8high=1.602000, depth_time=2026-11-04T01:00:11+00:00, book20_bid_proxy_usdt=1799130, book20_ask_proxy_usdt=1941068, funding_indicative=0.000046, next_funding_utc=2026-11-04T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.41%, turnover=6356729. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-04T01:00:03+00:00, last15m_closed_end=2026-11-04T01:00+00:00, prior8high=0.163410, depth_time=2026-11-04T01:00:18+00:00, book20_bid_proxy_usdt=130947, book20_ask_proxy_usdt=167618, funding_indicative=0.000100, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.46%, turnover=33509944. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-04T01:00:03+00:00, last15m_closed_end=2026-11-04T01:00+00:00, prior8high=0.064100, depth_time=2026-11-04T01:00:16+00:00, book20_bid_proxy_usdt=344415, book20_ask_proxy_usdt=447713, funding_indicative=0.000050, next_funding_utc=2026-11-04T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.23%, turnover=7199625. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
