# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-05T23:15:43Z**
- feed_generated_utc: 2026-11-05T23:15:44+00:00
- source_sha256: `b1c58969fb82daba6c61c3bccd5c41b5c1117eb386cda435da2f9eeef8a57653`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 19; crypto_deep: 15
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-05T23:15+00:00, close=75369.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-05T23:00+00:00, close=75684.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-05T20:00+00:00, close=76344.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002223|-13.83|-89.44|-12.99|19520983|9.00|
|FLUID_USDT|2.372000|-6.31|14.92|-5.47|7760126|8.44|
|ATOM_USDT|1.348000|-5.07|-17.35|-4.23|5401306|7.41|
|BCH_USDT|268.330000|-3.86|-6.92|-3.02|8542488|2.61|
|XRP_USDT|1.203200|-3.32|-8.11|-2.48|433904632|0.83|
|XPL_USDT|0.056800|-3.03|-28.03|-2.19|12386668|3.52|
|HYPE_USDT|76.425000|-2.89|-18.63|-2.05|88947979|0.13|
|FET_USDT|0.142700|-2.85|-22.78|-2.01|7248457|7.00|
|ZRO_USDT|1.577400|-2.76|-10.59|-1.92|6885597|1.27|
|ONDO_USDT|0.362300|-2.73|-15.70|-1.89|30824920|2.76|
|QNT_USDT|186.670000|-2.68|-6.07|-1.84|42632557|0.54|
|ENA_USDT|0.158370|-2.62|-25.96|-1.78|49774292|0.63|
|WLD_USDT|0.332300|-2.52|-23.83|-1.68|80367260|3.01|
|ADA_USDT|0.178200|-2.24|-13.66|-1.40|43681847|5.61|
|SUI_USDT|0.834000|-2.20|-12.55|-1.36|71919450|1.20|
|SEI_USDT|0.044430|-2.20|-16.86|-1.36|6267517|2.25|
|DOGE_USDT|0.070300|-2.11|-12.81|-1.27|154731911|1.42|
|PUMPFUN_USDT|0.003857|-2.05|-14.76|-1.21|12107564|2.59|
|PENGU_USDT|0.006380|-1.96|-21.53|-1.12|6112931|3.13|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ADA_USDT|0.178200|0.180400|0.178200|5.20|Y|Y/Y|Y/Y|Y|Y|
|AKE_USDT|0.002223|0.002108|0.002223|0.36|N|Y/Y|Y/Y|Y|N|
|ATOM_USDT|1.348000|1.370000|1.348000|3.62|Y|Y/Y|Y/N|Y|N|
|BCH_USDT|268.330000|270.070000|268.330000|5.79|Y|Y/Y|Y/N|Y|N|
|ENA_USDT|0.158370|0.161210|0.158400|3.28|Y|Y/Y|Y/Y|Y|Y|
|FET_USDT|0.142700|0.144900|0.142700|4.50|Y|Y/Y|Y/Y|Y|Y|
|FLUID_USDT|2.372000|2.347000|2.372000|3.25|N|Y/Y|N/N|Y|N|
|HYPE_USDT|76.425000|76.324000|76.429000|1.86|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.362300|0.365500|0.362300|4.01|Y|Y/Y|Y/Y|Y|Y|
|QNT_USDT|186.670000|187.390000|186.670000|1.83|Y|Y/Y|Y/Y|Y|Y|
|SUI_USDT|0.834000|0.837500|0.834000|4.09|Y|Y/Y|Y/Y|Y|Y|
|WLD_USDT|0.332300|0.335600|0.332300|2.63|Y|Y/Y|Y/Y|Y|Y|
|XPL_USDT|0.056800|0.058300|0.056800|3.47|Y|Y/Y|Y/Y|Y|Y|
|XRP_USDT|1.203200|1.214600|1.203300|3.13|Y|Y/Y|Y/Y|Y|Y|
|ZRO_USDT|1.577400|1.590000|1.577400|2.23|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- ADA_USDT: quote_utc=2026-11-05T23:15:00+00:00, last15m_closed_end=2026-11-05T23:15+00:00, prior8high=0.184100, depth_time=2026-11-05T23:15:39+00:00, book20_bid_proxy_usdt=6099339, book20_ask_proxy_usdt=7857234, funding_indicative=0.000045, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.24%, turnover=43681847. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-05T23:15:00+00:00, last15m_closed_end=2026-11-05T23:15+00:00, prior8high=0.002275, depth_time=2026-11-05T23:15:06+00:00, book20_bid_proxy_usdt=42014, book20_ask_proxy_usdt=33274, funding_indicative=-0.000767, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-13.83%, turnover=19520983. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ATOM_USDT: quote_utc=2026-11-05T23:15:00+00:00, last15m_closed_end=2026-11-05T23:15+00:00, prior8high=1.419000, depth_time=2026-11-05T23:15:08+00:00, book20_bid_proxy_usdt=2167680, book20_ask_proxy_usdt=1788185, funding_indicative=-0.000119, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-5.07%, turnover=5401306. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BCH_USDT: quote_utc=2026-11-05T23:15:00+00:00, last15m_closed_end=2026-11-05T23:15+00:00, prior8high=275.420000, depth_time=2026-11-05T23:15:14+00:00, book20_bid_proxy_usdt=66596, book20_ask_proxy_usdt=83209, funding_indicative=0.000100, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.86%, turnover=8542488. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-05T23:15:00+00:00, last15m_closed_end=2026-11-05T23:15+00:00, prior8high=0.164690, depth_time=2026-11-05T23:15:34+00:00, book20_bid_proxy_usdt=151518, book20_ask_proxy_usdt=100343, funding_indicative=0.000050, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.62%, turnover=49774292. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-11-05T23:15:00+00:00, last15m_closed_end=2026-11-05T23:15+00:00, prior8high=0.149000, depth_time=2026-11-05T23:15:23+00:00, book20_bid_proxy_usdt=1096561, book20_ask_proxy_usdt=1125882, funding_indicative=-0.000245, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.85%, turnover=7248457. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FLUID_USDT: quote_utc=2026-11-05T23:15:00+00:00, last15m_closed_end=2026-11-05T23:15+00:00, prior8high=2.411000, depth_time=2026-11-05T23:15:08+00:00, book20_bid_proxy_usdt=194815, book20_ask_proxy_usdt=163017, funding_indicative=0.000362, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-6.31%, turnover=7760126. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-05T23:15:00+00:00, last15m_closed_end=2026-11-05T23:15+00:00, prior8high=78.964000, depth_time=2026-11-05T23:15:21+00:00, book20_bid_proxy_usdt=41640, book20_ask_proxy_usdt=319052, funding_indicative=0.000050, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.89%, turnover=88947979. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-05T23:15:00+00:00, last15m_closed_end=2026-11-05T23:15+00:00, prior8high=0.372500, depth_time=2026-11-05T23:15:29+00:00, book20_bid_proxy_usdt=976344, book20_ask_proxy_usdt=1665599, funding_indicative=-0.000020, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.73%, turnover=30824920. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-05T23:15:00+00:00, last15m_closed_end=2026-11-05T23:15+00:00, prior8high=190.730000, depth_time=2026-11-05T23:15:31+00:00, book20_bid_proxy_usdt=64368, book20_ask_proxy_usdt=67771, funding_indicative=-0.000021, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.68%, turnover=42632557. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-11-05T23:15:00+00:00, last15m_closed_end=2026-11-05T23:15+00:00, prior8high=0.854800, depth_time=2026-11-05T23:15:42+00:00, book20_bid_proxy_usdt=989832, book20_ask_proxy_usdt=329032, funding_indicative=-0.000018, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.20%, turnover=71919450. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-05T23:15:00+00:00, last15m_closed_end=2026-11-05T23:15+00:00, prior8high=0.342000, depth_time=2026-11-05T23:15:36+00:00, book20_bid_proxy_usdt=2570597, book20_ask_proxy_usdt=2431772, funding_indicative=-0.000541, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.52%, turnover=80367260. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-05T23:15:00+00:00, last15m_closed_end=2026-11-05T23:15+00:00, prior8high=0.059490, depth_time=2026-11-05T23:15:19+00:00, book20_bid_proxy_usdt=336249, book20_ask_proxy_usdt=410188, funding_indicative=0.000050, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.03%, turnover=12386668. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-05T23:15:00+00:00, last15m_closed_end=2026-11-05T23:15+00:00, prior8high=1.232200, depth_time=2026-11-05T23:15:16+00:00, book20_bid_proxy_usdt=1996307, book20_ask_proxy_usdt=3027172, funding_indicative=0.000100, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.32%, turnover=433904632. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-05T23:15:00+00:00, last15m_closed_end=2026-11-05T23:15+00:00, prior8high=1.631100, depth_time=2026-11-05T23:15:26+00:00, book20_bid_proxy_usdt=20016, book20_ask_proxy_usdt=58350, funding_indicative=0.000050, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.76%, turnover=6885597. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
