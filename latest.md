# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T05:30:44Z**
- feed_generated_utc: 2026-10-17T05:30:47+00:00
- source_sha256: `d8421acafcc67e620430c3c75bc706823c6e286a6398241406cc2e1cd94d594a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 15; crypto_deep: 15
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T05:30+00:00, close=81570, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-17T05:00+00:00, close=81500.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-17T04:00+00:00, close=81534.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZRO_USDT|1.967300|-6.37|-3.41|-6.67|14493610|0.51|
|BAT_USDT|0.195600|-4.59|60.77|-4.89|14509234|1.02|
|STRK_USDT|0.070780|-4.28|-6.01|-4.58|21655200|1.41|
|RIVER_USDT|1.078000|-4.26|-8.79|-4.56|5016279|9.28|
|FET_USDT|0.194400|-2.60|-10.41|-2.90|11528121|5.14|
|ARB_USDT|0.190120|-2.47|5.15|-2.77|32652944|0.53|
|ZEC_USDT|1163.290000|-2.08|-4.52|-2.38|1379816164|0.09|
|TAO_USDT|275.610000|-1.78|0.34|-2.08|75037778|1.09|
|APT_USDT|0.841200|-1.74|5.08|-2.04|12416442|1.19|
|INJ_USDT|8.830000|-1.64|27.43|-1.94|101235182|2.27|
|AVAX_USDT|9.991000|-0.91|-1.97|-1.21|118623212|1.00|
|FARTCOIN_USDT|0.153340|-0.89|-6.13|-1.19|6984930|0.65|
|AAVE_USDT|155.890000|-0.88|-8.21|-1.18|28412013|1.28|
|SUI_USDT|1.012400|-0.79|-4.27|-1.09|93634577|0.99|
|XLM_USDT|0.179350|-0.73|-6.92|-1.03|14469873|0.56|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|155.890000|154.990000|155.880000|0.71|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.841200|0.836300|0.841200|1.96|N|N/Y|N/N|Y|N|
|ARB_USDT|0.190120|0.187870|0.190120|0.51|N|Y/Y|Y/N|Y|N|
|AVAX_USDT|9.991000|9.942000|9.991000|0.60|N|Y/Y|Y/Y|Y|N|
|BAT_USDT|0.195600|0.195330|0.195600|5.21|N|Y/N|N/N|Y|N|
|FARTCOIN_USDT|0.153340|0.152230|0.153340|0.45|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.194400|0.194100|0.194400|3.68|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|8.830000|8.849000|8.831000|2.22|Y|N/N|N/N|Y|N|
|RIVER_USDT|1.078000|1.071000|1.078000|0.66|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.070780|0.069640|0.070780|1.20|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|1.012400|1.003800|1.012400|1.28|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|275.610000|273.670000|275.610000|0.57|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.179350|0.179420|0.179350|0.33|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1163.290000|1145.180000|1163.290000|1.04|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.967300|1.948900|1.967300|1.04|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-17T05:29:59+00:00, last15m_closed_end=2026-10-17T05:30+00:00, prior8high=156.680000, depth_time=2026-10-17T05:30:38+00:00, book20_bid_proxy_usdt=298810, book20_ask_proxy_usdt=330161, funding_indicative=0.000045, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.88%, turnover=28412013. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-17T05:29:59+00:00, last15m_closed_end=2026-10-17T05:30+00:00, prior8high=0.856200, depth_time=2026-10-17T05:30:28+00:00, book20_bid_proxy_usdt=153560, book20_ask_proxy_usdt=146882, funding_indicative=0.000054, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.74%, turnover=12416442. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-17T05:29:59+00:00, last15m_closed_end=2026-10-17T05:30+00:00, prior8high=0.192330, depth_time=2026-10-17T05:30:20+00:00, book20_bid_proxy_usdt=96951, book20_ask_proxy_usdt=62465, funding_indicative=-0.000021, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.47%, turnover=32652944. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-17T05:29:59+00:00, last15m_closed_end=2026-10-17T05:30+00:00, prior8high=10.037000, depth_time=2026-10-17T05:30:32+00:00, book20_bid_proxy_usdt=787121, book20_ask_proxy_usdt=530937, funding_indicative=0.000062, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.91%, turnover=118623212. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-17T05:29:59+00:00, last15m_closed_end=2026-10-17T05:30+00:00, prior8high=0.203660, depth_time=2026-10-17T05:30:10+00:00, book20_bid_proxy_usdt=26520, book20_ask_proxy_usdt=30828, funding_indicative=-0.000057, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.59%, turnover=14509234. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-17T05:29:59+00:00, last15m_closed_end=2026-10-17T05:30+00:00, prior8high=0.154160, depth_time=2026-10-17T05:30:35+00:00, book20_bid_proxy_usdt=64517, book20_ask_proxy_usdt=65586, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.89%, turnover=6984930. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-17T05:29:59+00:00, last15m_closed_end=2026-10-17T05:30+00:00, prior8high=0.196500, depth_time=2026-10-17T05:30:17+00:00, book20_bid_proxy_usdt=1669713, book20_ask_proxy_usdt=1059343, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.60%, turnover=11528121. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-17T05:29:59+00:00, last15m_closed_end=2026-10-17T05:30+00:00, prior8high=8.973000, depth_time=2026-10-17T05:30:30+00:00, book20_bid_proxy_usdt=203251, book20_ask_proxy_usdt=283636, funding_indicative=0.000139, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.64%, turnover=101235182. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RIVER_USDT: quote_utc=2026-10-17T05:29:59+00:00, last15m_closed_end=2026-10-17T05:30+00:00, prior8high=1.090000, depth_time=2026-10-17T05:30:15+00:00, book20_bid_proxy_usdt=476086, book20_ask_proxy_usdt=435944, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.26%, turnover=5016279. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-17T05:29:59+00:00, last15m_closed_end=2026-10-17T05:30+00:00, prior8high=0.072130, depth_time=2026-10-17T05:30:12+00:00, book20_bid_proxy_usdt=181460, book20_ask_proxy_usdt=267856, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.28%, turnover=21655200. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-17T05:29:59+00:00, last15m_closed_end=2026-10-17T05:30+00:00, prior8high=1.019400, depth_time=2026-10-17T05:30:41+00:00, book20_bid_proxy_usdt=1447548, book20_ask_proxy_usdt=720842, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.79%, turnover=93634577. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-17T05:29:59+00:00, last15m_closed_end=2026-10-17T05:30+00:00, prior8high=277.190000, depth_time=2026-10-17T05:30:26+00:00, book20_bid_proxy_usdt=73010, book20_ask_proxy_usdt=81108, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.78%, turnover=75037778. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-10-17T05:29:59+00:00, last15m_closed_end=2026-10-17T05:30+00:00, prior8high=0.180460, depth_time=2026-10-17T05:30:41+00:00, book20_bid_proxy_usdt=305909, book20_ask_proxy_usdt=184965, funding_indicative=0.000043, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.73%, turnover=14469873. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-17T05:29:59+00:00, last15m_closed_end=2026-10-17T05:30+00:00, prior8high=1167.300000, depth_time=2026-10-17T05:30:23+00:00, book20_bid_proxy_usdt=300522, book20_ask_proxy_usdt=506500, funding_indicative=0.000020, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.08%, turnover=1379816164. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-17T05:29:59+00:00, last15m_closed_end=2026-10-17T05:30+00:00, prior8high=1.992900, depth_time=2026-10-17T05:30:08+00:00, book20_bid_proxy_usdt=72512, book20_ask_proxy_usdt=35839, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.37%, turnover=14493610. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
