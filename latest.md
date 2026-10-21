# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T18:15:16Z**
- feed_generated_utc: 2026-10-21T18:15:18+00:00
- source_sha256: `88bf7366694ed60a3ce1a58c0606ef911a2fa5669a7984c257e541bfb715a6ab`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T18:15+00:00, close=84674.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T18:00+00:00, close=84635.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T16:00+00:00, close=84499, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DOOD_USDT|0.002282|-19.76|60.93|-19.96|9068593|4.39|
|BR_USDT|0.525690|-2.93|28.92|-3.13|15281861|1.71|
|AKE_USDT|0.025966|-2.71|0.32|-2.91|10011991|4.63|
|INJ_USDT|8.678000|-0.91|13.60|-1.11|55253901|1.15|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.025966|0.025666|0.025966|0.90|N|Y/Y|Y/Y|N|N|
|BR_USDT|0.525690|0.513880|0.525350|0.68|N|Y/Y|Y/Y|N|N|
|DOOD_USDT|0.002282|0.002080|0.002280|0.16|N|Y/Y|N/N|N|N|
|INJ_USDT|8.678000|8.565000|8.677000|0.35|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-21T18:15:00+00:00, last15m_closed_end=2026-10-21T18:15+00:00, prior8high=0.026895, depth_time=2026-10-21T18:15:12+00:00, book20_bid_proxy_usdt=9976, book20_ask_proxy_usdt=9729, funding_indicative=0.000050, next_funding_utc=2026-10-21T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.71%, turnover=10011991. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T18:15:00+00:00, last15m_closed_end=2026-10-21T18:15+00:00, prior8high=0.541560, depth_time=2026-10-21T18:15:10+00:00, book20_bid_proxy_usdt=3900, book20_ask_proxy_usdt=3028, funding_indicative=-0.000122, next_funding_utc=2026-10-21T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.93%, turnover=15281861. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOOD_USDT: quote_utc=2026-10-21T18:15:00+00:00, last15m_closed_end=2026-10-21T18:15+00:00, prior8high=0.002845, depth_time=2026-10-21T18:15:08+00:00, book20_bid_proxy_usdt=198906, book20_ask_proxy_usdt=110363, funding_indicative=-0.000031, next_funding_utc=2026-10-21T19:00:00+00:00, funding_cycle_h=1, 24h_change=-19.76%, turnover=9068593. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-21T18:15:00+00:00, last15m_closed_end=2026-10-21T18:15+00:00, prior8high=8.758000, depth_time=2026-10-21T18:15:15+00:00, book20_bid_proxy_usdt=204975, book20_ask_proxy_usdt=196042, funding_indicative=0.000052, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.91%, turnover=55253901. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
