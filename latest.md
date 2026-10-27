# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T02:15:29Z**
- feed_generated_utc: 2026-10-27T02:15:32+00:00
- source_sha256: `bf1a2a373857c33fed3188bdadb8acbdd5c68e531e605862a940d6021beb7dae`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T02:15+00:00, close=80053.8, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-27T02:00+00:00, close=80041.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-27T00:00+00:00, close=80115.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZRO_USDT|1.617300|-5.26|-14.96|-4.83|5199621|1.24|
|PUMPFUN_USDT|0.004220|-2.49|-5.29|-2.06|21005835|2.37|
|DOT_USDT|0.998000|-2.40|-12.97|-1.97|10821220|1.00|
|NEAR_USDT|4.470000|-2.25|-8.84|-1.82|104296237|2.24|
|FILECOIN_USDT|0.904300|-1.78|-10.64|-1.35|6454405|1.11|
|LINK_USDT|11.328000|-1.73|-5.14|-1.30|104610743|1.77|
|FET_USDT|0.173600|-1.69|-8.14|-1.26|6090204|5.76|
|AAVE_USDT|134.430000|-1.68|-8.68|-1.25|24127678|0.74|
|TAO_USDT|249.620000|-1.53|-6.96|-1.10|46324783|1.20|
|PEPE_USDT|0.000004|-1.45|4.60|-1.02|76892066|0.23|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|134.430000|134.460000|134.430000|2.78|Y|Y/Y|Y/Y|Y|Y|
|DOT_USDT|0.998000|0.996300|0.998000|2.25|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.173600|0.173600|0.173600|0.85|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|0.904300|0.903000|0.904300|0.82|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|11.328000|11.316000|11.325000|0.94|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.470000|4.446000|4.470000|1.05|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|0.48|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004220|0.004235|0.004221|0.64|N|Y/N|Y/Y|Y|N|
|TAO_USDT|249.620000|249.270000|249.620000|1.02|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.617300|1.608300|1.618600|0.29|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T02:15:03+00:00, last15m_closed_end=2026-10-27T02:15+00:00, prior8high=136.180000, depth_time=2026-10-27T02:15:23+00:00, book20_bid_proxy_usdt=756396, book20_ask_proxy_usdt=393130, funding_indicative=0.000075, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.68%, turnover=24127678. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T02:15:03+00:00, last15m_closed_end=2026-10-27T02:15+00:00, prior8high=1.013800, depth_time=2026-10-27T02:15:12+00:00, book20_bid_proxy_usdt=282449, book20_ask_proxy_usdt=283762, funding_indicative=-0.000091, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.40%, turnover=10821220. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-27T02:15:03+00:00, last15m_closed_end=2026-10-27T02:15+00:00, prior8high=0.176400, depth_time=2026-10-27T02:15:22+00:00, book20_bid_proxy_usdt=1901883, book20_ask_proxy_usdt=1433291, funding_indicative=0.000100, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.69%, turnover=6090204. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T02:15:03+00:00, last15m_closed_end=2026-10-27T02:15+00:00, prior8high=0.916600, depth_time=2026-10-27T02:15:12+00:00, book20_bid_proxy_usdt=983179, book20_ask_proxy_usdt=1200410, funding_indicative=0.000061, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.78%, turnover=6454405. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-10-27T02:15:03+00:00, last15m_closed_end=2026-10-27T02:15+00:00, prior8high=11.421000, depth_time=2026-10-27T02:15:19+00:00, book20_bid_proxy_usdt=476147, book20_ask_proxy_usdt=452466, funding_indicative=0.000083, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.73%, turnover=104610743. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-27T02:15:02+00:00, last15m_closed_end=2026-10-27T02:15+00:00, prior8high=4.536000, depth_time=2026-10-27T02:15:14+00:00, book20_bid_proxy_usdt=3565592, book20_ask_proxy_usdt=3147114, funding_indicative=0.000061, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.25%, turnover=104296237. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-27T02:15:02+00:00, last15m_closed_end=2026-10-27T02:15+00:00, prior8high=0.000004, depth_time=2026-10-27T02:15:27+00:00, book20_bid_proxy_usdt=42289, book20_ask_proxy_usdt=57331, funding_indicative=0.000034, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.45%, turnover=76892066. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-27T02:15:03+00:00, last15m_closed_end=2026-10-27T02:15+00:00, prior8high=0.004315, depth_time=2026-10-27T02:15:10+00:00, book20_bid_proxy_usdt=2805822, book20_ask_proxy_usdt=1934692, funding_indicative=0.000050, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.49%, turnover=21005835. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-27T02:15:02+00:00, last15m_closed_end=2026-10-27T02:15+00:00, prior8high=252.300000, depth_time=2026-10-27T02:15:26+00:00, book20_bid_proxy_usdt=142252, book20_ask_proxy_usdt=85093, funding_indicative=0.000050, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.53%, turnover=46324783. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-27T02:15:03+00:00, last15m_closed_end=2026-10-27T02:15+00:00, prior8high=1.647700, depth_time=2026-10-27T02:15:07+00:00, book20_bid_proxy_usdt=44687, book20_ask_proxy_usdt=16452, funding_indicative=0.000050, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.26%, turnover=5199621. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
