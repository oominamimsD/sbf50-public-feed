# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T19:30:13Z**
- feed_generated_utc: 2026-10-25T19:30:15+00:00
- source_sha256: `ca26dfc0fde9a40d771dc93d3d37eef8ef33cb31077ffe2f57f0da831bcfcfd7`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T19:30+00:00, close=80508.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-25T19:00+00:00, close=80623.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-25T16:00+00:00, close=80602.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.035950|-6.47|194.67|-6.37|21183693|2.78|
|USELESS_USDT|0.167710|-2.81|18.57|-2.71|5252068|0.60|
|XMR_USDT|596.300000|-1.80|2.36|-1.70|6914354|1.84|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|IRYS_USDT|0.035950|0.035650|0.035950|0.55|N|Y/Y|Y/Y|Y|N|
|USELESS_USDT|0.167710|0.166550|0.167710|0.52|N|Y/Y|N/N|Y|N|
|XMR_USDT|596.300000|599.630000|596.300000|3.31|Y|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- IRYS_USDT: quote_utc=2026-10-25T19:30:01+00:00, last15m_closed_end=2026-10-25T19:30+00:00, prior8high=0.037780, depth_time=2026-10-25T19:30:06+00:00, book20_bid_proxy_usdt=90382, book20_ask_proxy_usdt=68513, funding_indicative=0.000008, next_funding_utc=2026-10-25T20:00:00+00:00, funding_cycle_h=1, 24h_change=-6.47%, turnover=21183693. target_RR/account_short_permission/settled_funding=UNKNOWN.
- USELESS_USDT: quote_utc=2026-10-25T19:30:02+00:00, last15m_closed_end=2026-10-25T19:30+00:00, prior8high=0.171370, depth_time=2026-10-25T19:30:10+00:00, book20_bid_proxy_usdt=33120, book20_ask_proxy_usdt=27060, funding_indicative=0.000136, next_funding_utc=2026-10-25T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.81%, turnover=5252068. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-25T19:30:01+00:00, last15m_closed_end=2026-10-25T19:30+00:00, prior8high=605.330000, depth_time=2026-10-25T19:30:12+00:00, book20_bid_proxy_usdt=14818, book20_ask_proxy_usdt=35068, funding_indicative=0.000100, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.80%, turnover=6914354. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
