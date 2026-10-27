# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T09:15:44Z**
- feed_generated_utc: 2026-10-27T09:15:48+00:00
- source_sha256: `fd383f2137b2d18972dbe418f7721fc2619a6aaebaf2fbb67704f64bb492980c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 16; crypto_deep: 15
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T09:15+00:00, close=79712.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-27T09:00+00:00, close=79834.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-27T08:00+00:00, close=79774.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BULLA_USDT|0.110390|-25.97|53.27|-25.09|11803577|7.26|
|IRYS_USDT|0.025560|-7.32|108.14|-6.44|7550703|7.82|
|AAVE_USDT|130.720000|-4.39|-11.20|-3.51|23983029|3.06|
|PUMPFUN_USDT|0.004142|-4.29|-7.04|-3.41|21296042|2.41|
|ENA_USDT|0.202680|-3.65|7.85|-2.77|83551450|0.49|
|DOT_USDT|0.990300|-3.15|-13.64|-2.27|10612807|1.01|
|NEAR_USDT|4.445000|-2.79|-9.35|-1.91|91532671|2.25|
|ONDO_USDT|0.407200|-2.76|-5.87|-1.88|22863209|2.46|
|FILECOIN_USDT|0.895400|-2.74|-11.52|-1.86|5748590|1.12|
|AVAX_USDT|8.765000|-2.57|-8.33|-1.69|29331242|1.14|
|WLD_USDT|0.434600|-2.33|-14.16|-1.45|65645215|2.30|
|TAO_USDT|247.800000|-2.25|-7.64|-1.37|44315784|1.21|
|INJ_USDT|7.757000|-2.23|-9.28|-1.35|22200657|1.29|
|SOL_USDT|99.750000|-2.05|-4.16|-1.17|664484329|1.00|
|ARB_USDT|0.166660|-1.95|-14.80|-1.07|19782068|0.60|
|SILVER_USDT|53.200000|-1.89|-7.26|-1.01|256628352|1.88|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|130.720000|130.610000|130.720000|1.88|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.166660|0.166490|0.166660|0.65|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.765000|8.747000|8.765000|2.01|N|Y/Y|Y/Y|Y|N|
|BULLA_USDT|0.110390|0.114150|0.110570|1.67|Y|Y/Y|N/N|Y|N|
|DOT_USDT|0.990300|0.989100|0.990700|2.90|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.202680|0.203650|0.202680|2.14|Y|Y/Y|N/N|Y|N|
|FILECOIN_USDT|0.895400|0.893700|0.895700|1.53|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.757000|7.750000|7.758000|0.82|N|Y/Y|Y/N|Y|N|
|IRYS_USDT|0.025560|0.025670|0.025560|2.60|Y|Y/Y|Y/Y|Y|Y|
|NEAR_USDT|4.445000|4.409000|4.445000|0.78|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.407200|0.406400|0.407200|0.70|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004142|0.004131|0.004145|1.87|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|99.750000|99.450000|99.770000|0.52|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|247.800000|247.500000|247.840000|0.94|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.434600|0.433600|0.434600|1.46|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T09:15:03+00:00, last15m_closed_end=2026-10-27T09:15+00:00, prior8high=132.300000, depth_time=2026-10-27T09:15:14+00:00, book20_bid_proxy_usdt=470624, book20_ask_proxy_usdt=325669, funding_indicative=0.000091, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.39%, turnover=23983029. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-27T09:15:03+00:00, last15m_closed_end=2026-10-27T09:15+00:00, prior8high=0.168680, depth_time=2026-10-27T09:15:42+00:00, book20_bid_proxy_usdt=74435, book20_ask_proxy_usdt=61860, funding_indicative=0.000014, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.95%, turnover=19782068. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-27T09:15:03+00:00, last15m_closed_end=2026-10-27T09:15+00:00, prior8high=8.828000, depth_time=2026-10-27T09:15:31+00:00, book20_bid_proxy_usdt=891040, book20_ask_proxy_usdt=1118282, funding_indicative=-0.000041, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.57%, turnover=29331242. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BULLA_USDT: quote_utc=2026-10-27T09:15:03+00:00, last15m_closed_end=2026-10-27T09:15+00:00, prior8high=0.133100, depth_time=2026-10-27T09:15:08+00:00, book20_bid_proxy_usdt=38458, book20_ask_proxy_usdt=8659, funding_indicative=-0.000607, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-25.97%, turnover=11803577. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T09:15:03+00:00, last15m_closed_end=2026-10-27T09:15+00:00, prior8high=1.001200, depth_time=2026-10-27T09:15:21+00:00, book20_bid_proxy_usdt=283826, book20_ask_proxy_usdt=224918, funding_indicative=-0.000043, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.15%, turnover=10612807. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-27T09:15:03+00:00, last15m_closed_end=2026-10-27T09:15+00:00, prior8high=0.208980, depth_time=2026-10-27T09:15:19+00:00, book20_bid_proxy_usdt=163900, book20_ask_proxy_usdt=120310, funding_indicative=0.000050, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.65%, turnover=83551450. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T09:15:03+00:00, last15m_closed_end=2026-10-27T09:15+00:00, prior8high=0.903000, depth_time=2026-10-27T09:15:29+00:00, book20_bid_proxy_usdt=905310, book20_ask_proxy_usdt=1444353, funding_indicative=0.000029, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.74%, turnover=5748590. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-27T09:15:03+00:00, last15m_closed_end=2026-10-27T09:15+00:00, prior8high=7.851000, depth_time=2026-10-27T09:15:37+00:00, book20_bid_proxy_usdt=329729, book20_ask_proxy_usdt=209518, funding_indicative=0.000188, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.23%, turnover=22200657. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-27T09:15:03+00:00, last15m_closed_end=2026-10-27T09:15+00:00, prior8high=0.027080, depth_time=2026-10-27T09:15:11+00:00, book20_bid_proxy_usdt=70515, book20_ask_proxy_usdt=100507, funding_indicative=-0.000436, next_funding_utc=2026-10-27T10:00:00+00:00, funding_cycle_h=1, 24h_change=-7.32%, turnover=7550703. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-27T09:15:03+00:00, last15m_closed_end=2026-10-27T09:15+00:00, prior8high=4.488000, depth_time=2026-10-27T09:15:24+00:00, book20_bid_proxy_usdt=1818759, book20_ask_proxy_usdt=2072057, funding_indicative=0.000078, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.79%, turnover=91532671. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-27T09:15:03+00:00, last15m_closed_end=2026-10-27T09:15+00:00, prior8high=0.411600, depth_time=2026-10-27T09:15:25+00:00, book20_bid_proxy_usdt=2405916, book20_ask_proxy_usdt=2170856, funding_indicative=0.000050, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.76%, turnover=22863209. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-27T09:15:03+00:00, last15m_closed_end=2026-10-27T09:15+00:00, prior8high=0.004216, depth_time=2026-10-27T09:15:16+00:00, book20_bid_proxy_usdt=1683935, book20_ask_proxy_usdt=1885125, funding_indicative=0.000050, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.29%, turnover=21296042. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-10-27T09:15:03+00:00, last15m_closed_end=2026-10-27T09:15+00:00, prior8high=100.360000, depth_time=2026-10-27T09:15:41+00:00, book20_bid_proxy_usdt=16880764, book20_ask_proxy_usdt=12265820, funding_indicative=0.000054, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.05%, turnover=664484329. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-27T09:15:03+00:00, last15m_closed_end=2026-10-27T09:15+00:00, prior8high=250.230000, depth_time=2026-10-27T09:15:36+00:00, book20_bid_proxy_usdt=162889, book20_ask_proxy_usdt=99254, funding_indicative=0.000050, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.25%, turnover=44315784. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-27T09:15:03+00:00, last15m_closed_end=2026-10-27T09:15+00:00, prior8high=0.439800, depth_time=2026-10-27T09:15:34+00:00, book20_bid_proxy_usdt=3438422, book20_ask_proxy_usdt=3337371, funding_indicative=-0.000192, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.33%, turnover=65645215. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
