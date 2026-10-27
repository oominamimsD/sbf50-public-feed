# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T13:15:45Z**
- feed_generated_utc: 2026-10-27T13:15:49+00:00
- source_sha256: `b23cdad6ccce6e750e60a26cd6264f5fa48049b7473c09b542f518bf9badd1ee`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 75/75 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 14; crypto_deep: 14
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T13:15+00:00, close=80234.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-27T13:00+00:00, close=80337, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-27T12:00+00:00, close=79880.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.024750|-10.26|101.54|-10.06|6979366|4.04|
|QNT_USDT|199.000000|-5.36|1.68|-5.16|104738375|0.50|
|AAVE_USDT|131.710000|-3.67|-10.53|-3.47|28318353|1.52|
|DOT_USDT|0.987900|-3.39|-13.85|-3.19|10965166|1.01|
|FILECOIN_USDT|0.891100|-3.21|-11.94|-3.01|6652485|1.12|
|WLD_USDT|0.432200|-2.87|-14.63|-2.67|67374211|2.31|
|PUMPFUN_USDT|0.004208|-2.77|-5.56|-2.57|19700671|2.38|
|AVAX_USDT|8.781000|-2.40|-8.16|-2.20|20737907|1.14|
|TIA_USDT|0.523000|-2.37|-14.05|-2.17|17209270|1.91|
|ICP_USDT|2.584000|-1.74|-9.42|-1.54|5191531|3.87|
|LINK_USDT|11.338000|-1.64|-5.06|-1.44|132499301|2.65|
|TAO_USDT|249.370000|-1.63|-7.05|-1.43|51486432|1.20|
|HBAR_USDT|0.076120|-1.60|-7.02|-1.40|10301231|1.31|
|ARB_USDT|0.167550|-1.43|-14.35|-1.23|17640236|0.60|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|131.710000|130.520000|131.710000|0.77|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.167550|0.166210|0.167540|2.33|N|N/Y|Y/Y|Y|N|
|AVAX_USDT|8.781000|8.732000|8.781000|2.98|N|N/Y|Y/Y|Y|N|
|DOT_USDT|0.987900|0.982200|0.987900|0.32|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|0.891100|0.887200|0.891100|3.10|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.076120|0.075590|0.076120|0.57|N|Y/Y|Y/Y|Y|N|
|ICP_USDT|2.584000|2.565000|2.584000|0.87|N|N/Y|Y/Y|Y|N|
|IRYS_USDT|0.024750|0.024650|0.024750|1.14|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|11.338000|11.290000|11.338000|1.30|N|N/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004208|0.004133|0.004206|0.77|N|N/Y|Y/Y|Y|N|
|QNT_USDT|199.000000|200.570000|198.990000|1.99|Y|Y/Y|N/N|Y|N|
|TAO_USDT|249.370000|247.220000|249.350000|1.65|N|N/Y|Y/Y|Y|N|
|TIA_USDT|0.523000|0.522500|0.523000|1.43|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.432200|0.428900|0.432000|1.33|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T13:15:00+00:00, last15m_closed_end=2026-10-27T13:15+00:00, prior8high=133.100000, depth_time=2026-10-27T13:15:16+00:00, book20_bid_proxy_usdt=360676, book20_ask_proxy_usdt=366647, funding_indicative=0.000100, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.67%, turnover=28318353. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-27T13:15:00+00:00, last15m_closed_end=2026-10-27T13:15+00:00, prior8high=0.169600, depth_time=2026-10-27T13:15:44+00:00, book20_bid_proxy_usdt=61025, book20_ask_proxy_usdt=90047, funding_indicative=0.000029, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.43%, turnover=17640236. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-27T13:15:00+00:00, last15m_closed_end=2026-10-27T13:15+00:00, prior8high=8.864000, depth_time=2026-10-27T13:15:29+00:00, book20_bid_proxy_usdt=978812, book20_ask_proxy_usdt=941013, funding_indicative=0.000055, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.40%, turnover=20737907. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T13:15:00+00:00, last15m_closed_end=2026-10-27T13:15+00:00, prior8high=0.996900, depth_time=2026-10-27T13:15:19+00:00, book20_bid_proxy_usdt=384221, book20_ask_proxy_usdt=475916, funding_indicative=-0.000145, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.39%, turnover=10965166. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T13:15:00+00:00, last15m_closed_end=2026-10-27T13:15+00:00, prior8high=0.902000, depth_time=2026-10-27T13:15:19+00:00, book20_bid_proxy_usdt=1037504, book20_ask_proxy_usdt=1373244, funding_indicative=0.000072, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.21%, turnover=6652485. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-27T13:15:00+00:00, last15m_closed_end=2026-10-27T13:15+00:00, prior8high=0.076600, depth_time=2026-10-27T13:15:39+00:00, book20_bid_proxy_usdt=911897, book20_ask_proxy_usdt=1276893, funding_indicative=0.000091, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.60%, turnover=10301231. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-27T13:15:00+00:00, last15m_closed_end=2026-10-27T13:15+00:00, prior8high=2.608000, depth_time=2026-10-27T13:15:33+00:00, book20_bid_proxy_usdt=1226868, book20_ask_proxy_usdt=1146356, funding_indicative=0.000100, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.74%, turnover=5191531. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-27T13:15:00+00:00, last15m_closed_end=2026-10-27T13:15+00:00, prior8high=0.025210, depth_time=2026-10-27T13:15:07+00:00, book20_bid_proxy_usdt=133899, book20_ask_proxy_usdt=131178, funding_indicative=-0.000314, next_funding_utc=2026-10-27T14:00:00+00:00, funding_cycle_h=1, 24h_change=-10.26%, turnover=6979366. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-10-27T13:15:00+00:00, last15m_closed_end=2026-10-27T13:15+00:00, prior8high=11.453000, depth_time=2026-10-27T13:15:36+00:00, book20_bid_proxy_usdt=543157, book20_ask_proxy_usdt=521399, funding_indicative=0.000100, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.64%, turnover=132499301. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-27T13:15:00+00:00, last15m_closed_end=2026-10-27T13:15+00:00, prior8high=0.004256, depth_time=2026-10-27T13:15:27+00:00, book20_bid_proxy_usdt=2142035, book20_ask_proxy_usdt=1749726, funding_indicative=0.000050, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.77%, turnover=19700671. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-27T13:15:00+00:00, last15m_closed_end=2026-10-27T13:15+00:00, prior8high=205.500000, depth_time=2026-10-27T13:15:13+00:00, book20_bid_proxy_usdt=31084, book20_ask_proxy_usdt=53481, funding_indicative=-0.000230, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.36%, turnover=104738375. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-27T13:15:00+00:00, last15m_closed_end=2026-10-27T13:15+00:00, prior8high=251.610000, depth_time=2026-10-27T13:15:39+00:00, book20_bid_proxy_usdt=181560, book20_ask_proxy_usdt=208120, funding_indicative=0.000050, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.63%, turnover=51486432. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-27T13:15:00+00:00, last15m_closed_end=2026-10-27T13:15+00:00, prior8high=0.531400, depth_time=2026-10-27T13:15:31+00:00, book20_bid_proxy_usdt=190911, book20_ask_proxy_usdt=519973, funding_indicative=0.000037, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.37%, turnover=17209270. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-27T13:15:00+00:00, last15m_closed_end=2026-10-27T13:15+00:00, prior8high=0.438400, depth_time=2026-10-27T13:15:23+00:00, book20_bid_proxy_usdt=3070714, book20_ask_proxy_usdt=3228236, funding_indicative=-0.000045, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.87%, turnover=67374211. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
