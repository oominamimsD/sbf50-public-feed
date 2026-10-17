# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T22:15:39Z**
- feed_generated_utc: 2026-10-17T22:15:41+00:00
- source_sha256: `7db6b92adef3deb48957a4568764f81d507310a3acd17c69e080f614e641f909`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T22:15+00:00, close=81316.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-17T22:00+00:00, close=81099.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-17T20:00+00:00, close=81575.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ICNT_USDT|0.173200|-6.47|74.77|-6.46|14486375|5.78|
|EIGEN_USDT|0.248700|-2.96|5.56|-2.95|10461433|4.02|
|FILECOIN_USDT|1.058500|-2.65|-6.14|-2.64|21759047|0.95|
|STRK_USDT|0.064410|-2.63|-31.06|-2.62|15931446|3.10|
|QNT_USDT|195.190000|-2.60|-20.37|-2.59|64510474|0.51|
|ARB_USDT|0.179970|-2.14|-3.58|-2.13|30651041|0.56|
|WLD_USDT|0.487200|-1.69|-12.84|-1.68|67726562|2.05|
|TIA_USDT|0.647700|-1.56|26.25|-1.55|75407112|1.54|
|ZEC_USDT|1124.010000|-1.51|-8.74|-1.50|1148945246|0.09|
|ZRO_USDT|1.858600|-1.41|-8.01|-1.40|8220249|0.54|
|PUMPFUN_USDT|0.004352|-1.35|-23.98|-1.34|29253415|2.30|
|AVAX_USDT|9.708000|-1.13|-7.76|-1.12|77906965|1.03|
|APT_USDT|0.788800|-1.09|-4.59|-1.08|9919685|1.27|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.788800|0.775800|0.788800|1.43|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.179970|0.176600|0.179970|1.69|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|9.708000|9.551000|9.708000|2.43|N|Y/Y|Y/Y|Y|N|
|EIGEN_USDT|0.248700|0.241300|0.248800|1.17|N|Y/Y|N/N|Y|N|
|FILECOIN_USDT|1.058500|1.038400|1.058500|0.46|N|Y/Y|Y/Y|Y|N|
|ICNT_USDT|0.173200|0.170600|0.173200|0.93|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004352|0.004262|0.004354|1.65|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|195.190000|190.470000|195.190000|2.16|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.064410|0.063090|0.064410|0.40|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.647700|0.634700|0.647700|0.96|N|Y/Y|N/N|Y|N|
|WLD_USDT|0.487200|0.477800|0.487200|7.48|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1124.010000|1098.000000|1124.480000|0.97|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.858600|1.845300|1.858900|0.78|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-17T22:15:02+00:00, last15m_closed_end=2026-10-17T22:15+00:00, prior8high=0.816800, depth_time=2026-10-17T22:15:38+00:00, book20_bid_proxy_usdt=122189, book20_ask_proxy_usdt=91870, funding_indicative=-0.000089, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.09%, turnover=9919685. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-17T22:15:02+00:00, last15m_closed_end=2026-10-17T22:15+00:00, prior8high=0.184600, depth_time=2026-10-17T22:15:20+00:00, book20_bid_proxy_usdt=43421, book20_ask_proxy_usdt=65202, funding_indicative=0.000044, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.14%, turnover=30651041. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-17T22:15:02+00:00, last15m_closed_end=2026-10-17T22:15+00:00, prior8high=9.906000, depth_time=2026-10-17T22:15:35+00:00, book20_bid_proxy_usdt=694374, book20_ask_proxy_usdt=546280, funding_indicative=-0.000002, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.13%, turnover=77906965. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-17T22:15:02+00:00, last15m_closed_end=2026-10-17T22:15+00:00, prior8high=0.256500, depth_time=2026-10-17T22:15:10+00:00, book20_bid_proxy_usdt=527014, book20_ask_proxy_usdt=372528, funding_indicative=0.000019, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.96%, turnover=10461433. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-17T22:15:02+00:00, last15m_closed_end=2026-10-17T22:15+00:00, prior8high=1.098300, depth_time=2026-10-17T22:15:13+00:00, book20_bid_proxy_usdt=410936, book20_ask_proxy_usdt=463940, funding_indicative=-0.000097, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.65%, turnover=21759047. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-17T22:15:02+00:00, last15m_closed_end=2026-10-17T22:15+00:00, prior8high=0.215400, depth_time=2026-10-17T22:15:08+00:00, book20_bid_proxy_usdt=142022, book20_ask_proxy_usdt=109490, funding_indicative=-0.000354, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-6.47%, turnover=14486375. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-17T22:15:02+00:00, last15m_closed_end=2026-10-17T22:15+00:00, prior8high=0.004487, depth_time=2026-10-17T22:15:33+00:00, book20_bid_proxy_usdt=1617141, book20_ask_proxy_usdt=920060, funding_indicative=0.000008, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.35%, turnover=29253415. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-17T22:15:02+00:00, last15m_closed_end=2026-10-17T22:15+00:00, prior8high=200.420000, depth_time=2026-10-17T22:15:17+00:00, book20_bid_proxy_usdt=47620, book20_ask_proxy_usdt=52838, funding_indicative=-0.000068, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.60%, turnover=64510474. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-17T22:15:02+00:00, last15m_closed_end=2026-10-17T22:15+00:00, prior8high=0.065670, depth_time=2026-10-17T22:15:15+00:00, book20_bid_proxy_usdt=204646, book20_ask_proxy_usdt=287956, funding_indicative=0.000050, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.63%, turnover=15931446. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-17T22:15:02+00:00, last15m_closed_end=2026-10-17T22:15+00:00, prior8high=0.676600, depth_time=2026-10-17T22:15:25+00:00, book20_bid_proxy_usdt=196628, book20_ask_proxy_usdt=199484, funding_indicative=-0.000054, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.56%, turnover=75407112. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-17T22:15:02+00:00, last15m_closed_end=2026-10-17T22:15+00:00, prior8high=0.506800, depth_time=2026-10-17T22:15:23+00:00, book20_bid_proxy_usdt=1384139, book20_ask_proxy_usdt=1479484, funding_indicative=-0.000133, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.69%, turnover=67726562. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-17T22:15:02+00:00, last15m_closed_end=2026-10-17T22:15+00:00, prior8high=1163.390000, depth_time=2026-10-17T22:15:28+00:00, book20_bid_proxy_usdt=36010, book20_ask_proxy_usdt=269970, funding_indicative=0.000030, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.51%, turnover=1148945246. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-17T22:15:02+00:00, last15m_closed_end=2026-10-17T22:15+00:00, prior8high=1.919600, depth_time=2026-10-17T22:15:30+00:00, book20_bid_proxy_usdt=30888, book20_ask_proxy_usdt=33816, funding_indicative=0.000050, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.41%, turnover=8220249. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
