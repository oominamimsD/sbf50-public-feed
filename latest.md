# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T10:45:25Z**
- feed_generated_utc: 2026-10-19T10:45:26+00:00
- source_sha256: `c4930fbdb03a0e8396307a17bb56a87a8ef138c8dd482981ca5acb8d059676f3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T10:45+00:00, close=82353.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-19T10:00+00:00, close=82729.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-19T08:00+00:00, close=82695, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|2.121100|-7.99|26.09|-9.48|21820085|0.47|
|STRK_USDT|0.058330|-5.24|-51.09|-6.73|18564705|1.72|
|HBAR_USDT|0.083380|-2.79|-11.08|-4.28|44492279|1.20|
|SAND_USDT|0.057710|-1.78|-13.13|-3.27|15740466|1.73|
|TIA_USDT|0.607300|-1.71|3.15|-3.20|53860511|1.65|
|SEI_USDT|0.059870|-0.61|-15.54|-2.10|8995227|1.67|
|XAUT_USDT|4160.370000|0.30|-0.69|-1.19|77448711|0.07|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|2.121100|2.129000|2.121100|1.84|Y|Y/Y|N/N|N|N|
|HBAR_USDT|0.083380|0.083280|0.083380|1.69|N|Y/Y|Y/Y|N|N|
|SAND_USDT|0.057710|0.057690|0.057710|1.77|N|Y/Y|N/N|N|N|
|SEI_USDT|0.059870|0.059860|0.059860|4.90|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.058330|0.058950|0.058330|4.39|Y|Y/Y|Y/Y|N|Y|
|TIA_USDT|0.607300|0.605200|0.606900|2.86|N|Y/Y|Y/Y|N|N|
|XAUT_USDT|4160.370000|4160.010000|4160.370000|1.41|N|Y/N|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-19T10:45:01+00:00, last15m_closed_end=2026-10-19T10:45+00:00, prior8high=2.310800, depth_time=2026-10-19T10:45:09+00:00, book20_bid_proxy_usdt=11487, book20_ask_proxy_usdt=15968, funding_indicative=-0.000597, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.99%, turnover=21820085. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-19T10:45:01+00:00, last15m_closed_end=2026-10-19T10:45+00:00, prior8high=0.084960, depth_time=2026-10-19T10:45:13+00:00, book20_bid_proxy_usdt=962492, book20_ask_proxy_usdt=1116194, funding_indicative=-0.000031, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.79%, turnover=44492279. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-19T10:45:01+00:00, last15m_closed_end=2026-10-19T10:45+00:00, prior8high=0.059300, depth_time=2026-10-19T10:45:16+00:00, book20_bid_proxy_usdt=533476, book20_ask_proxy_usdt=593193, funding_indicative=-0.003350, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.78%, turnover=15740466. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-19T10:45:01+00:00, last15m_closed_end=2026-10-19T10:45+00:00, prior8high=0.061510, depth_time=2026-10-19T10:45:21+00:00, book20_bid_proxy_usdt=253543, book20_ask_proxy_usdt=268685, funding_indicative=0.000037, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.61%, turnover=8995227. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-19T10:45:01+00:00, last15m_closed_end=2026-10-19T10:45+00:00, prior8high=0.060310, depth_time=2026-10-19T10:45:11+00:00, book20_bid_proxy_usdt=499167, book20_ask_proxy_usdt=924749, funding_indicative=0.000050, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.24%, turnover=18564705. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-19T10:45:01+00:00, last15m_closed_end=2026-10-19T10:45+00:00, prior8high=0.614100, depth_time=2026-10-19T10:45:19+00:00, book20_bid_proxy_usdt=313475, book20_ask_proxy_usdt=187991, funding_indicative=0.000004, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.71%, turnover=53860511. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAUT_USDT: quote_utc=2026-10-19T10:45:01+00:00, last15m_closed_end=2026-10-19T10:45+00:00, prior8high=4170.900000, depth_time=2026-10-19T10:45:24+00:00, book20_bid_proxy_usdt=181398, book20_ask_proxy_usdt=122688, funding_indicative=0.000009, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=0.30%, turnover=77448711. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
