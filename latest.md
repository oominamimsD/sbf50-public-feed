# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T12:15:22Z**
- feed_generated_utc: 2026-10-21T12:15:24+00:00
- source_sha256: `485ba3258621fd3c543f5cbed24ab5643a965c4cd4659d1377305e28c55a701e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1206; contracts: 1198; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T12:15+00:00, close=83513.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T12:00+00:00, close=83464, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T12:00+00:00, close=83464, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.045193|-30.07|179.36|-31.22|6592432|2.21|
|BAT_USDT|0.180990|-16.11|2.03|-17.26|10590333|0.55|
|BTW_USDT|1.626400|-12.06|-16.70|-13.21|24118789|0.61|
|BR_USDT|0.605310|-6.97|39.79|-8.12|20929060|0.66|
|AKE_USDT|0.030254|-2.69|20.69|-3.84|8128145|6.27|
|TIA_USDT|0.621400|-0.20|7.63|-1.35|45228461|1.61|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.045193|0.045062|0.045131|0.64|N|Y/Y|Y/Y|N|N|
|AKE_USDT|0.030254|0.028134|0.030356|4.37|N|Y/N|Y/N|N|N|
|BAT_USDT|0.180990|0.180140|0.180990|0.87|N|Y/Y|Y/Y|N|N|
|BR_USDT|0.605310|0.570180|0.605910|1.11|N|Y/Y|N/N|N|N|
|BTW_USDT|1.626400|1.612300|1.625700|0.93|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.621400|0.614700|0.621200|0.81|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-21T12:15:04+00:00, last15m_closed_end=2026-10-21T12:15+00:00, prior8high=0.051198, depth_time=2026-10-21T12:15:09+00:00, book20_bid_proxy_usdt=5456, book20_ask_proxy_usdt=9088, funding_indicative=0.000047, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-30.07%, turnover=6592432. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-10-21T12:15:04+00:00, last15m_closed_end=2026-10-21T12:15+00:00, prior8high=0.037704, depth_time=2026-10-21T12:15:19+00:00, book20_bid_proxy_usdt=9786, book20_ask_proxy_usdt=11556, funding_indicative=0.000050, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.69%, turnover=8128145. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T12:15:04+00:00, last15m_closed_end=2026-10-21T12:15+00:00, prior8high=0.183270, depth_time=2026-10-21T12:15:11+00:00, book20_bid_proxy_usdt=57755, book20_ask_proxy_usdt=46666, funding_indicative=-0.000124, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=-16.11%, turnover=10590333. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T12:15:04+00:00, last15m_closed_end=2026-10-21T12:15+00:00, prior8high=0.604780, depth_time=2026-10-21T12:15:16+00:00, book20_bid_proxy_usdt=3398, book20_ask_proxy_usdt=3111, funding_indicative=-0.000111, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.97%, turnover=20929060. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-21T12:15:04+00:00, last15m_closed_end=2026-10-21T12:15+00:00, prior8high=2.052700, depth_time=2026-10-21T12:15:13+00:00, book20_bid_proxy_usdt=7478, book20_ask_proxy_usdt=9933, funding_indicative=-0.004531, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-12.06%, turnover=24118789. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T12:15:04+00:00, last15m_closed_end=2026-10-21T12:15+00:00, prior8high=0.625900, depth_time=2026-10-21T12:15:21+00:00, book20_bid_proxy_usdt=262386, book20_ask_proxy_usdt=395930, funding_indicative=-0.000091, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-0.20%, turnover=45228461. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
