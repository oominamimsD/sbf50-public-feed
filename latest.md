# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-05T01:30:34Z**
- feed_generated_utc: 2026-11-05T01:30:35+00:00
- source_sha256: `b962888a145ff76fc05ff9800955a8e75794a880f3d2650d1fc54337ec581b34`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-05T01:30+00:00, close=80357.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-05T01:00+00:00, close=80509.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-05T00:00+00:00, close=80466.5, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002265|-19.39|-88.72|-19.49|16526241|4.41|
|TRUMPOFFICIAL_USDT|1.252000|-12.07|-26.74|-12.17|27388011|7.99|
|CLANKER_USDT|16.520000|-11.23|23.65|-11.33|20217726|6.05|
|IDOL_USDT|0.021152|-9.86|144.33|-9.96|6170568|0.94|
|BTW_USDT|1.005000|-8.55|-42.17|-8.65|6098632|0.99|
|VVV_USDT|21.186000|-8.49|-11.04|-8.59|5132154|2.36|
|EVAA_USDT|1.534400|-6.30|3.32|-6.40|5078529|2.61|
|WLD_USDT|0.373900|-4.64|-13.60|-4.74|75208313|2.67|
|PUMPFUN_USDT|0.004250|-4.49|1.02|-4.59|16687299|4.71|
|OP_USDT|0.109550|-4.07|-1.37|-4.17|11069708|0.91|
|ZRO_USDT|1.822900|-2.24|6.47|-2.34|10591029|0.55|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002265|0.002333|0.002265|4.73|Y|Y/Y|Y/Y|N|Y|
|BTW_USDT|1.005000|1.009200|1.005000|1.05|N|Y/Y|Y/N|N|N|
|CLANKER_USDT|16.520000|16.300000|16.520000|0.50|N|Y/Y|N/N|N|N|
|EVAA_USDT|1.534400|1.518600|1.534400|2.42|N|Y/Y|N/N|N|N|
|IDOL_USDT|0.021152|0.021076|0.021152|0.94|N|Y/Y|N/N|N|N|
|OP_USDT|0.109550|0.109240|0.109550|0.62|N|Y/Y|Y/N|N|N|
|PUMPFUN_USDT|0.004250|0.004236|0.004250|1.49|N|Y/Y|N/N|N|N|
|TRUMPOFFICIAL_USDT|1.252000|1.238000|1.252000|0.87|N|Y/Y|Y/Y|N|N|
|VVV_USDT|21.186000|20.977000|21.186000|0.41|N|Y/Y|Y/Y|N|N|
|WLD_USDT|0.373900|0.373000|0.373900|1.50|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.822900|1.807200|1.822900|2.95|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-05T01:30:00+00:00, last15m_closed_end=2026-11-05T01:30+00:00, prior8high=0.002555, depth_time=2026-11-05T01:30:08+00:00, book20_bid_proxy_usdt=45764, book20_ask_proxy_usdt=78760, funding_indicative=-0.000929, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-19.39%, turnover=16526241. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-05T01:30:00+00:00, last15m_closed_end=2026-11-05T01:30+00:00, prior8high=1.036000, depth_time=2026-11-05T01:30:16+00:00, book20_bid_proxy_usdt=39240, book20_ask_proxy_usdt=55225, funding_indicative=0.000028, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-8.55%, turnover=6098632. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CLANKER_USDT: quote_utc=2026-11-05T01:30:00+00:00, last15m_closed_end=2026-11-05T01:30+00:00, prior8high=18.850000, depth_time=2026-11-05T01:30:12+00:00, book20_bid_proxy_usdt=125792, book20_ask_proxy_usdt=164657, funding_indicative=0.000050, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-11.23%, turnover=20217726. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-11-05T01:30:00+00:00, last15m_closed_end=2026-11-05T01:30+00:00, prior8high=1.583900, depth_time=2026-11-05T01:30:22+00:00, book20_bid_proxy_usdt=9374, book20_ask_proxy_usdt=8697, funding_indicative=0.000050, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-6.30%, turnover=5078529. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-05T01:30:00+00:00, last15m_closed_end=2026-11-05T01:30+00:00, prior8high=0.022404, depth_time=2026-11-05T01:30:14+00:00, book20_bid_proxy_usdt=3378, book20_ask_proxy_usdt=5417, funding_indicative=0.000050, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-9.86%, turnover=6170568. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-05T01:30:00+00:00, last15m_closed_end=2026-11-05T01:30+00:00, prior8high=0.111560, depth_time=2026-11-05T01:30:29+00:00, book20_bid_proxy_usdt=68756, book20_ask_proxy_usdt=114262, funding_indicative=0.000008, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.07%, turnover=11069708. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-05T01:30:00+00:00, last15m_closed_end=2026-11-05T01:30+00:00, prior8high=0.004317, depth_time=2026-11-05T01:30:27+00:00, book20_bid_proxy_usdt=1760039, book20_ask_proxy_usdt=1378459, funding_indicative=0.000000, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.49%, turnover=16687299. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-05T01:30:00+00:00, last15m_closed_end=2026-11-05T01:30+00:00, prior8high=1.286000, depth_time=2026-11-05T01:30:10+00:00, book20_bid_proxy_usdt=1096396, book20_ask_proxy_usdt=1103203, funding_indicative=-0.000416, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-12.07%, turnover=27388011. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-05T01:30:00+00:00, last15m_closed_end=2026-11-05T01:30+00:00, prior8high=21.959000, depth_time=2026-11-05T01:30:17+00:00, book20_bid_proxy_usdt=34719, book20_ask_proxy_usdt=19248, funding_indicative=-0.000430, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-8.49%, turnover=5132154. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-05T01:30:00+00:00, last15m_closed_end=2026-11-05T01:30+00:00, prior8high=0.381000, depth_time=2026-11-05T01:30:25+00:00, book20_bid_proxy_usdt=2267746, book20_ask_proxy_usdt=2799966, funding_indicative=-0.000373, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.64%, turnover=75208313. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-05T01:30:00+00:00, last15m_closed_end=2026-11-05T01:30+00:00, prior8high=1.832000, depth_time=2026-11-05T01:30:32+00:00, book20_bid_proxy_usdt=34012, book20_ask_proxy_usdt=48067, funding_indicative=0.000050, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.24%, turnover=10591029. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
