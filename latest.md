# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T22:00:44Z**
- feed_generated_utc: 2026-10-23T22:00:48+00:00
- source_sha256: `e2cd9e0e6c4e1973deefedcf10ff120eb388f033f00f866618aac1623057a57d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1197; contracts: 1189; crypto_prefilter: 20; crypto_deep: 15
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T22:00+00:00, close=81348, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-23T22:00+00:00, close=81348, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T20:00+00:00, close=81252.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.002800|-38.65|32.26|-38.31|7827416|3.57|
|BR_USDT|0.495200|-8.14|5.43|-7.80|7502545|4.04|
|FARTCOIN_USDT|0.137600|-6.28|-11.06|-5.94|7000954|0.73|
|WLD_USDT|0.508700|-4.45|0.00|-4.11|99904094|1.97|
|STRK_USDT|0.049980|-4.36|-32.41|-4.02|11624816|2.00|
|PEPE_USDT|0.000005|-3.96|16.71|-3.62|141261544|0.21|
|ZRO_USDT|1.740000|-3.83|-17.19|-3.49|7314173|0.57|
|LIT_USDT|3.233200|-3.63|4.46|-3.29|7627464|0.31|
|XMR_USDT|589.790000|-3.02|7.48|-2.68|9141461|0.34|
|TRUMPOFFICIAL_USDT|1.736000|-3.01|-4.61|-2.67|5927522|5.76|
|ATOM_USDT|1.738000|-2.95|-0.11|-2.61|5401977|5.75|
|PENGU_USDT|0.007811|-2.70|3.23|-2.36|7065062|1.28|
|PUMPFUN_USDT|0.004469|-2.06|4.00|-1.72|31495942|2.23|
|SUI_USDT|0.974000|-1.86|-4.55|-1.52|60552263|1.03|
|DOT_USDT|1.106300|-1.81|-5.50|-1.47|20191319|1.81|
|ASTER_USDT|0.698300|-1.60|-0.82|-1.26|7021327|1.43|
|NEAR_USDT|4.785000|-1.52|-5.17|-1.18|112924101|2.09|
|APT_USDT|0.748500|-1.47|-12.56|-1.13|7697986|1.34|
|ONDO_USDT|0.425800|-1.38|-6.84|-1.04|12850508|2.35|
|LTC_USDT|57.790000|-1.36|-3.45|-1.02|6676109|3.46|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ATOM_USDT|1.738000|1.736000|1.738000|0.71|N|Y/Y|Y/N|Y|N|
|BR_USDT|0.495200|0.479700|0.495200|1.15|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.106300|1.106100|1.105500|0.79|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.137600|0.138070|0.137610|3.41|Y|Y/Y|Y/Y|Y|Y|
|JCT_USDT|0.002800|0.002567|0.002800|1.00|N|Y/Y|Y/N|Y|N|
|LIT_USDT|3.233200|3.229900|3.233200|0.45|N|Y/Y|Y/Y|Y|N|
|PENGU_USDT|0.007811|0.007786|0.007811|6.98|N|Y/Y|N/N|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|0.80|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004469|0.004419|0.004470|0.16|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.049980|0.049530|0.049970|0.30|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.974000|0.971400|0.973900|2.05|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.736000|1.733000|1.736000|0.15|N|Y/Y|Y/N|Y|N|
|WLD_USDT|0.508700|0.507500|0.508400|2.39|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|589.790000|588.540000|589.790000|2.54|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.740000|1.713200|1.738800|2.30|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ATOM_USDT: quote_utc=2026-10-23T22:00:03+00:00, last15m_closed_end=2026-10-23T22:00+00:00, prior8high=1.755000, depth_time=2026-10-23T22:00:33+00:00, book20_bid_proxy_usdt=2398792, book20_ask_proxy_usdt=2638379, funding_indicative=0.000000, next_funding_utc=2026-10-24T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.95%, turnover=5401977. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-23T22:00:02+00:00, last15m_closed_end=2026-10-23T22:00+00:00, prior8high=0.494000, depth_time=2026-10-23T22:00:11+00:00, book20_bid_proxy_usdt=20843, book20_ask_proxy_usdt=24321, funding_indicative=0.000050, next_funding_utc=2026-10-24T00:00:00+00:00, funding_cycle_h=4, 24h_change=-8.14%, turnover=7502545. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-23T22:00:02+00:00, last15m_closed_end=2026-10-23T22:00+00:00, prior8high=1.121400, depth_time=2026-10-23T22:00:43+00:00, book20_bid_proxy_usdt=156981, book20_ask_proxy_usdt=440088, funding_indicative=0.000039, next_funding_utc=2026-10-24T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.81%, turnover=20191319. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-23T22:00:03+00:00, last15m_closed_end=2026-10-23T22:00+00:00, prior8high=0.140320, depth_time=2026-10-23T22:00:13+00:00, book20_bid_proxy_usdt=72375, book20_ask_proxy_usdt=42114, funding_indicative=-0.000249, next_funding_utc=2026-10-24T00:00:00+00:00, funding_cycle_h=4, 24h_change=-6.28%, turnover=7000954. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-10-23T22:00:02+00:00, last15m_closed_end=2026-10-23T22:00+00:00, prior8high=0.002942, depth_time=2026-10-23T22:00:08+00:00, book20_bid_proxy_usdt=25346, book20_ask_proxy_usdt=15360, funding_indicative=0.000050, next_funding_utc=2026-10-24T00:00:00+00:00, funding_cycle_h=4, 24h_change=-38.65%, turnover=7827416. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T22:00:03+00:00, last15m_closed_end=2026-10-23T22:00+00:00, prior8high=3.284700, depth_time=2026-10-23T22:00:25+00:00, book20_bid_proxy_usdt=28650, book20_ask_proxy_usdt=25619, funding_indicative=-0.000032, next_funding_utc=2026-10-24T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.63%, turnover=7627464. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-23T22:00:03+00:00, last15m_closed_end=2026-10-23T22:00+00:00, prior8high=0.007971, depth_time=2026-10-23T22:00:34+00:00, book20_bid_proxy_usdt=123745, book20_ask_proxy_usdt=369491, funding_indicative=-0.000027, next_funding_utc=2026-10-24T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.70%, turnover=7065062. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-23T22:00:02+00:00, last15m_closed_end=2026-10-23T22:00+00:00, prior8high=0.000005, depth_time=2026-10-23T22:00:20+00:00, book20_bid_proxy_usdt=63398, book20_ask_proxy_usdt=39869, funding_indicative=0.000100, next_funding_utc=2026-10-24T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.96%, turnover=141261544. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-23T22:00:02+00:00, last15m_closed_end=2026-10-23T22:00+00:00, prior8high=0.004516, depth_time=2026-10-23T22:00:38+00:00, book20_bid_proxy_usdt=976236, book20_ask_proxy_usdt=1894165, funding_indicative=0.000008, next_funding_utc=2026-10-24T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.06%, turnover=31495942. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T22:00:02+00:00, last15m_closed_end=2026-10-23T22:00+00:00, prior8high=0.050700, depth_time=2026-10-23T22:00:19+00:00, book20_bid_proxy_usdt=485374, book20_ask_proxy_usdt=702927, funding_indicative=0.000049, next_funding_utc=2026-10-24T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.36%, turnover=11624816. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-23T22:00:02+00:00, last15m_closed_end=2026-10-23T22:00+00:00, prior8high=0.980700, depth_time=2026-10-23T22:00:41+00:00, book20_bid_proxy_usdt=382885, book20_ask_proxy_usdt=1337487, funding_indicative=0.000032, next_funding_utc=2026-10-24T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.86%, turnover=60552263. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-10-23T22:00:03+00:00, last15m_closed_end=2026-10-23T22:00+00:00, prior8high=1.758000, depth_time=2026-10-23T22:00:31+00:00, book20_bid_proxy_usdt=1108924, book20_ask_proxy_usdt=1187198, funding_indicative=0.000039, next_funding_utc=2026-10-24T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.01%, turnover=5927522. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-23T22:00:02+00:00, last15m_closed_end=2026-10-23T22:00+00:00, prior8high=0.520900, depth_time=2026-10-23T22:00:15+00:00, book20_bid_proxy_usdt=2161296, book20_ask_proxy_usdt=2306479, funding_indicative=-0.000083, next_funding_utc=2026-10-24T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.45%, turnover=99904094. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-23T22:00:02+00:00, last15m_closed_end=2026-10-23T22:00+00:00, prior8high=599.480000, depth_time=2026-10-23T22:00:27+00:00, book20_bid_proxy_usdt=8096, book20_ask_proxy_usdt=8406, funding_indicative=0.000100, next_funding_utc=2026-10-24T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.02%, turnover=9141461. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-23T22:00:03+00:00, last15m_closed_end=2026-10-23T22:00+00:00, prior8high=1.757700, depth_time=2026-10-23T22:00:23+00:00, book20_bid_proxy_usdt=52025, book20_ask_proxy_usdt=74975, funding_indicative=-0.000010, next_funding_utc=2026-10-24T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.83%, turnover=7314173. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
