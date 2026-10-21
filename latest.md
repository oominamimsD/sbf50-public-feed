# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T17:45:17Z**
- feed_generated_utc: 2026-10-21T17:45:19+00:00
- source_sha256: `44181a065ee708eab1ca7d8e30757bed876bd8a1e02b834752de4219a0a6046e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T17:45+00:00, close=84557.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T17:00+00:00, close=84506.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T16:00+00:00, close=84499, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DOOD_USDT|0.002234|-21.44|57.54|-21.52|9298318|4.47|
|BR_USDT|0.517380|-4.46|26.88|-4.54|16097940|1.16|
|AKE_USDT|0.026207|-1.80|1.25|-1.88|10041111|3.05|
|INJ_USDT|8.617000|-1.60|12.80|-1.68|56256600|1.16|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.026207|0.025666|0.026197|0.34|N|Y/Y|Y/Y|N|N|
|BR_USDT|0.517380|0.518820|0.517290|1.34|Y|Y/Y|Y/Y|N|Y|
|DOOD_USDT|0.002234|0.002080|0.002237|0.28|N|Y/Y|N/N|N|N|
|INJ_USDT|8.617000|8.565000|8.617000|0.96|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-21T17:45:01+00:00, last15m_closed_end=2026-10-21T17:45+00:00, prior8high=0.027270, depth_time=2026-10-21T17:45:12+00:00, book20_bid_proxy_usdt=11850, book20_ask_proxy_usdt=10053, funding_indicative=0.000050, next_funding_utc=2026-10-21T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.80%, turnover=10041111. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T17:45:01+00:00, last15m_closed_end=2026-10-21T17:45+00:00, prior8high=0.551330, depth_time=2026-10-21T17:45:11+00:00, book20_bid_proxy_usdt=3373, book20_ask_proxy_usdt=3616, funding_indicative=-0.000140, next_funding_utc=2026-10-21T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.46%, turnover=16097940. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOOD_USDT: quote_utc=2026-10-21T17:45:01+00:00, last15m_closed_end=2026-10-21T17:45+00:00, prior8high=0.003924, depth_time=2026-10-21T17:45:09+00:00, book20_bid_proxy_usdt=121924, book20_ask_proxy_usdt=164838, funding_indicative=-0.000920, next_funding_utc=2026-10-21T18:00:00+00:00, funding_cycle_h=1, 24h_change=-21.44%, turnover=9298318. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-21T17:45:01+00:00, last15m_closed_end=2026-10-21T17:45+00:00, prior8high=8.808000, depth_time=2026-10-21T17:45:16+00:00, book20_bid_proxy_usdt=190058, book20_ask_proxy_usdt=204485, funding_indicative=0.000034, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.60%, turnover=56256600. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
