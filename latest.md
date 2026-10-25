# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T20:15:13Z**
- feed_generated_utc: 2026-10-25T20:15:15+00:00
- source_sha256: `22c8a6200b33b3a4fd2a7ded84c103ee52b84fa00605ecaf29d0702e4d3af914`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T20:15+00:00, close=80570.8, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-25T20:00+00:00, close=80530.1, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-10-25T20:00+00:00, close=80530.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.035840|-6.76|193.77|-6.72|20537682|2.79|
|USELESS_USDT|0.170010|-1.48|20.19|-1.44|5214468|0.59|
|XMR_USDT|600.370000|-1.13|3.06|-1.09|7009210|0.67|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|IRYS_USDT|0.035840|0.035650|0.035840|0.98|N|Y/Y|Y/Y|Y|N|
|USELESS_USDT|0.170010|0.166550|0.170010|0.69|N|Y/Y|N/N|Y|N|
|XMR_USDT|600.370000|594.720000|600.410000|4.33|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- IRYS_USDT: quote_utc=2026-10-25T20:15:01+00:00, last15m_closed_end=2026-10-25T20:15+00:00, prior8high=0.037780, depth_time=2026-10-25T20:15:07+00:00, book20_bid_proxy_usdt=73454, book20_ask_proxy_usdt=74198, funding_indicative=-0.000029, next_funding_utc=2026-10-25T21:00:00+00:00, funding_cycle_h=1, 24h_change=-6.76%, turnover=20537682. target_RR/account_short_permission/settled_funding=UNKNOWN.
- USELESS_USDT: quote_utc=2026-10-25T20:15:01+00:00, last15m_closed_end=2026-10-25T20:15+00:00, prior8high=0.169980, depth_time=2026-10-25T20:15:06+00:00, book20_bid_proxy_usdt=22560, book20_ask_proxy_usdt=16040, funding_indicative=0.000131, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.48%, turnover=5214468. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-25T20:15:01+00:00, last15m_closed_end=2026-10-25T20:15+00:00, prior8high=604.170000, depth_time=2026-10-25T20:15:10+00:00, book20_bid_proxy_usdt=19308, book20_ask_proxy_usdt=43150, funding_indicative=0.000100, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.13%, turnover=7009210. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
