# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T08:00:28Z**
- feed_generated_utc: 2026-11-10T08:00:29+00:00
- source_sha256: `b3acc30486c1838bb595bd6ab46a395d54791d466b5fb9e2c6e5afcbcf85713e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T08:00+00:00, close=74805.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-10T08:00+00:00, close=74805.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T08:00+00:00, close=74805.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002492|-49.11|-54.70|-48.20|15219425|4.01|
|JCT_USDT|0.005835|-46.82|35.16|-45.91|24155884|3.43|
|ARB_USDT|0.167360|-7.17|5.03|-6.26|36093249|0.60|
|ZEC_USDT|1151.090000|-5.72|-8.21|-4.81|2301907310|0.43|
|QNT_USDT|191.420000|-4.25|-5.44|-3.34|32854051|0.52|
|DASH_USDT|45.620000|-4.19|-3.34|-3.28|10806600|2.19|
|AAVE_USDT|127.070000|-4.11|-2.67|-3.20|12403254|0.79|
|DOT_USDT|0.856700|-3.28|-8.28|-2.37|8373258|1.17|
|PUMPFUN_USDT|0.003576|-2.74|-12.86|-1.83|6873565|2.80|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|127.070000|125.050000|127.070000|0.76|N|Y/Y|Y/Y|Y|N|
|AKE_USDT|0.002492|0.002463|0.002493|0.21|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.167360|0.167760|0.167360|1.80|Y|Y/Y|Y/N|Y|N|
|DASH_USDT|45.620000|45.610000|45.610000|0.19|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.856700|0.853600|0.856700|0.78|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.005835|0.005726|0.005835|2.24|N|Y/Y|Y/N|Y|N|
|PUMPFUN_USDT|0.003576|0.003555|0.003576|0.60|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|191.420000|189.670000|191.420000|0.32|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1151.090000|1144.770000|1151.050000|0.87|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-10T08:00:02+00:00, last15m_closed_end=2026-11-10T08:00+00:00, prior8high=127.890000, depth_time=2026-11-10T08:00:20+00:00, book20_bid_proxy_usdt=382132, book20_ask_proxy_usdt=350376, funding_indicative=0.000064, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.11%, turnover=12403254. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-10T08:00:02+00:00, last15m_closed_end=2026-11-10T08:00+00:00, prior8high=0.002556, depth_time=2026-11-10T08:00:05+00:00, book20_bid_proxy_usdt=62110, book20_ask_proxy_usdt=36070, funding_indicative=0.000050, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-49.11%, turnover=15219425. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T08:00:02+00:00, last15m_closed_end=2026-11-10T08:00+00:00, prior8high=0.173110, depth_time=2026-11-10T08:00:11+00:00, book20_bid_proxy_usdt=83934, book20_ask_proxy_usdt=65097, funding_indicative=-0.000076, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-7.17%, turnover=36093249. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T08:00:02+00:00, last15m_closed_end=2026-11-10T08:00+00:00, prior8high=46.200000, depth_time=2026-11-10T08:00:15+00:00, book20_bid_proxy_usdt=671349, book20_ask_proxy_usdt=607341, funding_indicative=0.000043, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.19%, turnover=10806600. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T08:00:02+00:00, last15m_closed_end=2026-11-10T08:00+00:00, prior8high=0.862700, depth_time=2026-11-10T08:00:24+00:00, book20_bid_proxy_usdt=1055248, book20_ask_proxy_usdt=437069, funding_indicative=-0.000013, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.28%, turnover=8373258. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T08:00:02+00:00, last15m_closed_end=2026-11-10T08:00+00:00, prior8high=0.007220, depth_time=2026-11-10T08:00:10+00:00, book20_bid_proxy_usdt=22674, book20_ask_proxy_usdt=29797, funding_indicative=0.000050, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-46.82%, turnover=24155884. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-10T08:00:02+00:00, last15m_closed_end=2026-11-10T08:00+00:00, prior8high=0.003603, depth_time=2026-11-10T08:00:26+00:00, book20_bid_proxy_usdt=2502083, book20_ask_proxy_usdt=2317293, funding_indicative=0.000050, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.74%, turnover=6873565. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T08:00:02+00:00, last15m_closed_end=2026-11-10T08:00+00:00, prior8high=192.180000, depth_time=2026-11-10T08:00:17+00:00, book20_bid_proxy_usdt=86882, book20_ask_proxy_usdt=125545, funding_indicative=-0.000128, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.25%, turnover=32854051. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T08:00:02+00:00, last15m_closed_end=2026-11-10T08:00+00:00, prior8high=1165.460000, depth_time=2026-11-10T08:00:15+00:00, book20_bid_proxy_usdt=235238, book20_ask_proxy_usdt=143980, funding_indicative=0.000049, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.72%, turnover=2301907310. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
