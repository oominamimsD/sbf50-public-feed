# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T07:15:34Z**
- feed_generated_utc: 2026-10-31T07:15:36+00:00
- source_sha256: `67a6a50a44628e5d459e8b3ecfff3e157adc316181ee084ac1eea8e16c2372e5`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T07:15+00:00, close=77392.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T07:00+00:00, close=77350.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-31T04:00+00:00, close=77131.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.012634|-33.22|-63.89|-32.98|7041174|3.17|
|Q_USDT|0.032240|-32.09|-72.75|-31.85|18911214|6.22|
|BEAT_USDT|0.098150|-6.65|35.21|-6.41|8443072|1.02|
|EVAA_USDT|1.199300|-6.45|128.48|-6.21|5787124|5.00|
|HYPE_USDT|88.487000|-4.17|12.86|-3.93|106184801|0.11|
|BTW_USDT|1.155800|-3.64|-32.10|-3.40|9456218|0.86|
|TRX_USDT|0.323740|-3.50|-1.70|-3.26|5980184|0.62|
|ZRO_USDT|1.699700|-2.86|-6.05|-2.62|5350337|2.95|
|WLD_USDT|0.400300|-2.81|-24.81|-2.57|47959641|2.50|
|DASH_USDT|48.010000|-2.10|-10.84|-1.86|14165035|2.08|
|FET_USDT|0.163100|-2.10|-12.92|-1.86|6213779|6.13|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.012634|0.010838|0.012621|1.11|N|Y/Y|Y/Y|Y|N|
|BEAT_USDT|0.098150|0.096280|0.098150|1.33|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.155800|1.108600|1.155800|0.67|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|48.010000|47.870000|48.000000|7.26|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.199300|1.163200|1.199300|1.18|N|Y/Y|N/N|Y|N|
|FET_USDT|0.163100|0.162200|0.163200|0.82|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|88.487000|88.038000|88.487000|1.77|N|Y/Y|N/N|Y|N|
|Q_USDT|0.032240|0.027630|0.032480|0.61|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.323740|0.323840|0.323740|0.23|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.400300|0.394500|0.400300|0.99|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.699700|1.688700|1.698800|0.59|N|N/N|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T07:15:02+00:00, last15m_closed_end=2026-10-31T07:15+00:00, prior8high=0.012491, depth_time=2026-10-31T07:15:08+00:00, book20_bid_proxy_usdt=5762, book20_ask_proxy_usdt=6180, funding_indicative=-0.000123, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-33.22%, turnover=7041174. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-31T07:15:02+00:00, last15m_closed_end=2026-10-31T07:15+00:00, prior8high=0.098520, depth_time=2026-10-31T07:15:13+00:00, book20_bid_proxy_usdt=9102, book20_ask_proxy_usdt=14433, funding_indicative=0.000179, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.65%, turnover=8443072. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T07:15:02+00:00, last15m_closed_end=2026-10-31T07:15+00:00, prior8high=1.176000, depth_time=2026-10-31T07:15:21+00:00, book20_bid_proxy_usdt=12919, book20_ask_proxy_usdt=11425, funding_indicative=-0.000705, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.64%, turnover=9456218. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-31T07:15:03+00:00, last15m_closed_end=2026-10-31T07:15+00:00, prior8high=48.190000, depth_time=2026-10-31T07:15:28+00:00, book20_bid_proxy_usdt=776475, book20_ask_proxy_usdt=565942, funding_indicative=0.000084, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.10%, turnover=14165035. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-31T07:15:02+00:00, last15m_closed_end=2026-10-31T07:15+00:00, prior8high=1.242000, depth_time=2026-10-31T07:15:16+00:00, book20_bid_proxy_usdt=4998, book20_ask_proxy_usdt=7149, funding_indicative=0.000223, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.45%, turnover=5787124. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T07:15:02+00:00, last15m_closed_end=2026-10-31T07:15+00:00, prior8high=0.164200, depth_time=2026-10-31T07:15:33+00:00, book20_bid_proxy_usdt=1309715, book20_ask_proxy_usdt=897383, funding_indicative=0.000100, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.10%, turnover=6213779. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T07:15:02+00:00, last15m_closed_end=2026-10-31T07:15+00:00, prior8high=89.040000, depth_time=2026-10-31T07:15:18+00:00, book20_bid_proxy_usdt=124819, book20_ask_proxy_usdt=45570, funding_indicative=0.000050, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.17%, turnover=106184801. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T07:15:02+00:00, last15m_closed_end=2026-10-31T07:15+00:00, prior8high=0.032790, depth_time=2026-10-31T07:15:11+00:00, book20_bid_proxy_usdt=53861, book20_ask_proxy_usdt=81019, funding_indicative=-0.000773, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=1, 24h_change=-32.09%, turnover=18911214. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T07:15:02+00:00, last15m_closed_end=2026-10-31T07:15+00:00, prior8high=0.326220, depth_time=2026-10-31T07:15:22+00:00, book20_bid_proxy_usdt=1121192, book20_ask_proxy_usdt=103192, funding_indicative=-0.000606, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.50%, turnover=5980184. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T07:15:02+00:00, last15m_closed_end=2026-10-31T07:15+00:00, prior8high=0.401700, depth_time=2026-10-31T07:15:28+00:00, book20_bid_proxy_usdt=2673773, book20_ask_proxy_usdt=2559508, funding_indicative=0.000100, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.81%, turnover=47959641. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-31T07:15:02+00:00, last15m_closed_end=2026-10-31T07:15+00:00, prior8high=1.728600, depth_time=2026-10-31T07:15:26+00:00, book20_bid_proxy_usdt=21710, book20_ask_proxy_usdt=22608, funding_indicative=0.000050, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.86%, turnover=5350337. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
