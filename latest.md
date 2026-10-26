# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T05:00:26Z**
- feed_generated_utc: 2026-10-26T05:00:29+00:00
- source_sha256: `629d939413ef08613cf0b666c7c31fe633ddf7dc2d2540f95be6b54cf4217806`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T05:00+00:00, close=80102.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-26T05:00+00:00, close=80102.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T04:00+00:00, close=79565.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|APR_USDT|0.035090|-13.82|28.81|-13.21|11480740|2.85|
|T_USDT|0.004872|-9.49|3.61|-8.88|5945412|2.06|
|IRYS_USDT|0.035110|-8.66|187.78|-8.05|13927263|2.85|
|LIT_USDT|3.059500|-3.43|4.40|-2.82|6085101|0.33|
|XMR_USDT|592.730000|-2.56|1.75|-1.95|6772135|0.17|
|DASH_USDT|51.240000|-2.23|7.01|-1.62|13454252|3.90|
|WLD_USDT|0.444200|-1.76|-6.73|-1.15|72586012|2.25|
|BTW_USDT|1.630300|-1.72|-29.28|-1.11|12426767|1.23|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APR_USDT|0.035090|0.032590|0.035090|0.57|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.630300|1.620600|1.630500|1.02|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|51.240000|50.050000|51.230000|0.15|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.035110|0.034640|0.035140|0.53|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.059500|3.000300|3.059500|3.30|N|Y/Y|Y/Y|Y|N|
|T_USDT|0.004872|0.004908|0.004873|0.82|N|Y/Y|Y/N|Y|N|
|WLD_USDT|0.444200|0.434800|0.444200|0.95|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|592.730000|588.910000|592.730000|0.73|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APR_USDT: quote_utc=2026-10-26T05:00:01+00:00, last15m_closed_end=2026-10-26T05:00+00:00, prior8high=0.036370, depth_time=2026-10-26T05:00:08+00:00, book20_bid_proxy_usdt=76048, book20_ask_proxy_usdt=65792, funding_indicative=0.000050, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-13.82%, turnover=11480740. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-26T05:00:01+00:00, last15m_closed_end=2026-10-26T05:00+00:00, prior8high=1.683000, depth_time=2026-10-26T05:00:26+00:00, book20_bid_proxy_usdt=12226, book20_ask_proxy_usdt=10938, funding_indicative=-0.003779, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.72%, turnover=12426767. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-26T05:00:01+00:00, last15m_closed_end=2026-10-26T05:00+00:00, prior8high=51.060000, depth_time=2026-10-26T05:00:18+00:00, book20_bid_proxy_usdt=992355, book20_ask_proxy_usdt=588609, funding_indicative=0.000063, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.23%, turnover=13454252. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T05:00:01+00:00, last15m_closed_end=2026-10-26T05:00+00:00, prior8high=0.039970, depth_time=2026-10-26T05:00:13+00:00, book20_bid_proxy_usdt=76537, book20_ask_proxy_usdt=68097, funding_indicative=-0.000882, next_funding_utc=2026-10-26T06:00:00+00:00, funding_cycle_h=1, 24h_change=-8.66%, turnover=13927263. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T05:00:01+00:00, last15m_closed_end=2026-10-26T05:00+00:00, prior8high=3.136000, depth_time=2026-10-26T05:00:15+00:00, book20_bid_proxy_usdt=33395, book20_ask_proxy_usdt=20328, funding_indicative=0.000050, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.43%, turnover=6085101. target_RR/account_short_permission/settled_funding=UNKNOWN.
- T_USDT: quote_utc=2026-10-26T05:00:01+00:00, last15m_closed_end=2026-10-26T05:00+00:00, prior8high=0.004998, depth_time=2026-10-26T05:00:11+00:00, book20_bid_proxy_usdt=70830, book20_ask_proxy_usdt=88932, funding_indicative=-0.001346, next_funding_utc=2026-10-26T06:00:00+00:00, funding_cycle_h=1, 24h_change=-9.49%, turnover=5945412. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T05:00:01+00:00, last15m_closed_end=2026-10-26T05:00+00:00, prior8high=0.447400, depth_time=2026-10-26T05:00:22+00:00, book20_bid_proxy_usdt=2528923, book20_ask_proxy_usdt=2246089, funding_indicative=0.000056, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.76%, turnover=72586012. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T05:00:01+00:00, last15m_closed_end=2026-10-26T05:00+00:00, prior8high=598.030000, depth_time=2026-10-26T05:00:16+00:00, book20_bid_proxy_usdt=27746, book20_ask_proxy_usdt=12859, funding_indicative=0.000100, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.56%, turnover=6772135. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
