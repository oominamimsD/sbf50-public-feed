# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T05:30:22Z**
- feed_generated_utc: 2026-10-23T05:30:24+00:00
- source_sha256: `5c9b0920969535f2fc0cc3cd31e4559747f3be5ccbee779fc674ca58cd4bb828`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1214; contracts: 1206; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T05:30+00:00, close=81610.7, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-23T05:00+00:00, close=81561.7, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-10-23T04:00+00:00, close=81863.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.004227|-8.26|112.94|-8.22|8887078|7.09|
|LIT_USDT|3.431400|-5.05|10.99|-5.01|10477250|0.29|
|STRK_USDT|0.052740|-2.98|-45.26|-2.94|11459539|3.79|
|SILVER_USDT|54.090000|-2.11|-5.33|-2.07|359258114|1.85|
|TIA_USDT|0.557200|-1.97|-7.51|-1.93|23593417|1.79|
|PUMPFUN_USDT|0.004622|-1.21|2.12|-1.17|38506949|2.16|
|ZEC_USDT|1220.880000|-1.08|3.48|-1.04|1881884208|0.08|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|JCT_USDT|0.004227|0.004130|0.004227|0.75|N|Y/Y|N/N|Y|N|
|LIT_USDT|3.431400|3.428400|3.431400|0.91|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004622|0.004595|0.004622|0.21|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|54.090000|53.720000|54.090000|1.28|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.052740|0.052690|0.052730|0.50|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.557200|0.557400|0.557200|1.92|Y|Y/Y|Y/Y|Y|Y|
|ZEC_USDT|1220.880000|1211.520000|1220.880000|1.02|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- JCT_USDT: quote_utc=2026-10-23T05:29:59+00:00, last15m_closed_end=2026-10-23T05:30+00:00, prior8high=0.004367, depth_time=2026-10-23T05:30:07+00:00, book20_bid_proxy_usdt=42360, book20_ask_proxy_usdt=31942, funding_indicative=0.000050, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-8.26%, turnover=8887078. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T05:29:59+00:00, last15m_closed_end=2026-10-23T05:30+00:00, prior8high=3.509900, depth_time=2026-10-23T05:30:08+00:00, book20_bid_proxy_usdt=29640, book20_ask_proxy_usdt=107340, funding_indicative=0.000048, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.05%, turnover=10477250. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-23T05:29:59+00:00, last15m_closed_end=2026-10-23T05:30+00:00, prior8high=0.004668, depth_time=2026-10-23T05:30:19+00:00, book20_bid_proxy_usdt=2232120, book20_ask_proxy_usdt=1897828, funding_indicative=0.000017, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.21%, turnover=38506949. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T05:29:59+00:00, last15m_closed_end=2026-10-23T05:30+00:00, prior8high=54.220000, depth_time=2026-10-23T05:30:14+00:00, book20_bid_proxy_usdt=35621995, book20_ask_proxy_usdt=34700142, funding_indicative=0.000152, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.11%, turnover=359258114. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T05:29:59+00:00, last15m_closed_end=2026-10-23T05:30+00:00, prior8high=0.053370, depth_time=2026-10-23T05:30:12+00:00, book20_bid_proxy_usdt=861917, book20_ask_proxy_usdt=629828, funding_indicative=0.000008, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.98%, turnover=11459539. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T05:29:59+00:00, last15m_closed_end=2026-10-23T05:30+00:00, prior8high=0.565900, depth_time=2026-10-23T05:30:16+00:00, book20_bid_proxy_usdt=436850, book20_ask_proxy_usdt=380879, funding_indicative=0.000006, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.97%, turnover=23593417. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-23T05:29:59+00:00, last15m_closed_end=2026-10-23T05:30+00:00, prior8high=1231.090000, depth_time=2026-10-23T05:30:21+00:00, book20_bid_proxy_usdt=300404, book20_ask_proxy_usdt=329967, funding_indicative=0.000001, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.08%, turnover=1881884208. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
