# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T09:15:42Z**
- feed_generated_utc: 2026-11-10T09:15:44+00:00
- source_sha256: `5fde262426a65974019e14b16a607c40e13d811160eb89619582e0a5d097b6ca`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 15; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T09:15+00:00, close=74309.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T09:00+00:00, close=74699.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T08:00+00:00, close=74805.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002467|-49.62|-55.16|-48.05|15230091|4.05|
|JCT_USDT|0.006520|-35.64|51.03|-34.07|24828324|4.59|
|ARB_USDT|0.168510|-8.43|5.76|-6.86|36956705|0.59|
|ZEC_USDT|1140.510000|-6.95|-9.05|-5.38|2300080697|0.09|
|AAVE_USDT|124.700000|-6.48|-4.48|-4.91|12344779|0.80|
|QNT_USDT|188.320000|-5.85|-6.97|-4.28|32722757|1.59|
|DOT_USDT|0.848100|-4.80|-9.20|-3.23|8101284|1.18|
|PUMPFUN_USDT|0.003529|-4.15|-14.01|-2.58|7271804|2.83|
|INJ_USDT|7.865000|-3.81|12.21|-2.24|15948399|1.27|
|DASH_USDT|45.930000|-3.54|-2.69|-1.97|10473903|2.18|
|SOL_USDT|85.280000|-2.96|-8.80|-1.39|630843915|1.17|
|ENA_USDT|0.152610|-2.95|-12.81|-1.38|24243555|0.66|
|XRP_USDT|1.081700|-2.89|-13.35|-1.32|272235854|0.93|
|HBAR_USDT|0.066640|-2.67|-5.43|-1.10|9858476|1.50|
|HYPE_USDT|74.278000|-2.66|-13.34|-1.09|46196708|0.14|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|124.700000|125.480000|124.700000|2.46|Y|Y/Y|Y/Y|Y|Y|
|AKE_USDT|0.002467|0.002421|0.002467|0.58|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.168510|0.166250|0.168510|1.20|N|Y/Y|Y/N|Y|N|
|DASH_USDT|45.930000|45.390000|45.930000|4.32|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.848100|0.853100|0.848300|5.15|Y|Y/Y|Y/Y|Y|Y|
|ENA_USDT|0.152610|0.152450|0.152610|2.35|N|N/N|Y/Y|Y|N|
|HBAR_USDT|0.066640|0.066930|0.066640|6.44|Y|Y/N|Y/Y|Y|N|
|HYPE_USDT|74.278000|74.092000|74.279000|1.44|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.865000|7.966000|7.865000|3.86|Y|Y/Y|Y/Y|Y|Y|
|JCT_USDT|0.006520|0.005560|0.006500|1.58|N|Y/Y|Y/N|Y|N|
|PUMPFUN_USDT|0.003529|0.003532|0.003529|10.95|Y|Y/Y|Y/Y|Y|Y|
|QNT_USDT|188.320000|189.090000|188.320000|2.55|Y|Y/Y|Y/Y|Y|Y|
|SOL_USDT|85.280000|85.450000|85.280000|2.17|Y|Y/Y|Y/Y|Y|Y|
|XRP_USDT|1.081700|1.084400|1.081700|5.10|Y|Y/Y|Y/Y|Y|Y|
|ZEC_USDT|1140.510000|1134.630000|1140.560000|1.00|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-10T09:15:01+00:00, last15m_closed_end=2026-11-10T09:15+00:00, prior8high=127.890000, depth_time=2026-11-10T09:15:17+00:00, book20_bid_proxy_usdt=378395, book20_ask_proxy_usdt=469581, funding_indicative=0.000063, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.48%, turnover=12344779. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-10T09:15:01+00:00, last15m_closed_end=2026-11-10T09:15+00:00, prior8high=0.002555, depth_time=2026-11-10T09:15:07+00:00, book20_bid_proxy_usdt=58171, book20_ask_proxy_usdt=51680, funding_indicative=0.000050, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-49.62%, turnover=15230091. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T09:15:01+00:00, last15m_closed_end=2026-11-10T09:15+00:00, prior8high=0.171180, depth_time=2026-11-10T09:15:09+00:00, book20_bid_proxy_usdt=31330, book20_ask_proxy_usdt=68955, funding_indicative=-0.000117, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-8.43%, turnover=36956705. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T09:15:02+00:00, last15m_closed_end=2026-11-10T09:15+00:00, prior8high=46.150000, depth_time=2026-11-10T09:15:29+00:00, book20_bid_proxy_usdt=582470, book20_ask_proxy_usdt=647780, funding_indicative=0.000026, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.54%, turnover=10473903. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T09:15:01+00:00, last15m_closed_end=2026-11-10T09:15+00:00, prior8high=0.862700, depth_time=2026-11-10T09:15:21+00:00, book20_bid_proxy_usdt=796224, book20_ask_proxy_usdt=665934, funding_indicative=-0.000019, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.80%, turnover=8101284. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-10T09:15:01+00:00, last15m_closed_end=2026-11-10T09:15+00:00, prior8high=0.155020, depth_time=2026-11-10T09:15:33+00:00, book20_bid_proxy_usdt=142362, book20_ask_proxy_usdt=246295, funding_indicative=0.000050, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.95%, turnover=24243555. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-11-10T09:15:01+00:00, last15m_closed_end=2026-11-10T09:15+00:00, prior8high=0.067380, depth_time=2026-11-10T09:15:36+00:00, book20_bid_proxy_usdt=704492, book20_ask_proxy_usdt=713346, funding_indicative=0.000040, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.67%, turnover=9858476. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-10T09:15:01+00:00, last15m_closed_end=2026-11-10T09:15+00:00, prior8high=75.066000, depth_time=2026-11-10T09:15:39+00:00, book20_bid_proxy_usdt=132352, book20_ask_proxy_usdt=185623, funding_indicative=0.000050, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.66%, turnover=46196708. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-11-10T09:15:01+00:00, last15m_closed_end=2026-11-10T09:15+00:00, prior8high=8.206000, depth_time=2026-11-10T09:15:28+00:00, book20_bid_proxy_usdt=324986, book20_ask_proxy_usdt=366888, funding_indicative=-0.000041, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.81%, turnover=15948399. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T09:15:01+00:00, last15m_closed_end=2026-11-10T09:15+00:00, prior8high=0.006849, depth_time=2026-11-10T09:15:10+00:00, book20_bid_proxy_usdt=25899, book20_ask_proxy_usdt=27901, funding_indicative=0.000143, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-35.64%, turnover=24828324. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-10T09:15:02+00:00, last15m_closed_end=2026-11-10T09:15+00:00, prior8high=0.003602, depth_time=2026-11-10T09:15:22+00:00, book20_bid_proxy_usdt=2657557, book20_ask_proxy_usdt=2929095, funding_indicative=0.000031, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.15%, turnover=7271804. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T09:15:01+00:00, last15m_closed_end=2026-11-10T09:15+00:00, prior8high=192.140000, depth_time=2026-11-10T09:15:19+00:00, book20_bid_proxy_usdt=68508, book20_ask_proxy_usdt=70377, funding_indicative=-0.000174, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.85%, turnover=32722757. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-10T09:15:01+00:00, last15m_closed_end=2026-11-10T09:15+00:00, prior8high=86.490000, depth_time=2026-11-10T09:15:31+00:00, book20_bid_proxy_usdt=15164538, book20_ask_proxy_usdt=18473088, funding_indicative=0.000089, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.96%, turnover=630843915. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-10T09:15:01+00:00, last15m_closed_end=2026-11-10T09:15+00:00, prior8high=1.106100, depth_time=2026-11-10T09:15:37+00:00, book20_bid_proxy_usdt=2628086, book20_ask_proxy_usdt=3950810, funding_indicative=0.000088, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.89%, turnover=272235854. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T09:15:01+00:00, last15m_closed_end=2026-11-10T09:15+00:00, prior8high=1159.070000, depth_time=2026-11-10T09:15:15+00:00, book20_bid_proxy_usdt=561139, book20_ask_proxy_usdt=287388, funding_indicative=0.000047, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.95%, turnover=2300080697. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
