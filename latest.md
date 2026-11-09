# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T00:45:29Z**
- feed_generated_utc: 2026-11-09T00:45:30+00:00
- source_sha256: `955b152584a8f65197bf0e560b9a9fedf59c7ce3ccfbb0c683aa5c0279dbdbf6`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T00:45+00:00, close=74918.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-09T00:00+00:00, close=74823.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T00:00+00:00, close=74823.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001730|-11.65|48.54|-10.25|12027519|0.58|
|PUMPFUN_USDT|0.003560|-4.73|-15.59|-3.33|8739834|2.81|
|DASH_USDT|45.610000|-4.60|-6.15|-3.20|15216979|2.19|
|AKE_USDT|0.005171|-3.47|-43.54|-2.07|14605932|5.80|
|HYPE_USDT|74.767000|-3.44|-14.73|-2.04|37679076|0.13|
|WLD_USDT|0.314900|-3.37|-20.41|-1.97|31744369|3.17|
|LIT_USDT|3.089000|-3.26|-4.36|-1.86|11471131|0.32|
|XRP_USDT|1.120000|-3.09|-10.39|-1.69|231653777|0.89|
|DOT_USDT|0.866300|-2.76|-8.52|-1.36|6768813|1.15|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.005171|0.005161|0.005171|0.52|N|Y/Y|N/N|Y|N|
|DASH_USDT|45.610000|44.640000|45.610000|0.82|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.866300|0.856000|0.866300|0.16|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|74.767000|73.900000|74.767000|0.47|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.089000|3.023100|3.087800|1.18|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001730|0.001684|0.001727|0.55|N|Y/Y|Y/N|Y|N|
|PUMPFUN_USDT|0.003560|0.003495|0.003556|0.68|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.314900|0.308200|0.314900|1.32|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.120000|1.105100|1.120000|0.47|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-09T00:45:03+00:00, last15m_closed_end=2026-11-09T00:45+00:00, prior8high=0.005394, depth_time=2026-11-09T00:45:14+00:00, book20_bid_proxy_usdt=81676, book20_ask_proxy_usdt=32212, funding_indicative=0.000050, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.47%, turnover=14605932. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-09T00:45:03+00:00, last15m_closed_end=2026-11-09T00:45+00:00, prior8high=46.230000, depth_time=2026-11-09T00:45:13+00:00, book20_bid_proxy_usdt=642297, book20_ask_proxy_usdt=492868, funding_indicative=0.000032, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.60%, turnover=15216979. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-09T00:45:03+00:00, last15m_closed_end=2026-11-09T00:45+00:00, prior8high=0.877300, depth_time=2026-11-09T00:45:26+00:00, book20_bid_proxy_usdt=200337, book20_ask_proxy_usdt=1086805, funding_indicative=0.000046, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.76%, turnover=6768813. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-09T00:45:03+00:00, last15m_closed_end=2026-11-09T00:45+00:00, prior8high=75.837000, depth_time=2026-11-09T00:45:18+00:00, book20_bid_proxy_usdt=47766, book20_ask_proxy_usdt=75021, funding_indicative=0.000025, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.44%, turnover=37679076. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-09T00:45:03+00:00, last15m_closed_end=2026-11-09T00:45+00:00, prior8high=3.135200, depth_time=2026-11-09T00:45:22+00:00, book20_bid_proxy_usdt=20392, book20_ask_proxy_usdt=19839, funding_indicative=0.000050, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.26%, turnover=11471131. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T00:45:03+00:00, last15m_closed_end=2026-11-09T00:45+00:00, prior8high=0.001763, depth_time=2026-11-09T00:45:07+00:00, book20_bid_proxy_usdt=4880, book20_ask_proxy_usdt=8879, funding_indicative=-0.001063, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-11.65%, turnover=12027519. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-09T00:45:03+00:00, last15m_closed_end=2026-11-09T00:45+00:00, prior8high=0.003662, depth_time=2026-11-09T00:45:07+00:00, book20_bid_proxy_usdt=3435257, book20_ask_proxy_usdt=3843703, funding_indicative=-0.000002, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.73%, turnover=8739834. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-09T00:45:03+00:00, last15m_closed_end=2026-11-09T00:45+00:00, prior8high=0.319800, depth_time=2026-11-09T00:45:20+00:00, book20_bid_proxy_usdt=4091153, book20_ask_proxy_usdt=5069115, funding_indicative=-0.000193, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.37%, turnover=31744369. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T00:45:03+00:00, last15m_closed_end=2026-11-09T00:45+00:00, prior8high=1.131800, depth_time=2026-11-09T00:45:25+00:00, book20_bid_proxy_usdt=4154504, book20_ask_proxy_usdt=2220812, funding_indicative=0.000059, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.09%, turnover=231653777. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
