# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T16:00:15Z**
- feed_generated_utc: 2026-10-31T16:00:17+00:00
- source_sha256: `f7fa4feef9e367a51bc8a762db108f662d815336f88ff39eeb83a6e09963b77c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T16:00+00:00, close=77560.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T16:00+00:00, close=77560.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-31T16:00+00:00, close=77560.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IDOL_USDT|0.017521|-12.14|121.78|-12.14|15433416|1.14|
|Q_USDT|0.032080|-2.99|-59.35|-2.99|10780448|3.12|
|BTW_USDT|1.121900|-1.70|-35.57|-1.70|7663688|4.46|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.121900|1.097900|1.121900|1.03|N|Y/Y|Y/Y|Y|N|
|IDOL_USDT|0.017521|0.017035|0.017521|3.15|N|Y/Y|N/N|Y|N|
|Q_USDT|0.032080|0.031680|0.032080|0.46|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-31T16:00:01+00:00, last15m_closed_end=2026-10-31T16:00+00:00, prior8high=1.152900, depth_time=2026-10-31T16:00:14+00:00, book20_bid_proxy_usdt=36938, book20_ask_proxy_usdt=16265, funding_indicative=-0.000088, next_funding_utc=2026-10-31T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.70%, turnover=7663688. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-10-31T16:00:01+00:00, last15m_closed_end=2026-10-31T16:00+00:00, prior8high=0.020565, depth_time=2026-10-31T16:00:09+00:00, book20_bid_proxy_usdt=16760, book20_ask_proxy_usdt=6720, funding_indicative=0.000125, next_funding_utc=2026-10-31T20:00:00+00:00, funding_cycle_h=4, 24h_change=-12.14%, turnover=15433416. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T16:00:01+00:00, last15m_closed_end=2026-10-31T16:00+00:00, prior8high=0.033470, depth_time=2026-10-31T16:00:11+00:00, book20_bid_proxy_usdt=52631, book20_ask_proxy_usdt=74552, funding_indicative=-0.000626, next_funding_utc=2026-10-31T17:00:00+00:00, funding_cycle_h=1, 24h_change=-2.99%, turnover=10780448. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
