# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T15:45:25Z**
- feed_generated_utc: 2026-10-27T15:45:28+00:00
- source_sha256: `656647823290910ea8e13e5c716956fe90872a878f43989cd700b3cfc98aa6a2`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T15:45+00:00, close=80561.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-27T15:00+00:00, close=80328.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-27T12:00+00:00, close=79880.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.025220|-8.55|105.37|-8.73|6410799|7.94|
|QNT_USDT|198.610000|-5.54|1.48|-5.72|91211038|1.01|
|AAVE_USDT|132.400000|-3.16|-10.06|-3.34|26918730|0.76|
|DOT_USDT|0.993400|-2.85|-13.37|-3.03|11381521|1.01|
|FILECOIN_USDT|0.900300|-2.21|-11.03|-2.39|5333089|1.11|
|HBAR_USDT|0.076120|-1.60|-7.02|-1.78|10327883|1.31|
|ICP_USDT|2.591000|-1.48|-9.18|-1.66|5123997|3.86|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|132.400000|130.180000|132.400000|1.30|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.993400|0.977000|0.993400|0.42|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|0.900300|0.880500|0.900000|0.07|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.076120|0.075280|0.076090|2.72|N|Y/Y|Y/Y|Y|N|
|ICP_USDT|2.591000|2.552000|2.591000|0.27|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.025220|0.024620|0.025220|1.05|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|198.610000|196.560000|198.500000|0.62|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T15:45:03+00:00, last15m_closed_end=2026-10-27T15:45+00:00, prior8high=132.750000, depth_time=2026-10-27T15:45:13+00:00, book20_bid_proxy_usdt=316059, book20_ask_proxy_usdt=959082, funding_indicative=0.000100, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.16%, turnover=26918730. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T15:45:03+00:00, last15m_closed_end=2026-10-27T15:45+00:00, prior8high=0.997900, depth_time=2026-10-27T15:45:17+00:00, book20_bid_proxy_usdt=280626, book20_ask_proxy_usdt=502414, funding_indicative=-0.000117, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.85%, turnover=11381521. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T15:45:03+00:00, last15m_closed_end=2026-10-27T15:45+00:00, prior8high=0.901000, depth_time=2026-10-27T15:45:19+00:00, book20_bid_proxy_usdt=1059811, book20_ask_proxy_usdt=1635743, funding_indicative=0.000033, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.21%, turnover=5333089. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-27T15:45:03+00:00, last15m_closed_end=2026-10-27T15:45+00:00, prior8high=0.076230, depth_time=2026-10-27T15:45:21+00:00, book20_bid_proxy_usdt=912274, book20_ask_proxy_usdt=1113543, funding_indicative=0.000073, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.60%, turnover=10327883. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-27T15:45:03+00:00, last15m_closed_end=2026-10-27T15:45+00:00, prior8high=2.596000, depth_time=2026-10-27T15:45:24+00:00, book20_bid_proxy_usdt=1114470, book20_ask_proxy_usdt=1212449, funding_indicative=0.000100, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.48%, turnover=5123997. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-27T15:45:03+00:00, last15m_closed_end=2026-10-27T15:45+00:00, prior8high=0.025580, depth_time=2026-10-27T15:45:08+00:00, book20_bid_proxy_usdt=135510, book20_ask_proxy_usdt=101085, funding_indicative=-0.000741, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=1, 24h_change=-8.55%, turnover=6410799. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-27T15:45:03+00:00, last15m_closed_end=2026-10-27T15:45+00:00, prior8high=200.970000, depth_time=2026-10-27T15:45:12+00:00, book20_bid_proxy_usdt=76681, book20_ask_proxy_usdt=60045, funding_indicative=-0.000205, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.54%, turnover=91211038. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
