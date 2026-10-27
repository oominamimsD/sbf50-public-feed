# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T03:15:40Z**
- feed_generated_utc: 2026-10-27T03:15:44+00:00
- source_sha256: `19d1c13687323401904d92091659bee54244d42d8c401ab32331fd1cb5b2f222`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 16; crypto_deep: 15
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T03:15+00:00, close=79661.8, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-27T03:00+00:00, close=79789.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-27T00:00+00:00, close=80115.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZRO_USDT|1.607200|-5.85|-15.49|-4.94|5107564|0.62|
|PUMPFUN_USDT|0.004120|-4.80|-7.54|-3.89|21383159|2.43|
|NEAR_USDT|4.401000|-3.76|-10.25|-2.85|103310156|2.27|
|ONDO_USDT|0.405000|-3.29|-6.38|-2.38|22425555|4.94|
|FET_USDT|0.170900|-3.22|-9.57|-2.31|6353454|5.85|
|DOT_USDT|0.989700|-3.21|-13.69|-2.30|10825531|1.01|
|FILECOIN_USDT|0.893100|-2.99|-11.74|-2.08|6396189|1.12|
|AAVE_USDT|132.700000|-2.94|-9.86|-2.03|26064073|0.75|
|ICP_USDT|2.563000|-2.54|-10.16|-1.63|5168544|3.90|
|ENA_USDT|0.205170|-2.47|9.17|-1.56|95573612|0.49|
|AVAX_USDT|8.786000|-2.34|-8.11|-1.43|64738846|1.14|
|WLD_USDT|0.434700|-2.31|-14.14|-1.40|71147270|2.30|
|ARB_USDT|0.166070|-2.30|-15.11|-1.39|20063869|1.21|
|TAO_USDT|247.750000|-2.27|-7.65|-1.36|46044897|0.40|
|PENGU_USDT|0.007405|-2.23|-1.14|-1.32|5506550|1.35|
|LINK_USDT|11.290000|-2.06|-5.46|-1.15|107773416|1.77|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|132.700000|132.850000|132.700000|1.18|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.166070|0.166980|0.166020|1.50|Y|Y/Y|Y/Y|Y|Y|
|AVAX_USDT|8.786000|8.815000|8.786000|6.66|Y|Y/Y|Y/Y|Y|Y|
|DOT_USDT|0.989700|0.994400|0.989700|4.15|Y|Y/Y|Y/Y|Y|Y|
|ENA_USDT|0.205170|0.205120|0.205170|1.87|N|Y/N|N/N|Y|N|
|FET_USDT|0.170900|0.172200|0.171000|10.38|Y|Y/Y|Y/Y|Y|Y|
|FILECOIN_USDT|0.893100|0.899200|0.893000|3.13|Y|Y/Y|Y/Y|Y|Y|
|ICP_USDT|2.563000|2.577000|2.562000|2.08|Y|Y/Y|Y/Y|Y|Y|
|NEAR_USDT|4.401000|4.431000|4.401000|1.16|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.405000|0.407200|0.404900|2.19|Y|Y/Y|N/N|Y|N|
|PENGU_USDT|0.007405|0.007438|0.007405|5.87|Y|Y/Y|Y/Y|Y|Y|
|PUMPFUN_USDT|0.004120|0.004187|0.004120|14.46|Y|Y/Y|Y/Y|Y|Y|
|TAO_USDT|247.750000|248.330000|247.750000|1.13|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.434700|0.436900|0.434700|5.03|Y|Y/Y|Y/Y|Y|Y|
|ZRO_USDT|1.607200|1.607900|1.607200|0.38|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T03:15:01+00:00, last15m_closed_end=2026-10-27T03:15+00:00, prior8high=135.600000, depth_time=2026-10-27T03:15:22+00:00, book20_bid_proxy_usdt=723020, book20_ask_proxy_usdt=470759, funding_indicative=0.000065, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.94%, turnover=26064073. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-27T03:15:01+00:00, last15m_closed_end=2026-10-27T03:15+00:00, prior8high=0.169010, depth_time=2026-10-27T03:15:35+00:00, book20_bid_proxy_usdt=54604, book20_ask_proxy_usdt=95185, funding_indicative=-0.000025, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.30%, turnover=20063869. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-27T03:15:01+00:00, last15m_closed_end=2026-10-27T03:15+00:00, prior8high=8.953000, depth_time=2026-10-27T03:15:30+00:00, book20_bid_proxy_usdt=1847326, book20_ask_proxy_usdt=1375624, funding_indicative=0.000027, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.34%, turnover=64738846. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T03:15:01+00:00, last15m_closed_end=2026-10-27T03:15+00:00, prior8high=1.008000, depth_time=2026-10-27T03:15:18+00:00, book20_bid_proxy_usdt=363942, book20_ask_proxy_usdt=417275, funding_indicative=-0.000099, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.21%, turnover=10825531. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-27T03:15:01+00:00, last15m_closed_end=2026-10-27T03:15+00:00, prior8high=0.209820, depth_time=2026-10-27T03:15:27+00:00, book20_bid_proxy_usdt=148620, book20_ask_proxy_usdt=128850, funding_indicative=0.000050, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.47%, turnover=95573612. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-27T03:15:01+00:00, last15m_closed_end=2026-10-27T03:15+00:00, prior8high=0.175500, depth_time=2026-10-27T03:15:16+00:00, book20_bid_proxy_usdt=2049436, book20_ask_proxy_usdt=1048510, funding_indicative=0.000100, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.22%, turnover=6353454. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T03:15:01+00:00, last15m_closed_end=2026-10-27T03:15+00:00, prior8high=0.912000, depth_time=2026-10-27T03:15:21+00:00, book20_bid_proxy_usdt=1001298, book20_ask_proxy_usdt=1213380, funding_indicative=0.000013, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.99%, turnover=6396189. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-27T03:15:01+00:00, last15m_closed_end=2026-10-27T03:15+00:00, prior8high=2.624000, depth_time=2026-10-27T03:15:26+00:00, book20_bid_proxy_usdt=1135632, book20_ask_proxy_usdt=1030868, funding_indicative=0.000095, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.54%, turnover=5168544. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-27T03:15:01+00:00, last15m_closed_end=2026-10-27T03:15+00:00, prior8high=4.520000, depth_time=2026-10-27T03:15:12+00:00, book20_bid_proxy_usdt=3199359, book20_ask_proxy_usdt=3224396, funding_indicative=0.000060, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.76%, turnover=103310156. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-27T03:15:01+00:00, last15m_closed_end=2026-10-27T03:15+00:00, prior8high=0.413700, depth_time=2026-10-27T03:15:14+00:00, book20_bid_proxy_usdt=2492817, book20_ask_proxy_usdt=3242516, funding_indicative=0.000029, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.29%, turnover=22425555. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-27T03:15:01+00:00, last15m_closed_end=2026-10-27T03:15+00:00, prior8high=0.007532, depth_time=2026-10-27T03:15:39+00:00, book20_bid_proxy_usdt=230264, book20_ask_proxy_usdt=203535, funding_indicative=-0.000024, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.23%, turnover=5506550. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-27T03:15:01+00:00, last15m_closed_end=2026-10-27T03:15+00:00, prior8high=0.004305, depth_time=2026-10-27T03:15:09+00:00, book20_bid_proxy_usdt=1692168, book20_ask_proxy_usdt=1935901, funding_indicative=0.000040, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.80%, turnover=21383159. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-27T03:15:01+00:00, last15m_closed_end=2026-10-27T03:15+00:00, prior8high=251.550000, depth_time=2026-10-27T03:15:37+00:00, book20_bid_proxy_usdt=114660, book20_ask_proxy_usdt=98300, funding_indicative=0.000050, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.27%, turnover=46044897. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-27T03:15:01+00:00, last15m_closed_end=2026-10-27T03:15+00:00, prior8high=0.445000, depth_time=2026-10-27T03:15:32+00:00, book20_bid_proxy_usdt=3365698, book20_ask_proxy_usdt=3063304, funding_indicative=-0.000182, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.31%, turnover=71147270. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-27T03:15:01+00:00, last15m_closed_end=2026-10-27T03:15+00:00, prior8high=1.634200, depth_time=2026-10-27T03:15:07+00:00, book20_bid_proxy_usdt=86748, book20_ask_proxy_usdt=55689, funding_indicative=0.000050, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.85%, turnover=5107564. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
