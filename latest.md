# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T05:45:18Z**
- feed_generated_utc: 2026-10-23T05:45:20+00:00
- source_sha256: `f42ec54fe4cf5c8e906b2591beec2a5688d50837923b8a46e913ee9fa6d9fe3c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1214; contracts: 1206; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T05:45+00:00, close=81782.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-23T05:00+00:00, close=81561.7, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-10-23T04:00+00:00, close=81863.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.004305|-6.57|116.87|-6.75|8949926|4.63|
|LIT_USDT|3.448100|-4.59|11.53|-4.77|10536302|0.29|
|STRK_USDT|0.053110|-2.29|-44.88|-2.47|11533494|1.88|
|TIA_USDT|0.559900|-1.49|-7.07|-1.67|23949596|1.79|
|SILVER_USDT|54.550000|-1.28|-4.53|-1.46|363734852|1.83|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|JCT_USDT|0.004305|0.004130|0.004305|3.17|N|Y/Y|N/N|Y|N|
|LIT_USDT|3.448100|3.428400|3.448100|0.85|N|Y/Y|N/N|Y|N|
|SILVER_USDT|54.550000|53.720000|54.530000|2.27|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.053110|0.052690|0.053080|1.11|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.559900|0.556900|0.559900|1.73|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- JCT_USDT: quote_utc=2026-10-23T05:45:01+00:00, last15m_closed_end=2026-10-23T05:45+00:00, prior8high=0.004312, depth_time=2026-10-23T05:45:08+00:00, book20_bid_proxy_usdt=25931, book20_ask_proxy_usdt=26875, funding_indicative=0.000050, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.57%, turnover=8949926. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T05:45:02+00:00, last15m_closed_end=2026-10-23T05:45+00:00, prior8high=3.509900, depth_time=2026-10-23T05:45:08+00:00, book20_bid_proxy_usdt=21628, book20_ask_proxy_usdt=21766, funding_indicative=0.000035, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.59%, turnover=10536302. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T05:45:01+00:00, last15m_closed_end=2026-10-23T05:45+00:00, prior8high=54.220000, depth_time=2026-10-23T05:45:17+00:00, book20_bid_proxy_usdt=28901146, book20_ask_proxy_usdt=30157188, funding_indicative=0.000138, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.28%, turnover=363734852. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T05:45:02+00:00, last15m_closed_end=2026-10-23T05:45+00:00, prior8high=0.053370, depth_time=2026-10-23T05:45:12+00:00, book20_bid_proxy_usdt=524730, book20_ask_proxy_usdt=546319, funding_indicative=0.000002, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.29%, turnover=11533494. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T05:45:02+00:00, last15m_closed_end=2026-10-23T05:45+00:00, prior8high=0.565900, depth_time=2026-10-23T05:45:15+00:00, book20_bid_proxy_usdt=391015, book20_ask_proxy_usdt=372840, funding_indicative=0.000002, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.49%, turnover=23949596. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
