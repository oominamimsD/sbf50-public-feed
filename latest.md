# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T15:15:49Z**
- feed_generated_utc: 2026-10-27T15:15:53+00:00
- source_sha256: `8db13421aee8d3cc4a43a1f9a587640993c2fde0ecf9bd597bf306a2ded802a7`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 15; crypto_deep: 15
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T15:15+00:00, close=80285.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-27T15:00+00:00, close=80328.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-27T12:00+00:00, close=79880.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.025130|-8.88|104.64|-8.74|6331458|7.95|
|QNT_USDT|197.620000|-6.02|0.98|-5.88|89713949|1.01|
|AAVE_USDT|131.080000|-4.13|-10.96|-3.99|26411373|0.76|
|DOT_USDT|0.984000|-3.77|-14.19|-3.63|11153059|1.02|
|FILECOIN_USDT|0.887800|-3.57|-12.27|-3.43|5273666|1.13|
|WLD_USDT|0.429900|-3.39|-15.08|-3.25|69832242|2.33|
|APT_USDT|0.679600|-3.19|-10.91|-3.05|5193401|1.47|
|PUMPFUN_USDT|0.004203|-2.88|-5.67|-2.74|20497974|2.38|
|HBAR_USDT|0.075420|-2.50|-7.87|-2.36|9756585|1.33|
|AVAX_USDT|8.791000|-2.28|-8.06|-2.14|22979472|1.14|
|ICP_USDT|2.570000|-2.28|-9.91|-2.14|5063034|3.89|
|ARB_USDT|0.166950|-1.78|-14.66|-1.64|16278454|0.60|
|TAO_USDT|249.240000|-1.68|-7.10|-1.54|49327000|1.20|
|LINK_USDT|11.370000|-1.37|-4.79|-1.23|122956623|0.88|
|SOL_USDT|100.500000|-1.31|-3.44|-1.17|675365576|0.99|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|131.080000|130.180000|131.080000|0.79|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.679600|0.672700|0.679600|1.25|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.166950|0.166210|0.166950|1.05|N|N/N|Y/Y|Y|N|
|AVAX_USDT|8.791000|8.732000|8.791000|0.61|N|N/Y|Y/Y|Y|N|
|DOT_USDT|0.984000|0.977000|0.984000|1.20|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|0.887800|0.880500|0.887800|2.56|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.075420|0.075590|0.075420|2.51|Y|Y/Y|Y/Y|Y|Y|
|ICP_USDT|2.570000|2.552000|2.570000|0.27|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.025130|0.024590|0.025130|1.08|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|11.370000|11.274000|11.372000|0.78|N|N/N|Y/Y|Y|N|
|PUMPFUN_USDT|0.004203|0.004167|0.004204|7.00|N|N/N|Y/Y|Y|N|
|QNT_USDT|197.620000|196.560000|197.530000|0.86|N|Y/Y|N/N|Y|N|
|SOL_USDT|100.500000|99.820000|100.500000|1.62|N|N/N|Y/Y|Y|N|
|TAO_USDT|249.240000|247.440000|249.240000|1.07|N|N/N|Y/Y|Y|N|
|WLD_USDT|0.429900|0.424600|0.429900|0.58|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T15:15:02+00:00, last15m_closed_end=2026-10-27T15:15+00:00, prior8high=132.540000, depth_time=2026-10-27T15:15:14+00:00, book20_bid_proxy_usdt=372467, book20_ask_proxy_usdt=528183, funding_indicative=0.000100, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.13%, turnover=26411373. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-27T15:15:02+00:00, last15m_closed_end=2026-10-27T15:15+00:00, prior8high=0.688200, depth_time=2026-10-27T15:15:24+00:00, book20_bid_proxy_usdt=160416, book20_ask_proxy_usdt=126320, funding_indicative=-0.000028, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.19%, turnover=5193401. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-27T15:15:02+00:00, last15m_closed_end=2026-10-27T15:15+00:00, prior8high=0.169060, depth_time=2026-10-27T15:15:40+00:00, book20_bid_proxy_usdt=79964, book20_ask_proxy_usdt=86448, funding_indicative=0.000009, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.78%, turnover=16278454. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-27T15:15:02+00:00, last15m_closed_end=2026-10-27T15:15+00:00, prior8high=8.857000, depth_time=2026-10-27T15:15:31+00:00, book20_bid_proxy_usdt=1311531, book20_ask_proxy_usdt=1079802, funding_indicative=0.000053, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.28%, turnover=22979472. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T15:15:02+00:00, last15m_closed_end=2026-10-27T15:15+00:00, prior8high=0.994700, depth_time=2026-10-27T15:15:17+00:00, book20_bid_proxy_usdt=290947, book20_ask_proxy_usdt=384515, funding_indicative=-0.000150, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.77%, turnover=11153059. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T15:15:02+00:00, last15m_closed_end=2026-10-27T15:15+00:00, prior8high=0.896800, depth_time=2026-10-27T15:15:19+00:00, book20_bid_proxy_usdt=1055158, book20_ask_proxy_usdt=1685103, funding_indicative=0.000019, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.57%, turnover=5273666. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-27T15:15:02+00:00, last15m_closed_end=2026-10-27T15:15+00:00, prior8high=0.076530, depth_time=2026-10-27T15:15:29+00:00, book20_bid_proxy_usdt=998031, book20_ask_proxy_usdt=935128, funding_indicative=0.000076, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.50%, turnover=9756585. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-27T15:15:02+00:00, last15m_closed_end=2026-10-27T15:15+00:00, prior8high=2.598000, depth_time=2026-10-27T15:15:36+00:00, book20_bid_proxy_usdt=1086393, book20_ask_proxy_usdt=1187085, funding_indicative=0.000100, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.28%, turnover=5063034. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-27T15:15:01+00:00, last15m_closed_end=2026-10-27T15:15+00:00, prior8high=0.025580, depth_time=2026-10-27T15:15:06+00:00, book20_bid_proxy_usdt=131471, book20_ask_proxy_usdt=95882, funding_indicative=-0.000693, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=1, 24h_change=-8.88%, turnover=6331458. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-10-27T15:15:01+00:00, last15m_closed_end=2026-10-27T15:15+00:00, prior8high=11.418000, depth_time=2026-10-27T15:15:44+00:00, book20_bid_proxy_usdt=640754, book20_ask_proxy_usdt=573156, funding_indicative=0.000100, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.37%, turnover=122956623. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-27T15:15:02+00:00, last15m_closed_end=2026-10-27T15:15+00:00, prior8high=0.004237, depth_time=2026-10-27T15:15:27+00:00, book20_bid_proxy_usdt=2354050, book20_ask_proxy_usdt=2190461, funding_indicative=0.000050, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.88%, turnover=20497974. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-27T15:15:01+00:00, last15m_closed_end=2026-10-27T15:15+00:00, prior8high=201.960000, depth_time=2026-10-27T15:15:12+00:00, book20_bid_proxy_usdt=72995, book20_ask_proxy_usdt=75055, funding_indicative=-0.000201, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.02%, turnover=89713949. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-10-27T15:15:01+00:00, last15m_closed_end=2026-10-27T15:15+00:00, prior8high=100.930000, depth_time=2026-10-27T15:15:47+00:00, book20_bid_proxy_usdt=17244338, book20_ask_proxy_usdt=13952903, funding_indicative=0.000070, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.31%, turnover=675365576. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-27T15:15:01+00:00, last15m_closed_end=2026-10-27T15:15+00:00, prior8high=250.950000, depth_time=2026-10-27T15:15:43+00:00, book20_bid_proxy_usdt=153847, book20_ask_proxy_usdt=109992, funding_indicative=0.000050, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.68%, turnover=49327000. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-27T15:15:01+00:00, last15m_closed_end=2026-10-27T15:15+00:00, prior8high=0.435600, depth_time=2026-10-27T15:15:20+00:00, book20_bid_proxy_usdt=2709598, book20_ask_proxy_usdt=3565856, funding_indicative=-0.000046, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.39%, turnover=69832242. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
