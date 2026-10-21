# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T00:15:11Z**
- feed_generated_utc: 2026-10-21T00:15:13+00:00
- source_sha256: `4127bfed4378e6acbbf5c48e638d0a05532834664735a4c0fd0dc54424d1c4a2`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T00:15+00:00, close=83047, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T00:00+00:00, close=82984.8, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T00:00+00:00, close=82984.8, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.193640|-10.25|9.16|-10.81|10030388|0.52|
|XMR_USDT|588.630000|-5.09|11.50|-5.65|15882883|0.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BAT_USDT|0.193640|0.193360|0.193640|0.26|N|Y/Y|N/N|N|N|
|XMR_USDT|588.630000|588.100000|588.630000|15.81|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BAT_USDT: quote_utc=2026-10-21T00:15:00+00:00, last15m_closed_end=2026-10-21T00:15+00:00, prior8high=0.196740, depth_time=2026-10-21T00:15:07+00:00, book20_bid_proxy_usdt=22355, book20_ask_proxy_usdt=20605, funding_indicative=0.000066, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-10.25%, turnover=10030388. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-21T00:15:00+00:00, last15m_closed_end=2026-10-21T00:15+00:00, prior8high=624.900000, depth_time=2026-10-21T00:15:10+00:00, book20_bid_proxy_usdt=18120, book20_ask_proxy_usdt=306540, funding_indicative=0.000100, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.09%, turnover=15882883. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
