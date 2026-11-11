# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T10:15:34Z**
- feed_generated_utc: 2026-11-11T10:15:36+00:00
- source_sha256: `2561011ffe2409f13973563e49d8dde2b517bc2880ccd75300a2a94b30f5e595`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T10:15+00:00, close=73700.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-11T10:00+00:00, close=73761.1, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-11-11T08:00+00:00, close=74064.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|INIT_USDT|0.188090|-25.04|39.86|-25.75|68530689|4.78|
|ONE_USDT|0.001555|-13.31|39.28|-14.02|10838410|0.64|
|AKE_USDT|0.002543|-12.73|-38.81|-13.44|8870088|3.93|
|ZEC_USDT|980.180000|-10.35|-18.57|-11.06|2147196449|0.10|
|BTW_USDT|1.092700|-8.83|3.19|-9.54|5977352|2.75|
|UNI_USDT|6.408000|-6.17|-12.85|-6.88|41142985|1.56|
|PEPE_USDT|0.000005|-4.35|2.66|-5.06|79233745|0.80|
|DASH_USDT|43.660000|-3.27|-5.37|-3.98|16920136|2.29|
|QNT_USDT|177.270000|-1.89|-9.28|-2.60|44881662|1.69|
|VVV_USDT|18.888000|-1.82|-15.53|-2.53|5459469|0.53|
|ARB_USDT|0.158590|-1.72|-0.80|-2.43|28479647|1.26|
|HBAR_USDT|0.065500|-0.42|-6.46|-1.13|6343770|1.53|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002543|0.002493|0.002543|1.44|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.158590|0.158090|0.158590|0.54|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.092700|1.086400|1.092700|1.12|N|Y/Y|Y/N|Y|N|
|DASH_USDT|43.660000|42.990000|43.660000|0.02|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.065500|0.065210|0.065500|1.14|N|Y/Y|Y/Y|Y|N|
|INIT_USDT|0.188090|0.174240|0.188040|1.52|N|Y/Y|N/N|Y|N|
|ONE_USDT|0.001555|0.001541|0.001555|0.38|N|Y/Y|Y/N|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|1.52|N|Y/Y|N/N|Y|N|
|QNT_USDT|177.270000|176.850000|177.280000|0.70|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.408000|6.336000|6.408000|0.52|N|Y/Y|Y/Y|Y|N|
|VVV_USDT|18.888000|18.772000|18.888000|1.54|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|980.180000|960.750000|980.180000|0.52|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-11T10:15:01+00:00, last15m_closed_end=2026-11-11T10:15+00:00, prior8high=0.002591, depth_time=2026-11-11T10:15:11+00:00, book20_bid_proxy_usdt=63407, book20_ask_proxy_usdt=51498, funding_indicative=0.000050, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-12.73%, turnover=8870088. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-11T10:15:01+00:00, last15m_closed_end=2026-11-11T10:15+00:00, prior8high=0.160150, depth_time=2026-11-11T10:15:31+00:00, book20_bid_proxy_usdt=407114, book20_ask_proxy_usdt=44320, funding_indicative=-0.000028, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.72%, turnover=28479647. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-11T10:15:01+00:00, last15m_closed_end=2026-11-11T10:15+00:00, prior8high=1.136400, depth_time=2026-11-11T10:15:14+00:00, book20_bid_proxy_usdt=29803, book20_ask_proxy_usdt=12140, funding_indicative=-0.000543, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-8.83%, turnover=5977352. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-11T10:15:01+00:00, last15m_closed_end=2026-11-11T10:15+00:00, prior8high=44.240000, depth_time=2026-11-11T10:15:22+00:00, book20_bid_proxy_usdt=666849, book20_ask_proxy_usdt=679479, funding_indicative=-0.000074, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.27%, turnover=16920136. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-11-11T10:15:01+00:00, last15m_closed_end=2026-11-11T10:15+00:00, prior8high=0.065780, depth_time=2026-11-11T10:15:33+00:00, book20_bid_proxy_usdt=900429, book20_ask_proxy_usdt=735587, funding_indicative=0.000038, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.42%, turnover=6343770. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INIT_USDT: quote_utc=2026-11-11T10:15:01+00:00, last15m_closed_end=2026-11-11T10:15+00:00, prior8high=0.225680, depth_time=2026-11-11T10:15:07+00:00, book20_bid_proxy_usdt=11149, book20_ask_proxy_usdt=19623, funding_indicative=-0.009085, next_funding_utc=2026-11-11T11:00:00+00:00, funding_cycle_h=1, 24h_change=-25.04%, turnover=68530689. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-11T10:15:01+00:00, last15m_closed_end=2026-11-11T10:15+00:00, prior8high=0.001632, depth_time=2026-11-11T10:15:09+00:00, book20_bid_proxy_usdt=43048, book20_ask_proxy_usdt=14656, funding_indicative=-0.000687, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-13.31%, turnover=10838410. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-11T10:15:01+00:00, last15m_closed_end=2026-11-11T10:15+00:00, prior8high=0.000005, depth_time=2026-11-11T10:15:21+00:00, book20_bid_proxy_usdt=27129, book20_ask_proxy_usdt=28696, funding_indicative=-0.000141, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.35%, turnover=79233745. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-11T10:15:01+00:00, last15m_closed_end=2026-11-11T10:15+00:00, prior8high=179.710000, depth_time=2026-11-11T10:15:22+00:00, book20_bid_proxy_usdt=105277, book20_ask_proxy_usdt=76285, funding_indicative=-0.000190, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.89%, turnover=44881662. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T10:15:01+00:00, last15m_closed_end=2026-11-11T10:15+00:00, prior8high=6.473000, depth_time=2026-11-11T10:15:15+00:00, book20_bid_proxy_usdt=2966339, book20_ask_proxy_usdt=3098955, funding_indicative=-0.000013, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.17%, turnover=41142985. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-11T10:15:01+00:00, last15m_closed_end=2026-11-11T10:15+00:00, prior8high=19.174000, depth_time=2026-11-11T10:15:27+00:00, book20_bid_proxy_usdt=26478, book20_ask_proxy_usdt=18513, funding_indicative=0.000008, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.82%, turnover=5459469. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T10:15:01+00:00, last15m_closed_end=2026-11-11T10:15+00:00, prior8high=1002.300000, depth_time=2026-11-11T10:15:13+00:00, book20_bid_proxy_usdt=229460, book20_ask_proxy_usdt=250684, funding_indicative=0.000022, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-10.35%, turnover=2147196449. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
