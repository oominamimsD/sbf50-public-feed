# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T15:15:20Z**
- feed_generated_utc: 2026-10-26T15:15:24+00:00
- source_sha256: `83f08b524f9c082541b3650385f3ca37a390e1d40ea9d84785bf7b87d3128f3d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1186; contracts: 1178; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T15:15+00:00, close=80472.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-26T15:00+00:00, close=80385.4, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T12:00+00:00, close=80382.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.143000|-31.09|-50.42|-30.92|12930709|0.88|
|IRYS_USDT|0.027660|-28.04|126.72|-27.87|10768936|3.62|
|APR_USDT|0.031890|-22.80|17.07|-22.63|5594529|3.14|
|BRL_USDT|0.184100|-8.04|-6.45|-7.87|5594280|5.43|
|XMR_USDT|591.540000|-2.58|1.55|-2.41|5182901|0.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APR_USDT|0.031890|0.031070|0.031890|1.26|N|Y/Y|N/N|Y|N|
|BRL_USDT|0.184100|0.179700|0.183900|1.08|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.143000|1.065200|1.144800|2.80|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.027660|0.027330|0.027620|1.17|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|591.540000|590.710000|591.490000|0.95|N|N/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APR_USDT: quote_utc=2026-10-26T15:15:03+00:00, last15m_closed_end=2026-10-26T15:15+00:00, prior8high=0.037130, depth_time=2026-10-26T15:15:14+00:00, book20_bid_proxy_usdt=46226, book20_ask_proxy_usdt=63879, funding_indicative=0.000050, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-22.80%, turnover=5594529. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BRL_USDT: quote_utc=2026-10-26T15:15:03+00:00, last15m_closed_end=2026-10-26T15:15+00:00, prior8high=0.183800, depth_time=2026-10-26T15:15:17+00:00, book20_bid_proxy_usdt=380838, book20_ask_proxy_usdt=386760, funding_indicative=-0.000116, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.04%, turnover=5594280. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-26T15:15:03+00:00, last15m_closed_end=2026-10-26T15:15+00:00, prior8high=1.456300, depth_time=2026-10-26T15:15:10+00:00, book20_bid_proxy_usdt=15010, book20_ask_proxy_usdt=11644, funding_indicative=-0.020000, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-31.09%, turnover=12930709. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T15:15:03+00:00, last15m_closed_end=2026-10-26T15:15+00:00, prior8high=0.029270, depth_time=2026-10-26T15:15:12+00:00, book20_bid_proxy_usdt=63670, book20_ask_proxy_usdt=153741, funding_indicative=-0.000703, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=1, 24h_change=-28.04%, turnover=10768936. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T15:15:03+00:00, last15m_closed_end=2026-10-26T15:15+00:00, prior8high=594.690000, depth_time=2026-10-26T15:15:18+00:00, book20_bid_proxy_usdt=10147, book20_ask_proxy_usdt=17394, funding_indicative=0.000100, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.58%, turnover=5182901. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
