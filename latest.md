# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T08:30:33Z**
- feed_generated_utc: 2026-10-26T08:30:36+00:00
- source_sha256: `a3124d4a468fb22566a41acbb482eb3bd1dd6a3a40155736870710f91097a0f2`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T08:30+00:00, close=80183, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-26T08:00+00:00, close=80002, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T08:00+00:00, close=80002, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|CAP_USDT|0.082330|-23.39|23.80|-22.87|6729930|4.86|
|IRYS_USDT|0.029670|-22.81|143.19|-22.29|13206186|3.37|
|APR_USDT|0.038030|-7.93|39.61|-7.41|9003762|2.63|
|BTW_USDT|1.529000|-7.83|-33.67|-7.31|10955790|3.27|
|WLD_USDT|0.440400|-3.54|-7.53|-3.02|69323021|2.27|
|XMR_USDT|588.660000|-3.06|1.05|-2.54|6208396|2.89|
|LIT_USDT|3.087200|-2.86|5.35|-2.34|5848397|2.59|
|DOT_USDT|1.014000|-2.42|-5.18|-1.90|10729400|4.93|
|DASH_USDT|51.210000|-2.28|6.95|-1.76|11904894|1.95|
|PUMPFUN_USDT|0.004196|-2.07|0.02|-1.55|16889538|2.38|
|STRK_USDT|0.044920|-1.79|-27.03|-1.27|9927158|2.23|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APR_USDT|0.038030|0.032200|0.038030|1.20|N|N/Y|N/N|Y|N|
|BTW_USDT|1.529000|1.534500|1.529000|3.37|Y|Y/Y|Y/Y|Y|Y|
|CAP_USDT|0.082330|0.085940|0.082350|1.60|Y|Y/Y|N/N|Y|N|
|DASH_USDT|51.210000|50.720000|51.200000|4.01|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.014000|1.002700|1.014000|2.24|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.029670|0.028940|0.029690|0.88|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.087200|3.052200|3.090000|0.12|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004196|0.004136|0.004196|2.99|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.044920|0.044160|0.044920|2.90|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.440400|0.434300|0.440300|1.93|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|588.660000|583.560000|588.660000|0.25|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APR_USDT: quote_utc=2026-10-26T08:30:02+00:00, last15m_closed_end=2026-10-26T08:30+00:00, prior8high=0.039060, depth_time=2026-10-26T08:30:13+00:00, book20_bid_proxy_usdt=153159, book20_ask_proxy_usdt=58644, funding_indicative=0.000050, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.93%, turnover=9003762. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-26T08:30:02+00:00, last15m_closed_end=2026-10-26T08:30+00:00, prior8high=1.643500, depth_time=2026-10-26T08:30:15+00:00, book20_bid_proxy_usdt=15609, book20_ask_proxy_usdt=12104, funding_indicative=-0.005488, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.83%, turnover=10955790. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CAP_USDT: quote_utc=2026-10-26T08:30:02+00:00, last15m_closed_end=2026-10-26T08:30+00:00, prior8high=0.111390, depth_time=2026-10-26T08:30:08+00:00, book20_bid_proxy_usdt=56799, book20_ask_proxy_usdt=70194, funding_indicative=0.000352, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-23.39%, turnover=6729930. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-26T08:30:03+00:00, last15m_closed_end=2026-10-26T08:30+00:00, prior8high=51.320000, depth_time=2026-10-26T08:30:25+00:00, book20_bid_proxy_usdt=749430, book20_ask_proxy_usdt=845673, funding_indicative=0.000043, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.28%, turnover=11904894. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-26T08:30:02+00:00, last15m_closed_end=2026-10-26T08:30+00:00, prior8high=1.010900, depth_time=2026-10-26T08:30:25+00:00, book20_bid_proxy_usdt=268101, book20_ask_proxy_usdt=461494, funding_indicative=-0.000073, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.42%, turnover=10729400. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T08:30:02+00:00, last15m_closed_end=2026-10-26T08:30+00:00, prior8high=0.033830, depth_time=2026-10-26T08:30:10+00:00, book20_bid_proxy_usdt=60643, book20_ask_proxy_usdt=83328, funding_indicative=-0.000104, next_funding_utc=2026-10-26T09:00:00+00:00, funding_cycle_h=1, 24h_change=-22.81%, turnover=13206186. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T08:30:03+00:00, last15m_closed_end=2026-10-26T08:30+00:00, prior8high=3.131600, depth_time=2026-10-26T08:30:23+00:00, book20_bid_proxy_usdt=18476, book20_ask_proxy_usdt=12740, funding_indicative=0.000050, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.86%, turnover=5848397. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-26T08:30:02+00:00, last15m_closed_end=2026-10-26T08:30+00:00, prior8high=0.004212, depth_time=2026-10-26T08:30:30+00:00, book20_bid_proxy_usdt=1657487, book20_ask_proxy_usdt=2105502, funding_indicative=-0.000010, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.07%, turnover=16889538. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-26T08:30:03+00:00, last15m_closed_end=2026-10-26T08:30+00:00, prior8high=0.045030, depth_time=2026-10-26T08:30:32+00:00, book20_bid_proxy_usdt=635841, book20_ask_proxy_usdt=773689, funding_indicative=0.000032, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.79%, turnover=9927158. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T08:30:02+00:00, last15m_closed_end=2026-10-26T08:30+00:00, prior8high=0.441300, depth_time=2026-10-26T08:30:18+00:00, book20_bid_proxy_usdt=2449400, book20_ask_proxy_usdt=2086043, funding_indicative=-0.000078, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.54%, turnover=69323021. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T08:30:03+00:00, last15m_closed_end=2026-10-26T08:30+00:00, prior8high=589.800000, depth_time=2026-10-26T08:30:18+00:00, book20_bid_proxy_usdt=17624, book20_ask_proxy_usdt=32882, funding_indicative=0.000100, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.06%, turnover=6208396. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
