# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-22T02:00:45Z**
- feed_generated_utc: 2026-10-22T02:00:47+00:00
- source_sha256: `b000da0dc2f5b9ba3e79554039c95e73e997c8447bb0df946b2a24c475e3ff80`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 22; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-22T02:00+00:00, close=83361.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-22T02:00+00:00, close=83361.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-22T00:00+00:00, close=84050, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IOST_USDT|0.000937|-36.01|17.05|-34.68|15282592|1.06|
|BR_USDT|0.474440|-18.08|16.35|-16.75|14024193|0.21|
|AKE_USDT|0.022865|-16.33|-11.65|-15.00|10939904|3.94|
|ZRO_USDT|1.942000|-5.18|2.53|-3.85|7541318|1.54|
|TIA_USDT|0.600400|-4.41|12.53|-3.08|36090746|1.67|
|TRUMPOFFICIAL_USDT|1.812000|-4.37|-2.94|-3.04|5675578|5.52|
|AVAX_USDT|9.518000|-4.01|-3.04|-2.68|157563358|1.05|
|DASH_USDT|51.330000|-3.11|5.70|-1.78|11523642|1.95|
|LDO_USDT|0.403400|-2.98|-0.59|-1.65|5163696|2.48|
|PEPE_USDT|0.000005|-2.86|13.01|-1.53|71725152|0.22|
|TAO_USDT|268.300000|-2.83|0.12|-1.50|62314394|1.12|
|ONDO_USDT|0.453400|-2.82|2.71|-1.49|25378113|2.21|
|DOT_USDT|1.138300|-2.79|1.22|-1.46|17636236|3.52|
|DOGE_USDT|0.081130|-2.78|-1.03|-1.45|81692672|1.23|
|AAVE_USDT|152.700000|-2.76|-2.04|-1.43|131980603|1.31|
|ARB_USDT|0.188610|-2.76|3.55|-1.43|31295991|0.53|
|ICP_USDT|2.863000|-2.71|-4.47|-1.38|5747901|3.50|
|FET_USDT|0.192600|-2.67|-5.54|-1.34|7995010|5.19|
|INJ_USDT|8.517000|-2.66|11.49|-1.33|45163111|1.17|
|STRK_USDT|0.056530|-2.58|-26.75|-1.25|24010243|1.77|
|SUI_USDT|1.016900|-2.56|0.87|-1.23|65738465|0.98|
|OP_USDT|0.127250|-2.34|-8.01|-1.01|6778364|2.36|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|152.700000|152.740000|152.690000|1.96|Y|Y/Y|N/N|Y|N|
|AKE_USDT|0.022865|0.022893|0.022865|0.76|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|9.518000|9.522000|9.519000|2.42|Y|Y/Y|Y/N|Y|N|
|BR_USDT|0.474440|0.469940|0.474440|0.57|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|51.330000|51.130000|51.330000|5.86|N|Y/Y|N/N|Y|N|
|DOGE_USDT|0.081130|0.080850|0.081140|1.12|N|Y/Y|N/N|Y|N|
|DOT_USDT|1.138300|1.135700|1.138300|2.80|N|Y/Y|Y/N|Y|N|
|IOST_USDT|0.000937|0.000912|0.000943|0.55|N|Y/Y|Y/N|Y|N|
|LDO_USDT|0.403400|0.401700|0.403400|2.42|N|Y/Y|N/N|Y|N|
|ONDO_USDT|0.453400|0.452900|0.453600|2.28|N|Y/Y|N/N|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|1.38|N|Y/Y|N/N|Y|N|
|TAO_USDT|268.300000|267.590000|268.300000|1.73|N|Y/Y|N/N|Y|N|
|TIA_USDT|0.600400|0.595900|0.600400|0.69|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.812000|1.807000|1.813000|1.81|N|Y/Y|N/N|Y|N|
|ZRO_USDT|1.942000|1.932100|1.942000|1.40|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-22T02:00:00+00:00, last15m_closed_end=2026-10-22T02:00+00:00, prior8high=156.040000, depth_time=2026-10-22T02:00:43+00:00, book20_bid_proxy_usdt=255167, book20_ask_proxy_usdt=318130, funding_indicative=-0.000011, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.76%, turnover=131980603. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-10-22T02:00:00+00:00, last15m_closed_end=2026-10-22T02:00+00:00, prior8high=0.024607, depth_time=2026-10-22T02:00:12+00:00, book20_bid_proxy_usdt=13989, book20_ask_proxy_usdt=13868, funding_indicative=0.000050, next_funding_utc=2026-10-22T04:00:00+00:00, funding_cycle_h=4, 24h_change=-16.33%, turnover=10939904. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-22T02:00:00+00:00, last15m_closed_end=2026-10-22T02:00+00:00, prior8high=9.717000, depth_time=2026-10-22T02:00:23+00:00, book20_bid_proxy_usdt=1122089, book20_ask_proxy_usdt=1618279, funding_indicative=-0.000046, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.01%, turnover=157563358. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-22T02:00:00+00:00, last15m_closed_end=2026-10-22T02:00+00:00, prior8high=0.491340, depth_time=2026-10-22T02:00:10+00:00, book20_bid_proxy_usdt=3984, book20_ask_proxy_usdt=4685, funding_indicative=-0.000175, next_funding_utc=2026-10-22T04:00:00+00:00, funding_cycle_h=4, 24h_change=-18.08%, turnover=14024193. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-22T02:00:00+00:00, last15m_closed_end=2026-10-22T02:00+00:00, prior8high=52.350000, depth_time=2026-10-22T02:00:25+00:00, book20_bid_proxy_usdt=483996, book20_ask_proxy_usdt=609065, funding_indicative=0.000096, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.11%, turnover=11523642. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOGE_USDT: quote_utc=2026-10-22T02:00:00+00:00, last15m_closed_end=2026-10-22T02:00+00:00, prior8high=0.082150, depth_time=2026-10-22T02:00:41+00:00, book20_bid_proxy_usdt=2661012, book20_ask_proxy_usdt=2207766, funding_indicative=0.000007, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.78%, turnover=81692672. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-22T02:00:00+00:00, last15m_closed_end=2026-10-22T02:00+00:00, prior8high=1.159800, depth_time=2026-10-22T02:00:39+00:00, book20_bid_proxy_usdt=303423, book20_ask_proxy_usdt=117599, funding_indicative=-0.000243, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.79%, turnover=17636236. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IOST_USDT: quote_utc=2026-10-22T02:00:00+00:00, last15m_closed_end=2026-10-22T02:00+00:00, prior8high=0.001050, depth_time=2026-10-22T02:00:08+00:00, book20_bid_proxy_usdt=4448, book20_ask_proxy_usdt=9978, funding_indicative=-0.003605, next_funding_utc=2026-10-22T03:00:00+00:00, funding_cycle_h=1, 24h_change=-36.01%, turnover=15282592. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LDO_USDT: quote_utc=2026-10-22T02:00:00+00:00, last15m_closed_end=2026-10-22T02:00+00:00, prior8high=0.409100, depth_time=2026-10-22T02:00:28+00:00, book20_bid_proxy_usdt=331120, book20_ask_proxy_usdt=427231, funding_indicative=-0.000050, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.98%, turnover=5163696. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-22T02:00:00+00:00, last15m_closed_end=2026-10-22T02:00+00:00, prior8high=0.462100, depth_time=2026-10-22T02:00:36+00:00, book20_bid_proxy_usdt=2165933, book20_ask_proxy_usdt=2213171, funding_indicative=0.000050, next_funding_utc=2026-10-22T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.82%, turnover=25378113. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-22T02:00:00+00:00, last15m_closed_end=2026-10-22T02:00+00:00, prior8high=0.000005, depth_time=2026-10-22T02:00:31+00:00, book20_bid_proxy_usdt=37783, book20_ask_proxy_usdt=75309, funding_indicative=0.000100, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.86%, turnover=71725152. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-22T02:00:00+00:00, last15m_closed_end=2026-10-22T02:00+00:00, prior8high=273.590000, depth_time=2026-10-22T02:00:33+00:00, book20_bid_proxy_usdt=84315, book20_ask_proxy_usdt=71460, funding_indicative=-0.000040, next_funding_utc=2026-10-22T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.83%, turnover=62314394. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-22T02:00:00+00:00, last15m_closed_end=2026-10-22T02:00+00:00, prior8high=0.606600, depth_time=2026-10-22T02:00:18+00:00, book20_bid_proxy_usdt=330945, book20_ask_proxy_usdt=186166, funding_indicative=-0.000119, next_funding_utc=2026-10-22T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.41%, turnover=36090746. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-10-22T02:00:00+00:00, last15m_closed_end=2026-10-22T02:00+00:00, prior8high=1.861000, depth_time=2026-10-22T02:00:20+00:00, book20_bid_proxy_usdt=1158860, book20_ask_proxy_usdt=829080, funding_indicative=0.000050, next_funding_utc=2026-10-22T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.37%, turnover=5675578. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-22T02:00:00+00:00, last15m_closed_end=2026-10-22T02:00+00:00, prior8high=1.983600, depth_time=2026-10-22T02:00:15+00:00, book20_bid_proxy_usdt=35170, book20_ask_proxy_usdt=37444, funding_indicative=0.000041, next_funding_utc=2026-10-22T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.18%, turnover=7541318. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
