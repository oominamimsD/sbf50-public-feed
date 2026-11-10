# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T15:15:43Z**
- feed_generated_utc: 2026-11-10T15:15:45+00:00
- source_sha256: `87f56bc294f296c7f15b864985f31e902d61b0881176bba523537da58c6009a1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 16; crypto_deep: 15
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T15:15+00:00, close=74443.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-10T15:00+00:00, close=74373.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T12:00+00:00, close=74389.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.006163|-39.16|42.76|-37.75|23567066|3.25|
|AKE_USDT|0.003000|-38.73|-45.47|-37.32|13952349|3.32|
|ARB_USDT|0.164340|-10.70|3.14|-9.29|38328467|0.61|
|ANTHROPIC_USDT|1293.210000|-9.48|-22.96|-8.07|7594805|1.24|
|XMR_USDT|555.870000|-7.94|-8.16|-6.53|6425324|0.18|
|QNT_USDT|184.920000|-7.55|-8.65|-6.14|36796827|0.54|
|AVAX_USDT|8.358000|-7.03|-1.68|-5.62|40586198|1.20|
|AAVE_USDT|125.670000|-5.75|-3.74|-4.34|10511411|1.59|
|XRP_USDT|1.061200|-4.73|-14.99|-3.32|291759133|1.89|
|SOL_USDT|84.500000|-3.85|-9.63|-2.44|674034811|1.18|
|ETH_USDT|2075.460000|-3.32|-8.66|-1.91|1433755503|0.05|
|HYPE_USDT|73.931000|-3.12|-13.74|-1.71|41330337|0.14|
|ADA_USDT|0.177500|-2.68|-6.48|-1.27|21468271|5.63|
|LINK_USDT|10.503000|-2.61|-6.50|-1.20|100370733|1.90|
|HBAR_USDT|0.066780|-2.46|-5.23|-1.05|8829636|1.50|
|XLM_USDT|0.145980|-2.45|-12.89|-1.04|22685796|0.69|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|125.670000|122.640000|125.670000|2.74|N|Y/Y|Y/Y|Y|N|
|ADA_USDT|0.177500|0.173700|0.177500|2.72|N|Y/Y|Y/Y|Y|N|
|AKE_USDT|0.003000|0.002383|0.003021|5.14|N|Y/Y|Y/Y|Y|N|
|ANTHROPIC_USDT|1293.210000|1277.520000|1293.470000|0.66|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.164340|0.161200|0.164380|2.45|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.358000|8.228000|8.357000|10.34|N|Y/Y|Y/N|Y|N|
|ETH_USDT|2075.460000|2030.110000|2075.990000|2.68|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.066780|0.065660|0.066780|0.66|N|N/Y|Y/Y|Y|N|
|HYPE_USDT|73.931000|72.149000|73.931000|1.98|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.006163|0.005819|0.006163|2.15|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|10.503000|10.302000|10.504000|1.68|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|184.920000|178.810000|184.920000|1.07|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|84.500000|82.420000|84.500000|1.70|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|555.870000|544.080000|555.870000|4.43|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.061200|1.048300|1.061300|1.32|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-10T15:15:01+00:00, last15m_closed_end=2026-11-10T15:15+00:00, prior8high=125.920000, depth_time=2026-11-10T15:15:24+00:00, book20_bid_proxy_usdt=284479, book20_ask_proxy_usdt=462182, funding_indicative=0.000027, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.75%, turnover=10511411. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ADA_USDT: quote_utc=2026-11-10T15:15:01+00:00, last15m_closed_end=2026-11-10T15:15+00:00, prior8high=0.177900, depth_time=2026-11-10T15:15:37+00:00, book20_bid_proxy_usdt=9713128, book20_ask_proxy_usdt=10260788, funding_indicative=0.000064, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.68%, turnover=21468271. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-10T15:15:01+00:00, last15m_closed_end=2026-11-10T15:15+00:00, prior8high=0.002815, depth_time=2026-11-10T15:15:10+00:00, book20_bid_proxy_usdt=23128, book20_ask_proxy_usdt=25650, funding_indicative=0.000050, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=4, 24h_change=-38.73%, turnover=13952349. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ANTHROPIC_USDT: quote_utc=2026-11-10T15:15:01+00:00, last15m_closed_end=2026-11-10T15:15+00:00, prior8high=1309.180000, depth_time=2026-11-10T15:15:14+00:00, book20_bid_proxy_usdt=6633, book20_ask_proxy_usdt=14645, funding_indicative=0.000050, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-9.48%, turnover=7594805. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T15:15:01+00:00, last15m_closed_end=2026-11-10T15:15+00:00, prior8high=0.166050, depth_time=2026-11-10T15:15:11+00:00, book20_bid_proxy_usdt=61165, book20_ask_proxy_usdt=56066, funding_indicative=-0.000128, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-10.70%, turnover=38328467. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-11-10T15:15:01+00:00, last15m_closed_end=2026-11-10T15:15+00:00, prior8high=8.428000, depth_time=2026-11-10T15:15:22+00:00, book20_bid_proxy_usdt=625838, book20_ask_proxy_usdt=567140, funding_indicative=-0.000022, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-7.03%, turnover=40586198. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETH_USDT: quote_utc=2026-11-10T15:15:01+00:00, last15m_closed_end=2026-11-10T15:15+00:00, prior8high=2103.900000, depth_time=2026-11-10T15:15:32+00:00, book20_bid_proxy_usdt=2071787, book20_ask_proxy_usdt=2866053, funding_indicative=0.000016, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.32%, turnover=1433755503. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-11-10T15:15:01+00:00, last15m_closed_end=2026-11-10T15:15+00:00, prior8high=0.067050, depth_time=2026-11-10T15:15:40+00:00, book20_bid_proxy_usdt=610321, book20_ask_proxy_usdt=573473, funding_indicative=0.000082, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.46%, turnover=8829636. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-10T15:15:01+00:00, last15m_closed_end=2026-11-10T15:15+00:00, prior8high=74.000000, depth_time=2026-11-10T15:15:34+00:00, book20_bid_proxy_usdt=43334, book20_ask_proxy_usdt=56672, funding_indicative=0.000050, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.12%, turnover=41330337. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T15:15:01+00:00, last15m_closed_end=2026-11-10T15:15+00:00, prior8high=0.008172, depth_time=2026-11-10T15:15:06+00:00, book20_bid_proxy_usdt=13787, book20_ask_proxy_usdt=34479, funding_indicative=0.000472, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=4, 24h_change=-39.16%, turnover=23567066. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-10T15:15:01+00:00, last15m_closed_end=2026-11-10T15:15+00:00, prior8high=10.578000, depth_time=2026-11-10T15:15:40+00:00, book20_bid_proxy_usdt=253726, book20_ask_proxy_usdt=184340, funding_indicative=0.000100, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.61%, turnover=100370733. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T15:15:01+00:00, last15m_closed_end=2026-11-10T15:15+00:00, prior8high=187.790000, depth_time=2026-11-10T15:15:19+00:00, book20_bid_proxy_usdt=82564, book20_ask_proxy_usdt=53577, funding_indicative=-0.000081, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-7.55%, turnover=36796827. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-10T15:15:01+00:00, last15m_closed_end=2026-11-10T15:15+00:00, prior8high=85.210000, depth_time=2026-11-10T15:15:29+00:00, book20_bid_proxy_usdt=13449440, book20_ask_proxy_usdt=12594722, funding_indicative=0.000038, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.85%, turnover=674034811. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-11-10T15:15:01+00:00, last15m_closed_end=2026-11-10T15:15+00:00, prior8high=555.790000, depth_time=2026-11-10T15:15:17+00:00, book20_bid_proxy_usdt=44795, book20_ask_proxy_usdt=4677, funding_indicative=0.000100, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-7.94%, turnover=6425324. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-10T15:15:01+00:00, last15m_closed_end=2026-11-10T15:15+00:00, prior8high=1.082900, depth_time=2026-11-10T15:15:27+00:00, book20_bid_proxy_usdt=3099934, book20_ask_proxy_usdt=3097479, funding_indicative=0.000065, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.73%, turnover=291759133. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
