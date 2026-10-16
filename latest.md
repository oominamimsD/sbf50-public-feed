# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T14:30:13Z**
- feed_generated_utc: 2026-10-16T14:30:15+00:00
- source_sha256: `dc59cdbdefe6dfacfb755e13f2c4fb120e61f9e03b0908b05a090eecdcc152e4`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T14:30+00:00, close=82315.3, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-16T14:00+00:00, close=81992.1, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-10-16T12:00+00:00, close=82599.5, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.076700|-20.40|27.49|-20.33|39256994|1.30|
|AKE_USDT|0.028852|-8.71|-0.58|-8.64|15934805|0.69|
|PYTH_USDT|0.089190|-8.37|21.18|-8.30|9218500|3.36|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.028852|0.028750|0.028852|1.98|N|Y/Y|N/N|N|N|
|PYTH_USDT|0.089190|0.086360|0.089190|0.39|N|Y/Y|N/N|N|N|
|STRK_USDT|0.076700|0.075410|0.076700|0.79|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-16T14:30:01+00:00, last15m_closed_end=2026-10-16T14:30+00:00, prior8high=0.030019, depth_time=2026-10-16T14:30:09+00:00, book20_bid_proxy_usdt=12958, book20_ask_proxy_usdt=10806, funding_indicative=0.000050, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.71%, turnover=15934805. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PYTH_USDT: quote_utc=2026-10-16T14:30:01+00:00, last15m_closed_end=2026-10-16T14:30+00:00, prior8high=0.091480, depth_time=2026-10-16T14:30:10+00:00, book20_bid_proxy_usdt=58919, book20_ask_proxy_usdt=113373, funding_indicative=0.000013, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.37%, turnover=9218500. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-16T14:30:01+00:00, last15m_closed_end=2026-10-16T14:30+00:00, prior8high=0.077670, depth_time=2026-10-16T14:30:07+00:00, book20_bid_proxy_usdt=493783, book20_ask_proxy_usdt=356971, funding_indicative=-0.000010, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-20.40%, turnover=39256994. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
