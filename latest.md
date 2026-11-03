# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-03T21:00:25Z**
- feed_generated_utc: 2026-11-03T21:00:27+00:00
- source_sha256: `dc1fc94863d9cbfef86931e8725a4f78f2a3a5e49cd81ad4e75ef692c0e71b56`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-03T21:00+00:00, close=77833.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-03T21:00+00:00, close=77833.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-03T20:00+00:00, close=77586.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|EVAA_USDT|1.440200|-5.03|106.12|-5.26|5407266|1.39|
|AKE_USDT|0.003953|-4.88|-81.28|-5.11|13527397|2.53|
|TIA_USDT|0.430200|-2.20|-19.75|-2.43|11533542|2.32|
|OP_USDT|0.108860|-2.08|-2.20|-2.31|8536504|0.92|
|TRUMPOFFICIAL_USDT|1.575000|-1.93|-6.69|-2.16|5683561|6.35|
|QNT_USDT|192.300000|-1.24|-2.82|-1.47|56706791|0.52|
|XLM_USDT|0.162950|-1.11|-3.69|-1.34|32367073|1.23|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.003953|0.003851|0.003951|1.66|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.440200|1.427900|1.439500|1.67|N|Y/Y|N/N|Y|N|
|OP_USDT|0.108860|0.108610|0.108860|0.20|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|192.300000|190.330000|192.300000|0.67|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.430200|0.427600|0.430200|1.40|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.575000|1.571000|1.575000|0.37|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.162950|0.162240|0.162930|1.28|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-03T21:00:01+00:00, last15m_closed_end=2026-11-03T21:00+00:00, prior8high=0.004125, depth_time=2026-11-03T21:00:12+00:00, book20_bid_proxy_usdt=34621, book20_ask_proxy_usdt=35845, funding_indicative=-0.000495, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.88%, turnover=13527397. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-11-03T21:00:01+00:00, last15m_closed_end=2026-11-03T21:00+00:00, prior8high=1.498200, depth_time=2026-11-03T21:00:08+00:00, book20_bid_proxy_usdt=7887, book20_ask_proxy_usdt=12841, funding_indicative=0.000050, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=4, 24h_change=-5.03%, turnover=5407266. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-03T21:00:01+00:00, last15m_closed_end=2026-11-03T21:00+00:00, prior8high=0.110680, depth_time=2026-11-03T21:00:15+00:00, book20_bid_proxy_usdt=170167, book20_ask_proxy_usdt=154569, funding_indicative=0.000100, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.08%, turnover=8536504. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-03T21:00:01+00:00, last15m_closed_end=2026-11-03T21:00+00:00, prior8high=192.440000, depth_time=2026-11-03T21:00:21+00:00, book20_bid_proxy_usdt=84351, book20_ask_proxy_usdt=86420, funding_indicative=0.000100, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.24%, turnover=56706791. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-03T21:00:01+00:00, last15m_closed_end=2026-11-03T21:00+00:00, prior8high=0.432900, depth_time=2026-11-03T21:00:14+00:00, book20_bid_proxy_usdt=272844, book20_ask_proxy_usdt=260642, funding_indicative=-0.000015, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.20%, turnover=11533542. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-03T21:00:02+00:00, last15m_closed_end=2026-11-03T21:00+00:00, prior8high=1.587000, depth_time=2026-11-03T21:00:19+00:00, book20_bid_proxy_usdt=1139893, book20_ask_proxy_usdt=1010888, funding_indicative=0.000034, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.93%, turnover=5683561. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-03T21:00:01+00:00, last15m_closed_end=2026-11-03T21:00+00:00, prior8high=0.164380, depth_time=2026-11-03T21:00:23+00:00, book20_bid_proxy_usdt=191354, book20_ask_proxy_usdt=220916, funding_indicative=0.000100, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.11%, turnover=32367073. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
