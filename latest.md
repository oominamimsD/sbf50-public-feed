# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T13:45:11Z**
- feed_generated_utc: 2026-10-16T13:45:12+00:00
- source_sha256: `c24caa267035de8cb8eb9271db9b45d692c18cdf846f95bf17efb49d83994305`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T13:45+00:00, close=81953.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-16T13:00+00:00, close=82010.8, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-10-16T12:00+00:00, close=82599.5, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.075980|-21.14|26.29|-20.63|39995761|1.31|
|AKE_USDT|0.029462|-6.78|1.51|-6.27|17171261|1.70|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.029462|0.029184|0.029462|1.09|N|Y/Y|N/N|N|N|
|STRK_USDT|0.075980|0.075410|0.075980|0.44|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-16T13:44:59+00:00, last15m_closed_end=2026-10-16T13:45+00:00, prior8high=0.030019, depth_time=2026-10-16T13:45:10+00:00, book20_bid_proxy_usdt=22128, book20_ask_proxy_usdt=17818, funding_indicative=0.000050, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.78%, turnover=17171261. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-16T13:44:59+00:00, last15m_closed_end=2026-10-16T13:45+00:00, prior8high=0.080420, depth_time=2026-10-16T13:45:07+00:00, book20_bid_proxy_usdt=321149, book20_ask_proxy_usdt=525077, funding_indicative=-0.000001, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-21.14%, turnover=39995761. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
