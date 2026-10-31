# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T04:45:35Z**
- feed_generated_utc: 2026-10-31T04:45:37+00:00
- source_sha256: `f540353784d246f4d2c1f29d6480a7596060d9ea87452491dd75edf4b72f2267`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T04:45+00:00, close=77119.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-31T04:00+00:00, close=77131.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-31T04:00+00:00, close=77131.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.011367|-39.92|-67.52|-39.33|6558520|3.52|
|EVAA_USDT|1.176500|-8.23|124.13|-7.64|6451555|7.65|
|BEAT_USDT|0.098580|-6.24|35.80|-5.65|8836814|1.01|
|WLD_USDT|0.392900|-4.61|-26.20|-4.02|51229451|2.54|
|PEPE_USDT|0.000005|-4.51|-0.59|-3.92|139472676|0.21|
|HYPE_USDT|88.508000|-4.15|12.88|-3.56|112725687|0.11|
|LIT_USDT|2.720200|-3.68|-18.16|-3.09|5586019|0.37|
|TRX_USDT|0.324320|-3.33|-1.52|-2.74|7310989|0.62|
|DASH_USDT|47.970000|-2.18|-10.91|-1.59|16362072|2.08|
|BTW_USDT|1.176300|-1.93|-30.90|-1.34|9783056|5.11|
|XMR_USDT|590.220000|-1.88|-2.76|-1.29|8799557|0.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.011367|0.011264|0.011367|0.61|N|Y/Y|Y/Y|Y|N|
|BEAT_USDT|0.098580|0.096210|0.098630|1.19|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.176300|1.134400|1.176300|1.48|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|47.970000|48.200000|47.970000|18.27|Y|Y/Y|Y/Y|Y|Y|
|EVAA_USDT|1.176500|1.178700|1.176500|1.90|Y|N/N|N/N|Y|N|
|HYPE_USDT|88.508000|89.108000|88.508000|5.23|Y|Y/Y|N/N|Y|N|
|LIT_USDT|2.720200|2.734100|2.720200|1.93|Y|Y/Y|Y/Y|Y|Y|
|PEPE_USDT|0.000005|0.000005|0.000005|2.21|Y|Y/Y|N/N|Y|N|
|TRX_USDT|0.324320|0.324100|0.324320|1.96|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.392900|0.398600|0.392900|6.74|Y|Y/Y|Y/Y|Y|Y|
|XMR_USDT|590.220000|589.670000|590.310000|0.79|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T04:44:59+00:00, last15m_closed_end=2026-10-31T04:45+00:00, prior8high=0.012057, depth_time=2026-10-31T04:45:07+00:00, book20_bid_proxy_usdt=8031, book20_ask_proxy_usdt=5310, funding_indicative=-0.000069, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-39.92%, turnover=6558520. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-31T04:44:59+00:00, last15m_closed_end=2026-10-31T04:45+00:00, prior8high=0.101470, depth_time=2026-10-31T04:45:14+00:00, book20_bid_proxy_usdt=11292, book20_ask_proxy_usdt=9472, funding_indicative=0.000136, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.24%, turnover=8836814. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T04:44:59+00:00, last15m_closed_end=2026-10-31T04:45+00:00, prior8high=1.271600, depth_time=2026-10-31T04:45:32+00:00, book20_bid_proxy_usdt=9524, book20_ask_proxy_usdt=10689, funding_indicative=-0.000405, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.93%, turnover=9783056. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-31T04:45:00+00:00, last15m_closed_end=2026-10-31T04:45+00:00, prior8high=48.760000, depth_time=2026-10-31T04:45:26+00:00, book20_bid_proxy_usdt=577198, book20_ask_proxy_usdt=626536, funding_indicative=0.000068, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.18%, turnover=16362072. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-31T04:44:59+00:00, last15m_closed_end=2026-10-31T04:45+00:00, prior8high=1.292600, depth_time=2026-10-31T04:45:08+00:00, book20_bid_proxy_usdt=2997, book20_ask_proxy_usdt=9629, funding_indicative=0.000185, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-8.23%, turnover=6451555. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T04:44:59+00:00, last15m_closed_end=2026-10-31T04:45+00:00, prior8high=90.160000, depth_time=2026-10-31T04:45:22+00:00, book20_bid_proxy_usdt=183975, book20_ask_proxy_usdt=60678, funding_indicative=0.000050, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.15%, turnover=112725687. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-31T04:45:00+00:00, last15m_closed_end=2026-10-31T04:45+00:00, prior8high=2.792700, depth_time=2026-10-31T04:45:24+00:00, book20_bid_proxy_usdt=32933, book20_ask_proxy_usdt=37089, funding_indicative=0.000050, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.68%, turnover=5586019. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-31T04:44:59+00:00, last15m_closed_end=2026-10-31T04:45+00:00, prior8high=0.000005, depth_time=2026-10-31T04:45:19+00:00, book20_bid_proxy_usdt=16976, book20_ask_proxy_usdt=22112, funding_indicative=-0.000212, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.51%, turnover=139472676. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T04:44:59+00:00, last15m_closed_end=2026-10-31T04:45+00:00, prior8high=0.327950, depth_time=2026-10-31T04:45:26+00:00, book20_bid_proxy_usdt=45685, book20_ask_proxy_usdt=49674, funding_indicative=-0.001399, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.33%, turnover=7310989. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T04:44:59+00:00, last15m_closed_end=2026-10-31T04:45+00:00, prior8high=0.402800, depth_time=2026-10-31T04:45:17+00:00, book20_bid_proxy_usdt=2797491, book20_ask_proxy_usdt=2823340, funding_indicative=0.000100, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.61%, turnover=51229451. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-31T04:45:00+00:00, last15m_closed_end=2026-10-31T04:45+00:00, prior8high=597.630000, depth_time=2026-10-31T04:45:34+00:00, book20_bid_proxy_usdt=8666, book20_ask_proxy_usdt=11109, funding_indicative=0.000539, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.88%, turnover=8799557. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
