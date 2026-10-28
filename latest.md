# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T19:15:17Z**
- feed_generated_utc: 2026-10-28T19:15:21+00:00
- source_sha256: `622688d685a95485ec14c4e9a275fc1b4adfae24ae307e68f1e886c1e6e8a983`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.08 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T19:15+00:00, close=81087.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-28T19:00+00:00, close=80980.6, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-28T16:00+00:00, close=80528, belowEMA20=True, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AIN_USDT|0.141690|-5.91|253.78|-6.60|7551795|2.83|
|BCH_USDT|286.410000|-2.22|-1.12|-2.91|5353747|4.54|
|HBAR_USDT|0.075440|-0.61|-12.21|-1.30|12244147|1.33|
|XMR_USDT|600.410000|-0.61|0.70|-1.30|5492420|0.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AIN_USDT|0.141690|0.141720|0.141690|0.65|N|Y/Y|N/N|N|N|
|BCH_USDT|286.410000|282.710000|286.520000|0.35|N|Y/Y|N/N|N|N|
|HBAR_USDT|0.075440|0.074570|0.075460|0.71|N|Y/Y|Y/Y|N|N|
|XMR_USDT|600.410000|598.000000|600.410000|0.17|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AIN_USDT: quote_utc=2026-10-28T19:15:01+00:00, last15m_closed_end=2026-10-28T19:15+00:00, prior8high=0.148560, depth_time=2026-10-28T19:15:09+00:00, book20_bid_proxy_usdt=14139, book20_ask_proxy_usdt=18584, funding_indicative=0.000744, next_funding_utc=2026-10-28T20:00:00+00:00, funding_cycle_h=4, 24h_change=-5.91%, turnover=7551795. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BCH_USDT: quote_utc=2026-10-28T19:15:02+00:00, last15m_closed_end=2026-10-28T19:15+00:00, prior8high=288.630000, depth_time=2026-10-28T19:15:11+00:00, book20_bid_proxy_usdt=48311, book20_ask_proxy_usdt=71991, funding_indicative=0.000022, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.22%, turnover=5353747. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-28T19:15:01+00:00, last15m_closed_end=2026-10-28T19:15+00:00, prior8high=0.075900, depth_time=2026-10-28T19:15:12+00:00, book20_bid_proxy_usdt=1053874, book20_ask_proxy_usdt=503676, funding_indicative=0.000095, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.61%, turnover=12244147. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-28T19:15:02+00:00, last15m_closed_end=2026-10-28T19:15+00:00, prior8high=605.630000, depth_time=2026-10-28T19:15:16+00:00, book20_bid_proxy_usdt=19884, book20_ask_proxy_usdt=10927, funding_indicative=0.000100, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.61%, turnover=5492420. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
