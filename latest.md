# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T13:00:22Z**
- feed_generated_utc: 2026-10-26T13:00:25+00:00
- source_sha256: `b87e7ef1a75adf302f518a1c06cd915ac734034a52d96a17202309482deceef4`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1182; contracts: 1174; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T13:00+00:00, close=80301.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-26T13:00+00:00, close=80301.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-26T12:00+00:00, close=80382.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|CAP_USDT|0.084760|-19.70|27.45|-19.33|6994671|2.35|
|IRYS_USDT|0.029140|-17.26|138.85|-16.89|11867161|3.45|
|BTW_USDT|1.453800|-12.36|-36.93|-11.99|10782291|4.82|
|APR_USDT|0.036250|-12.24|33.07|-11.87|6226100|8.28|
|WLD_USDT|0.439200|-2.87|-7.78|-2.50|58776293|2.28|
|XMR_USDT|593.000000|-2.34|1.80|-1.97|5502468|0.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APR_USDT|0.036250|0.033120|0.036280|0.88|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.453800|1.395000|1.454700|1.57|N|Y/Y|Y/Y|Y|N|
|CAP_USDT|0.084760|0.070960|0.084750|1.21|N|Y/Y|Y/N|Y|N|
|IRYS_USDT|0.029140|0.027970|0.029130|1.47|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.439200|0.435800|0.439200|1.35|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|593.000000|588.790000|593.020000|1.39|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APR_USDT: quote_utc=2026-10-26T13:00:01+00:00, last15m_closed_end=2026-10-26T13:00+00:00, prior8high=0.035300, depth_time=2026-10-26T13:00:16+00:00, book20_bid_proxy_usdt=54303, book20_ask_proxy_usdt=46074, funding_indicative=0.000050, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-12.24%, turnover=6226100. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-26T13:00:02+00:00, last15m_closed_end=2026-10-26T13:00+00:00, prior8high=1.516100, depth_time=2026-10-26T13:00:13+00:00, book20_bid_proxy_usdt=12217, book20_ask_proxy_usdt=13398, funding_indicative=-0.014819, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-12.36%, turnover=10782291. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CAP_USDT: quote_utc=2026-10-26T13:00:01+00:00, last15m_closed_end=2026-10-26T13:00+00:00, prior8high=0.080320, depth_time=2026-10-26T13:00:09+00:00, book20_bid_proxy_usdt=55838, book20_ask_proxy_usdt=53332, funding_indicative=0.000050, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-19.70%, turnover=6994671. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T13:00:01+00:00, last15m_closed_end=2026-10-26T13:00+00:00, prior8high=0.028980, depth_time=2026-10-26T13:00:11+00:00, book20_bid_proxy_usdt=72878, book20_ask_proxy_usdt=46082, funding_indicative=-0.000667, next_funding_utc=2026-10-26T14:00:00+00:00, funding_cycle_h=1, 24h_change=-17.26%, turnover=11867161. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T13:00:02+00:00, last15m_closed_end=2026-10-26T13:00+00:00, prior8high=0.444700, depth_time=2026-10-26T13:00:18+00:00, book20_bid_proxy_usdt=2318691, book20_ask_proxy_usdt=2979784, funding_indicative=-0.000164, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.87%, turnover=58776293. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T13:00:02+00:00, last15m_closed_end=2026-10-26T13:00+00:00, prior8high=593.790000, depth_time=2026-10-26T13:00:21+00:00, book20_bid_proxy_usdt=10428, book20_ask_proxy_usdt=7166, funding_indicative=0.000100, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.34%, turnover=5502468. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
