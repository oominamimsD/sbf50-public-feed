# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T21:45:43Z**
- feed_generated_utc: 2026-10-16T21:45:46+00:00
- source_sha256: `00041169853a0af2795e009f3e628299a8150508426268ec06691508b2ddc179`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 21; crypto_deep: 15
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T21:45+00:00, close=81677.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-16T21:00+00:00, close=81694.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-16T20:00+00:00, close=81561.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|INJ_USDT|8.594000|-4.27|24.02|-4.70|117269529|1.16|
|ZEC_USDT|1141.840000|-3.88|-6.28|-4.31|1463855085|0.09|
|FILECOIN_USDT|1.125100|-3.57|5.14|-4.00|23770033|4.45|
|TAO_USDT|272.730000|-2.81|-0.70|-3.24|82777032|1.10|
|ZRO_USDT|2.047100|-2.57|0.50|-3.00|15984018|0.98|
|OP_USDT|0.137010|-2.13|11.19|-2.56|14721641|0.73|
|APT_USDT|0.840900|-1.77|5.04|-2.20|12638844|4.76|
|ARB_USDT|0.191600|-1.71|5.97|-2.14|32957652|0.52|
|AAVE_USDT|154.620000|-1.69|-8.96|-2.12|31960205|0.65|
|DOT_USDT|1.154000|-1.43|-2.86|-1.86|22361780|2.60|
|AVAX_USDT|9.939000|-1.42|-2.48|-1.85|128166722|1.01|
|STRK_USDT|0.073030|-1.24|-3.02|-1.67|22927502|2.74|
|ICP_USDT|3.001000|-1.21|-0.59|-1.64|9192873|3.33|
|BAT_USDT|0.202600|-1.18|66.52|-1.61|19176620|2.47|
|HBAR_USDT|0.083170|-1.11|-8.46|-1.54|20925132|1.20|
|FARTCOIN_USDT|0.153170|-1.00|-6.24|-1.43|7261203|1.31|
|ENA_USDT|0.197940|-0.99|-8.18|-1.42|41085246|0.51|
|ONDO_USDT|0.452900|-0.91|-5.66|-1.34|28750543|2.21|
|LTC_USDT|59.350000|-0.85|-6.68|-1.28|9831151|3.37|
|NEAR_USDT|5.011000|-0.69|5.47|-1.12|165977446|2.00|
|ETH_USDT|2416.420000|-0.57|-2.86|-1.00|1775939869|0.04|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|154.620000|154.930000|154.620000|0.70|N|Y/Y|Y/N|Y|N|
|APT_USDT|0.840900|0.834700|0.840800|0.74|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.191600|0.190740|0.191600|0.17|N|Y/Y|N/N|Y|N|
|AVAX_USDT|9.939000|9.924000|9.941000|0.77|N|Y/Y|Y/N|Y|N|
|BAT_USDT|0.202600|0.195230|0.202800|0.70|N|Y/Y|N/N|Y|N|
|DOT_USDT|1.154000|1.145600|1.153700|0.34|N|Y/Y|N/N|Y|N|
|FILECOIN_USDT|1.125100|1.123800|1.125100|1.38|N|Y/Y|N/N|Y|N|
|HBAR_USDT|0.083170|0.082200|0.083170|0.27|N|Y/Y|Y/Y|Y|N|
|ICP_USDT|3.001000|2.984000|3.001000|0.38|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|8.594000|8.469000|8.594000|0.32|N|Y/Y|N/N|Y|N|
|OP_USDT|0.137010|0.135160|0.137010|0.33|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.073030|0.071640|0.073030|0.34|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|272.730000|270.100000|272.760000|0.41|N|Y/Y|Y/N|Y|N|
|ZEC_USDT|1141.840000|1131.850000|1141.840000|0.37|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|2.047100|2.022300|2.047100|0.91|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-16T21:45:01+00:00, last15m_closed_end=2026-10-16T21:45+00:00, prior8high=156.610000, depth_time=2026-10-16T21:45:23+00:00, book20_bid_proxy_usdt=291482, book20_ask_proxy_usdt=248371, funding_indicative=0.000066, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.69%, turnover=31960205. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-16T21:45:01+00:00, last15m_closed_end=2026-10-16T21:45+00:00, prior8high=0.848000, depth_time=2026-10-16T21:45:23+00:00, book20_bid_proxy_usdt=132859, book20_ask_proxy_usdt=100993, funding_indicative=0.000068, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.77%, turnover=12638844. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-16T21:45:01+00:00, last15m_closed_end=2026-10-16T21:45+00:00, prior8high=0.194080, depth_time=2026-10-16T21:45:24+00:00, book20_bid_proxy_usdt=41996, book20_ask_proxy_usdt=53364, funding_indicative=-0.000058, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.71%, turnover=32957652. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-16T21:45:01+00:00, last15m_closed_end=2026-10-16T21:45+00:00, prior8high=10.024000, depth_time=2026-10-16T21:45:31+00:00, book20_bid_proxy_usdt=640206, book20_ask_proxy_usdt=581978, funding_indicative=-0.000016, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.42%, turnover=128166722. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-16T21:45:01+00:00, last15m_closed_end=2026-10-16T21:45+00:00, prior8high=0.199860, depth_time=2026-10-16T21:45:40+00:00, book20_bid_proxy_usdt=32527, book20_ask_proxy_usdt=17224, funding_indicative=-0.000097, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.18%, turnover=19176620. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-16T21:45:01+00:00, last15m_closed_end=2026-10-16T21:45+00:00, prior8high=1.162700, depth_time=2026-10-16T21:45:30+00:00, book20_bid_proxy_usdt=531732, book20_ask_proxy_usdt=278394, funding_indicative=0.000064, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.43%, turnover=22361780. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-16T21:45:01+00:00, last15m_closed_end=2026-10-16T21:45+00:00, prior8high=1.145500, depth_time=2026-10-16T21:45:12+00:00, book20_bid_proxy_usdt=515316, book20_ask_proxy_usdt=549287, funding_indicative=0.000090, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.57%, turnover=23770033. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-16T21:45:01+00:00, last15m_closed_end=2026-10-16T21:45+00:00, prior8high=0.083430, depth_time=2026-10-16T21:45:43+00:00, book20_bid_proxy_usdt=1467473, book20_ask_proxy_usdt=1354434, funding_indicative=-0.000013, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.11%, turnover=20925132. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-16T21:45:01+00:00, last15m_closed_end=2026-10-16T21:45+00:00, prior8high=3.023000, depth_time=2026-10-16T21:45:38+00:00, book20_bid_proxy_usdt=1121883, book20_ask_proxy_usdt=1059508, funding_indicative=0.000098, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.21%, turnover=9192873. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-16T21:45:01+00:00, last15m_closed_end=2026-10-16T21:45+00:00, prior8high=8.745000, depth_time=2026-10-16T21:45:07+00:00, book20_bid_proxy_usdt=290936, book20_ask_proxy_usdt=229440, funding_indicative=-0.000026, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.27%, turnover=117269529. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-16T21:45:01+00:00, last15m_closed_end=2026-10-16T21:45+00:00, prior8high=0.137590, depth_time=2026-10-16T21:45:20+00:00, book20_bid_proxy_usdt=69537, book20_ask_proxy_usdt=61450, funding_indicative=0.000047, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.13%, turnover=14721641. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-16T21:45:01+00:00, last15m_closed_end=2026-10-16T21:45+00:00, prior8high=0.073730, depth_time=2026-10-16T21:45:35+00:00, book20_bid_proxy_usdt=413488, book20_ask_proxy_usdt=181819, funding_indicative=0.000050, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.24%, turnover=22927502. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-16T21:45:01+00:00, last15m_closed_end=2026-10-16T21:45+00:00, prior8high=276.400000, depth_time=2026-10-16T21:45:14+00:00, book20_bid_proxy_usdt=246374, book20_ask_proxy_usdt=110260, funding_indicative=0.000050, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.81%, turnover=82777032. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-16T21:45:01+00:00, last15m_closed_end=2026-10-16T21:45+00:00, prior8high=1153.360000, depth_time=2026-10-16T21:45:10+00:00, book20_bid_proxy_usdt=268298, book20_ask_proxy_usdt=321733, funding_indicative=0.000100, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.88%, turnover=1463855085. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-16T21:45:01+00:00, last15m_closed_end=2026-10-16T21:45+00:00, prior8high=2.113300, depth_time=2026-10-16T21:45:18+00:00, book20_bid_proxy_usdt=44388, book20_ask_proxy_usdt=67227, funding_indicative=0.000050, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.57%, turnover=15984018. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
