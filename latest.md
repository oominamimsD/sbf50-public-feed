# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T12:15:49Z**
- feed_generated_utc: 2026-10-27T12:15:53+00:00
- source_sha256: `e88a021963529b451dc9b049a17dd8013abeb48d70d13d1c5208871b1781152d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 19; crypto_deep: 15
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T12:15+00:00, close=79885.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-27T12:00+00:00, close=79880.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-27T12:00+00:00, close=79880.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.025170|-8.73|104.96|-8.11|7243833|3.97|
|ENA_USDT|0.201180|-4.36|7.05|-3.74|85738231|0.50|
|AAVE_USDT|130.800000|-4.33|-11.15|-3.71|27597225|0.76|
|PUMPFUN_USDT|0.004143|-4.27|-7.02|-3.65|19353108|2.41|
|QNT_USDT|201.370000|-4.23|2.89|-3.61|112452536|1.99|
|DOT_USDT|0.983100|-3.86|-14.27|-3.24|11004917|1.02|
|FILECOIN_USDT|0.888900|-3.45|-12.16|-2.83|6432423|1.12|
|ZRO_USDT|1.652000|-3.22|-13.14|-2.60|5034471|2.42|
|WLD_USDT|0.430700|-3.21|-14.93|-2.59|66779745|2.32|
|AVAX_USDT|8.739000|-2.86|-8.60|-2.24|20702896|1.14|
|ONDO_USDT|0.407200|-2.76|-5.87|-2.14|22602102|2.46|
|TIA_USDT|0.523200|-2.33|-14.01|-1.71|17171191|5.73|
|NEAR_USDT|4.471000|-2.23|-8.82|-1.61|89816464|2.23|
|TAO_USDT|247.900000|-2.21|-7.60|-1.59|49558932|0.40|
|HBAR_USDT|0.075660|-2.19|-7.58|-1.57|10682877|1.32|
|PEPE_USDT|0.000004|-2.06|3.96|-1.44|59226165|0.23|
|LINK_USDT|11.297000|-2.00|-5.40|-1.38|131058587|0.89|
|ARB_USDT|0.166890|-1.82|-14.69|-1.20|17510650|3.00|
|SOL_USDT|100.030000|-1.77|-3.90|-1.15|675274031|1.00|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|130.800000|129.420000|130.700000|0.68|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.739000|8.687000|8.739000|1.41|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.983100|0.979300|0.983100|0.22|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.201180|0.197200|0.201180|0.65|N|Y/Y|Y/N|Y|N|
|FILECOIN_USDT|0.888900|0.884300|0.888600|0.87|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.075660|0.075460|0.075660|0.29|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.025170|0.024650|0.025170|0.40|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.471000|4.389000|4.471000|1.19|N|N/N|Y/Y|Y|N|
|ONDO_USDT|0.407200|0.402800|0.407200|0.47|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004143|0.004100|0.004143|1.07|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|201.370000|200.970000|201.370000|1.03|N|Y/N|N/N|Y|N|
|TAO_USDT|247.900000|245.490000|247.900000|0.99|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.523200|0.519500|0.523400|0.86|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.430700|0.427800|0.430700|2.28|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.652000|1.605300|1.652000|1.06|N|N/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T12:15:00+00:00, last15m_closed_end=2026-10-27T12:15+00:00, prior8high=131.800000, depth_time=2026-10-27T12:15:13+00:00, book20_bid_proxy_usdt=379598, book20_ask_proxy_usdt=699294, funding_indicative=0.000097, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.33%, turnover=27597225. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-27T12:15:00+00:00, last15m_closed_end=2026-10-27T12:15+00:00, prior8high=8.826000, depth_time=2026-10-27T12:15:35+00:00, book20_bid_proxy_usdt=861508, book20_ask_proxy_usdt=1894913, funding_indicative=0.000052, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.86%, turnover=20702896. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T12:15:00+00:00, last15m_closed_end=2026-10-27T12:15+00:00, prior8high=0.992500, depth_time=2026-10-27T12:15:21+00:00, book20_bid_proxy_usdt=452271, book20_ask_proxy_usdt=369594, funding_indicative=-0.000117, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.86%, turnover=11004917. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-27T12:15:00+00:00, last15m_closed_end=2026-10-27T12:15+00:00, prior8high=0.205910, depth_time=2026-10-27T12:15:12+00:00, book20_bid_proxy_usdt=152254, book20_ask_proxy_usdt=205616, funding_indicative=-0.000001, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.36%, turnover=85738231. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T12:15:00+00:00, last15m_closed_end=2026-10-27T12:15+00:00, prior8high=0.900900, depth_time=2026-10-27T12:15:26+00:00, book20_bid_proxy_usdt=1228276, book20_ask_proxy_usdt=1584668, funding_indicative=0.000054, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.45%, turnover=6432423. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-27T12:15:00+00:00, last15m_closed_end=2026-10-27T12:15+00:00, prior8high=0.076310, depth_time=2026-10-27T12:15:48+00:00, book20_bid_proxy_usdt=996705, book20_ask_proxy_usdt=1165528, funding_indicative=0.000100, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.19%, turnover=10682877. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-27T12:15:00+00:00, last15m_closed_end=2026-10-27T12:15+00:00, prior8high=0.025490, depth_time=2026-10-27T12:15:09+00:00, book20_bid_proxy_usdt=132011, book20_ask_proxy_usdt=122257, funding_indicative=-0.000291, next_funding_utc=2026-10-27T13:00:00+00:00, funding_cycle_h=1, 24h_change=-8.73%, turnover=7243833. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-27T12:15:00+00:00, last15m_closed_end=2026-10-27T12:15+00:00, prior8high=4.522000, depth_time=2026-10-27T12:15:42+00:00, book20_bid_proxy_usdt=2794637, book20_ask_proxy_usdt=2948784, funding_indicative=0.000100, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.23%, turnover=89816464. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-27T12:15:00+00:00, last15m_closed_end=2026-10-27T12:15+00:00, prior8high=0.411000, depth_time=2026-10-27T12:15:38+00:00, book20_bid_proxy_usdt=2227359, book20_ask_proxy_usdt=3561331, funding_indicative=0.000022, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.76%, turnover=22602102. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-27T12:15:00+00:00, last15m_closed_end=2026-10-27T12:15+00:00, prior8high=0.004221, depth_time=2026-10-27T12:15:18+00:00, book20_bid_proxy_usdt=2012932, book20_ask_proxy_usdt=2866541, funding_indicative=0.000050, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.27%, turnover=19353108. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-27T12:15:00+00:00, last15m_closed_end=2026-10-27T12:15+00:00, prior8high=206.180000, depth_time=2026-10-27T12:15:21+00:00, book20_bid_proxy_usdt=53342, book20_ask_proxy_usdt=62084, funding_indicative=-0.000191, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.23%, turnover=112452536. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-27T12:15:00+00:00, last15m_closed_end=2026-10-27T12:15+00:00, prior8high=250.060000, depth_time=2026-10-27T12:15:46+00:00, book20_bid_proxy_usdt=131907, book20_ask_proxy_usdt=125683, funding_indicative=0.000049, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.21%, turnover=49558932. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-27T12:15:00+00:00, last15m_closed_end=2026-10-27T12:15+00:00, prior8high=0.529500, depth_time=2026-10-27T12:15:40+00:00, book20_bid_proxy_usdt=386712, book20_ask_proxy_usdt=487681, funding_indicative=0.000037, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.33%, turnover=17171191. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-27T12:15:00+00:00, last15m_closed_end=2026-10-27T12:15+00:00, prior8high=0.435500, depth_time=2026-10-27T12:15:33+00:00, book20_bid_proxy_usdt=3578139, book20_ask_proxy_usdt=3835020, funding_indicative=-0.000068, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.21%, turnover=66779745. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-27T12:15:00+00:00, last15m_closed_end=2026-10-27T12:15+00:00, prior8high=1.668700, depth_time=2026-10-27T12:15:30+00:00, book20_bid_proxy_usdt=50064, book20_ask_proxy_usdt=49515, funding_indicative=0.000020, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.22%, turnover=5034471. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
