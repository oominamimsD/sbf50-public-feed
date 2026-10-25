# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T17:30:13Z**
- feed_generated_utc: 2026-10-25T17:30:16+00:00
- source_sha256: `be6afe3217384a1e7614749979b3c94d107905698ed2fb06de121ae28bbd2c25`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T17:30+00:00, close=80732.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-25T17:00+00:00, close=80777.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-25T16:00+00:00, close=80602.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.036420|-5.25|198.52|-5.41|22229433|2.75|
|BTW_USDT|1.626800|-1.93|-29.43|-2.09|13009172|0.61|
|XMR_USDT|601.700000|-0.91|3.29|-1.07|7195158|0.33|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.626800|1.557100|1.626700|0.56|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.036420|0.035490|0.036420|0.59|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|601.700000|601.330000|601.700000|0.97|N|Y/N|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-25T17:29:59+00:00, last15m_closed_end=2026-10-25T17:30+00:00, prior8high=1.687100, depth_time=2026-10-25T17:30:10+00:00, book20_bid_proxy_usdt=10090, book20_ask_proxy_usdt=15479, funding_indicative=-0.008054, next_funding_utc=2026-10-25T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.93%, turnover=13009172. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T17:29:59+00:00, last15m_closed_end=2026-10-25T17:30+00:00, prior8high=0.039980, depth_time=2026-10-25T17:30:07+00:00, book20_bid_proxy_usdt=52698, book20_ask_proxy_usdt=58377, funding_indicative=-0.000053, next_funding_utc=2026-10-25T18:00:00+00:00, funding_cycle_h=1, 24h_change=-5.25%, turnover=22229433. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-25T17:29:59+00:00, last15m_closed_end=2026-10-25T17:30+00:00, prior8high=608.570000, depth_time=2026-10-25T17:30:12+00:00, book20_bid_proxy_usdt=14626, book20_ask_proxy_usdt=16317, funding_indicative=0.000100, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.91%, turnover=7195158. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
