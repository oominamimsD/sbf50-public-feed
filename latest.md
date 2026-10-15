# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-15T02:15:52Z**
- feed_generated_utc: 2026-10-15T02:15:55+00:00
- source_sha256: `1c66d97663165ecbbdbc7ba700990c27e4a0af9b58bd7a7fcc98b56e7af85761`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 17; crypto_deep: 15
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-15T02:15+00:00, close=81412.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-15T02:00+00:00, close=81602, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-15T00:00+00:00, close=81639.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|PONS_USDT|0.311100|-9.56|-24.21|-9.33|6950124|3.22|
|FARTCOIN_USDT|0.151230|-3.45|-5.58|-3.22|8281753|0.66|
|FET_USDT|0.197000|-3.38|-13.02|-3.15|11021614|5.07|
|BAT_USDT|0.169000|-3.10|70.43|-2.87|22969911|1.77|
|NEAR_USDT|4.726000|-2.37|-6.11|-2.14|178503259|2.12|
|QNT_USDT|200.250000|-2.32|-17.51|-2.09|94962787|2.50|
|ENA_USDT|0.190890|-2.21|-16.32|-1.98|39623391|0.52|
|AAVE_USDT|152.560000|-2.13|-11.17|-1.90|25842804|1.31|
|ARB_USDT|0.178530|-1.98|-3.23|-1.75|22361546|0.56|
|UNI_USDT|7.005000|-1.94|-10.67|-1.71|16749959|1.43|
|PUMPFUN_USDT|0.004634|-1.78|-26.10|-1.55|21536621|4.31|
|STRK_USDT|0.075890|-1.67|53.43|-1.44|23472944|1.32|
|ZEC_USDT|1124.740000|-1.65|-15.22|-1.42|1596164587|9.87|
|PENGU_USDT|0.007463|-1.51|-13.03|-1.28|6291644|1.34|
|INJ_USDT|7.528000|-1.45|2.99|-1.22|30906642|2.66|
|ONDO_USDT|0.435500|-1.33|-6.60|-1.10|33713452|2.30|
|WLD_USDT|0.482800|-1.24|-6.66|-1.01|73465031|2.07|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|152.560000|153.100000|152.560000|0.69|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.178530|0.179770|0.178530|3.58|Y|Y/Y|Y/Y|Y|Y|
|BAT_USDT|0.169000|0.166430|0.169070|1.06|N|Y/Y|N/N|Y|N|
|ENA_USDT|0.190890|0.192430|0.190840|2.28|Y|Y/Y|Y/Y|Y|Y|
|FARTCOIN_USDT|0.151230|0.152300|0.151220|4.89|Y|Y/Y|Y/Y|Y|Y|
|FET_USDT|0.197000|0.196800|0.197000|0.77|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.528000|7.566000|7.527000|2.30|Y|Y/Y|Y/Y|Y|Y|
|NEAR_USDT|4.726000|4.731000|4.726000|2.11|Y|Y/Y|Y/Y|Y|Y|
|PENGU_USDT|0.007463|0.007518|0.007463|3.67|Y|Y/Y|Y/Y|Y|Y|
|PONS_USDT|0.311100|0.307900|0.310900|0.92|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004634|0.004697|0.004633|5.78|Y|Y/Y|Y/Y|Y|Y|
|QNT_USDT|200.250000|201.640000|200.200000|1.46|Y|Y/Y|Y/Y|Y|Y|
|STRK_USDT|0.075890|0.075820|0.075890|1.88|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|7.005000|7.080000|7.005000|4.71|Y|Y/Y|Y/Y|Y|Y|
|ZEC_USDT|1124.740000|1130.510000|1124.670000|0.99|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-15T02:15:00+00:00, last15m_closed_end=2026-10-15T02:15+00:00, prior8high=154.480000, depth_time=2026-10-15T02:15:29+00:00, book20_bid_proxy_usdt=176012, book20_ask_proxy_usdt=310728, funding_indicative=0.000021, next_funding_utc=2026-10-15T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.13%, turnover=25842804. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-15T02:15:00+00:00, last15m_closed_end=2026-10-15T02:15+00:00, prior8high=0.183490, depth_time=2026-10-15T02:15:32+00:00, book20_bid_proxy_usdt=49944, book20_ask_proxy_usdt=112730, funding_indicative=-0.000095, next_funding_utc=2026-10-15T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.98%, turnover=22361546. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-15T02:15:00+00:00, last15m_closed_end=2026-10-15T02:15+00:00, prior8high=0.178290, depth_time=2026-10-15T02:15:16+00:00, book20_bid_proxy_usdt=13894, book20_ask_proxy_usdt=26694, funding_indicative=0.000023, next_funding_utc=2026-10-15T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.10%, turnover=22969911. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-15T02:15:00+00:00, last15m_closed_end=2026-10-15T02:15+00:00, prior8high=0.197030, depth_time=2026-10-15T02:15:26+00:00, book20_bid_proxy_usdt=130019, book20_ask_proxy_usdt=177768, funding_indicative=-0.000017, next_funding_utc=2026-10-15T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.21%, turnover=39623391. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-15T02:15:01+00:00, last15m_closed_end=2026-10-15T02:15+00:00, prior8high=0.156150, depth_time=2026-10-15T02:15:11+00:00, book20_bid_proxy_usdt=59134, book20_ask_proxy_usdt=62787, funding_indicative=0.000050, next_funding_utc=2026-10-15T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.45%, turnover=8281753. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-15T02:15:00+00:00, last15m_closed_end=2026-10-15T02:15+00:00, prior8high=0.200300, depth_time=2026-10-15T02:15:14+00:00, book20_bid_proxy_usdt=980521, book20_ask_proxy_usdt=833844, funding_indicative=-0.000081, next_funding_utc=2026-10-15T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.38%, turnover=11021614. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-15T02:15:00+00:00, last15m_closed_end=2026-10-15T02:15+00:00, prior8high=7.696000, depth_time=2026-10-15T02:15:51+00:00, book20_bid_proxy_usdt=207239, book20_ask_proxy_usdt=179702, funding_indicative=0.000171, next_funding_utc=2026-10-15T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.45%, turnover=30906642. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-15T02:15:00+00:00, last15m_closed_end=2026-10-15T02:15+00:00, prior8high=4.925000, depth_time=2026-10-15T02:15:20+00:00, book20_bid_proxy_usdt=1527236, book20_ask_proxy_usdt=658766, funding_indicative=0.000100, next_funding_utc=2026-10-15T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.37%, turnover=178503259. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-15T02:15:01+00:00, last15m_closed_end=2026-10-15T02:15+00:00, prior8high=0.007675, depth_time=2026-10-15T02:15:48+00:00, book20_bid_proxy_usdt=129606, book20_ask_proxy_usdt=118674, funding_indicative=0.000050, next_funding_utc=2026-10-15T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.51%, turnover=6291644. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PONS_USDT: quote_utc=2026-10-15T02:15:00+00:00, last15m_closed_end=2026-10-15T02:15+00:00, prior8high=0.333100, depth_time=2026-10-15T02:15:08+00:00, book20_bid_proxy_usdt=182506, book20_ask_proxy_usdt=173630, funding_indicative=0.000050, next_funding_utc=2026-10-15T04:00:00+00:00, funding_cycle_h=4, 24h_change=-9.56%, turnover=6950124. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-15T02:15:00+00:00, last15m_closed_end=2026-10-15T02:15+00:00, prior8high=0.004808, depth_time=2026-10-15T02:15:39+00:00, book20_bid_proxy_usdt=1731666, book20_ask_proxy_usdt=993253, funding_indicative=0.000050, next_funding_utc=2026-10-15T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.78%, turnover=21536621. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-15T02:15:00+00:00, last15m_closed_end=2026-10-15T02:15+00:00, prior8high=206.710000, depth_time=2026-10-15T02:15:23+00:00, book20_bid_proxy_usdt=31245, book20_ask_proxy_usdt=49800, funding_indicative=0.000002, next_funding_utc=2026-10-15T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.32%, turnover=94962787. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-15T02:15:00+00:00, last15m_closed_end=2026-10-15T02:15+00:00, prior8high=0.077900, depth_time=2026-10-15T02:15:41+00:00, book20_bid_proxy_usdt=225648, book20_ask_proxy_usdt=279241, funding_indicative=0.000023, next_funding_utc=2026-10-15T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.67%, turnover=23472944. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-15T02:15:00+00:00, last15m_closed_end=2026-10-15T02:15+00:00, prior8high=7.210000, depth_time=2026-10-15T02:15:36+00:00, book20_bid_proxy_usdt=1085844, book20_ask_proxy_usdt=1423284, funding_indicative=-0.000009, next_funding_utc=2026-10-15T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.94%, turnover=16749959. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-15T02:15:00+00:00, last15m_closed_end=2026-10-15T02:15+00:00, prior8high=1156.160000, depth_time=2026-10-15T02:15:44+00:00, book20_bid_proxy_usdt=462593, book20_ask_proxy_usdt=141004, funding_indicative=0.000053, next_funding_utc=2026-10-15T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.65%, turnover=1596164587. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
