# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T22:15:22Z**
- feed_generated_utc: 2026-11-04T22:15:25+00:00
- source_sha256: `0de6500bf5c16ab42ea3228987d26d7395eb63f14bdf68b1ca458eb3e3cac70d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T22:15+00:00, close=80423.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T22:00+00:00, close=80198.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T20:00+00:00, close=79956.9, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002494|-11.24|-87.58|-11.42|16543681|4.01|
|TRUMPOFFICIAL_USDT|1.283000|-9.90|-24.92|-10.08|26338453|7.82|
|IDOL_USDT|0.021231|-9.53|145.24|-9.71|6302670|3.30|
|BTW_USDT|1.032600|-6.04|-40.58|-6.22|6224078|1.94|
|PUMPFUN_USDT|0.004263|-4.20|1.33|-4.38|18490315|2.35|
|HYPE_USDT|83.694000|-2.57|4.80|-2.75|91310136|0.12|
|ZRO_USDT|1.822500|-2.26|6.45|-2.44|11040502|0.55|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002494|0.002493|0.002494|0.76|N|Y/Y|Y/Y|N|N|
|BTW_USDT|1.032600|1.026000|1.032600|1.21|N|Y/Y|Y/N|N|N|
|HYPE_USDT|83.694000|82.778000|83.686000|0.82|N|Y/Y|Y/Y|N|N|
|IDOL_USDT|0.021231|0.020994|0.021231|0.85|N|Y/Y|N/N|N|N|
|PUMPFUN_USDT|0.004263|0.004163|0.004263|1.23|N|Y/Y|Y/N|N|N|
|TRUMPOFFICIAL_USDT|1.283000|1.257000|1.283000|1.16|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.822500|1.757900|1.822500|0.17|N|Y/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-04T22:15:02+00:00, last15m_closed_end=2026-11-04T22:15+00:00, prior8high=0.002701, depth_time=2026-11-04T22:15:07+00:00, book20_bid_proxy_usdt=109246, book20_ask_proxy_usdt=89102, funding_indicative=-0.000803, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-11.24%, turnover=16543681. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-04T22:15:02+00:00, last15m_closed_end=2026-11-04T22:15+00:00, prior8high=1.057000, depth_time=2026-11-04T22:15:15+00:00, book20_bid_proxy_usdt=37876, book20_ask_proxy_usdt=28649, funding_indicative=0.000043, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-6.04%, turnover=6224078. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-04T22:15:02+00:00, last15m_closed_end=2026-11-04T22:15+00:00, prior8high=84.049000, depth_time=2026-11-04T22:15:19+00:00, book20_bid_proxy_usdt=209050, book20_ask_proxy_usdt=39206, funding_indicative=0.000050, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.57%, turnover=91310136. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-04T22:15:02+00:00, last15m_closed_end=2026-11-04T22:15+00:00, prior8high=0.022314, depth_time=2026-11-04T22:15:11+00:00, book20_bid_proxy_usdt=11290, book20_ask_proxy_usdt=4614, funding_indicative=0.000050, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-9.53%, turnover=6302670. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-04T22:15:02+00:00, last15m_closed_end=2026-11-04T22:15+00:00, prior8high=0.004245, depth_time=2026-11-04T22:15:17+00:00, book20_bid_proxy_usdt=2205252, book20_ask_proxy_usdt=1786155, funding_indicative=0.000040, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.20%, turnover=18490315. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T22:15:02+00:00, last15m_closed_end=2026-11-04T22:15+00:00, prior8high=1.301000, depth_time=2026-11-04T22:15:09+00:00, book20_bid_proxy_usdt=869934, book20_ask_proxy_usdt=1053757, funding_indicative=-0.000135, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-9.90%, turnover=26338453. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-04T22:15:02+00:00, last15m_closed_end=2026-11-04T22:15+00:00, prior8high=1.823700, depth_time=2026-11-04T22:15:21+00:00, book20_bid_proxy_usdt=48346, book20_ask_proxy_usdt=55589, funding_indicative=0.000050, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.26%, turnover=11040502. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
