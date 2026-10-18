# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T10:45:36Z**
- feed_generated_utc: 2026-10-18T10:45:39+00:00
- source_sha256: `cdddc09bc0a089279b053b00d8e1e50307ff4a394d2fba523f7b43bc1b886046`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T10:45+00:00, close=82152.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-18T10:00+00:00, close=82122.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-18T08:00+00:00, close=81644.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.062460|-5.57|-33.14|-6.59|15229189|1.60|
|AGT_USDT|0.068628|-4.75|285.83|-5.77|14119922|5.26|
|EIGEN_USDT|0.246000|-4.01|4.41|-5.03|6805719|4.06|
|SAND_USDT|0.061030|-3.18|-9.30|-4.20|47686812|3.28|
|FILECOIN_USDT|1.062600|-2.28|-5.78|-3.30|18503869|0.94|
|PUMPFUN_USDT|0.004323|-2.01|-24.48|-3.03|23426771|2.31|
|TIA_USDT|0.645200|-1.94|25.76|-2.96|61806429|1.55|
|ZRO_USDT|1.852900|-1.71|-8.29|-2.73|7119531|0.54|
|XPL_USDT|0.078820|-1.63|-9.15|-2.65|5847293|1.27|
|OP_USDT|0.127060|-1.50|-8.29|-2.52|8678342|0.79|
|ICP_USDT|2.907000|-0.71|-7.68|-1.73|6025503|3.44|
|DOT_USDT|1.111400|-0.53|-11.57|-1.55|16764488|0.90|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.068628|0.077270|0.069288|4.21|Y|N/N|N/N|Y|N|
|DOT_USDT|1.111400|1.098300|1.111400|0.72|N|Y/Y|Y/Y|Y|N|
|EIGEN_USDT|0.246000|0.245800|0.246000|6.56|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|1.062600|1.044000|1.062600|1.44|N|Y/Y|Y/Y|Y|N|
|ICP_USDT|2.907000|2.904000|2.907000|0.95|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.127060|0.125540|0.127060|0.63|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004323|0.004256|0.004323|0.22|N|Y/Y|Y/Y|Y|N|
|SAND_USDT|0.061030|0.060970|0.061030|0.27|N|N/N|N/N|Y|N|
|STRK_USDT|0.062460|0.061570|0.062460|2.22|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.645200|0.636200|0.645000|1.11|N|N/Y|Y/Y|Y|N|
|XPL_USDT|0.078820|0.077860|0.078820|0.57|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.852900|1.823800|1.852900|0.52|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-18T10:45:01+00:00, last15m_closed_end=2026-10-18T10:45+00:00, prior8high=0.081290, depth_time=2026-10-18T10:45:11+00:00, book20_bid_proxy_usdt=13957, book20_ask_proxy_usdt=58943, funding_indicative=0.000477, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.75%, turnover=14119922. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-18T10:45:01+00:00, last15m_closed_end=2026-10-18T10:45+00:00, prior8high=1.120400, depth_time=2026-10-18T10:45:35+00:00, book20_bid_proxy_usdt=378602, book20_ask_proxy_usdt=245771, funding_indicative=-0.000072, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.53%, turnover=16764488. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-18T10:45:01+00:00, last15m_closed_end=2026-10-18T10:45+00:00, prior8high=0.249900, depth_time=2026-10-18T10:45:10+00:00, book20_bid_proxy_usdt=616500, book20_ask_proxy_usdt=393931, funding_indicative=-0.000016, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.01%, turnover=6805719. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-18T10:45:01+00:00, last15m_closed_end=2026-10-18T10:45+00:00, prior8high=1.069800, depth_time=2026-10-18T10:45:14+00:00, book20_bid_proxy_usdt=568421, book20_ask_proxy_usdt=511763, funding_indicative=-0.000036, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.28%, turnover=18503869. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-18T10:45:01+00:00, last15m_closed_end=2026-10-18T10:45+00:00, prior8high=2.941000, depth_time=2026-10-18T10:45:33+00:00, book20_bid_proxy_usdt=955523, book20_ask_proxy_usdt=1074195, funding_indicative=0.000002, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.71%, turnover=6025503. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-18T10:45:01+00:00, last15m_closed_end=2026-10-18T10:45+00:00, prior8high=0.128100, depth_time=2026-10-18T10:45:29+00:00, book20_bid_proxy_usdt=100660, book20_ask_proxy_usdt=57403, funding_indicative=-0.000219, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.50%, turnover=8678342. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T10:45:01+00:00, last15m_closed_end=2026-10-18T10:45+00:00, prior8high=0.004347, depth_time=2026-10-18T10:45:20+00:00, book20_bid_proxy_usdt=1700303, book20_ask_proxy_usdt=1156794, funding_indicative=0.000050, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.01%, turnover=23426771. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-18T10:45:01+00:00, last15m_closed_end=2026-10-18T10:45+00:00, prior8high=0.063750, depth_time=2026-10-18T10:45:15+00:00, book20_bid_proxy_usdt=776473, book20_ask_proxy_usdt=757077, funding_indicative=-0.007486, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.18%, turnover=47686812. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T10:45:01+00:00, last15m_closed_end=2026-10-18T10:45+00:00, prior8high=0.064850, depth_time=2026-10-18T10:45:08+00:00, book20_bid_proxy_usdt=586276, book20_ask_proxy_usdt=473925, funding_indicative=0.000050, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.57%, turnover=15229189. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-18T10:45:01+00:00, last15m_closed_end=2026-10-18T10:45+00:00, prior8high=0.665300, depth_time=2026-10-18T10:45:23+00:00, book20_bid_proxy_usdt=176953, book20_ask_proxy_usdt=254435, funding_indicative=-0.000068, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.94%, turnover=61806429. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-10-18T10:45:01+00:00, last15m_closed_end=2026-10-18T10:45+00:00, prior8high=0.079050, depth_time=2026-10-18T10:45:28+00:00, book20_bid_proxy_usdt=564418, book20_ask_proxy_usdt=484661, funding_indicative=0.000050, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.63%, turnover=5847293. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-18T10:45:01+00:00, last15m_closed_end=2026-10-18T10:45+00:00, prior8high=1.874500, depth_time=2026-10-18T10:45:22+00:00, book20_bid_proxy_usdt=63886, book20_ask_proxy_usdt=55336, funding_indicative=-0.000016, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.71%, turnover=7119531. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
