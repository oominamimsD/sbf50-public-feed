# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-30T12:15:43Z**
- feed_generated_utc: 2026-10-30T12:15:46+00:00
- source_sha256: `60ea13d47b0e163aaf3c589ba2640f48f63d60d4634a1f2d035c4b15fe711d95`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1194; contracts: 1186; crypto_prefilter: 20; crypto_deep: 15
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-30T12:15+00:00, close=77520.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-30T12:00+00:00, close=77345.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-30T12:00+00:00, close=77345.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.325500|-19.08|-25.94|-13.93|9581730|1.51|
|PYTH_USDT|0.060510|-17.32|-18.42|-12.17|5295528|1.65|
|TIA_USDT|0.462900|-15.71|-18.56|-10.56|20203599|2.16|
|LIT_USDT|2.774100|-14.82|-23.24|-9.67|17537319|0.36|
|CRV_USDT|0.288000|-14.28|-21.58|-9.13|9402201|3.47|
|ENA_USDT|0.185870|-13.11|-6.38|-7.96|115470860|1.08|
|FARTCOIN_USDT|0.118340|-11.94|-17.15|-6.79|15601099|0.84|
|LDO_USDT|0.334400|-11.62|-12.57|-6.47|6355068|2.99|
|INJ_USDT|7.201000|-11.44|-9.21|-6.29|31187234|1.39|
|PENGU_USDT|0.007238|-10.98|-6.34|-5.83|10089778|2.76|
|FET_USDT|0.164800|-10.82|-11.06|-5.67|14150166|6.07|
|ETHFI_USDT|0.609300|-10.33|-8.00|-5.18|5836786|1.64|
|TAO_USDT|232.300000|-10.23|-9.83|-5.08|86888654|0.86|
|TRUMPOFFICIAL_USDT|1.554000|-10.06|-10.89|-4.91|10787049|6.43|
|PUMPFUN_USDT|0.004083|-9.76|-12.73|-4.61|30724796|2.45|
|JUP_USDT|0.255200|-9.43|-17.67|-4.28|6883730|3.92|
|SEI_USDT|0.048590|-9.07|-16.32|-3.92|6925691|2.06|
|ZEC_USDT|1247.300000|-8.11|1.05|-2.96|2181606200|0.72|
|AVAX_USDT|8.389000|-6.83|-8.47|-1.68|34351780|1.19|
|BNB_USDT|702.000000|-6.66|-4.00|-1.51|56091220|1.42|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.325500|1.248100|1.325500|2.79|N|Y/Y|Y/Y|Y|N|
|CRV_USDT|0.288000|0.281300|0.288000|4.43|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.185870|0.184400|0.185760|1.87|N|Y/Y|Y/Y|Y|N|
|ETHFI_USDT|0.609300|0.603900|0.609300|0.85|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.118340|0.116630|0.118360|0.96|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.164800|0.163000|0.164800|0.63|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.201000|7.100000|7.201000|0.35|N|Y/Y|Y/Y|Y|N|
|LDO_USDT|0.334400|0.328800|0.334400|1.39|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|2.774100|2.777900|2.774200|1.30|N|Y/Y|Y/Y|Y|N|
|PENGU_USDT|0.007238|0.007058|0.007238|0.59|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004083|0.004034|0.004087|0.79|N|Y/Y|Y/Y|Y|N|
|PYTH_USDT|0.060510|0.060360|0.060510|0.53|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|232.300000|231.840000|232.290000|0.47|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.462900|0.461700|0.462600|1.31|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.554000|1.545000|1.554000|1.02|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-30T12:14:59+00:00, last15m_closed_end=2026-10-30T12:15+00:00, prior8high=1.549900, depth_time=2026-10-30T12:15:07+00:00, book20_bid_proxy_usdt=8470, book20_ask_proxy_usdt=12200, funding_indicative=0.000046, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-19.08%, turnover=9581730. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CRV_USDT: quote_utc=2026-10-30T12:14:59+00:00, last15m_closed_end=2026-10-30T12:15+00:00, prior8high=0.288000, depth_time=2026-10-30T12:15:16+00:00, book20_bid_proxy_usdt=508094, book20_ask_proxy_usdt=537121, funding_indicative=-0.000220, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-14.28%, turnover=9402201. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-30T12:14:59+00:00, last15m_closed_end=2026-10-30T12:15+00:00, prior8high=0.191700, depth_time=2026-10-30T12:15:19+00:00, book20_bid_proxy_usdt=96168, book20_ask_proxy_usdt=106962, funding_indicative=0.000050, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-13.11%, turnover=115470860. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETHFI_USDT: quote_utc=2026-10-30T12:14:59+00:00, last15m_closed_end=2026-10-30T12:15+00:00, prior8high=0.613800, depth_time=2026-10-30T12:15:34+00:00, book20_bid_proxy_usdt=223952, book20_ask_proxy_usdt=152269, funding_indicative=0.000050, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-10.33%, turnover=5836786. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-30T12:14:59+00:00, last15m_closed_end=2026-10-30T12:15+00:00, prior8high=0.119010, depth_time=2026-10-30T12:15:22+00:00, book20_bid_proxy_usdt=62763, book20_ask_proxy_usdt=45846, funding_indicative=0.000050, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-11.94%, turnover=15601099. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-30T12:14:59+00:00, last15m_closed_end=2026-10-30T12:15+00:00, prior8high=0.166000, depth_time=2026-10-30T12:15:31+00:00, book20_bid_proxy_usdt=1043894, book20_ask_proxy_usdt=734825, funding_indicative=0.000100, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-10.82%, turnover=14150166. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-30T12:14:59+00:00, last15m_closed_end=2026-10-30T12:15+00:00, prior8high=7.256000, depth_time=2026-10-30T12:15:27+00:00, book20_bid_proxy_usdt=286551, book20_ask_proxy_usdt=167124, funding_indicative=0.000098, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-11.44%, turnover=31187234. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LDO_USDT: quote_utc=2026-10-30T12:14:59+00:00, last15m_closed_end=2026-10-30T12:15+00:00, prior8high=0.335300, depth_time=2026-10-30T12:15:23+00:00, book20_bid_proxy_usdt=303465, book20_ask_proxy_usdt=1288591, funding_indicative=0.000077, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-11.62%, turnover=6355068. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-30T12:14:59+00:00, last15m_closed_end=2026-10-30T12:15+00:00, prior8high=2.848700, depth_time=2026-10-30T12:15:14+00:00, book20_bid_proxy_usdt=26148, book20_ask_proxy_usdt=33099, funding_indicative=0.000050, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-14.82%, turnover=17537319. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-30T12:14:59+00:00, last15m_closed_end=2026-10-30T12:15+00:00, prior8high=0.007281, depth_time=2026-10-30T12:15:29+00:00, book20_bid_proxy_usdt=119682, book20_ask_proxy_usdt=71763, funding_indicative=0.000050, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-10.98%, turnover=10089778. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-30T12:14:59+00:00, last15m_closed_end=2026-10-30T12:15+00:00, prior8high=0.004139, depth_time=2026-10-30T12:15:42+00:00, book20_bid_proxy_usdt=1334453, book20_ask_proxy_usdt=1112558, funding_indicative=0.000011, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.76%, turnover=30724796. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PYTH_USDT: quote_utc=2026-10-30T12:14:59+00:00, last15m_closed_end=2026-10-30T12:15+00:00, prior8high=0.061880, depth_time=2026-10-30T12:15:09+00:00, book20_bid_proxy_usdt=219708, book20_ask_proxy_usdt=126806, funding_indicative=-0.000120, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-17.32%, turnover=5295528. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-30T12:14:59+00:00, last15m_closed_end=2026-10-30T12:15+00:00, prior8high=235.330000, depth_time=2026-10-30T12:15:37+00:00, book20_bid_proxy_usdt=40973, book20_ask_proxy_usdt=71314, funding_indicative=0.000050, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-10.23%, turnover=86888654. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-30T12:14:59+00:00, last15m_closed_end=2026-10-30T12:15+00:00, prior8high=0.470200, depth_time=2026-10-30T12:15:12+00:00, book20_bid_proxy_usdt=209332, book20_ask_proxy_usdt=130672, funding_indicative=0.000024, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-15.71%, turnover=20203599. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-10-30T12:14:59+00:00, last15m_closed_end=2026-10-30T12:15+00:00, prior8high=1.573000, depth_time=2026-10-30T12:15:37+00:00, book20_bid_proxy_usdt=1488219, book20_ask_proxy_usdt=1441014, funding_indicative=-0.000021, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-10.06%, turnover=10787049. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
