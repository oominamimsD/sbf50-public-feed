# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T22:00:42Z**
- feed_generated_utc: 2026-10-26T22:00:46+00:00
- source_sha256: `a960872bcb698824d48ddec5384b52625f765a6f91820b5ea293159a30b616ce`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 75/75 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 14; crypto_deep: 14
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T22:00+00:00, close=80070.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-26T22:00+00:00, close=80070.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T20:00+00:00, close=79988.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZRO_USDT|1.633000|-4.83|-14.14|-4.43|5205452|0.61|
|LIT_USDT|2.998400|-4.80|-1.10|-4.40|5197235|0.33|
|BR_USDT|0.475900|-4.72|-22.74|-4.32|12040445|4.21|
|NEAR_USDT|4.461000|-4.16|-9.03|-3.76|116673554|2.24|
|IRYS_USDT|0.026750|-3.00|117.83|-2.60|9285110|3.74|
|PUMPFUN_USDT|0.004232|-2.86|-5.02|-2.46|21798739|2.36|
|ARB_USDT|0.167220|-2.72|-14.52|-2.32|20461703|0.60|
|FILECOIN_USDT|0.902200|-2.62|-10.84|-2.22|6391202|1.11|
|DOT_USDT|1.005600|-2.48|-12.31|-2.08|10443056|1.99|
|TAO_USDT|249.810000|-1.97|-6.89|-1.57|45342667|0.80|
|PEPE_USDT|0.000004|-1.95|4.13|-1.55|79417015|0.93|
|WLD_USDT|0.436600|-1.88|-13.76|-1.48|71999073|2.29|
|LINK_USDT|11.332000|-1.70|-5.11|-1.30|98042501|0.88|
|HBAR_USDT|0.076510|-1.50|-6.54|-1.10|10766091|1.31|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.167220|0.166370|0.167220|1.04|N|Y/Y|Y/Y|Y|N|
|BR_USDT|0.475900|0.472600|0.476000|0.08|N|Y/Y|Y/N|Y|N|
|DOT_USDT|1.005600|0.999300|1.005600|0.24|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|0.902200|0.895300|0.902200|0.88|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.076510|0.076260|0.076510|1.51|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.026750|0.025640|0.026760|1.22|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|11.332000|11.304000|11.338000|0.50|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|2.998400|2.972000|2.998400|0.32|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.461000|4.437000|4.461000|0.80|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|0.66|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004232|0.004178|0.004232|0.91|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|249.810000|248.640000|249.810000|0.49|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.436600|0.432200|0.436400|0.43|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.633000|1.608700|1.634100|2.57|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-26T22:00:05+00:00, last15m_closed_end=2026-10-26T22:00+00:00, prior8high=0.168670, depth_time=2026-10-26T22:00:24+00:00, book20_bid_proxy_usdt=68831, book20_ask_proxy_usdt=46942, funding_indicative=-0.000043, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.72%, turnover=20461703. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-26T22:00:04+00:00, last15m_closed_end=2026-10-26T22:00+00:00, prior8high=0.481400, depth_time=2026-10-26T22:00:13+00:00, book20_bid_proxy_usdt=40634, book20_ask_proxy_usdt=41082, funding_indicative=0.000050, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.72%, turnover=12040445. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-26T22:00:05+00:00, last15m_closed_end=2026-10-26T22:00+00:00, prior8high=1.011200, depth_time=2026-10-26T22:00:28+00:00, book20_bid_proxy_usdt=417861, book20_ask_proxy_usdt=246524, funding_indicative=-0.000061, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.48%, turnover=10443056. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-26T22:00:05+00:00, last15m_closed_end=2026-10-26T22:00+00:00, prior8high=0.909600, depth_time=2026-10-26T22:00:27+00:00, book20_bid_proxy_usdt=1180324, book20_ask_proxy_usdt=1471218, funding_indicative=0.000083, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.62%, turnover=6391202. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-26T22:00:05+00:00, last15m_closed_end=2026-10-26T22:00+00:00, prior8high=0.077060, depth_time=2026-10-26T22:00:40+00:00, book20_bid_proxy_usdt=1093514, book20_ask_proxy_usdt=746071, funding_indicative=0.000100, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.50%, turnover=10766091. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T22:00:04+00:00, last15m_closed_end=2026-10-26T22:00+00:00, prior8high=0.026420, depth_time=2026-10-26T22:00:20+00:00, book20_bid_proxy_usdt=93055, book20_ask_proxy_usdt=84500, funding_indicative=-0.000823, next_funding_utc=2026-10-26T23:00:00+00:00, funding_cycle_h=1, 24h_change=-3.00%, turnover=9285110. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-10-26T22:00:05+00:00, last15m_closed_end=2026-10-26T22:00+00:00, prior8high=11.418000, depth_time=2026-10-26T22:00:39+00:00, book20_bid_proxy_usdt=430978, book20_ask_proxy_usdt=503513, funding_indicative=0.000099, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.70%, turnover=98042501. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T22:00:05+00:00, last15m_closed_end=2026-10-26T22:00+00:00, prior8high=3.051300, depth_time=2026-10-26T22:00:12+00:00, book20_bid_proxy_usdt=19300, book20_ask_proxy_usdt=37140, funding_indicative=0.000050, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.80%, turnover=5197235. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-26T22:00:04+00:00, last15m_closed_end=2026-10-26T22:00+00:00, prior8high=4.502000, depth_time=2026-10-26T22:00:17+00:00, book20_bid_proxy_usdt=3983688, book20_ask_proxy_usdt=4049119, funding_indicative=0.000064, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.16%, turnover=116673554. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-26T22:00:04+00:00, last15m_closed_end=2026-10-26T22:00+00:00, prior8high=0.000004, depth_time=2026-10-26T22:00:33+00:00, book20_bid_proxy_usdt=45071, book20_ask_proxy_usdt=60769, funding_indicative=0.000067, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.95%, turnover=79417015. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-26T22:00:05+00:00, last15m_closed_end=2026-10-26T22:00+00:00, prior8high=0.004251, depth_time=2026-10-26T22:00:20+00:00, book20_bid_proxy_usdt=2804445, book20_ask_proxy_usdt=1680574, funding_indicative=-0.000002, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.86%, turnover=21798739. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-26T22:00:04+00:00, last15m_closed_end=2026-10-26T22:00+00:00, prior8high=251.400000, depth_time=2026-10-26T22:00:31+00:00, book20_bid_proxy_usdt=126432, book20_ask_proxy_usdt=45523, funding_indicative=0.000050, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.97%, turnover=45342667. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T22:00:04+00:00, last15m_closed_end=2026-10-26T22:00+00:00, prior8high=0.441300, depth_time=2026-10-26T22:00:36+00:00, book20_bid_proxy_usdt=2691984, book20_ask_proxy_usdt=2700331, funding_indicative=-0.000124, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.88%, turnover=71999073. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-26T22:00:05+00:00, last15m_closed_end=2026-10-26T22:00+00:00, prior8high=1.637100, depth_time=2026-10-26T22:00:10+00:00, book20_bid_proxy_usdt=36270, book20_ask_proxy_usdt=28009, funding_indicative=-0.000054, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.83%, turnover=5205452. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
