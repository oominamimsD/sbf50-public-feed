# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T09:15:21Z**
- feed_generated_utc: 2026-10-28T09:15:24+00:00
- source_sha256: `5592dbcb140fe0b58c7fcc8cab2c48947c856743e20014460a1f619fa8e3f154`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T09:15+00:00, close=81499.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-28T09:00+00:00, close=81450, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T08:00+00:00, close=81049, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.058920|-7.33|-52.00|-8.53|26072400|1.70|
|AKE_USDT|0.020249|-4.14|-34.87|-5.34|5940613|2.96|
|DASH_USDT|54.150000|-0.03|8.43|-1.23|16180737|1.85|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.020249|0.020088|0.020249|1.91|N|Y/Y|Y/Y|N|N|
|DASH_USDT|54.150000|53.960000|54.130000|0.16|N|Y/Y|N/N|N|N|
|Q_USDT|0.058920|0.053780|0.058920|0.58|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-28T09:15:00+00:00, last15m_closed_end=2026-10-28T09:15+00:00, prior8high=0.021005, depth_time=2026-10-28T09:15:10+00:00, book20_bid_proxy_usdt=4262, book20_ask_proxy_usdt=4470, funding_indicative=0.000050, next_funding_utc=2026-10-28T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.14%, turnover=5940613. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-28T09:15:01+00:00, last15m_closed_end=2026-10-28T09:15+00:00, prior8high=54.730000, depth_time=2026-10-28T09:15:20+00:00, book20_bid_proxy_usdt=567250, book20_ask_proxy_usdt=504045, funding_indicative=0.000100, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.03%, turnover=16180737. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-28T09:15:00+00:00, last15m_closed_end=2026-10-28T09:15+00:00, prior8high=0.061020, depth_time=2026-10-28T09:15:08+00:00, book20_bid_proxy_usdt=13433, book20_ask_proxy_usdt=21834, funding_indicative=-0.000684, next_funding_utc=2026-10-28T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.33%, turnover=26072400. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
