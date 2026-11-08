# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T04:00:20Z**
- feed_generated_utc: 2026-11-08T04:00:21+00:00
- source_sha256: `cac0fcd2018edd712418b8fdfdb17956b851e4d6f69b8c607ae1bcb79892344f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T04:00+00:00, close=75885, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T04:00+00:00, close=75885, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-11-08T04:00+00:00, close=75885, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AIN_USDT|0.139690|-10.32|-39.83|-10.52|9554979|5.73|
|ONE_USDT|0.001846|-9.36|57.20|-9.56|26847243|0.54|
|ENA_USDT|0.154480|-2.33|-20.37|-2.53|28518343|0.65|
|QNT_USDT|194.340000|-2.26|-3.33|-2.46|44602145|0.52|
|WLD_USDT|0.330200|-1.60|-18.34|-1.80|25325707|3.03|
|TIA_USDT|0.437200|-0.99|-10.79|-1.19|7297401|2.29|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AIN_USDT|0.139690|0.117040|0.139690|1.93|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.154480|0.153550|0.154480|0.59|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001846|0.001812|0.001846|0.81|N|Y/Y|N/N|Y|N|
|QNT_USDT|194.340000|193.120000|194.340000|1.16|N|Y/Y|Y/N|Y|N|
|TIA_USDT|0.437200|0.434500|0.437200|0.87|N|Y/Y|Y/N|Y|N|
|WLD_USDT|0.330200|0.329000|0.330200|1.31|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AIN_USDT: quote_utc=2026-11-08T03:59:59+00:00, last15m_closed_end=2026-11-08T04:00+00:00, prior8high=0.157480, depth_time=2026-11-08T04:00:06+00:00, book20_bid_proxy_usdt=4862, book20_ask_proxy_usdt=17047, funding_indicative=0.000286, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-10.32%, turnover=9554979. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-08T03:59:59+00:00, last15m_closed_end=2026-11-08T04:00+00:00, prior8high=0.156250, depth_time=2026-11-08T04:00:11+00:00, book20_bid_proxy_usdt=266499, book20_ask_proxy_usdt=228422, funding_indicative=-0.000006, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.33%, turnover=28518343. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T03:59:59+00:00, last15m_closed_end=2026-11-08T04:00+00:00, prior8high=0.002086, depth_time=2026-11-08T04:00:09+00:00, book20_bid_proxy_usdt=12977, book20_ask_proxy_usdt=9594, funding_indicative=-0.000006, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-9.36%, turnover=26847243. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-08T03:59:59+00:00, last15m_closed_end=2026-11-08T04:00+00:00, prior8high=195.100000, depth_time=2026-11-08T04:00:14+00:00, book20_bid_proxy_usdt=80549, book20_ask_proxy_usdt=75055, funding_indicative=0.000100, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.26%, turnover=44602145. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T03:59:59+00:00, last15m_closed_end=2026-11-08T04:00+00:00, prior8high=0.438500, depth_time=2026-11-08T04:00:14+00:00, book20_bid_proxy_usdt=276162, book20_ask_proxy_usdt=335057, funding_indicative=0.000024, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.99%, turnover=7297401. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T03:59:59+00:00, last15m_closed_end=2026-11-08T04:00+00:00, prior8high=0.332300, depth_time=2026-11-08T04:00:16+00:00, book20_bid_proxy_usdt=3398243, book20_ask_proxy_usdt=3468116, funding_indicative=-0.000112, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.60%, turnover=25325707. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
