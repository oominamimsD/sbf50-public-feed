# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T11:15:42Z**
- feed_generated_utc: 2026-10-27T11:15:46+00:00
- source_sha256: `15117b7d64c6a0a5a43a545900708c749b99f7fe5545fe8d24a45ad84836eaba`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 18; crypto_deep: 15
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T11:15+00:00, close=79905.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-27T11:00+00:00, close=79941, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-27T08:00+00:00, close=79774.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BULLA_USDT|0.076000|-49.03|5.52|-48.41|11201640|2.63|
|IRYS_USDT|0.024860|-9.86|102.44|-9.24|7421016|4.02|
|AAVE_USDT|131.400000|-3.89|-10.74|-3.27|27491120|0.76|
|DOT_USDT|0.988300|-3.35|-13.82|-2.73|11124799|1.01|
|ZRO_USDT|1.652300|-3.21|-13.12|-2.59|5109478|0.61|
|PUMPFUN_USDT|0.004192|-3.14|-5.92|-2.52|20472817|2.38|
|QNT_USDT|203.770000|-3.09|4.12|-2.47|122364490|2.94|
|WLD_USDT|0.432200|-2.87|-14.63|-2.25|67592309|2.31|
|FILECOIN_USDT|0.897100|-2.56|-11.35|-1.94|6343622|1.11|
|ONDO_USDT|0.409000|-2.34|-5.45|-1.72|22995420|2.44|
|AVAX_USDT|8.788000|-2.32|-8.09|-1.70|21326573|1.14|
|PEPE_USDT|0.000004|-2.01|4.01|-1.39|59417478|0.23|
|TAO_USDT|248.800000|-1.85|-7.26|-1.23|49322534|1.21|
|HBAR_USDT|0.075930|-1.84|-7.25|-1.22|10853056|1.32|
|NEAR_USDT|4.491000|-1.79|-8.42|-1.17|92470108|2.23|
|ARB_USDT|0.167040|-1.73|-14.61|-1.11|17876792|0.60|
|SOL_USDT|100.100000|-1.70|-3.83|-1.08|676185112|1.00|
|TIA_USDT|0.526700|-1.68|-13.44|-1.06|17117806|1.90|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|131.400000|129.420000|131.400000|0.64|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.788000|8.687000|8.788000|1.76|N|Y/Y|Y/Y|Y|N|
|BULLA_USDT|0.076000|0.067070|0.076000|1.80|N|Y/Y|N/N|Y|N|
|DOT_USDT|0.988300|0.979300|0.988300|1.73|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|0.897100|0.884300|0.897500|1.24|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.075930|0.075460|0.075960|1.98|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.024860|0.024890|0.024860|1.01|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.491000|4.389000|4.491000|6.86|N|N/Y|Y/Y|Y|N|
|ONDO_USDT|0.409000|0.402800|0.409000|1.72|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|1.20|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004192|0.004093|0.004192|0.84|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|203.770000|200.970000|203.780000|0.80|N|N/N|N/N|Y|N|
|TAO_USDT|248.800000|245.490000|248.800000|3.43|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.432200|0.427500|0.432300|2.10|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.652300|1.605300|1.652000|1.81|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T11:15:01+00:00, last15m_closed_end=2026-10-27T11:15+00:00, prior8high=131.750000, depth_time=2026-10-27T11:15:12+00:00, book20_bid_proxy_usdt=411274, book20_ask_proxy_usdt=397545, funding_indicative=0.000100, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.89%, turnover=27491120. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-27T11:15:01+00:00, last15m_closed_end=2026-10-27T11:15+00:00, prior8high=8.826000, depth_time=2026-10-27T11:15:32+00:00, book20_bid_proxy_usdt=1315459, book20_ask_proxy_usdt=1932783, funding_indicative=0.000037, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.32%, turnover=21326573. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BULLA_USDT: quote_utc=2026-10-27T11:15:00+00:00, last15m_closed_end=2026-10-27T11:15+00:00, prior8high=0.129000, depth_time=2026-10-27T11:15:08+00:00, book20_bid_proxy_usdt=19508, book20_ask_proxy_usdt=29305, funding_indicative=-0.006613, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-49.03%, turnover=11201640. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T11:15:01+00:00, last15m_closed_end=2026-10-27T11:15+00:00, prior8high=0.995100, depth_time=2026-10-27T11:15:15+00:00, book20_bid_proxy_usdt=388508, book20_ask_proxy_usdt=268920, funding_indicative=-0.000063, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.35%, turnover=11124799. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T11:15:01+00:00, last15m_closed_end=2026-10-27T11:15+00:00, prior8high=0.899900, depth_time=2026-10-27T11:15:27+00:00, book20_bid_proxy_usdt=1067001, book20_ask_proxy_usdt=1912331, funding_indicative=0.000049, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.56%, turnover=6343622. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-27T11:15:01+00:00, last15m_closed_end=2026-10-27T11:15+00:00, prior8high=0.076460, depth_time=2026-10-27T11:15:38+00:00, book20_bid_proxy_usdt=1080980, book20_ask_proxy_usdt=1285245, funding_indicative=0.000100, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.84%, turnover=10853056. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-27T11:15:00+00:00, last15m_closed_end=2026-10-27T11:15+00:00, prior8high=0.026140, depth_time=2026-10-27T11:15:10+00:00, book20_bid_proxy_usdt=164355, book20_ask_proxy_usdt=115400, funding_indicative=-0.000736, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=1, 24h_change=-9.86%, turnover=7421016. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-27T11:15:00+00:00, last15m_closed_end=2026-10-27T11:15+00:00, prior8high=4.510000, depth_time=2026-10-27T11:15:41+00:00, book20_bid_proxy_usdt=4235539, book20_ask_proxy_usdt=531695, funding_indicative=0.000100, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.79%, turnover=92470108. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-27T11:15:01+00:00, last15m_closed_end=2026-10-27T11:15+00:00, prior8high=0.409900, depth_time=2026-10-27T11:15:29+00:00, book20_bid_proxy_usdt=2410674, book20_ask_proxy_usdt=2719033, funding_indicative=0.000047, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.34%, turnover=22995420. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-27T11:15:01+00:00, last15m_closed_end=2026-10-27T11:15+00:00, prior8high=0.000004, depth_time=2026-10-27T11:15:34+00:00, book20_bid_proxy_usdt=44069, book20_ask_proxy_usdt=74258, funding_indicative=0.000091, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.01%, turnover=59417478. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-27T11:15:01+00:00, last15m_closed_end=2026-10-27T11:15+00:00, prior8high=0.004213, depth_time=2026-10-27T11:15:20+00:00, book20_bid_proxy_usdt=2800004, book20_ask_proxy_usdt=2478773, funding_indicative=0.000050, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.14%, turnover=20472817. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-27T11:15:00+00:00, last15m_closed_end=2026-10-27T11:15+00:00, prior8high=207.860000, depth_time=2026-10-27T11:15:22+00:00, book20_bid_proxy_usdt=42616, book20_ask_proxy_usdt=46400, funding_indicative=-0.000205, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.09%, turnover=122364490. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-27T11:15:01+00:00, last15m_closed_end=2026-10-27T11:15+00:00, prior8high=249.660000, depth_time=2026-10-27T11:15:36+00:00, book20_bid_proxy_usdt=131702, book20_ask_proxy_usdt=95490, funding_indicative=0.000030, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.85%, turnover=49322534. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-27T11:15:00+00:00, last15m_closed_end=2026-10-27T11:15+00:00, prior8high=0.436700, depth_time=2026-10-27T11:15:24+00:00, book20_bid_proxy_usdt=3571602, book20_ask_proxy_usdt=3573409, funding_indicative=-0.000084, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.87%, turnover=67592309. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-27T11:15:01+00:00, last15m_closed_end=2026-10-27T11:15+00:00, prior8high=1.640300, depth_time=2026-10-27T11:15:18+00:00, book20_bid_proxy_usdt=51202, book20_ask_proxy_usdt=124976, funding_indicative=0.000050, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.21%, turnover=5109478. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
