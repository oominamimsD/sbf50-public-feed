# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-05T02:30:26Z**
- feed_generated_utc: 2026-11-05T02:30:27+00:00
- source_sha256: `047eff0c3bba2cb20c06bd38d329797fe294154cc4f297317a9e99e4c4cb4536`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-05T02:30+00:00, close=80652, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-05T02:00+00:00, close=80640.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-05T00:00+00:00, close=80466.5, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|TRUMPOFFICIAL_USDT|1.238000|-13.06|-27.55|-13.53|27198342|8.08|
|CLANKER_USDT|16.690000|-10.31|24.92|-10.78|20299410|5.99|
|IDOL_USDT|0.021391|-8.85|147.09|-9.32|5912059|2.80|
|AKE_USDT|0.002570|-8.54|-87.21|-9.01|17142383|3.90|
|VVV_USDT|21.455000|-7.33|-9.91|-7.80|5047321|0.47|
|BTW_USDT|1.026300|-6.61|-40.94|-7.08|5974797|0.97|
|WLD_USDT|0.375600|-4.20|-13.21|-4.67|73853951|2.66|
|ZRO_USDT|1.825500|-2.10|6.62|-2.57|10447217|0.55|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002570|0.002197|0.002566|2.46|N|Y/Y|Y/Y|N|N|
|BTW_USDT|1.026300|1.003000|1.026300|0.81|N|Y/Y|Y/N|N|N|
|CLANKER_USDT|16.690000|15.780000|16.680000|0.13|N|Y/Y|N/N|N|N|
|IDOL_USDT|0.021391|0.020956|0.021391|0.88|N|Y/Y|N/N|N|N|
|TRUMPOFFICIAL_USDT|1.238000|1.229000|1.238000|0.44|N|Y/Y|Y/Y|N|N|
|VVV_USDT|21.455000|20.977000|21.455000|0.13|N|Y/Y|Y/Y|N|N|
|WLD_USDT|0.375600|0.370800|0.375600|0.81|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.825500|1.807200|1.825100|0.91|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-05T02:30:03+00:00, last15m_closed_end=2026-11-05T02:30+00:00, prior8high=0.002642, depth_time=2026-11-05T02:30:15+00:00, book20_bid_proxy_usdt=34144, book20_ask_proxy_usdt=37288, funding_indicative=-0.000666, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-8.54%, turnover=17142383. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-05T02:30:03+00:00, last15m_closed_end=2026-11-05T02:30+00:00, prior8high=1.037600, depth_time=2026-11-05T02:30:19+00:00, book20_bid_proxy_usdt=28057, book20_ask_proxy_usdt=16615, funding_indicative=0.000041, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-6.61%, turnover=5974797. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CLANKER_USDT: quote_utc=2026-11-05T02:30:02+00:00, last15m_closed_end=2026-11-05T02:30+00:00, prior8high=18.700000, depth_time=2026-11-05T02:30:10+00:00, book20_bid_proxy_usdt=134144, book20_ask_proxy_usdt=146048, funding_indicative=0.000050, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-10.31%, turnover=20299410. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-05T02:30:02+00:00, last15m_closed_end=2026-11-05T02:30+00:00, prior8high=0.022100, depth_time=2026-11-05T02:30:11+00:00, book20_bid_proxy_usdt=2706, book20_ask_proxy_usdt=7018, funding_indicative=0.000050, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-8.85%, turnover=5912059. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-05T02:30:03+00:00, last15m_closed_end=2026-11-05T02:30+00:00, prior8high=1.284000, depth_time=2026-11-05T02:30:07+00:00, book20_bid_proxy_usdt=1328232, book20_ask_proxy_usdt=1266931, funding_indicative=-0.000375, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-13.06%, turnover=27198342. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-05T02:30:03+00:00, last15m_closed_end=2026-11-05T02:30+00:00, prior8high=21.524000, depth_time=2026-11-05T02:30:18+00:00, book20_bid_proxy_usdt=26882, book20_ask_proxy_usdt=12722, funding_indicative=-0.000330, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-7.33%, turnover=5047321. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-05T02:30:03+00:00, last15m_closed_end=2026-11-05T02:30+00:00, prior8high=0.381000, depth_time=2026-11-05T02:30:22+00:00, book20_bid_proxy_usdt=2560249, book20_ask_proxy_usdt=2411145, funding_indicative=-0.000376, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.20%, turnover=73853951. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-05T02:30:03+00:00, last15m_closed_end=2026-11-05T02:30+00:00, prior8high=1.831700, depth_time=2026-11-05T02:30:25+00:00, book20_bid_proxy_usdt=35288, book20_ask_proxy_usdt=48460, funding_indicative=0.000050, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.10%, turnover=10447217. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
