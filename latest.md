# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T07:15:34Z**
- feed_generated_utc: 2026-11-11T07:15:35+00:00
- source_sha256: `11ec73326de00ecdfa64ae08dbdb548983d0e62c6084e351922f2239002bc070`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T07:15+00:00, close=73569.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-11T07:00+00:00, close=73586.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-11T04:00+00:00, close=73740.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|INIT_USDT|0.202520|-19.29|50.59|-19.82|67167162|1.98|
|ZEC_USDT|971.730000|-11.12|-19.27|-11.65|2168116596|0.10|
|AKE_USDT|0.002663|-8.61|-35.92|-9.14|9195996|3.75|
|ONE_USDT|0.001662|-7.38|48.81|-7.91|12294783|0.60|
|UNI_USDT|6.391000|-6.42|-13.08|-6.95|38728070|3.13|
|DASH_USDT|43.420000|-3.81|-5.89|-4.34|15331111|2.30|
|ARB_USDT|0.157380|-2.47|-1.56|-3.00|31401773|0.64|
|DOT_USDT|0.826400|-1.81|-12.32|-2.34|8460235|1.21|
|QNT_USDT|177.740000|-1.63|-9.04|-2.16|45861808|1.69|
|VVV_USDT|18.943000|-1.53|-15.28|-2.06|5402068|0.53|
|HBAR_USDT|0.065010|-1.17|-7.16|-1.70|6061234|1.54|
|AAVE_USDT|122.050000|-0.61|-4.98|-1.14|10264780|0.82|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|122.050000|122.390000|122.050000|1.02|N|Y/Y|Y/Y|Y|N|
|AKE_USDT|0.002663|0.002607|0.002663|1.94|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.157380|0.158600|0.157380|2.05|Y|Y/Y|Y/Y|Y|Y|
|DASH_USDT|43.420000|43.490000|43.420000|0.58|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.826400|0.831700|0.826300|4.62|Y|Y/Y|Y/Y|Y|Y|
|HBAR_USDT|0.065010|0.065120|0.065010|6.22|Y|Y/Y|Y/Y|Y|Y|
|INIT_USDT|0.202520|0.207580|0.202520|2.46|Y|Y/N|N/N|Y|N|
|ONE_USDT|0.001662|0.001655|0.001663|1.10|N|Y/Y|N/N|Y|N|
|QNT_USDT|177.740000|178.300000|177.660000|1.14|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.391000|6.437000|6.391000|2.22|Y|Y/Y|Y/Y|Y|Y|
|VVV_USDT|18.943000|18.910000|18.943000|2.49|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|971.730000|977.100000|971.670000|1.14|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-11T07:15:02+00:00, last15m_closed_end=2026-11-11T07:15+00:00, prior8high=124.420000, depth_time=2026-11-11T07:15:30+00:00, book20_bid_proxy_usdt=569288, book20_ask_proxy_usdt=394260, funding_indicative=0.000048, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.61%, turnover=10264780. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-11T07:15:02+00:00, last15m_closed_end=2026-11-11T07:15+00:00, prior8high=0.002864, depth_time=2026-11-11T07:15:07+00:00, book20_bid_proxy_usdt=47318, book20_ask_proxy_usdt=45358, funding_indicative=0.000050, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=4, 24h_change=-8.61%, turnover=9195996. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-11T07:15:02+00:00, last15m_closed_end=2026-11-11T07:15+00:00, prior8high=0.163800, depth_time=2026-11-11T07:15:19+00:00, book20_bid_proxy_usdt=32398, book20_ask_proxy_usdt=81374, funding_indicative=0.000002, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.47%, turnover=31401773. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-11T07:15:02+00:00, last15m_closed_end=2026-11-11T07:15+00:00, prior8high=45.400000, depth_time=2026-11-11T07:15:18+00:00, book20_bid_proxy_usdt=666693, book20_ask_proxy_usdt=729069, funding_indicative=-0.000160, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.81%, turnover=15331111. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-11T07:15:02+00:00, last15m_closed_end=2026-11-11T07:15+00:00, prior8high=0.845900, depth_time=2026-11-11T07:15:21+00:00, book20_bid_proxy_usdt=455343, book20_ask_proxy_usdt=591606, funding_indicative=0.000035, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.81%, turnover=8460235. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-11-11T07:15:02+00:00, last15m_closed_end=2026-11-11T07:15+00:00, prior8high=0.065870, depth_time=2026-11-11T07:15:30+00:00, book20_bid_proxy_usdt=733395, book20_ask_proxy_usdt=812148, funding_indicative=-0.000009, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.17%, turnover=6061234. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INIT_USDT: quote_utc=2026-11-11T07:15:01+00:00, last15m_closed_end=2026-11-11T07:15+00:00, prior8high=0.299550, depth_time=2026-11-11T07:15:06+00:00, book20_bid_proxy_usdt=13065, book20_ask_proxy_usdt=19439, funding_indicative=-0.014479, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=1, 24h_change=-19.29%, turnover=67167162. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-11T07:15:01+00:00, last15m_closed_end=2026-11-11T07:15+00:00, prior8high=0.001832, depth_time=2026-11-11T07:15:14+00:00, book20_bid_proxy_usdt=24332, book20_ask_proxy_usdt=15064, funding_indicative=-0.003797, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=4, 24h_change=-7.38%, turnover=12294783. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-11T07:15:02+00:00, last15m_closed_end=2026-11-11T07:15+00:00, prior8high=181.050000, depth_time=2026-11-11T07:15:25+00:00, book20_bid_proxy_usdt=86534, book20_ask_proxy_usdt=107369, funding_indicative=-0.000102, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.63%, turnover=45861808. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T07:15:02+00:00, last15m_closed_end=2026-11-11T07:15+00:00, prior8high=6.687000, depth_time=2026-11-11T07:15:12+00:00, book20_bid_proxy_usdt=1278418, book20_ask_proxy_usdt=2848655, funding_indicative=0.000003, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.42%, turnover=38728070. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-11T07:15:02+00:00, last15m_closed_end=2026-11-11T07:15+00:00, prior8high=19.229000, depth_time=2026-11-11T07:15:28+00:00, book20_bid_proxy_usdt=14227, book20_ask_proxy_usdt=22476, funding_indicative=0.000050, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.53%, turnover=5402068. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T07:15:01+00:00, last15m_closed_end=2026-11-11T07:15+00:00, prior8high=1023.190000, depth_time=2026-11-11T07:15:09+00:00, book20_bid_proxy_usdt=196156, book20_ask_proxy_usdt=415435, funding_indicative=0.000072, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-11.12%, turnover=2168116596. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
