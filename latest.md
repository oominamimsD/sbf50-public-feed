# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T08:00:29Z**
- feed_generated_utc: 2026-10-26T08:00:33+00:00
- source_sha256: `3d2c91ceac9c6adf1f2b9e73f4a133f07af157b24edf7dc5806eef0e5fae85d0`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T08:00+00:00, close=80002, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-26T08:00+00:00, close=80002, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T08:00+00:00, close=80002, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.030290|-13.99|148.27|-13.25|12885209|3.30|
|APR_USDT|0.037620|-7.61|38.10|-6.87|8900973|2.65|
|WLD_USDT|0.435800|-4.55|-8.50|-3.81|67906830|2.29|
|BTW_USDT|1.592700|-3.99|-30.91|-3.25|10534871|8.79|
|DASH_USDT|50.900000|-3.98|6.30|-3.24|11768349|1.97|
|XMR_USDT|586.010000|-3.66|0.60|-2.92|6176625|0.68|
|LIT_USDT|3.065700|-3.23|4.61|-2.49|5829599|0.33|
|DOT_USDT|1.008800|-2.33|-5.66|-1.59|10499512|0.99|
|FET_USDT|0.172900|-1.76|-7.73|-1.02|5194954|5.78|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APR_USDT|0.037620|0.032200|0.037620|2.31|N|N/Y|N/N|Y|N|
|BTW_USDT|1.592700|1.578900|1.596200|1.23|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|50.900000|50.730000|50.900000|0.26|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.008800|1.002800|1.008800|0.66|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.172900|0.172600|0.172800|1.07|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.030290|0.030290|0.030290|1.97|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.065700|3.063600|3.065700|0.67|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.435800|0.435300|0.435800|0.74|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|586.010000|584.290000|586.010000|0.64|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APR_USDT: quote_utc=2026-10-26T08:00:02+00:00, last15m_closed_end=2026-10-26T08:00+00:00, prior8high=0.037240, depth_time=2026-10-26T08:00:11+00:00, book20_bid_proxy_usdt=30672, book20_ask_proxy_usdt=49353, funding_indicative=0.000050, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.61%, turnover=8900973. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-26T08:00:02+00:00, last15m_closed_end=2026-10-26T08:00+00:00, prior8high=1.657000, depth_time=2026-10-26T08:00:16+00:00, book20_bid_proxy_usdt=13662, book20_ask_proxy_usdt=29422, funding_indicative=-0.004047, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.99%, turnover=10534871. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-26T08:00:02+00:00, last15m_closed_end=2026-10-26T08:00+00:00, prior8high=51.350000, depth_time=2026-10-26T08:00:16+00:00, book20_bid_proxy_usdt=932636, book20_ask_proxy_usdt=569228, funding_indicative=0.000022, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.98%, turnover=11768349. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-26T08:00:02+00:00, last15m_closed_end=2026-10-26T08:00+00:00, prior8high=1.018300, depth_time=2026-10-26T08:00:25+00:00, book20_bid_proxy_usdt=306535, book20_ask_proxy_usdt=230741, funding_indicative=-0.000103, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.33%, turnover=10499512. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-26T08:00:02+00:00, last15m_closed_end=2026-10-26T08:00+00:00, prior8high=0.175500, depth_time=2026-10-26T08:00:29+00:00, book20_bid_proxy_usdt=1621826, book20_ask_proxy_usdt=1062799, funding_indicative=0.000100, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.76%, turnover=5194954. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T08:00:02+00:00, last15m_closed_end=2026-10-26T08:00+00:00, prior8high=0.033830, depth_time=2026-10-26T08:00:08+00:00, book20_bid_proxy_usdt=139680, book20_ask_proxy_usdt=70728, funding_indicative=-0.000205, next_funding_utc=2026-10-26T09:00:00+00:00, funding_cycle_h=1, 24h_change=-13.99%, turnover=12885209. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T08:00:02+00:00, last15m_closed_end=2026-10-26T08:00+00:00, prior8high=3.131600, depth_time=2026-10-26T08:00:23+00:00, book20_bid_proxy_usdt=18762, book20_ask_proxy_usdt=21036, funding_indicative=0.000047, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.23%, turnover=5829599. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T08:00:02+00:00, last15m_closed_end=2026-10-26T08:00+00:00, prior8high=0.445300, depth_time=2026-10-26T08:00:13+00:00, book20_bid_proxy_usdt=2329572, book20_ask_proxy_usdt=2655695, funding_indicative=-0.000077, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.55%, turnover=67906830. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T08:00:02+00:00, last15m_closed_end=2026-10-26T08:00+00:00, prior8high=591.270000, depth_time=2026-10-26T08:00:21+00:00, book20_bid_proxy_usdt=32186, book20_ask_proxy_usdt=10817, funding_indicative=0.000100, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.66%, turnover=6176625. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
