# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T14:00:41Z**
- feed_generated_utc: 2026-10-28T14:00:46+00:00
- source_sha256: `4676e64e7e8adb13523ca05a14542243a2b259b8b1471dc097d3d789feaecc2c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 75/75 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 14; crypto_deep: 14
- snapshot_age_at_feed_build: 0.08 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T14:00+00:00, close=80713.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-28T14:00+00:00, close=80713.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-28T12:00+00:00, close=81305.7, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.019629|-33.60|-36.86|-33.81|6614591|2.55|
|Q_USDT|0.053180|-19.41|-56.67|-19.62|17680739|3.76|
|BEAT_USDT|0.079020|-8.34|5.76|-8.55|12184928|1.26|
|ENA_USDT|0.196650|-5.61|3.56|-5.82|79092119|0.51|
|INJ_USDT|7.816000|-2.22|-9.11|-2.43|24325245|1.28|
|ARB_USDT|0.164820|-2.18|-12.77|-2.39|16469285|0.61|
|UNI_USDT|7.021000|-1.92|-3.43|-2.13|13861202|1.43|
|DASH_USDT|53.040000|-1.90|6.20|-2.11|15456547|1.88|
|BULLA_USDT|0.057700|-1.78|-18.05|-1.99|8526761|8.68|
|ADA_USDT|0.202200|-1.65|-8.67|-1.86|35433887|4.94|
|WLD_USDT|0.429000|-1.60|-23.77|-1.81|59527532|2.33|
|QNT_USDT|195.550000|-1.48|0.19|-1.69|65654887|0.51|
|SILVER_USDT|54.000000|-1.17|-6.81|-1.38|248773599|1.85|
|HBAR_USDT|0.075460|-0.86|-9.47|-1.07|10165438|1.33|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ADA_USDT|0.202200|0.202000|0.202400|4.76|N|Y/Y|N/N|Y|N|
|AKE_USDT|0.019629|0.019399|0.019629|0.38|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.164820|0.164190|0.164820|6.83|N|Y/Y|Y/Y|Y|N|
|BEAT_USDT|0.079020|0.078570|0.079020|0.59|N|Y/Y|Y/N|Y|N|
|BULLA_USDT|0.057700|0.057670|0.058070|1.82|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|53.040000|52.980000|53.040000|0.97|N|Y/Y|N/N|Y|N|
|ENA_USDT|0.196650|0.197780|0.196650|2.65|Y|Y/Y|Y/N|Y|N|
|HBAR_USDT|0.075460|0.075140|0.075450|6.83|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.816000|7.804000|7.816000|6.14|N|Y/Y|N/N|Y|N|
|QNT_USDT|195.550000|194.120000|195.550000|1.61|N|Y/Y|N/N|Y|N|
|Q_USDT|0.053180|0.052780|0.053180|0.59|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|54.000000|53.860000|54.010000|2.88|N|Y/N|Y/Y|Y|N|
|UNI_USDT|7.021000|7.004000|7.022000|1.97|N|Y/Y|N/N|Y|N|
|WLD_USDT|0.429000|0.425300|0.429000|2.02|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ADA_USDT: quote_utc=2026-10-28T14:00:01+00:00, last15m_closed_end=2026-10-28T14:00+00:00, prior8high=0.207000, depth_time=2026-10-28T14:00:30+00:00, book20_bid_proxy_usdt=8176864, book20_ask_proxy_usdt=7839432, funding_indicative=-0.000061, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.65%, turnover=35433887. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-10-28T14:00:01+00:00, last15m_closed_end=2026-10-28T14:00+00:00, prior8high=0.020235, depth_time=2026-10-28T14:00:08+00:00, book20_bid_proxy_usdt=4432, book20_ask_proxy_usdt=5164, funding_indicative=0.000050, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-33.60%, turnover=6614591. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-28T14:00:01+00:00, last15m_closed_end=2026-10-28T14:00+00:00, prior8high=0.168910, depth_time=2026-10-28T14:00:20+00:00, book20_bid_proxy_usdt=94770, book20_ask_proxy_usdt=98950, funding_indicative=-0.000094, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.18%, turnover=16469285. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-28T14:00:01+00:00, last15m_closed_end=2026-10-28T14:00+00:00, prior8high=0.081820, depth_time=2026-10-28T14:00:12+00:00, book20_bid_proxy_usdt=8303, book20_ask_proxy_usdt=9621, funding_indicative=0.000050, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.34%, turnover=12184928. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BULLA_USDT: quote_utc=2026-10-28T14:00:01+00:00, last15m_closed_end=2026-10-28T14:00+00:00, prior8high=0.061900, depth_time=2026-10-28T14:00:28+00:00, book20_bid_proxy_usdt=7674, book20_ask_proxy_usdt=12566, funding_indicative=0.000050, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.78%, turnover=8526761. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-28T14:00:01+00:00, last15m_closed_end=2026-10-28T14:00+00:00, prior8high=53.670000, depth_time=2026-10-28T14:00:19+00:00, book20_bid_proxy_usdt=1007434, book20_ask_proxy_usdt=761413, funding_indicative=0.000100, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.90%, turnover=15456547. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-28T14:00:01+00:00, last15m_closed_end=2026-10-28T14:00+00:00, prior8high=0.205170, depth_time=2026-10-28T14:00:16+00:00, book20_bid_proxy_usdt=161454, book20_ask_proxy_usdt=177847, funding_indicative=-0.000033, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.61%, turnover=79092119. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-28T14:00:01+00:00, last15m_closed_end=2026-10-28T14:00+00:00, prior8high=0.076410, depth_time=2026-10-28T14:00:40+00:00, book20_bid_proxy_usdt=1412838, book20_ask_proxy_usdt=848321, funding_indicative=0.000008, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.86%, turnover=10165438. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-28T14:00:01+00:00, last15m_closed_end=2026-10-28T14:00+00:00, prior8high=7.964000, depth_time=2026-10-28T14:00:18+00:00, book20_bid_proxy_usdt=281321, book20_ask_proxy_usdt=231530, funding_indicative=0.000149, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.22%, turnover=24325245. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-28T14:00:01+00:00, last15m_closed_end=2026-10-28T14:00+00:00, prior8high=201.030000, depth_time=2026-10-28T14:00:36+00:00, book20_bid_proxy_usdt=112193, book20_ask_proxy_usdt=36578, funding_indicative=-0.000337, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.48%, turnover=65654887. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-28T14:00:01+00:00, last15m_closed_end=2026-10-28T14:00+00:00, prior8high=0.055830, depth_time=2026-10-28T14:00:10+00:00, book20_bid_proxy_usdt=27640, book20_ask_proxy_usdt=22425, funding_indicative=-0.000820, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-19.41%, turnover=17680739. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-28T14:00:01+00:00, last15m_closed_end=2026-10-28T14:00+00:00, prior8high=54.480000, depth_time=2026-10-28T14:00:38+00:00, book20_bid_proxy_usdt=51015658, book20_ask_proxy_usdt=53343447, funding_indicative=0.000021, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.17%, turnover=248773599. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-28T14:00:01+00:00, last15m_closed_end=2026-10-28T14:00+00:00, prior8high=7.167000, depth_time=2026-10-28T14:00:23+00:00, book20_bid_proxy_usdt=2346768, book20_ask_proxy_usdt=1802011, funding_indicative=0.000100, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.92%, turnover=13861202. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-28T14:00:01+00:00, last15m_closed_end=2026-10-28T14:00+00:00, prior8high=0.438400, depth_time=2026-10-28T14:00:33+00:00, book20_bid_proxy_usdt=3426669, book20_ask_proxy_usdt=3792287, funding_indicative=-0.000086, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.60%, turnover=59527532. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
