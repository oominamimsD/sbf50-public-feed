# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T08:45:43Z**
- feed_generated_utc: 2026-10-27T08:45:47+00:00
- source_sha256: `236d557e69f23f52dece5d9b28388bdb6e6a018186a686c7bd1cfc49c749dadd`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 16; crypto_deep: 15
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T08:45+00:00, close=79735.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-27T08:00+00:00, close=79774.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-27T08:00+00:00, close=79774.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.025760|-6.59|109.77|-5.77|7911142|3.88|
|AAVE_USDT|130.860000|-4.29|-11.11|-3.47|24457863|0.76|
|PUMPFUN_USDT|0.004162|-3.83|-6.59|-3.01|21858995|2.40|
|DOT_USDT|0.994300|-2.76|-13.29|-1.94|10877550|1.01|
|NEAR_USDT|4.451000|-2.66|-9.23|-1.84|95451480|2.25|
|FILECOIN_USDT|0.896400|-2.63|-11.42|-1.81|6146878|1.12|
|ONDO_USDT|0.408000|-2.57|-5.68|-1.75|23444110|2.45|
|ENA_USDT|0.204980|-2.56|9.07|-1.74|87763395|0.49|
|AVAX_USDT|8.777000|-2.44|-8.20|-1.62|38158760|1.14|
|SILVER_USDT|52.940000|-2.37|-7.72|-1.55|261230317|1.89|
|WLD_USDT|0.434700|-2.31|-14.14|-1.49|68345870|2.30|
|TAO_USDT|247.990000|-2.17|-7.56|-1.35|46907458|0.81|
|SOL_USDT|99.770000|-2.03|-4.15|-1.21|720297544|1.00|
|INJ_USDT|7.778000|-1.96|-9.03|-1.14|23644399|1.29|
|PEPE_USDT|0.000004|-1.93|4.10|-1.11|63429981|1.17|
|ARB_USDT|0.166720|-1.92|-14.77|-1.10|20493554|0.60|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|130.860000|130.780000|130.860000|2.34|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.777000|8.743000|8.778000|0.73|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.994300|0.988200|0.994300|0.52|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.204980|0.204950|0.205010|1.71|N|Y/N|N/N|Y|N|
|FILECOIN_USDT|0.896400|0.892900|0.896400|0.06|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.778000|7.736000|7.778000|0.40|N|Y/Y|Y/N|Y|N|
|IRYS_USDT|0.025760|0.026070|0.025760|2.94|Y|Y/Y|Y/Y|Y|Y|
|NEAR_USDT|4.451000|4.405000|4.452000|0.85|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.408000|0.406100|0.408000|0.71|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|1.21|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004162|0.004131|0.004162|3.44|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|52.940000|52.800000|52.940000|2.06|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|99.770000|99.380000|99.770000|0.75|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|247.990000|247.500000|247.990000|2.04|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.434700|0.432500|0.434700|1.18|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T08:45:01+00:00, last15m_closed_end=2026-10-27T08:45+00:00, prior8high=132.300000, depth_time=2026-10-27T08:45:11+00:00, book20_bid_proxy_usdt=396607, book20_ask_proxy_usdt=384770, funding_indicative=0.000080, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.29%, turnover=24457863. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-27T08:45:01+00:00, last15m_closed_end=2026-10-27T08:45+00:00, prior8high=8.828000, depth_time=2026-10-27T08:45:27+00:00, book20_bid_proxy_usdt=1385776, book20_ask_proxy_usdt=1527882, funding_indicative=-0.000058, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.44%, turnover=38158760. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T08:45:01+00:00, last15m_closed_end=2026-10-27T08:45+00:00, prior8high=1.001200, depth_time=2026-10-27T08:45:15+00:00, book20_bid_proxy_usdt=321369, book20_ask_proxy_usdt=327078, funding_indicative=-0.000050, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.76%, turnover=10877550. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-27T08:45:01+00:00, last15m_closed_end=2026-10-27T08:45+00:00, prior8high=0.208980, depth_time=2026-10-27T08:45:25+00:00, book20_bid_proxy_usdt=152308, book20_ask_proxy_usdt=146018, funding_indicative=0.000050, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.56%, turnover=87763395. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T08:45:01+00:00, last15m_closed_end=2026-10-27T08:45+00:00, prior8high=0.903000, depth_time=2026-10-27T08:45:16+00:00, book20_bid_proxy_usdt=1160194, book20_ask_proxy_usdt=1497578, funding_indicative=0.000020, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.63%, turnover=6146878. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-27T08:45:01+00:00, last15m_closed_end=2026-10-27T08:45+00:00, prior8high=7.851000, depth_time=2026-10-27T08:45:38+00:00, book20_bid_proxy_usdt=259448, book20_ask_proxy_usdt=319845, funding_indicative=0.000183, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.96%, turnover=23644399. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-27T08:45:01+00:00, last15m_closed_end=2026-10-27T08:45+00:00, prior8high=0.028150, depth_time=2026-10-27T08:45:08+00:00, book20_bid_proxy_usdt=137293, book20_ask_proxy_usdt=103020, funding_indicative=-0.000663, next_funding_utc=2026-10-27T09:00:00+00:00, funding_cycle_h=1, 24h_change=-6.59%, turnover=7911142. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-27T08:45:01+00:00, last15m_closed_end=2026-10-27T08:45+00:00, prior8high=4.488000, depth_time=2026-10-27T08:45:18+00:00, book20_bid_proxy_usdt=5813627, book20_ask_proxy_usdt=4738263, funding_indicative=0.000071, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.66%, turnover=95451480. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-27T08:45:01+00:00, last15m_closed_end=2026-10-27T08:45+00:00, prior8high=0.411600, depth_time=2026-10-27T08:45:22+00:00, book20_bid_proxy_usdt=2144032, book20_ask_proxy_usdt=3114351, funding_indicative=0.000044, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.57%, turnover=23444110. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-27T08:45:01+00:00, last15m_closed_end=2026-10-27T08:45+00:00, prior8high=0.000004, depth_time=2026-10-27T08:45:42+00:00, book20_bid_proxy_usdt=23689, book20_ask_proxy_usdt=60213, funding_indicative=0.000037, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.93%, turnover=63429981. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-27T08:45:01+00:00, last15m_closed_end=2026-10-27T08:45+00:00, prior8high=0.004216, depth_time=2026-10-27T08:45:12+00:00, book20_bid_proxy_usdt=2338680, book20_ask_proxy_usdt=2686229, funding_indicative=0.000044, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.83%, turnover=21858995. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-27T08:45:01+00:00, last15m_closed_end=2026-10-27T08:45+00:00, prior8high=53.160000, depth_time=2026-10-27T08:45:29+00:00, book20_bid_proxy_usdt=47344282, book20_ask_proxy_usdt=40888853, funding_indicative=0.000068, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.37%, turnover=261230317. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-10-27T08:45:01+00:00, last15m_closed_end=2026-10-27T08:45+00:00, prior8high=100.360000, depth_time=2026-10-27T08:45:37+00:00, book20_bid_proxy_usdt=19521945, book20_ask_proxy_usdt=17139840, funding_indicative=0.000053, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.03%, turnover=720297544. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-27T08:45:01+00:00, last15m_closed_end=2026-10-27T08:45+00:00, prior8high=250.230000, depth_time=2026-10-27T08:45:34+00:00, book20_bid_proxy_usdt=184547, book20_ask_proxy_usdt=73933, funding_indicative=0.000048, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.17%, turnover=46907458. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-27T08:45:01+00:00, last15m_closed_end=2026-10-27T08:45+00:00, prior8high=0.439800, depth_time=2026-10-27T08:45:32+00:00, book20_bid_proxy_usdt=3368404, book20_ask_proxy_usdt=3983521, funding_indicative=-0.000211, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.31%, turnover=68345870. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
