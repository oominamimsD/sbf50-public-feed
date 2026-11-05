# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-05T03:30:18Z**
- feed_generated_utc: 2026-11-05T03:30:19+00:00
- source_sha256: `f26fca4e68e339c6c7b76fc4ab9a8c21252b940292c6049b542b1f1264f33929`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-05T03:30+00:00, close=80664.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-05T03:00+00:00, close=80544.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-05T00:00+00:00, close=80466.5, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|CLANKER_USDT|16.300000|-12.41|22.00|-12.88|20209149|6.12|
|TRUMPOFFICIAL_USDT|1.273000|-10.60|-25.51|-11.07|26905463|7.85|
|AKE_USDT|0.002530|-9.96|-87.41|-10.43|16914425|7.96|
|IDOL_USDT|0.021277|-9.33|145.77|-9.80|5775267|0.47|
|VVV_USDT|21.703000|-6.26|-8.87|-6.73|5047069|1.38|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002530|0.002197|0.002530|0.55|N|Y/Y|Y/Y|N|N|
|CLANKER_USDT|16.300000|15.780000|16.300000|0.34|N|Y/Y|N/N|N|N|
|IDOL_USDT|0.021277|0.020956|0.021266|1.17|N|Y/Y|N/N|N|N|
|TRUMPOFFICIAL_USDT|1.273000|1.228000|1.273000|1.44|N|Y/Y|Y/Y|N|N|
|VVV_USDT|21.703000|21.043000|21.696000|0.98|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-05T03:30:03+00:00, last15m_closed_end=2026-11-05T03:30+00:00, prior8high=0.002642, depth_time=2026-11-05T03:30:12+00:00, book20_bid_proxy_usdt=41939, book20_ask_proxy_usdt=55576, funding_indicative=-0.000501, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-9.96%, turnover=16914425. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CLANKER_USDT: quote_utc=2026-11-05T03:30:02+00:00, last15m_closed_end=2026-11-05T03:30+00:00, prior8high=17.830000, depth_time=2026-11-05T03:30:07+00:00, book20_bid_proxy_usdt=162610, book20_ask_proxy_usdt=115810, funding_indicative=0.000050, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-12.41%, turnover=20209149. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-05T03:30:03+00:00, last15m_closed_end=2026-11-05T03:30+00:00, prior8high=0.021639, depth_time=2026-11-05T03:30:14+00:00, book20_bid_proxy_usdt=5552, book20_ask_proxy_usdt=7468, funding_indicative=0.000094, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-9.33%, turnover=5775267. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-05T03:30:03+00:00, last15m_closed_end=2026-11-05T03:30+00:00, prior8high=1.276000, depth_time=2026-11-05T03:30:10+00:00, book20_bid_proxy_usdt=1037409, book20_ask_proxy_usdt=1129009, funding_indicative=-0.000289, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-10.60%, turnover=26905463. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-05T03:29:59+00:00, last15m_closed_end=2026-11-05T03:30+00:00, prior8high=21.641000, depth_time=2026-11-05T03:30:16+00:00, book20_bid_proxy_usdt=22153, book20_ask_proxy_usdt=16107, funding_indicative=-0.000231, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-6.26%, turnover=5047069. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
