# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T10:00:40Z**
- feed_generated_utc: 2026-11-11T10:00:42+00:00
- source_sha256: `e8d4d13946642f4fdc7b74156aeeb3e60dfb5ee1cba1f1c575c47927975dde5e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 75/75 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 14; crypto_deep: 14
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T10:00+00:00, close=73761.1, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-11-11T10:00+00:00, close=73761.1, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-11-11T08:00+00:00, close=74064.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|INIT_USDT|0.183000|-27.07|36.07|-27.87|68125462|1.09|
|AKE_USDT|0.002506|-14.00|-39.70|-14.80|8822333|3.99|
|ONE_USDT|0.001553|-11.47|39.11|-12.27|10811488|0.64|
|ZEC_USDT|980.790000|-10.29|-18.52|-11.09|2136618143|0.10|
|UNI_USDT|6.397000|-9.45|-13.00|-10.25|40958216|1.56|
|PEPE_USDT|0.000005|-9.27|3.04|-10.07|78313299|0.20|
|BTW_USDT|1.087400|-9.27|2.69|-10.07|5943811|0.92|
|JCT_USDT|0.005621|-6.76|34.53|-7.56|19866384|3.56|
|DASH_USDT|43.560000|-6.42|-5.59|-7.22|16918045|2.29|
|VVV_USDT|18.970000|-4.27|-15.16|-5.07|5399043|2.64|
|ENA_USDT|0.151340|-3.46|-12.10|-4.26|36652162|0.66|
|ARB_USDT|0.159480|-3.38|-0.25|-4.18|28395088|0.63|
|HBAR_USDT|0.065710|-1.80|-6.16|-2.60|6279478|1.52|
|QNT_USDT|179.210000|-0.82|-8.29|-1.62|44723533|0.56|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002506|0.002495|0.002496|0.75|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.159480|0.157810|0.159480|0.44|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.087400|1.086400|1.088000|0.87|N|Y/Y|Y/N|Y|N|
|DASH_USDT|43.560000|42.990000|43.560000|0.75|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.151340|0.149410|0.151340|0.67|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.065710|0.065080|0.065710|1.09|N|Y/Y|Y/Y|Y|N|
|INIT_USDT|0.183000|0.174240|0.184590|0.96|N|Y/Y|N/N|Y|N|
|JCT_USDT|0.005621|0.005340|0.005621|0.39|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001553|0.001547|0.001553|0.45|N|Y/Y|Y/N|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|1.26|N|Y/Y|N/N|Y|N|
|QNT_USDT|179.210000|176.850000|179.200000|0.54|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.397000|6.336000|6.397000|0.96|N|Y/Y|Y/Y|Y|N|
|VVV_USDT|18.970000|18.772000|18.970000|1.04|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|980.790000|960.750000|980.500000|0.42|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-11T10:00:01+00:00, last15m_closed_end=2026-11-11T10:00+00:00, prior8high=0.002630, depth_time=2026-11-11T10:00:09+00:00, book20_bid_proxy_usdt=43764, book20_ask_proxy_usdt=44209, funding_indicative=0.000050, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-14.00%, turnover=8822333. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-11T10:00:01+00:00, last15m_closed_end=2026-11-11T10:00+00:00, prior8high=0.160150, depth_time=2026-11-11T10:00:33+00:00, book20_bid_proxy_usdt=49703, book20_ask_proxy_usdt=41175, funding_indicative=-0.000019, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.38%, turnover=28395088. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-11T10:00:02+00:00, last15m_closed_end=2026-11-11T10:00+00:00, prior8high=1.144300, depth_time=2026-11-11T10:00:20+00:00, book20_bid_proxy_usdt=32348, book20_ask_proxy_usdt=18275, funding_indicative=-0.000515, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-9.27%, turnover=5943811. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-11T10:00:02+00:00, last15m_closed_end=2026-11-11T10:00+00:00, prior8high=44.240000, depth_time=2026-11-11T10:00:23+00:00, book20_bid_proxy_usdt=593009, book20_ask_proxy_usdt=561514, funding_indicative=-0.000080, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.42%, turnover=16918045. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-11T10:00:01+00:00, last15m_closed_end=2026-11-11T10:00+00:00, prior8high=0.153710, depth_time=2026-11-11T10:00:32+00:00, book20_bid_proxy_usdt=225100, book20_ask_proxy_usdt=212693, funding_indicative=0.000050, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.46%, turnover=36652162. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-11-11T10:00:02+00:00, last15m_closed_end=2026-11-11T10:00+00:00, prior8high=0.065780, depth_time=2026-11-11T10:00:34+00:00, book20_bid_proxy_usdt=690896, book20_ask_proxy_usdt=838253, funding_indicative=0.000035, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.80%, turnover=6279478. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INIT_USDT: quote_utc=2026-11-11T10:00:01+00:00, last15m_closed_end=2026-11-11T10:00+00:00, prior8high=0.225680, depth_time=2026-11-11T10:00:07+00:00, book20_bid_proxy_usdt=11419, book20_ask_proxy_usdt=15653, funding_indicative=-0.009974, next_funding_utc=2026-11-11T11:00:00+00:00, funding_cycle_h=1, 24h_change=-27.07%, turnover=68125462. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-11T10:00:01+00:00, last15m_closed_end=2026-11-11T10:00+00:00, prior8high=0.006949, depth_time=2026-11-11T10:00:24+00:00, book20_bid_proxy_usdt=30763, book20_ask_proxy_usdt=29753, funding_indicative=0.000050, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.76%, turnover=19866384. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-11T10:00:01+00:00, last15m_closed_end=2026-11-11T10:00+00:00, prior8high=0.001634, depth_time=2026-11-11T10:00:11+00:00, book20_bid_proxy_usdt=17474, book20_ask_proxy_usdt=49121, funding_indicative=-0.000860, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-11.47%, turnover=10811488. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-11T10:00:01+00:00, last15m_closed_end=2026-11-11T10:00+00:00, prior8high=0.000005, depth_time=2026-11-11T10:00:18+00:00, book20_bid_proxy_usdt=35242, book20_ask_proxy_usdt=29011, funding_indicative=-0.000133, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-9.27%, turnover=78313299. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-11T10:00:01+00:00, last15m_closed_end=2026-11-11T10:00+00:00, prior8high=179.710000, depth_time=2026-11-11T10:00:37+00:00, book20_bid_proxy_usdt=64673, book20_ask_proxy_usdt=54379, funding_indicative=-0.000169, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.82%, turnover=44723533. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T10:00:01+00:00, last15m_closed_end=2026-11-11T10:00+00:00, prior8high=6.473000, depth_time=2026-11-11T10:00:15+00:00, book20_bid_proxy_usdt=3542092, book20_ask_proxy_usdt=2897100, funding_indicative=-0.000007, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-9.45%, turnover=40958216. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-11T10:00:02+00:00, last15m_closed_end=2026-11-11T10:00+00:00, prior8high=19.191000, depth_time=2026-11-11T10:00:27+00:00, book20_bid_proxy_usdt=18347, book20_ask_proxy_usdt=26148, funding_indicative=0.000009, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.27%, turnover=5399043. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T10:00:01+00:00, last15m_closed_end=2026-11-11T10:00+00:00, prior8high=1003.100000, depth_time=2026-11-11T10:00:14+00:00, book20_bid_proxy_usdt=351596, book20_ask_proxy_usdt=186518, funding_indicative=0.000020, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-10.29%, turnover=2136618143. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
