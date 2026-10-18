# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T18:15:16Z**
- feed_generated_utc: 2026-10-18T18:15:18+00:00
- source_sha256: `b5ee8679b14156683dcccd926caf96b4e0f2091acb997455dacd1ea1d24354ec`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T18:15+00:00, close=81136.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-18T18:00+00:00, close=81150, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-18T16:00+00:00, close=81137.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.059050|-4.07|-50.49|-4.07|15702180|5.08|
|BAT_USDT|0.170800|-2.61|2.49|-2.61|8723189|0.58|
|PUMPFUN_USDT|0.004124|-1.69|-28.58|-1.69|29606623|2.43|
|HBAR_USDT|0.084440|-1.56|-9.95|-1.56|41855076|1.19|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BAT_USDT|0.170800|0.170390|0.170800|0.26|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.084440|0.084290|0.084440|0.43|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004124|0.004107|0.004123|0.69|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.059050|0.059590|0.059070|4.57|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- BAT_USDT: quote_utc=2026-10-18T18:14:59+00:00, last15m_closed_end=2026-10-18T18:15+00:00, prior8high=0.177360, depth_time=2026-10-18T18:15:09+00:00, book20_bid_proxy_usdt=29646, book20_ask_proxy_usdt=25732, funding_indicative=0.000009, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.61%, turnover=8723189. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-18T18:14:59+00:00, last15m_closed_end=2026-10-18T18:15+00:00, prior8high=0.086580, depth_time=2026-10-18T18:15:15+00:00, book20_bid_proxy_usdt=474230, book20_ask_proxy_usdt=945421, funding_indicative=0.000019, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.56%, turnover=41855076. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T18:14:59+00:00, last15m_closed_end=2026-10-18T18:15+00:00, prior8high=0.004195, depth_time=2026-10-18T18:15:13+00:00, book20_bid_proxy_usdt=2364281, book20_ask_proxy_usdt=2022701, funding_indicative=0.000050, next_funding_utc=2026-10-18T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.69%, turnover=29606623. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T18:14:59+00:00, last15m_closed_end=2026-10-18T18:15+00:00, prior8high=0.062250, depth_time=2026-10-18T18:15:07+00:00, book20_bid_proxy_usdt=562702, book20_ask_proxy_usdt=396883, funding_indicative=0.000050, next_funding_utc=2026-10-18T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.07%, turnover=15702180. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
