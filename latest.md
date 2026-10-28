# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T13:45:38Z**
- feed_generated_utc: 2026-10-28T13:45:42+00:00
- source_sha256: `834bc795d7dbd4c12cf4e228924222efb4de54e0dd4f45fcd28031c47e6a671c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T13:45+00:00, close=80729.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-28T13:00+00:00, close=80708.1, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T12:00+00:00, close=81305.7, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.053710|-15.52|-56.24|-15.76|18669266|1.86|
|BEAT_USDT|0.079700|-12.50|6.67|-12.74|15047203|3.77|
|AKE_USDT|0.019622|-7.11|-36.88|-7.35|6690597|0.51|
|ENA_USDT|0.198700|-6.61|4.64|-6.85|79160424|0.50|
|INJ_USDT|7.868000|-3.95|-8.51|-4.19|24661560|1.27|
|DASH_USDT|53.090000|-1.99|6.30|-2.23|16065621|1.88|
|ARB_USDT|0.165660|-1.68|-12.32|-1.92|16666299|0.60|
|UNI_USDT|7.050000|-1.52|-3.03|-1.76|14443649|1.42|
|ADA_USDT|0.203000|-1.26|-8.31|-1.50|36228782|4.92|
|WLD_USDT|0.430900|-1.16|-23.43|-1.40|65486926|2.32|
|SILVER_USDT|54.020000|-1.13|-6.78|-1.37|263859311|1.85|
|PUMPFUN_USDT|0.004247|-0.88|-5.85|-1.12|16240015|2.35|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ADA_USDT|0.203000|0.202000|0.203000|3.21|N|Y/Y|N/N|N|N|
|AKE_USDT|0.019622|0.019399|0.019622|0.78|N|Y/Y|Y/Y|N|N|
|ARB_USDT|0.165660|0.164190|0.165660|2.42|N|Y/Y|Y/Y|N|N|
|BEAT_USDT|0.079700|0.078570|0.079700|0.25|N|Y/Y|Y/N|N|N|
|DASH_USDT|53.090000|52.980000|53.090000|0.10|N|Y/Y|N/N|N|N|
|ENA_USDT|0.198700|0.197780|0.198700|0.96|N|Y/Y|Y/N|N|N|
|INJ_USDT|7.868000|7.804000|7.868000|1.80|N|Y/Y|N/N|N|N|
|PUMPFUN_USDT|0.004247|0.004221|0.004247|0.51|N|Y/Y|N/N|N|N|
|Q_USDT|0.053710|0.052780|0.053710|0.68|N|Y/Y|Y/Y|N|N|
|SILVER_USDT|54.020000|53.860000|54.030000|3.24|N|N/Y|Y/Y|N|N|
|UNI_USDT|7.050000|7.004000|7.049000|3.07|N|Y/Y|N/N|N|N|
|WLD_USDT|0.430900|0.425300|0.430900|0.75|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- ADA_USDT: quote_utc=2026-10-28T13:45:00+00:00, last15m_closed_end=2026-10-28T13:45+00:00, prior8high=0.207200, depth_time=2026-10-28T13:45:29+00:00, book20_bid_proxy_usdt=8854809, book20_ask_proxy_usdt=7203649, funding_indicative=-0.000058, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.26%, turnover=36228782. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-10-28T13:45:00+00:00, last15m_closed_end=2026-10-28T13:45+00:00, prior8high=0.020235, depth_time=2026-10-28T13:45:13+00:00, book20_bid_proxy_usdt=3838, book20_ask_proxy_usdt=4789, funding_indicative=0.000050, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.11%, turnover=6690597. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-28T13:45:00+00:00, last15m_closed_end=2026-10-28T13:45+00:00, prior8high=0.168910, depth_time=2026-10-28T13:45:25+00:00, book20_bid_proxy_usdt=128697, book20_ask_proxy_usdt=83171, funding_indicative=-0.000074, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.68%, turnover=16666299. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-28T13:45:00+00:00, last15m_closed_end=2026-10-28T13:45+00:00, prior8high=0.081840, depth_time=2026-10-28T13:45:11+00:00, book20_bid_proxy_usdt=8774, book20_ask_proxy_usdt=9358, funding_indicative=0.000050, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-12.50%, turnover=15047203. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-28T13:45:00+00:00, last15m_closed_end=2026-10-28T13:45+00:00, prior8high=53.670000, depth_time=2026-10-28T13:45:20+00:00, book20_bid_proxy_usdt=789550, book20_ask_proxy_usdt=754593, funding_indicative=0.000100, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.99%, turnover=16065621. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-28T13:45:00+00:00, last15m_closed_end=2026-10-28T13:45+00:00, prior8high=0.205170, depth_time=2026-10-28T13:45:17+00:00, book20_bid_proxy_usdt=234470, book20_ask_proxy_usdt=460997, funding_indicative=-0.000029, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.61%, turnover=79160424. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-28T13:45:00+00:00, last15m_closed_end=2026-10-28T13:45+00:00, prior8high=7.964000, depth_time=2026-10-28T13:45:19+00:00, book20_bid_proxy_usdt=269634, book20_ask_proxy_usdt=293945, funding_indicative=0.000162, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.95%, turnover=24661560. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-28T13:45:00+00:00, last15m_closed_end=2026-10-28T13:45+00:00, prior8high=0.004344, depth_time=2026-10-28T13:45:37+00:00, book20_bid_proxy_usdt=2201624, book20_ask_proxy_usdt=2234110, funding_indicative=0.000003, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-0.88%, turnover=16240015. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-28T13:45:00+00:00, last15m_closed_end=2026-10-28T13:45+00:00, prior8high=0.055830, depth_time=2026-10-28T13:45:09+00:00, book20_bid_proxy_usdt=29752, book20_ask_proxy_usdt=26892, funding_indicative=-0.000767, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-15.52%, turnover=18669266. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-28T13:45:00+00:00, last15m_closed_end=2026-10-28T13:45+00:00, prior8high=54.480000, depth_time=2026-10-28T13:45:35+00:00, book20_bid_proxy_usdt=47750189, book20_ask_proxy_usdt=51162784, funding_indicative=0.000024, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.13%, turnover=263859311. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-28T13:45:00+00:00, last15m_closed_end=2026-10-28T13:45+00:00, prior8high=7.167000, depth_time=2026-10-28T13:45:26+00:00, book20_bid_proxy_usdt=2366938, book20_ask_proxy_usdt=2277001, funding_indicative=0.000100, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.52%, turnover=14443649. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-28T13:45:00+00:00, last15m_closed_end=2026-10-28T13:45+00:00, prior8high=0.438400, depth_time=2026-10-28T13:45:32+00:00, book20_bid_proxy_usdt=2835652, book20_ask_proxy_usdt=3155306, funding_indicative=-0.000092, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.16%, turnover=65486926. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
