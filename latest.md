# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T14:45:21Z**
- feed_generated_utc: 2026-11-09T14:45:22+00:00
- source_sha256: `0eaf97a472cb443b8a4c791a089351f0da9e48cc8dbac19e999c5696762980ed`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T14:45+00:00, close=74718.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-09T14:00+00:00, close=74694.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T12:00+00:00, close=74345.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001506|-23.07|29.34|-21.34|6182078|0.66|
|AKE_USDT|0.004739|-11.53|-48.26|-9.80|9085275|2.11|
|ASTER_USDT|0.640500|-5.78|-8.42|-4.05|5783507|1.56|
|ETH_USDT|2125.790000|-5.14|-6.17|-3.41|1653790695|0.05|
|XRP_USDT|1.099100|-4.90|-12.06|-3.17|290996811|0.91|
|TRUMPOFFICIAL_USDT|1.131000|-4.87|-34.09|-3.14|6480549|8.84|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004739|0.004671|0.004739|0.49|N|Y/Y|N/Y|Y|N|
|ASTER_USDT|0.640500|0.638300|0.640500|0.95|N|Y/Y|Y/Y|Y|N|
|ETH_USDT|2125.790000|2115.100000|2126.000000|4.13|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001506|0.001470|0.001506|1.31|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.131000|1.120000|1.131000|2.39|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.099100|1.090800|1.099100|1.07|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-09T14:44:59+00:00, last15m_closed_end=2026-11-09T14:45+00:00, prior8high=0.004952, depth_time=2026-11-09T14:45:09+00:00, book20_bid_proxy_usdt=39305, book20_ask_proxy_usdt=35789, funding_indicative=0.000050, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-11.53%, turnover=9085275. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ASTER_USDT: quote_utc=2026-11-09T14:44:59+00:00, last15m_closed_end=2026-11-09T14:45+00:00, prior8high=0.643800, depth_time=2026-11-09T14:45:12+00:00, book20_bid_proxy_usdt=623501, book20_ask_proxy_usdt=624087, funding_indicative=0.000050, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.78%, turnover=5783507. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETH_USDT: quote_utc=2026-11-09T14:44:59+00:00, last15m_closed_end=2026-11-09T14:45+00:00, prior8high=2131.940000, depth_time=2026-11-09T14:45:15+00:00, book20_bid_proxy_usdt=3463876, book20_ask_proxy_usdt=3168158, funding_indicative=0.000000, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.14%, turnover=1653790695. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T14:44:59+00:00, last15m_closed_end=2026-11-09T14:45+00:00, prior8high=0.001538, depth_time=2026-11-09T14:45:07+00:00, book20_bid_proxy_usdt=25307, book20_ask_proxy_usdt=18486, funding_indicative=-0.000085, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-23.07%, turnover=6182078. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-09T14:44:59+00:00, last15m_closed_end=2026-11-09T14:45+00:00, prior8high=1.148000, depth_time=2026-11-09T14:45:19+00:00, book20_bid_proxy_usdt=2499062, book20_ask_proxy_usdt=3110500, funding_indicative=0.000037, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.87%, turnover=6480549. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T14:44:59+00:00, last15m_closed_end=2026-11-09T14:45+00:00, prior8high=1.110100, depth_time=2026-11-09T14:45:17+00:00, book20_bid_proxy_usdt=2706970, book20_ask_proxy_usdt=3083310, funding_indicative=0.000081, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.90%, turnover=290996811. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
