# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-01T22:49:00Z**
- feed_generated_utc: 2026-11-01T22:49:18+00:00
- source_sha256: `259330370c067388d083b8cbc7536c2b58577e6b09ec09b0f2977ae2ba9521fa`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1197; contracts: 1189; crypto_prefilter: 22; crypto_deep: 15
- snapshot_age_at_feed_build: 0.29 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-01T22:45+00:00, close=77781.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-01T22:00+00:00, close=77855.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-01T20:00+00:00, close=77770.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.162500|-18.75|-35.12|-18.55|6584784|6.15|
|APR_USDT|0.056840|-8.20|37.59|-8.00|7018047|5.28|
|ZRO_USDT|1.812700|-4.49|3.52|-4.29|10236609|0.55|
|BTW_USDT|1.083100|-3.82|-34.70|-3.62|5667040|1.85|
|LIT_USDT|3.123300|-3.30|-1.73|-3.10|28831509|0.32|
|XPL_USDT|0.070840|-3.05|-2.47|-2.85|14187156|1.41|
|LINK_USDT|11.276000|-2.91|-1.27|-2.71|128225689|1.77|
|AAVE_USDT|133.830000|-2.64|-1.93|-2.44|29412066|2.24|
|PUMPFUN_USDT|0.004114|-2.46|-3.99|-2.26|6680248|2.43|
|ENA_USDT|0.180850|-2.32|-10.92|-2.12|48671528|0.55|
|LSK_USDT|0.202050|-1.95|23.80|-1.75|11659451|0.99|
|NEAR_USDT|4.247000|-1.93|-6.53|-1.73|51397127|2.35|
|AKE_USDT|0.008989|-1.86|-70.55|-1.66|6322403|5.57|
|ARB_USDT|0.163230|-1.77|-2.49|-1.57|10816198|0.61|
|AVAX_USDT|8.618000|-1.68|-3.19|-1.48|27515122|1.16|
|DASH_USDT|47.790000|-1.66|-8.81|-1.46|5209873|2.09|
|ZEC_USDT|1218.150000|-1.59|0.71|-1.39|983224673|0.08|
|ONDO_USDT|0.400200|-1.52|-1.42|-1.32|16724109|2.50|
|UNI_USDT|7.149000|-1.47|4.25|-1.27|15444254|1.40|
|WLD_USDT|0.389900|-1.46|-14.60|-1.26|36874918|2.57|
|OP_USDT|0.112700|-1.37|1.08|-1.17|11067399|0.89|
|INJ_USDT|7.104000|-1.22|-7.78|-1.02|19631745|1.41|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|133.830000|133.480000|133.770000|0.34|N|Y/Y|N/N|Y|N|
|AKE_USDT|0.008989|0.008844|0.008981|1.05|N|Y/Y|Y/Y|Y|N|
|APR_USDT|0.056840|0.057040|0.056740|1.36|Y|Y/Y|N/N|Y|N|
|ARB_USDT|0.163230|0.162260|0.163170|0.31|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.618000|8.582000|8.620000|2.66|N|Y/Y|Y/N|Y|N|
|BTW_USDT|1.083100|1.060700|1.080600|1.34|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.180850|0.180520|0.180970|0.41|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|11.276000|11.234000|11.280000|0.54|N|Y/Y|Y/N|Y|N|
|LIT_USDT|3.123300|3.115200|3.123400|1.02|N|N/N|N/N|Y|N|
|LSK_USDT|0.202050|0.203070|0.202610|1.05|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.247000|4.240000|4.251000|2.36|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004114|0.004091|0.004114|1.15|N|Y/Y|Y/N|Y|N|
|UAI_USDT|0.162500|0.160300|0.162600|0.25|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.070840|0.070440|0.070780|0.80|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.812700|1.790400|1.811900|0.23|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-01T22:46:32+00:00, last15m_closed_end=2026-11-01T22:45+00:00, prior8high=134.660000, depth_time=2026-11-01T22:47:31+00:00, book20_bid_proxy_usdt=255250, book20_ask_proxy_usdt=251999, funding_indicative=0.000100, next_funding_utc=2026-11-02T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.64%, turnover=29412066. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-01T22:46:33+00:00, last15m_closed_end=2026-11-01T22:45+00:00, prior8high=0.009308, depth_time=2026-11-01T22:48:44+00:00, book20_bid_proxy_usdt=11816, book20_ask_proxy_usdt=13694, funding_indicative=-0.003149, next_funding_utc=2026-11-02T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.86%, turnover=6322403. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APR_USDT: quote_utc=2026-11-01T22:46:33+00:00, last15m_closed_end=2026-11-01T22:45+00:00, prior8high=0.059330, depth_time=2026-11-01T22:46:48+00:00, book20_bid_proxy_usdt=43032, book20_ask_proxy_usdt=47338, funding_indicative=0.000054, next_funding_utc=2026-11-02T00:00:00+00:00, funding_cycle_h=4, 24h_change=-8.20%, turnover=7018047. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-01T22:46:33+00:00, last15m_closed_end=2026-11-01T22:45+00:00, prior8high=0.164280, depth_time=2026-11-01T22:48:52+00:00, book20_bid_proxy_usdt=78141, book20_ask_proxy_usdt=58966, funding_indicative=0.000100, next_funding_utc=2026-11-02T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.77%, turnover=10816198. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-11-01T22:46:33+00:00, last15m_closed_end=2026-11-01T22:45+00:00, prior8high=8.698000, depth_time=2026-11-01T22:48:57+00:00, book20_bid_proxy_usdt=1818986, book20_ask_proxy_usdt=2083269, funding_indicative=0.000100, next_funding_utc=2026-11-02T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.68%, turnover=27515122. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-01T22:46:33+00:00, last15m_closed_end=2026-11-01T22:45+00:00, prior8high=1.135900, depth_time=2026-11-01T22:47:05+00:00, book20_bid_proxy_usdt=14068, book20_ask_proxy_usdt=20284, funding_indicative=0.000050, next_funding_utc=2026-11-02T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.82%, turnover=5667040. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-01T22:46:33+00:00, last15m_closed_end=2026-11-01T22:45+00:00, prior8high=0.182980, depth_time=2026-11-01T22:47:40+00:00, book20_bid_proxy_usdt=99397, book20_ask_proxy_usdt=245566, funding_indicative=0.000050, next_funding_utc=2026-11-02T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.32%, turnover=48671528. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-01T22:46:33+00:00, last15m_closed_end=2026-11-01T22:45+00:00, prior8high=11.433000, depth_time=2026-11-01T22:47:27+00:00, book20_bid_proxy_usdt=418728, book20_ask_proxy_usdt=359367, funding_indicative=0.000100, next_funding_utc=2026-11-02T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.91%, turnover=128225689. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-01T22:46:33+00:00, last15m_closed_end=2026-11-01T22:45+00:00, prior8high=3.210500, depth_time=2026-11-01T22:47:16+00:00, book20_bid_proxy_usdt=32409, book20_ask_proxy_usdt=42849, funding_indicative=0.000050, next_funding_utc=2026-11-02T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.30%, turnover=28831509. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LSK_USDT: quote_utc=2026-11-01T22:46:32+00:00, last15m_closed_end=2026-11-01T22:45+00:00, prior8high=0.207500, depth_time=2026-11-01T22:48:02+00:00, book20_bid_proxy_usdt=14724, book20_ask_proxy_usdt=10288, funding_indicative=-0.002698, next_funding_utc=2026-11-02T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.95%, turnover=11659451. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-01T22:46:32+00:00, last15m_closed_end=2026-11-01T22:45+00:00, prior8high=4.312000, depth_time=2026-11-01T22:48:33+00:00, book20_bid_proxy_usdt=3715373, book20_ask_proxy_usdt=3901569, funding_indicative=0.000100, next_funding_utc=2026-11-02T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.93%, turnover=51397127. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-01T22:46:33+00:00, last15m_closed_end=2026-11-01T22:45+00:00, prior8high=0.004173, depth_time=2026-11-01T22:47:33+00:00, book20_bid_proxy_usdt=1952253, book20_ask_proxy_usdt=1608090, funding_indicative=0.000050, next_funding_utc=2026-11-02T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.46%, turnover=6680248. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-01T22:46:33+00:00, last15m_closed_end=2026-11-01T22:45+00:00, prior8high=0.165500, depth_time=2026-11-01T22:46:45+00:00, book20_bid_proxy_usdt=107799, book20_ask_proxy_usdt=81930, funding_indicative=0.000016, next_funding_utc=2026-11-02T00:00:00+00:00, funding_cycle_h=4, 24h_change=-18.75%, turnover=6584784. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-01T22:46:33+00:00, last15m_closed_end=2026-11-01T22:45+00:00, prior8high=0.071630, depth_time=2026-11-01T22:47:21+00:00, book20_bid_proxy_usdt=290697, book20_ask_proxy_usdt=420303, funding_indicative=0.000050, next_funding_utc=2026-11-02T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.05%, turnover=14187156. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-01T22:46:32+00:00, last15m_closed_end=2026-11-01T22:45+00:00, prior8high=1.826300, depth_time=2026-11-01T22:46:55+00:00, book20_bid_proxy_usdt=66969, book20_ask_proxy_usdt=24409, funding_indicative=0.000050, next_funding_utc=2026-11-02T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.49%, turnover=10236609. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
