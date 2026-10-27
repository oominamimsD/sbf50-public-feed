# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T14:00:47Z**
- feed_generated_utc: 2026-10-27T14:00:51+00:00
- source_sha256: `c4dc7d030f22ee132faca0f686bd36029ecc89282326d8d5d33e88bef1de3986`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 16; crypto_deep: 15
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T14:00+00:00, close=80014.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-27T14:00+00:00, close=80014.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-27T12:00+00:00, close=79880.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.024740|-10.29|101.46|-9.82|6439545|4.04|
|QNT_USDT|197.520000|-6.06|0.92|-5.59|96797051|2.03|
|AAVE_USDT|130.920000|-5.04|-11.07|-4.57|27167222|0.76|
|WLD_USDT|0.426600|-4.81|-15.74|-4.34|69684098|2.34|
|DOT_USDT|0.982800|-4.69|-14.30|-4.22|10856623|3.05|
|FILECOIN_USDT|0.885100|-4.46|-12.53|-3.99|5729089|1.13|
|TIA_USDT|0.522300|-3.56|-14.16|-3.09|17223847|1.92|
|PUMPFUN_USDT|0.004193|-3.11|-5.90|-2.64|20942996|2.38|
|AVAX_USDT|8.766000|-2.61|-8.32|-2.14|23282822|1.14|
|TAO_USDT|248.400000|-2.53|-7.41|-2.06|50799309|0.40|
|ICP_USDT|2.564000|-2.50|-10.12|-2.03|5090604|3.90|
|HBAR_USDT|0.075830|-2.38|-7.37|-1.91|9473885|1.32|
|LINK_USDT|11.321000|-1.79|-5.20|-1.32|127704860|1.77|
|ARB_USDT|0.167000|-1.75|-14.63|-1.28|16770771|0.60|
|SOL_USDT|100.100000|-1.70|-3.83|-1.23|679909758|1.00|
|ADA_USDT|0.203400|-1.59|-6.26|-1.12|21522434|4.92|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|130.920000|130.520000|130.920000|0.63|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.167000|0.166210|0.166990|0.90|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.766000|8.732000|8.766000|1.17|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.982800|0.982200|0.982800|1.35|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|0.885100|0.885000|0.885100|0.81|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.075830|0.075590|0.075830|0.51|N|Y/Y|Y/Y|Y|N|
|ICP_USDT|2.564000|2.563000|2.564000|1.86|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.024740|0.024590|0.024720|0.86|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|11.321000|11.274000|11.324000|1.16|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004193|0.004133|0.004193|21.74|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|197.520000|197.350000|197.570000|1.43|N|Y/Y|N/N|Y|N|
|SOL_USDT|100.100000|99.900000|100.100000|2.44|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|248.400000|247.220000|248.400000|0.69|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.522300|0.519900|0.522300|0.76|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.426600|0.425700|0.426600|2.48|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T14:00:02+00:00, last15m_closed_end=2026-10-27T14:00+00:00, prior8high=133.100000, depth_time=2026-10-27T14:00:15+00:00, book20_bid_proxy_usdt=363738, book20_ask_proxy_usdt=283588, funding_indicative=0.000100, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.04%, turnover=27167222. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-27T14:00:02+00:00, last15m_closed_end=2026-10-27T14:00+00:00, prior8high=0.169600, depth_time=2026-10-27T14:00:43+00:00, book20_bid_proxy_usdt=126484, book20_ask_proxy_usdt=81431, funding_indicative=0.000016, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.75%, turnover=16770771. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-27T14:00:02+00:00, last15m_closed_end=2026-10-27T14:00+00:00, prior8high=8.864000, depth_time=2026-10-27T14:00:31+00:00, book20_bid_proxy_usdt=1728668, book20_ask_proxy_usdt=1080026, funding_indicative=0.000041, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.61%, turnover=23282822. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T14:00:02+00:00, last15m_closed_end=2026-10-27T14:00+00:00, prior8high=0.996900, depth_time=2026-10-27T14:00:20+00:00, book20_bid_proxy_usdt=290439, book20_ask_proxy_usdt=292812, funding_indicative=-0.000216, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.69%, turnover=10856623. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T14:00:02+00:00, last15m_closed_end=2026-10-27T14:00+00:00, prior8high=0.902000, depth_time=2026-10-27T14:00:22+00:00, book20_bid_proxy_usdt=1062558, book20_ask_proxy_usdt=1313862, funding_indicative=0.000046, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.46%, turnover=5729089. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-27T14:00:02+00:00, last15m_closed_end=2026-10-27T14:00+00:00, prior8high=0.076600, depth_time=2026-10-27T14:00:38+00:00, book20_bid_proxy_usdt=609576, book20_ask_proxy_usdt=857979, funding_indicative=0.000076, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.38%, turnover=9473885. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-27T14:00:02+00:00, last15m_closed_end=2026-10-27T14:00+00:00, prior8high=2.608000, depth_time=2026-10-27T14:00:36+00:00, book20_bid_proxy_usdt=1110331, book20_ask_proxy_usdt=933603, funding_indicative=0.000100, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.50%, turnover=5090604. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-27T14:00:02+00:00, last15m_closed_end=2026-10-27T14:00+00:00, prior8high=0.025210, depth_time=2026-10-27T14:00:09+00:00, book20_bid_proxy_usdt=159026, book20_ask_proxy_usdt=81459, funding_indicative=-0.000252, next_funding_utc=2026-10-27T15:00:00+00:00, funding_cycle_h=1, 24h_change=-10.29%, turnover=6439545. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-10-27T14:00:02+00:00, last15m_closed_end=2026-10-27T14:00+00:00, prior8high=11.453000, depth_time=2026-10-27T14:00:41+00:00, book20_bid_proxy_usdt=385794, book20_ask_proxy_usdt=392204, funding_indicative=0.000100, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.79%, turnover=127704860. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-27T14:00:02+00:00, last15m_closed_end=2026-10-27T14:00+00:00, prior8high=0.004256, depth_time=2026-10-27T14:00:28+00:00, book20_bid_proxy_usdt=1878628, book20_ask_proxy_usdt=1828322, funding_indicative=0.000050, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.11%, turnover=20942996. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-27T14:00:02+00:00, last15m_closed_end=2026-10-27T14:00+00:00, prior8high=203.620000, depth_time=2026-10-27T14:00:12+00:00, book20_bid_proxy_usdt=51565, book20_ask_proxy_usdt=62341, funding_indicative=-0.000230, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.06%, turnover=96797051. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-10-27T14:00:02+00:00, last15m_closed_end=2026-10-27T14:00+00:00, prior8high=101.160000, depth_time=2026-10-27T14:00:46+00:00, book20_bid_proxy_usdt=16467319, book20_ask_proxy_usdt=14483814, funding_indicative=0.000083, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.70%, turnover=679909758. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-27T14:00:02+00:00, last15m_closed_end=2026-10-27T14:00+00:00, prior8high=251.610000, depth_time=2026-10-27T14:00:33+00:00, book20_bid_proxy_usdt=126098, book20_ask_proxy_usdt=56138, funding_indicative=0.000050, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.53%, turnover=50799309. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-27T14:00:02+00:00, last15m_closed_end=2026-10-27T14:00+00:00, prior8high=0.531400, depth_time=2026-10-27T14:00:26+00:00, book20_bid_proxy_usdt=336111, book20_ask_proxy_usdt=528925, funding_indicative=0.000007, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.56%, turnover=17223847. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-27T14:00:02+00:00, last15m_closed_end=2026-10-27T14:00+00:00, prior8high=0.438400, depth_time=2026-10-27T14:00:16+00:00, book20_bid_proxy_usdt=3017863, book20_ask_proxy_usdt=4217668, funding_indicative=-0.000050, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.81%, turnover=69684098. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
