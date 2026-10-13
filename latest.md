# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T08:30:40Z**
- feed_generated_utc: 2026-10-13T08:30:43+00:00
- source_sha256: `fa3cd5eaad7ba3c63e447709f5ec2d8dbc222e492935db33844b19c3a42e27c2`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T08:30+00:00, close=83890.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-13T08:00+00:00, close=83829.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-13T08:00+00:00, close=83829.3, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DOS_USDT|0.224800|-22.34|5.53|-23.80|9395587|4.45|
|W_USDT|0.019531|-18.82|38.09|-20.28|30448763|9.72|
|RSR_USDT|0.002018|-14.12|18.63|-15.58|16196807|9.91|
|NEAR_USDT|5.178000|-6.68|3.10|-8.14|271421474|1.93|
|ZRO_USDT|2.119800|-6.24|3.62|-7.70|25499826|0.47|
|LIT_USDT|3.420800|-5.63|-10.02|-7.09|10238531|0.29|
|RLC_USDT|0.942400|-4.67|71.97|-6.13|6756287|2.12|
|STRK_USDT|0.086750|-4.32|66.47|-5.78|62055391|2.31|
|ONDO_USDT|0.477400|-4.15|-2.33|-5.61|65448241|2.10|
|PUMPFUN_USDT|0.005097|-3.99|-19.54|-5.45|31959835|3.92|
|PONS_USDT|0.286300|-2.85|-25.34|-4.31|6222278|3.49|
|JUP_USDT|0.335300|-2.21|-0.76|-3.67|8623754|2.98|
|QNT_USDT|225.440000|-1.28|-12.20|-2.74|76515448|0.89|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOS_USDT|0.224800|0.224800|0.224800|0.76|N|Y/Y|Y/Y|N|N|
|JUP_USDT|0.335300|0.333800|0.335300|0.06|N|Y/Y|Y/Y|N|N|
|LIT_USDT|3.420800|3.407500|3.420800|0.48|N|Y/Y|Y/Y|N|N|
|NEAR_USDT|5.178000|5.151000|5.178000|0.82|N|Y/Y|Y/Y|N|N|
|ONDO_USDT|0.477400|0.476800|0.477400|1.02|N|Y/Y|Y/Y|N|N|
|PONS_USDT|0.286300|0.287500|0.286300|3.64|Y|Y/Y|Y/Y|N|Y|
|PUMPFUN_USDT|0.005097|0.005044|0.005098|0.52|N|Y/Y|Y/Y|N|N|
|QNT_USDT|225.440000|225.140000|225.440000|0.83|N|Y/Y|Y/Y|N|N|
|RLC_USDT|0.942400|0.917000|0.942500|1.54|N|Y/Y|Y/Y|N|N|
|RSR_USDT|0.002018|0.001998|0.002018|1.94|N|Y/Y|N/N|N|N|
|STRK_USDT|0.086750|0.083010|0.086760|1.78|N|Y/Y|Y/Y|N|N|
|W_USDT|0.019531|0.019206|0.019531|1.03|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|2.119800|2.075100|2.119800|0.84|N|Y/Y|N/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- DOS_USDT: quote_utc=2026-10-13T08:29:59+00:00, last15m_closed_end=2026-10-13T08:30+00:00, prior8high=0.234500, depth_time=2026-10-13T08:30:08+00:00, book20_bid_proxy_usdt=77783, book20_ask_proxy_usdt=77641, funding_indicative=0.000050, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-22.34%, turnover=9395587. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JUP_USDT: quote_utc=2026-10-13T08:30:00+00:00, last15m_closed_end=2026-10-13T08:30+00:00, prior8high=0.339200, depth_time=2026-10-13T08:30:37+00:00, book20_bid_proxy_usdt=577049, book20_ask_proxy_usdt=562606, funding_indicative=-0.000013, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.21%, turnover=8623754. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-13T08:30:00+00:00, last15m_closed_end=2026-10-13T08:30+00:00, prior8high=3.465900, depth_time=2026-10-13T08:30:21+00:00, book20_bid_proxy_usdt=26068, book20_ask_proxy_usdt=31544, funding_indicative=0.000050, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.63%, turnover=10238531. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-13T08:29:59+00:00, last15m_closed_end=2026-10-13T08:30+00:00, prior8high=5.340000, depth_time=2026-10-13T08:30:14+00:00, book20_bid_proxy_usdt=3487918, book20_ask_proxy_usdt=2271707, funding_indicative=0.000003, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.68%, turnover=271421474. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-13T08:29:59+00:00, last15m_closed_end=2026-10-13T08:30+00:00, prior8high=0.485500, depth_time=2026-10-13T08:30:29+00:00, book20_bid_proxy_usdt=3227070, book20_ask_proxy_usdt=1536462, funding_indicative=0.000012, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.15%, turnover=65448241. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PONS_USDT: quote_utc=2026-10-13T08:30:00+00:00, last15m_closed_end=2026-10-13T08:30+00:00, prior8high=0.295200, depth_time=2026-10-13T08:30:33+00:00, book20_bid_proxy_usdt=237444, book20_ask_proxy_usdt=213358, funding_indicative=0.000050, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.85%, turnover=6222278. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-13T08:30:00+00:00, last15m_closed_end=2026-10-13T08:30+00:00, prior8high=0.005142, depth_time=2026-10-13T08:30:32+00:00, book20_bid_proxy_usdt=1868653, book20_ask_proxy_usdt=1344392, funding_indicative=-0.000007, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.99%, turnover=31959835. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-13T08:29:59+00:00, last15m_closed_end=2026-10-13T08:30+00:00, prior8high=231.170000, depth_time=2026-10-13T08:30:39+00:00, book20_bid_proxy_usdt=79920, book20_ask_proxy_usdt=152512, funding_indicative=0.000059, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.28%, turnover=76515448. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-13T08:30:00+00:00, last15m_closed_end=2026-10-13T08:30+00:00, prior8high=0.963200, depth_time=2026-10-13T08:30:25+00:00, book20_bid_proxy_usdt=39896, book20_ask_proxy_usdt=65274, funding_indicative=-0.000918, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.67%, turnover=6756287. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RSR_USDT: quote_utc=2026-10-13T08:29:59+00:00, last15m_closed_end=2026-10-13T08:30+00:00, prior8high=0.002122, depth_time=2026-10-13T08:30:12+00:00, book20_bid_proxy_usdt=191372, book20_ask_proxy_usdt=289861, funding_indicative=-0.005448, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=8, 24h_change=-14.12%, turnover=16196807. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-13T08:29:59+00:00, last15m_closed_end=2026-10-13T08:30+00:00, prior8high=0.088100, depth_time=2026-10-13T08:30:28+00:00, book20_bid_proxy_usdt=112986, book20_ask_proxy_usdt=122707, funding_indicative=0.000012, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.32%, turnover=62055391. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-13T08:29:59+00:00, last15m_closed_end=2026-10-13T08:30+00:00, prior8high=0.019841, depth_time=2026-10-13T08:30:10+00:00, book20_bid_proxy_usdt=18633, book20_ask_proxy_usdt=17383, funding_indicative=-0.000511, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-18.82%, turnover=30448763. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-13T08:30:00+00:00, last15m_closed_end=2026-10-13T08:30+00:00, prior8high=2.157300, depth_time=2026-10-13T08:30:20+00:00, book20_bid_proxy_usdt=58326, book20_ask_proxy_usdt=31044, funding_indicative=-0.000030, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.24%, turnover=25499826. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
