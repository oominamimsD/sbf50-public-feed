# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T01:15:20Z**
- feed_generated_utc: 2026-10-20T01:15:22+00:00
- source_sha256: `b0322b5b562d3afe2d58a754d9b98f3a29fce6484c34db527d5577e79ede8094`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T01:15+00:00, close=81237.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-20T01:00+00:00, close=81700.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T00:00+00:00, close=81903.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZRO_USDT|1.836000|-3.47|-18.79|-2.64|7788255|0.54|
|SAND_USDT|0.057170|-3.33|-7.92|-2.50|8708622|1.75|
|NEAR_USDT|4.791000|-2.30|-13.66|-1.47|169559621|2.09|
|QNT_USDT|191.450000|-2.17|-16.17|-1.34|74580778|4.18|
|SEI_USDT|0.059400|-2.09|-10.50|-1.26|6612091|1.68|
|TAO_USDT|263.170000|-1.91|-8.07|-1.08|54957357|1.14|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|NEAR_USDT|4.791000|4.813000|4.791000|0.89|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|191.450000|192.920000|191.450000|1.79|Y|Y/Y|Y/Y|Y|Y|
|SAND_USDT|0.057170|0.057780|0.057170|6.83|Y|Y/Y|N/Y|Y|N|
|SEI_USDT|0.059400|0.060210|0.059400|2.05|Y|Y/N|Y/Y|Y|N|
|TAO_USDT|263.170000|265.540000|263.170000|2.86|Y|Y/Y|Y/Y|Y|Y|
|ZRO_USDT|1.836000|1.872900|1.836000|2.06|Y|Y/N|N/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- NEAR_USDT: quote_utc=2026-10-20T01:15:02+00:00, last15m_closed_end=2026-10-20T01:15+00:00, prior8high=4.939000, depth_time=2026-10-20T01:15:13+00:00, book20_bid_proxy_usdt=1947952, book20_ask_proxy_usdt=510060, funding_indicative=0.000023, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.30%, turnover=169559621. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-20T01:15:02+00:00, last15m_closed_end=2026-10-20T01:15+00:00, prior8high=195.220000, depth_time=2026-10-20T01:15:15+00:00, book20_bid_proxy_usdt=68818, book20_ask_proxy_usdt=60606, funding_indicative=0.000057, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.17%, turnover=74580778. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-20T01:15:02+00:00, last15m_closed_end=2026-10-20T01:15+00:00, prior8high=0.059370, depth_time=2026-10-20T01:15:09+00:00, book20_bid_proxy_usdt=514628, book20_ask_proxy_usdt=532981, funding_indicative=-0.002386, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.33%, turnover=8708622. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-20T01:15:02+00:00, last15m_closed_end=2026-10-20T01:15+00:00, prior8high=0.060920, depth_time=2026-10-20T01:15:16+00:00, book20_bid_proxy_usdt=195554, book20_ask_proxy_usdt=104175, funding_indicative=0.000100, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.09%, turnover=6612091. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-20T01:15:02+00:00, last15m_closed_end=2026-10-20T01:15+00:00, prior8high=269.030000, depth_time=2026-10-20T01:15:19+00:00, book20_bid_proxy_usdt=54947, book20_ask_proxy_usdt=252993, funding_indicative=0.000040, next_funding_utc=2026-10-20T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.91%, turnover=54957357. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-20T01:15:02+00:00, last15m_closed_end=2026-10-20T01:15+00:00, prior8high=1.924500, depth_time=2026-10-20T01:15:08+00:00, book20_bid_proxy_usdt=32155, book20_ask_proxy_usdt=43433, funding_indicative=0.000050, next_funding_utc=2026-10-20T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.47%, turnover=7788255. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
