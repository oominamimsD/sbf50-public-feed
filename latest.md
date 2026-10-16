# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T16:30:10Z**
- feed_generated_utc: 2026-10-16T16:30:12+00:00
- source_sha256: `48715c6674e7f6f007df3c327885278ecbb3cefbf0bd601a6ec59c5609ac393b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T16:30+00:00, close=81619, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-16T16:00+00:00, close=81322.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-16T16:00+00:00, close=81322.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZEC_USDT|1179.260000|-0.73|-3.21|-1.10|1517433036|0.09|
|AKE_USDT|0.028592|-0.67|1.85|-1.04|13005138|0.35|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.028592|0.028349|0.028595|0.66|N|Y/Y|N/N|Y|N|
|ZEC_USDT|1179.260000|1177.740000|1179.560000|1.10|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-16T16:29:59+00:00, last15m_closed_end=2026-10-16T16:30+00:00, prior8high=0.029553, depth_time=2026-10-16T16:30:08+00:00, book20_bid_proxy_usdt=14718, book20_ask_proxy_usdt=17275, funding_indicative=0.000066, next_funding_utc=2026-10-16T20:00:00+00:00, funding_cycle_h=4, 24h_change=-0.67%, turnover=13005138. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-16T16:30:02+00:00, last15m_closed_end=2026-10-16T16:30+00:00, prior8high=1227.350000, depth_time=2026-10-16T16:30:06+00:00, book20_bid_proxy_usdt=105197, book20_ask_proxy_usdt=873538, funding_indicative=0.000011, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.73%, turnover=1517433036. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
