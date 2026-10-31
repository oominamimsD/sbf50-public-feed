# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T05:45:34Z**
- feed_generated_utc: 2026-10-31T05:45:36+00:00
- source_sha256: `23e5b6cafe23e6640c1320f33e5674094c5dc068f387240619bf84ee34122803`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T05:45+00:00, close=77287, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T05:00+00:00, close=77154.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-31T04:00+00:00, close=77131.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.011294|-40.30|-67.72|-39.92|6749163|4.43|
|BEAT_USDT|0.097550|-7.22|34.38|-6.84|8754528|3.07|
|BTW_USDT|1.134900|-5.38|-33.33|-5.00|9579278|6.16|
|EVAA_USDT|1.219600|-4.87|132.34|-4.49|6334913|4.10|
|HYPE_USDT|88.766000|-3.87|13.21|-3.49|110648193|0.11|
|PEPE_USDT|0.000005|-3.84|0.10|-3.46|136036557|2.26|
|WLD_USDT|0.396400|-3.76|-25.54|-3.38|50303409|2.52|
|LIT_USDT|2.732000|-3.26|-17.80|-2.88|5116481|0.37|
|TRX_USDT|0.325230|-3.06|-1.24|-2.68|6866291|0.31|
|FET_USDT|0.162800|-2.28|-13.08|-1.90|6644097|6.14|
|DASH_USDT|48.140000|-1.83|-10.60|-1.45|15776829|2.08|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.011294|0.010838|0.011294|0.75|N|Y/Y|Y/Y|Y|N|
|BEAT_USDT|0.097550|0.096950|0.097550|0.94|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.134900|1.108600|1.134300|1.01|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|48.140000|47.930000|48.140000|0.27|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.219600|1.141300|1.219800|1.43|N|Y/N|N/N|Y|N|
|FET_USDT|0.162800|0.162500|0.162800|2.40|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|88.766000|88.396000|88.773000|2.28|N|Y/Y|N/N|Y|N|
|LIT_USDT|2.732000|2.717700|2.731800|0.99|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|1.44|N|Y/Y|N/N|Y|N|
|TRX_USDT|0.325230|0.322650|0.325230|0.76|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.396400|0.392600|0.396400|1.52|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T05:45:02+00:00, last15m_closed_end=2026-10-31T05:45+00:00, prior8high=0.012057, depth_time=2026-10-31T05:45:06+00:00, book20_bid_proxy_usdt=4735, book20_ask_proxy_usdt=9071, funding_indicative=-0.000035, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-40.30%, turnover=6749163. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-31T05:45:02+00:00, last15m_closed_end=2026-10-31T05:45+00:00, prior8high=0.100590, depth_time=2026-10-31T05:45:11+00:00, book20_bid_proxy_usdt=9256, book20_ask_proxy_usdt=8503, funding_indicative=0.000135, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-7.22%, turnover=8754528. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T05:45:02+00:00, last15m_closed_end=2026-10-31T05:45+00:00, prior8high=1.210000, depth_time=2026-10-31T05:45:12+00:00, book20_bid_proxy_usdt=12968, book20_ask_proxy_usdt=12195, funding_indicative=-0.000452, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.38%, turnover=9579278. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-31T05:45:02+00:00, last15m_closed_end=2026-10-31T05:45+00:00, prior8high=48.580000, depth_time=2026-10-31T05:45:33+00:00, book20_bid_proxy_usdt=625339, book20_ask_proxy_usdt=748799, funding_indicative=0.000048, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.83%, turnover=15776829. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-31T05:45:02+00:00, last15m_closed_end=2026-10-31T05:45+00:00, prior8high=1.253100, depth_time=2026-10-31T05:45:14+00:00, book20_bid_proxy_usdt=8339, book20_ask_proxy_usdt=5470, funding_indicative=0.000246, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.87%, turnover=6334913. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T05:45:02+00:00, last15m_closed_end=2026-10-31T05:45+00:00, prior8high=0.165000, depth_time=2026-10-31T05:45:28+00:00, book20_bid_proxy_usdt=1159885, book20_ask_proxy_usdt=732463, funding_indicative=0.000100, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.28%, turnover=6644097. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T05:45:02+00:00, last15m_closed_end=2026-10-31T05:45+00:00, prior8high=89.857000, depth_time=2026-10-31T05:45:18+00:00, book20_bid_proxy_usdt=291554, book20_ask_proxy_usdt=97367, funding_indicative=0.000050, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.87%, turnover=110648193. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-31T05:45:02+00:00, last15m_closed_end=2026-10-31T05:45+00:00, prior8high=2.763800, depth_time=2026-10-31T05:45:24+00:00, book20_bid_proxy_usdt=33810, book20_ask_proxy_usdt=20523, funding_indicative=0.000050, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.26%, turnover=5116481. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-31T05:45:02+00:00, last15m_closed_end=2026-10-31T05:45+00:00, prior8high=0.000005, depth_time=2026-10-31T05:45:21+00:00, book20_bid_proxy_usdt=32502, book20_ask_proxy_usdt=22815, funding_indicative=-0.000093, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.84%, turnover=136036557. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T05:45:02+00:00, last15m_closed_end=2026-10-31T05:45+00:00, prior8high=0.327950, depth_time=2026-10-31T05:45:28+00:00, book20_bid_proxy_usdt=31798, book20_ask_proxy_usdt=48556, funding_indicative=-0.001096, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.06%, turnover=6866291. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T05:45:02+00:00, last15m_closed_end=2026-10-31T05:45+00:00, prior8high=0.401700, depth_time=2026-10-31T05:45:22+00:00, book20_bid_proxy_usdt=3339571, book20_ask_proxy_usdt=3558789, funding_indicative=0.000100, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.76%, turnover=50303409. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
