# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T05:15:38Z**
- feed_generated_utc: 2026-10-31T05:15:40+00:00
- source_sha256: `ce3f3267363f1fb0b7dc51d1c57d4c03bdb200c89d19d9ee792e3f4c8e6a044d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T05:15+00:00, close=77183.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-31T05:00+00:00, close=77154.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-31T04:00+00:00, close=77131.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.010921|-42.28|-68.79|-41.76|6624674|2.75|
|Q_USDT|0.027850|-41.34|-76.46|-40.82|21149253|7.15|
|EVAA_USDT|1.171200|-8.64|123.12|-8.12|6285529|5.12|
|BTW_USDT|1.116500|-6.91|-34.41|-6.39|9426674|2.68|
|BEAT_USDT|0.097990|-6.80|34.99|-6.28|8654597|2.04|
|PEPE_USDT|0.000005|-4.41|-0.49|-3.89|134666741|0.62|
|WLD_USDT|0.394700|-4.17|-25.86|-3.65|49828179|2.53|
|HYPE_USDT|88.653000|-3.99|13.07|-3.47|109752340|0.11|
|LIT_USDT|2.726300|-3.46|-17.98|-2.94|5082212|0.37|
|TRX_USDT|0.325240|-3.05|-1.24|-2.53|6793090|0.31|
|FET_USDT|0.162700|-2.34|-13.13|-1.82|6552850|6.15|
|DASH_USDT|48.020000|-2.07|-10.82|-1.55|15765979|2.08|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.010921|0.011037|0.010921|1.34|Y|Y/Y|Y/Y|Y|Y|
|BEAT_USDT|0.097990|0.097470|0.098000|1.31|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.116500|1.119500|1.116500|0.81|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|48.020000|47.930000|48.020000|2.62|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.171200|1.141300|1.171200|0.69|N|Y/N|N/N|Y|N|
|FET_USDT|0.162700|0.162600|0.162700|0.56|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|88.653000|88.396000|88.682000|1.06|N|Y/Y|N/N|Y|N|
|LIT_USDT|2.726300|2.717700|2.726300|0.29|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|1.09|N|Y/Y|N/N|Y|N|
|Q_USDT|0.027850|0.026260|0.027850|0.57|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.325240|0.322650|0.325240|0.36|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.394700|0.392600|0.394700|1.09|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T05:15:01+00:00, last15m_closed_end=2026-10-31T05:15+00:00, prior8high=0.012057, depth_time=2026-10-31T05:15:08+00:00, book20_bid_proxy_usdt=8684, book20_ask_proxy_usdt=6653, funding_indicative=-0.000044, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-42.28%, turnover=6624674. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-31T05:15:02+00:00, last15m_closed_end=2026-10-31T05:15+00:00, prior8high=0.101470, depth_time=2026-10-31T05:15:17+00:00, book20_bid_proxy_usdt=17516, book20_ask_proxy_usdt=11288, funding_indicative=0.000135, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.80%, turnover=8654597. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T05:15:02+00:00, last15m_closed_end=2026-10-31T05:15+00:00, prior8high=1.224900, depth_time=2026-10-31T05:15:16+00:00, book20_bid_proxy_usdt=8537, book20_ask_proxy_usdt=10576, funding_indicative=-0.000422, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.91%, turnover=9426674. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-31T05:15:02+00:00, last15m_closed_end=2026-10-31T05:15+00:00, prior8high=48.640000, depth_time=2026-10-31T05:15:35+00:00, book20_bid_proxy_usdt=806929, book20_ask_proxy_usdt=627879, funding_indicative=0.000078, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.07%, turnover=15765979. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-31T05:15:01+00:00, last15m_closed_end=2026-10-31T05:15+00:00, prior8high=1.275000, depth_time=2026-10-31T05:15:12+00:00, book20_bid_proxy_usdt=5034, book20_ask_proxy_usdt=18932, funding_indicative=0.000184, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-8.64%, turnover=6285529. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T05:15:02+00:00, last15m_closed_end=2026-10-31T05:15+00:00, prior8high=0.165400, depth_time=2026-10-31T05:15:34+00:00, book20_bid_proxy_usdt=1138261, book20_ask_proxy_usdt=867854, funding_indicative=0.000100, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.34%, turnover=6552850. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T05:15:01+00:00, last15m_closed_end=2026-10-31T05:15+00:00, prior8high=89.960000, depth_time=2026-10-31T05:15:27+00:00, book20_bid_proxy_usdt=71425, book20_ask_proxy_usdt=134444, funding_indicative=0.000050, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.99%, turnover=109752340. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-31T05:15:02+00:00, last15m_closed_end=2026-10-31T05:15+00:00, prior8high=2.772000, depth_time=2026-10-31T05:15:29+00:00, book20_bid_proxy_usdt=18301, book20_ask_proxy_usdt=38475, funding_indicative=0.000050, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.46%, turnover=5082212. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-31T05:15:01+00:00, last15m_closed_end=2026-10-31T05:15+00:00, prior8high=0.000005, depth_time=2026-10-31T05:15:21+00:00, book20_bid_proxy_usdt=14148, book20_ask_proxy_usdt=21184, funding_indicative=-0.000166, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.41%, turnover=134666741. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T05:15:01+00:00, last15m_closed_end=2026-10-31T05:15+00:00, prior8high=0.034080, depth_time=2026-10-31T05:15:10+00:00, book20_bid_proxy_usdt=41778, book20_ask_proxy_usdt=38090, funding_indicative=-0.002657, next_funding_utc=2026-10-31T06:00:00+00:00, funding_cycle_h=1, 24h_change=-41.34%, turnover=21149253. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T05:15:02+00:00, last15m_closed_end=2026-10-31T05:15+00:00, prior8high=0.327950, depth_time=2026-10-31T05:15:27+00:00, book20_bid_proxy_usdt=35598, book20_ask_proxy_usdt=33516, funding_indicative=-0.001244, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.05%, turnover=6793090. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T05:15:01+00:00, last15m_closed_end=2026-10-31T05:15+00:00, prior8high=0.402700, depth_time=2026-10-31T05:15:21+00:00, book20_bid_proxy_usdt=3248402, book20_ask_proxy_usdt=2886175, funding_indicative=0.000100, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.17%, turnover=49828179. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
