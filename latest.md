# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T18:45:16Z**
- feed_generated_utc: 2026-10-28T18:45:20+00:00
- source_sha256: `5cd62409d44606a3b253aab29a0a93885650e08c28fac6f76cebfdbe91792303`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T18:45+00:00, close=81143.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-28T18:00+00:00, close=80827.7, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-28T16:00+00:00, close=80528, belowEMA20=True, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AIN_USDT|0.142460|-5.40|255.70|-6.16|7905895|6.32|
|APR_USDT|0.047460|-2.98|73.08|-3.74|5119686|2.11|
|BCH_USDT|286.100000|-2.33|-1.23|-3.09|5389143|0.35|
|XMR_USDT|599.550000|-0.75|0.55|-1.51|5636100|2.83|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AIN_USDT|0.142460|0.142430|0.142460|0.63|N|Y/N|N/N|N|N|
|APR_USDT|0.047460|0.047550|0.047460|0.57|N|N/N|N/N|N|N|
|BCH_USDT|286.100000|282.710000|286.100000|4.85|N|Y/Y|N/N|N|N|
|XMR_USDT|599.550000|598.000000|599.550000|1.24|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AIN_USDT: quote_utc=2026-10-28T18:45:00+00:00, last15m_closed_end=2026-10-28T18:45+00:00, prior8high=0.148560, depth_time=2026-10-28T18:45:08+00:00, book20_bid_proxy_usdt=5740, book20_ask_proxy_usdt=14163, funding_indicative=0.000688, next_funding_utc=2026-10-28T20:00:00+00:00, funding_cycle_h=4, 24h_change=-5.40%, turnover=7905895. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APR_USDT: quote_utc=2026-10-28T18:45:00+00:00, last15m_closed_end=2026-10-28T18:45+00:00, prior8high=0.051020, depth_time=2026-10-28T18:45:11+00:00, book20_bid_proxy_usdt=44044, book20_ask_proxy_usdt=43110, funding_indicative=0.000142, next_funding_utc=2026-10-28T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.98%, turnover=5119686. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BCH_USDT: quote_utc=2026-10-28T18:45:01+00:00, last15m_closed_end=2026-10-28T18:45+00:00, prior8high=290.820000, depth_time=2026-10-28T18:45:13+00:00, book20_bid_proxy_usdt=45925, book20_ask_proxy_usdt=48341, funding_indicative=0.000037, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.33%, turnover=5389143. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-28T18:45:01+00:00, last15m_closed_end=2026-10-28T18:45+00:00, prior8high=608.380000, depth_time=2026-10-28T18:45:15+00:00, book20_bid_proxy_usdt=6881, book20_ask_proxy_usdt=10550, funding_indicative=0.000100, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.75%, turnover=5636100. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
