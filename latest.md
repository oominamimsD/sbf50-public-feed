# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-02T21:30:44Z**
- feed_generated_utc: 2026-11-02T21:30:47+00:00
- source_sha256: `656f9c55a1acf7cde43988159e9d846dbd16c81f93a97a85d3d4460c72a44aff`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 21; crypto_deep: 15
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-02T21:30+00:00, close=76779.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-02T21:00+00:00, close=76766.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-02T20:00+00:00, close=77068.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.119400|-10.02|-52.00|-9.13|6428973|8.39|
|ZEC_USDT|1143.860000|-8.79|-8.32|-7.90|1864920555|0.44|
|XPL_USDT|0.066410|-4.55|-10.60|-3.66|9981872|1.51|
|QNT_USDT|194.400000|-3.97|-7.55|-3.08|50704075|4.11|
|PUMPFUN_USDT|0.003941|-3.97|-8.94|-3.08|11163281|5.07|
|ZRO_USDT|1.701100|-3.79|-0.35|-2.90|6224197|0.59|
|NEAR_USDT|3.889000|-3.01|-14.95|-2.12|81830355|5.14|
|ENA_USDT|0.169980|-2.89|-19.19|-2.00|75087968|2.35|
|DASH_USDT|45.890000|-2.77|-12.12|-1.88|10255497|6.53|
|AAVE_USDT|127.060000|-2.68|-7.07|-1.79|23396196|0.79|
|TIA_USDT|0.445500|-2.49|-16.83|-1.60|12320559|4.49|
|TRUMPOFFICIAL_USDT|1.596000|-2.44|-5.50|-1.55|12616741|6.26|
|Q_USDT|0.025410|-2.41|-56.97|-1.52|6166499|3.94|
|HYPE_USDT|83.689000|-2.36|6.68|-1.47|105156156|0.12|
|LIT_USDT|3.034000|-2.34|-2.70|-1.45|10878422|2.96|
|XLM_USDT|0.163730|-2.30|-3.45|-1.41|32738957|2.44|
|WLD_USDT|0.372600|-2.25|-16.26|-1.36|48623797|2.68|
|ARB_USDT|0.155740|-2.25|-8.38|-1.36|13638329|2.57|
|SOL_USDT|91.610000|-2.03|-10.04|-1.14|758041214|1.09|
|UNI_USDT|7.056000|-2.02|-0.77|-1.13|93513140|1.42|
|OP_USDT|0.110160|-2.01|-1.37|-1.12|12509060|1.82|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|127.060000|126.360000|127.060000|0.81|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|45.890000|45.500000|45.890000|0.19|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.169980|0.169020|0.169980|0.56|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|83.689000|82.855000|83.694000|0.76|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.034000|3.046000|3.034000|1.29|N|Y/Y|N/N|Y|N|
|NEAR_USDT|3.889000|3.843000|3.889000|0.79|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003941|0.003877|0.003941|0.52|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|194.400000|192.300000|194.400000|0.69|N|Y/Y|Y/N|Y|N|
|Q_USDT|0.025410|0.025090|0.025410|0.40|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.445500|0.440400|0.445500|0.32|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.596000|1.563000|1.596000|1.24|N|Y/Y|Y/Y|Y|N|
|UAI_USDT|0.119400|0.112100|0.119400|1.06|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.066410|0.066130|0.066410|1.95|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1143.860000|1127.170000|1144.980000|0.72|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.701100|1.692200|1.701100|1.05|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-02T21:30:00+00:00, last15m_closed_end=2026-11-02T21:30+00:00, prior8high=127.880000, depth_time=2026-11-02T21:30:31+00:00, book20_bid_proxy_usdt=553354, book20_ask_proxy_usdt=498430, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.68%, turnover=23396196. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-02T21:30:00+00:00, last15m_closed_end=2026-11-02T21:30+00:00, prior8high=46.230000, depth_time=2026-11-02T21:30:29+00:00, book20_bid_proxy_usdt=381495, book20_ask_proxy_usdt=670748, funding_indicative=0.000035, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.77%, turnover=10255497. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-02T21:30:00+00:00, last15m_closed_end=2026-11-02T21:30+00:00, prior8high=0.172110, depth_time=2026-11-02T21:30:26+00:00, book20_bid_proxy_usdt=114182, book20_ask_proxy_usdt=283633, funding_indicative=0.000050, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.89%, turnover=75087968. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-02T21:30:04+00:00, last15m_closed_end=2026-11-02T21:30+00:00, prior8high=84.144000, depth_time=2026-11-02T21:30:41+00:00, book20_bid_proxy_usdt=31834, book20_ask_proxy_usdt=156077, funding_indicative=0.000050, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.36%, turnover=105156156. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-02T21:30:00+00:00, last15m_closed_end=2026-11-02T21:30+00:00, prior8high=3.114000, depth_time=2026-11-02T21:30:43+00:00, book20_bid_proxy_usdt=18140, book20_ask_proxy_usdt=35638, funding_indicative=0.000050, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.34%, turnover=10878422. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-02T21:30:00+00:00, last15m_closed_end=2026-11-02T21:30+00:00, prior8high=3.936000, depth_time=2026-11-02T21:30:24+00:00, book20_bid_proxy_usdt=2171090, book20_ask_proxy_usdt=2468064, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.01%, turnover=81830355. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-02T21:30:00+00:00, last15m_closed_end=2026-11-02T21:30+00:00, prior8high=0.003989, depth_time=2026-11-02T21:30:18+00:00, book20_bid_proxy_usdt=625767, book20_ask_proxy_usdt=1518375, funding_indicative=0.000050, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.97%, turnover=11163281. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-02T21:30:00+00:00, last15m_closed_end=2026-11-02T21:30+00:00, prior8high=195.840000, depth_time=2026-11-02T21:30:15+00:00, book20_bid_proxy_usdt=73948, book20_ask_proxy_usdt=57094, funding_indicative=0.000073, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.97%, turnover=50704075. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-11-02T21:30:00+00:00, last15m_closed_end=2026-11-02T21:30+00:00, prior8high=0.026180, depth_time=2026-11-02T21:30:38+00:00, book20_bid_proxy_usdt=60576, book20_ask_proxy_usdt=46124, funding_indicative=-0.000371, next_funding_utc=2026-11-02T22:00:00+00:00, funding_cycle_h=1, 24h_change=-2.41%, turnover=6166499. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-02T21:30:00+00:00, last15m_closed_end=2026-11-02T21:30+00:00, prior8high=0.446800, depth_time=2026-11-02T21:30:34+00:00, book20_bid_proxy_usdt=190621, book20_ask_proxy_usdt=248060, funding_indicative=0.000050, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.49%, turnover=12320559. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-02T21:30:00+00:00, last15m_closed_end=2026-11-02T21:30+00:00, prior8high=1.596000, depth_time=2026-11-02T21:30:36+00:00, book20_bid_proxy_usdt=1100572, book20_ask_proxy_usdt=1049868, funding_indicative=0.000025, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.44%, turnover=12616741. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-02T21:30:00+00:00, last15m_closed_end=2026-11-02T21:30+00:00, prior8high=0.117700, depth_time=2026-11-02T21:30:07+00:00, book20_bid_proxy_usdt=119212, book20_ask_proxy_usdt=126248, funding_indicative=-0.000156, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-10.02%, turnover=6428973. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-02T21:30:00+00:00, last15m_closed_end=2026-11-02T21:30+00:00, prior8high=0.067700, depth_time=2026-11-02T21:30:13+00:00, book20_bid_proxy_usdt=299291, book20_ask_proxy_usdt=474470, funding_indicative=0.000036, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.55%, turnover=9981872. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-02T21:30:04+00:00, last15m_closed_end=2026-11-02T21:30+00:00, prior8high=1164.850000, depth_time=2026-11-02T21:30:10+00:00, book20_bid_proxy_usdt=245068, book20_ask_proxy_usdt=1105866, funding_indicative=0.000068, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-8.79%, turnover=1864920555. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-02T21:30:00+00:00, last15m_closed_end=2026-11-02T21:30+00:00, prior8high=1.734000, depth_time=2026-11-02T21:30:21+00:00, book20_bid_proxy_usdt=43115, book20_ask_proxy_usdt=26215, funding_indicative=0.000050, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.79%, turnover=6224197. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
