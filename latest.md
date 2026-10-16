# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T18:15:42Z**
- feed_generated_utc: 2026-10-16T18:15:45+00:00
- source_sha256: `dc006fd31990b9c1b0455d864ccf1c3d3276e2b92e702f44271030807f9db1be`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 17; crypto_deep: 15
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T18:15+00:00, close=81297.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-16T18:00+00:00, close=81185.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-16T16:00+00:00, close=81322.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.197200|-3.81|62.09|-3.80|21913259|0.51|
|ZRO_USDT|2.022500|-3.75|-0.70|-3.74|15748385|0.49|
|INJ_USDT|8.653000|-3.61|24.88|-3.60|112462929|1.16|
|ZEC_USDT|1146.480000|-3.49|-5.90|-3.48|1514286455|0.09|
|OP_USDT|0.135870|-2.95|10.26|-2.94|14677302|1.47|
|PYTH_USDT|0.083880|-2.78|-1.76|-2.77|5708587|2.38|
|WLD_USDT|0.499100|-1.88|1.34|-1.87|91872880|2.00|
|STRK_USDT|0.072600|-1.82|-3.59|-1.81|26894638|1.38|
|APT_USDT|0.841000|-1.76|5.05|-1.75|12386201|1.19|
|TAO_USDT|275.970000|-1.65|0.47|-1.64|81581722|0.72|
|HBAR_USDT|0.082840|-1.50|-8.82|-1.49|22315043|1.21|
|FARTCOIN_USDT|0.152440|-1.47|-6.69|-1.46|7501851|0.66|
|ARB_USDT|0.192150|-1.43|6.27|-1.42|36469373|0.52|
|AAVE_USDT|155.080000|-1.39|-8.69|-1.38|32276770|0.65|
|BCH_USDT|274.180000|-1.39|-0.41|-1.38|5827321|2.92|
|ICP_USDT|3.000000|-1.25|-0.62|-1.24|8943020|3.33|
|ENA_USDT|0.197440|-1.24|-8.41|-1.23|37492679|3.04|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|155.080000|153.780000|155.100000|0.73|N|Y/Y|Y/N|Y|N|
|APT_USDT|0.841000|0.825100|0.840900|1.39|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.192150|0.189190|0.192230|1.47|N|Y/Y|N/N|Y|N|
|BAT_USDT|0.197200|0.191460|0.197200|1.30|N|Y/N|N/N|Y|N|
|BCH_USDT|274.180000|272.380000|274.180000|1.52|N|Y/Y|N/N|Y|N|
|FARTCOIN_USDT|0.152440|0.150210|0.152440|1.56|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.082840|0.082080|0.082840|0.66|N|Y/Y|Y/N|Y|N|
|INJ_USDT|8.653000|8.573000|8.653000|0.78|N|Y/Y|N/N|Y|N|
|OP_USDT|0.135870|0.133270|0.135890|0.65|N|Y/Y|N/N|Y|N|
|PYTH_USDT|0.083880|0.083450|0.083880|0.51|N|Y/Y|Y/N|Y|N|
|STRK_USDT|0.072600|0.072400|0.072700|1.66|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|275.970000|272.270000|275.920000|0.49|N|Y/Y|N/N|Y|N|
|WLD_USDT|0.499100|0.492700|0.498800|1.52|N|Y/Y|N/N|Y|N|
|ZEC_USDT|1146.480000|1133.160000|1145.340000|0.91|N|Y/Y|Y/N|Y|N|
|ZRO_USDT|2.022500|1.975000|2.022200|1.11|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-16T18:15:02+00:00, last15m_closed_end=2026-10-16T18:15+00:00, prior8high=158.030000, depth_time=2026-10-16T18:15:39+00:00, book20_bid_proxy_usdt=246946, book20_ask_proxy_usdt=309517, funding_indicative=0.000089, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.39%, turnover=32276770. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-16T18:15:02+00:00, last15m_closed_end=2026-10-16T18:15+00:00, prior8high=0.858800, depth_time=2026-10-16T18:15:27+00:00, book20_bid_proxy_usdt=68083, book20_ask_proxy_usdt=105630, funding_indicative=0.000100, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.76%, turnover=12386201. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-16T18:15:02+00:00, last15m_closed_end=2026-10-16T18:15+00:00, prior8high=0.196000, depth_time=2026-10-16T18:15:37+00:00, book20_bid_proxy_usdt=43329, book20_ask_proxy_usdt=74224, funding_indicative=0.000038, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.43%, turnover=36469373. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-16T18:15:02+00:00, last15m_closed_end=2026-10-16T18:15+00:00, prior8high=0.205380, depth_time=2026-10-16T18:15:08+00:00, book20_bid_proxy_usdt=19354, book20_ask_proxy_usdt=31499, funding_indicative=-0.000270, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.81%, turnover=21913259. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BCH_USDT: quote_utc=2026-10-16T18:15:02+00:00, last15m_closed_end=2026-10-16T18:15+00:00, prior8high=278.930000, depth_time=2026-10-16T18:15:42+00:00, book20_bid_proxy_usdt=149183, book20_ask_proxy_usdt=78371, funding_indicative=0.000100, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.39%, turnover=5827321. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-16T18:15:02+00:00, last15m_closed_end=2026-10-16T18:15+00:00, prior8high=0.155460, depth_time=2026-10-16T18:15:35+00:00, book20_bid_proxy_usdt=57507, book20_ask_proxy_usdt=52533, funding_indicative=0.000050, next_funding_utc=2026-10-16T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.47%, turnover=7501851. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-16T18:15:02+00:00, last15m_closed_end=2026-10-16T18:15+00:00, prior8high=0.084470, depth_time=2026-10-16T18:15:31+00:00, book20_bid_proxy_usdt=506213, book20_ask_proxy_usdt=1381493, funding_indicative=0.000044, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.50%, turnover=22315043. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-16T18:15:02+00:00, last15m_closed_end=2026-10-16T18:15+00:00, prior8high=9.045000, depth_time=2026-10-16T18:15:13+00:00, book20_bid_proxy_usdt=398118, book20_ask_proxy_usdt=197877, funding_indicative=-0.000032, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.61%, turnover=112462929. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-16T18:15:02+00:00, last15m_closed_end=2026-10-16T18:15+00:00, prior8high=0.140640, depth_time=2026-10-16T18:15:17+00:00, book20_bid_proxy_usdt=33276, book20_ask_proxy_usdt=39945, funding_indicative=0.000057, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.95%, turnover=14677302. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PYTH_USDT: quote_utc=2026-10-16T18:15:02+00:00, last15m_closed_end=2026-10-16T18:15+00:00, prior8high=0.087360, depth_time=2026-10-16T18:15:20+00:00, book20_bid_proxy_usdt=130781, book20_ask_proxy_usdt=115944, funding_indicative=-0.000062, next_funding_utc=2026-10-16T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.78%, turnover=5708587. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-16T18:15:02+00:00, last15m_closed_end=2026-10-16T18:15+00:00, prior8high=0.074470, depth_time=2026-10-16T18:15:25+00:00, book20_bid_proxy_usdt=619673, book20_ask_proxy_usdt=329052, funding_indicative=0.000050, next_funding_utc=2026-10-16T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.82%, turnover=26894638. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-16T18:15:02+00:00, last15m_closed_end=2026-10-16T18:15+00:00, prior8high=282.080000, depth_time=2026-10-16T18:15:29+00:00, book20_bid_proxy_usdt=43641, book20_ask_proxy_usdt=136440, funding_indicative=0.000050, next_funding_utc=2026-10-16T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.65%, turnover=81581722. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-16T18:15:02+00:00, last15m_closed_end=2026-10-16T18:15+00:00, prior8high=0.516400, depth_time=2026-10-16T18:15:23+00:00, book20_bid_proxy_usdt=973073, book20_ask_proxy_usdt=1462720, funding_indicative=0.000100, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.88%, turnover=91872880. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-16T18:15:02+00:00, last15m_closed_end=2026-10-16T18:15+00:00, prior8high=1189.890000, depth_time=2026-10-16T18:15:15+00:00, book20_bid_proxy_usdt=470905, book20_ask_proxy_usdt=184561, funding_indicative=0.000039, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.49%, turnover=1514286455. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-16T18:15:02+00:00, last15m_closed_end=2026-10-16T18:15+00:00, prior8high=2.125800, depth_time=2026-10-16T18:15:10+00:00, book20_bid_proxy_usdt=40379, book20_ask_proxy_usdt=33882, funding_indicative=0.000050, next_funding_utc=2026-10-16T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.75%, turnover=15748385. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
