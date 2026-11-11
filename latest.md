# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T11:30:33Z**
- feed_generated_utc: 2026-11-11T11:30:35+00:00
- source_sha256: `43659143d952befff9b939cc9a136a00056870e78cdc86756c57a53338c277e3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T11:30+00:00, close=73976.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-11T11:00+00:00, close=74018, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-11T08:00+00:00, close=74064.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|INIT_USDT|0.182950|-27.09|36.04|-28.17|68370527|0.55|
|AKE_USDT|0.002476|-15.03|-40.42|-16.11|8995867|4.04|
|ONE_USDT|0.001532|-14.61|37.20|-15.69|9063395|0.65|
|BTW_USDT|1.085600|-9.42|2.52|-10.50|6054674|5.53|
|ZEC_USDT|990.730000|-9.38|-17.70|-10.46|2157661130|0.10|
|UNI_USDT|6.452000|-5.53|-12.25|-6.61|41400268|1.55|
|PEPE_USDT|0.000005|-5.49|1.43|-6.57|80285076|0.40|
|DASH_USDT|43.860000|-2.83|-4.94|-3.91|17006508|4.56|
|QNT_USDT|178.060000|-1.46|-8.88|-2.54|44388055|0.56|
|ARB_USDT|0.159190|-1.35|-0.43|-2.43|28361862|1.26|
|HBAR_USDT|0.065790|0.01|-6.05|-1.07|6820639|1.52|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002476|0.002493|0.002476|1.54|Y|Y/Y|Y/Y|Y|Y|
|ARB_USDT|0.159190|0.158090|0.159160|2.43|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.085600|1.072100|1.085600|0.91|N|Y/Y|Y/N|Y|N|
|DASH_USDT|43.860000|42.990000|43.860000|0.81|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.065790|0.065320|0.065790|1.66|N|Y/Y|Y/Y|Y|N|
|INIT_USDT|0.182950|0.174240|0.182950|0.35|N|Y/Y|N/N|Y|N|
|ONE_USDT|0.001532|0.001533|0.001532|0.61|N|Y/Y|Y/N|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|1.30|N|Y/Y|N/N|Y|N|
|QNT_USDT|178.060000|176.950000|178.060000|1.62|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.452000|6.336000|6.452000|0.48|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|990.730000|962.630000|990.730000|0.69|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-11T11:29:59+00:00, last15m_closed_end=2026-11-11T11:30+00:00, prior8high=0.002623, depth_time=2026-11-11T11:30:10+00:00, book20_bid_proxy_usdt=46944, book20_ask_proxy_usdt=79017, funding_indicative=0.000050, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-15.03%, turnover=8995867. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-11T11:29:59+00:00, last15m_closed_end=2026-11-11T11:30+00:00, prior8high=0.160070, depth_time=2026-11-11T11:30:29+00:00, book20_bid_proxy_usdt=54080, book20_ask_proxy_usdt=41882, funding_indicative=-0.000069, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.35%, turnover=28361862. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-11T11:30:00+00:00, last15m_closed_end=2026-11-11T11:30+00:00, prior8high=1.129100, depth_time=2026-11-11T11:30:14+00:00, book20_bid_proxy_usdt=19379, book20_ask_proxy_usdt=9762, funding_indicative=-0.000421, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-9.42%, turnover=6054674. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-11T11:30:00+00:00, last15m_closed_end=2026-11-11T11:30+00:00, prior8high=44.240000, depth_time=2026-11-11T11:30:25+00:00, book20_bid_proxy_usdt=622212, book20_ask_proxy_usdt=569766, funding_indicative=-0.000018, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.83%, turnover=17006508. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-11-11T11:30:00+00:00, last15m_closed_end=2026-11-11T11:30+00:00, prior8high=0.066060, depth_time=2026-11-11T11:30:30+00:00, book20_bid_proxy_usdt=716710, book20_ask_proxy_usdt=757552, funding_indicative=0.000051, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=0.01%, turnover=6820639. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INIT_USDT: quote_utc=2026-11-11T11:29:59+00:00, last15m_closed_end=2026-11-11T11:30+00:00, prior8high=0.202120, depth_time=2026-11-11T11:30:08+00:00, book20_bid_proxy_usdt=10951, book20_ask_proxy_usdt=9304, funding_indicative=-0.005742, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=1, 24h_change=-27.09%, turnover=68370527. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-11T11:29:59+00:00, last15m_closed_end=2026-11-11T11:30+00:00, prior8high=0.001583, depth_time=2026-11-11T11:30:12+00:00, book20_bid_proxy_usdt=32506, book20_ask_proxy_usdt=26767, funding_indicative=-0.000422, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-14.61%, turnover=9063395. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-11T11:29:59+00:00, last15m_closed_end=2026-11-11T11:30+00:00, prior8high=0.000005, depth_time=2026-11-11T11:30:23+00:00, book20_bid_proxy_usdt=23261, book20_ask_proxy_usdt=43569, funding_indicative=-0.000187, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.49%, turnover=80285076. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-11T11:29:59+00:00, last15m_closed_end=2026-11-11T11:30+00:00, prior8high=179.750000, depth_time=2026-11-11T11:30:26+00:00, book20_bid_proxy_usdt=50283, book20_ask_proxy_usdt=58753, funding_indicative=-0.000159, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.46%, turnover=44388055. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T11:30:00+00:00, last15m_closed_end=2026-11-11T11:30+00:00, prior8high=6.519000, depth_time=2026-11-11T11:30:20+00:00, book20_bid_proxy_usdt=3177308, book20_ask_proxy_usdt=2762250, funding_indicative=-0.000005, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.53%, turnover=41400268. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T11:29:59+00:00, last15m_closed_end=2026-11-11T11:30+00:00, prior8high=999.700000, depth_time=2026-11-11T11:30:17+00:00, book20_bid_proxy_usdt=216328, book20_ask_proxy_usdt=272841, funding_indicative=0.000037, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-9.38%, turnover=2157661130. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
