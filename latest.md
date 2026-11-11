# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T13:00:30Z**
- feed_generated_utc: 2026-11-11T13:00:32+00:00
- source_sha256: `bb556892e5ae7111af1fd90507d042f314fcd6612ec9e789cc4902a8a566eecb`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T13:00+00:00, close=73854.4, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-11-11T13:00+00:00, close=73854.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-11T12:00+00:00, close=73963.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|INIT_USDT|0.167700|-33.17|24.70|-34.09|68145079|3.58|
|ONE_USDT|0.001539|-14.23|37.81|-15.15|8264091|0.65|
|AKE_USDT|0.002591|-11.08|-37.65|-12.00|8821102|3.86|
|ZEC_USDT|979.410000|-10.42|-18.64|-11.34|2192588066|0.10|
|DASH_USDT|43.800000|-5.90|-5.07|-6.82|16840727|2.28|
|UNI_USDT|6.454000|-5.50|-12.22|-6.42|41686480|1.55|
|PEPE_USDT|0.000005|-5.27|1.67|-6.19|83490505|0.20|
|BTW_USDT|1.091000|-4.05|3.03|-4.97|5958166|4.59|
|QNT_USDT|177.990000|-1.49|-8.91|-2.41|44302570|1.12|
|ARB_USDT|0.159710|-1.03|-0.10|-1.95|27448999|1.25|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002591|0.002465|0.002591|1.38|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.159710|0.158170|0.159710|0.73|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.091000|1.070000|1.091000|0.96|N|Y/Y|Y/N|Y|N|
|DASH_USDT|43.800000|43.670000|43.800000|0.59|N|Y/Y|Y/Y|Y|N|
|INIT_USDT|0.167700|0.167620|0.167750|0.84|N|Y/Y|Y/N|Y|N|
|ONE_USDT|0.001539|0.001528|0.001538|1.06|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|1.12|N|Y/Y|Y/N|Y|N|
|QNT_USDT|177.990000|176.980000|177.990000|0.90|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.454000|6.413000|6.454000|1.30|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|979.410000|975.170000|979.410000|0.67|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-11T12:59:59+00:00, last15m_closed_end=2026-11-11T13:00+00:00, prior8high=0.002572, depth_time=2026-11-11T13:00:12+00:00, book20_bid_proxy_usdt=73549, book20_ask_proxy_usdt=45336, funding_indicative=0.000050, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=4, 24h_change=-11.08%, turnover=8821102. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-11T12:59:59+00:00, last15m_closed_end=2026-11-11T13:00+00:00, prior8high=0.161860, depth_time=2026-11-11T13:00:28+00:00, book20_bid_proxy_usdt=75052, book20_ask_proxy_usdt=56169, funding_indicative=-0.000164, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.03%, turnover=27448999. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-11T13:00:00+00:00, last15m_closed_end=2026-11-11T13:00+00:00, prior8high=1.095300, depth_time=2026-11-11T13:00:24+00:00, book20_bid_proxy_usdt=23488, book20_ask_proxy_usdt=11658, funding_indicative=-0.000406, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.05%, turnover=5958166. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-11T13:00:00+00:00, last15m_closed_end=2026-11-11T13:00+00:00, prior8high=44.430000, depth_time=2026-11-11T13:00:17+00:00, book20_bid_proxy_usdt=817743, book20_ask_proxy_usdt=567085, funding_indicative=0.000021, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.90%, turnover=16840727. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INIT_USDT: quote_utc=2026-11-11T12:59:59+00:00, last15m_closed_end=2026-11-11T13:00+00:00, prior8high=0.190750, depth_time=2026-11-11T13:00:08+00:00, book20_bid_proxy_usdt=14462, book20_ask_proxy_usdt=13356, funding_indicative=-0.002152, next_funding_utc=2026-11-11T14:00:00+00:00, funding_cycle_h=1, 24h_change=-33.17%, turnover=68145079. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-11T12:59:59+00:00, last15m_closed_end=2026-11-11T13:00+00:00, prior8high=0.001569, depth_time=2026-11-11T13:00:09+00:00, book20_bid_proxy_usdt=22459, book20_ask_proxy_usdt=24295, funding_indicative=-0.000620, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=4, 24h_change=-14.23%, turnover=8264091. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-11T12:59:59+00:00, last15m_closed_end=2026-11-11T13:00+00:00, prior8high=0.000005, depth_time=2026-11-11T13:00:22+00:00, book20_bid_proxy_usdt=36558, book20_ask_proxy_usdt=32095, funding_indicative=-0.000213, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.27%, turnover=83490505. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-11T12:59:59+00:00, last15m_closed_end=2026-11-11T13:00+00:00, prior8high=179.200000, depth_time=2026-11-11T13:00:25+00:00, book20_bid_proxy_usdt=102990, book20_ask_proxy_usdt=78520, funding_indicative=-0.000135, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.49%, turnover=44302570. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T12:59:59+00:00, last15m_closed_end=2026-11-11T13:00+00:00, prior8high=6.492000, depth_time=2026-11-11T13:00:19+00:00, book20_bid_proxy_usdt=2012807, book20_ask_proxy_usdt=1895708, funding_indicative=-0.000008, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.50%, turnover=41686480. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T12:59:59+00:00, last15m_closed_end=2026-11-11T13:00+00:00, prior8high=994.360000, depth_time=2026-11-11T13:00:15+00:00, book20_bid_proxy_usdt=196189, book20_ask_proxy_usdt=184444, funding_indicative=0.000037, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-10.42%, turnover=2192588066. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
