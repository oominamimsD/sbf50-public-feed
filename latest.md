# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T08:00:38Z**
- feed_generated_utc: 2026-10-31T08:00:40+00:00
- source_sha256: `b66f62e1a998f66dd176a8c9610a33635d7d57e00c3b4e8ee37b9296efa62e7e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T08:00+00:00, close=77316.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T08:00+00:00, close=77316.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-31T08:00+00:00, close=77316.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.010385|-45.11|-70.32|-44.78|8562758|9.63|
|Q_USDT|0.032880|-30.42|-72.21|-30.09|17939134|6.08|
|BEAT_USDT|0.097200|-8.06|33.90|-7.73|8099500|2.06|
|EVAA_USDT|1.205600|-6.53|129.68|-6.20|5600495|3.32|
|HYPE_USDT|88.263000|-4.83|12.57|-4.50|101072353|0.11|
|TRX_USDT|0.321770|-4.35|-2.29|-4.02|5688975|0.31|
|WLD_USDT|0.398000|-3.37|-25.24|-3.04|47481883|2.51|
|ZRO_USDT|1.690900|-3.36|-6.54|-3.03|5507226|0.59|
|DASH_USDT|47.870000|-2.64|-11.10|-2.31|13378101|2.09|
|BTW_USDT|1.174600|-2.07|-31.00|-1.74|9417214|0.85|
|FET_USDT|0.162300|-1.69|-13.34|-1.36|6022932|6.16|
|ARB_USDT|0.160990|-1.57|-10.52|-1.24|20132159|0.62|
|LTC_USDT|54.820000|-1.43|-6.21|-1.10|6352056|1.82|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.010385|0.010034|0.010403|14.74|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.160990|0.161010|0.160990|1.60|Y|Y/Y|Y/Y|Y|Y|
|BEAT_USDT|0.097200|0.096280|0.097200|0.67|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.174600|1.124600|1.175500|0.88|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|47.870000|47.750000|47.870000|1.80|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.205600|1.168700|1.205600|1.21|N|N/N|N/N|Y|N|
|FET_USDT|0.162300|0.161900|0.162300|0.08|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|88.263000|88.038000|88.263000|2.23|N|Y/Y|N/N|Y|N|
|LTC_USDT|54.820000|54.800000|54.820000|2.78|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.032880|0.029070|0.032880|0.38|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.321770|0.321300|0.321770|0.96|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.398000|0.395400|0.398100|2.64|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.690900|1.676300|1.690800|0.89|N|Y/N|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T08:00:03+00:00, last15m_closed_end=2026-10-31T08:00+00:00, prior8high=0.013245, depth_time=2026-10-31T08:00:08+00:00, book20_bid_proxy_usdt=52906, book20_ask_proxy_usdt=5132, funding_indicative=-0.001235, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-45.11%, turnover=8562758. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-31T08:00:03+00:00, last15m_closed_end=2026-10-31T08:00+00:00, prior8high=0.163850, depth_time=2026-10-31T08:00:35+00:00, book20_bid_proxy_usdt=63550, book20_ask_proxy_usdt=58448, funding_indicative=0.000069, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.57%, turnover=20132159. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-31T08:00:03+00:00, last15m_closed_end=2026-10-31T08:00+00:00, prior8high=0.098520, depth_time=2026-10-31T08:00:13+00:00, book20_bid_proxy_usdt=30187, book20_ask_proxy_usdt=9433, funding_indicative=0.000160, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-8.06%, turnover=8099500. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T08:00:03+00:00, last15m_closed_end=2026-10-31T08:00+00:00, prior8high=1.176000, depth_time=2026-10-31T08:00:30+00:00, book20_bid_proxy_usdt=12900, book20_ask_proxy_usdt=13510, funding_indicative=-0.000437, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.07%, turnover=9417214. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-31T08:00:03+00:00, last15m_closed_end=2026-10-31T08:00+00:00, prior8high=48.190000, depth_time=2026-10-31T08:00:27+00:00, book20_bid_proxy_usdt=647791, book20_ask_proxy_usdt=633987, funding_indicative=0.000081, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.64%, turnover=13378101. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-31T08:00:03+00:00, last15m_closed_end=2026-10-31T08:00+00:00, prior8high=1.223500, depth_time=2026-10-31T08:00:15+00:00, book20_bid_proxy_usdt=3554, book20_ask_proxy_usdt=6074, funding_indicative=0.000239, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.53%, turnover=5600495. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T08:00:03+00:00, last15m_closed_end=2026-10-31T08:00+00:00, prior8high=0.164200, depth_time=2026-10-31T08:00:31+00:00, book20_bid_proxy_usdt=1315437, book20_ask_proxy_usdt=863103, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.69%, turnover=6022932. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T08:00:03+00:00, last15m_closed_end=2026-10-31T08:00+00:00, prior8high=89.040000, depth_time=2026-10-31T08:00:16+00:00, book20_bid_proxy_usdt=81284, book20_ask_proxy_usdt=98988, funding_indicative=0.000050, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.83%, turnover=101072353. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LTC_USDT: quote_utc=2026-10-31T08:00:03+00:00, last15m_closed_end=2026-10-31T08:00+00:00, prior8high=55.350000, depth_time=2026-10-31T08:00:36+00:00, book20_bid_proxy_usdt=1226440, book20_ask_proxy_usdt=1202028, funding_indicative=0.000023, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.43%, turnover=6352056. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T08:00:03+00:00, last15m_closed_end=2026-10-31T08:00+00:00, prior8high=0.033340, depth_time=2026-10-31T08:00:10+00:00, book20_bid_proxy_usdt=30570, book20_ask_proxy_usdt=84300, funding_indicative=-0.000770, next_funding_utc=2026-10-31T09:00:00+00:00, funding_cycle_h=1, 24h_change=-30.42%, turnover=17939134. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T08:00:03+00:00, last15m_closed_end=2026-10-31T08:00+00:00, prior8high=0.326220, depth_time=2026-10-31T08:00:20+00:00, book20_bid_proxy_usdt=164347, book20_ask_proxy_usdt=131152, funding_indicative=-0.000411, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.35%, turnover=5688975. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T08:00:03+00:00, last15m_closed_end=2026-10-31T08:00+00:00, prior8high=0.401700, depth_time=2026-10-31T08:00:23+00:00, book20_bid_proxy_usdt=3390862, book20_ask_proxy_usdt=2664193, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.37%, turnover=47481883. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-31T08:00:03+00:00, last15m_closed_end=2026-10-31T08:00+00:00, prior8high=1.728600, depth_time=2026-10-31T08:00:25+00:00, book20_bid_proxy_usdt=18404, book20_ask_proxy_usdt=67483, funding_indicative=0.000050, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.36%, turnover=5507226. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
