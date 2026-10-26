# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T12:45:29Z**
- feed_generated_utc: 2026-10-26T12:45:32+00:00
- source_sha256: `60f26f46ae8c7e1e903351d2d8675de4ed5374bb0c9b10ddcfe271a1397f7c38`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1182; contracts: 1174; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T12:45+00:00, close=80317.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-26T12:00+00:00, close=80382.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-26T12:00+00:00, close=80382.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.028230|-26.56|131.39|-26.17|12289655|3.54|
|CAP_USDT|0.080620|-24.99|21.23|-24.60|7274189|4.96|
|APR_USDT|0.034810|-15.73|27.79|-15.34|7232036|2.88|
|BTW_USDT|1.427400|-13.95|-38.08|-13.56|11975095|0.70|
|WLD_USDT|0.440000|-3.63|-7.62|-3.24|61362599|2.27|
|LIT_USDT|3.093800|-2.66|5.57|-2.27|5427824|0.32|
|STRK_USDT|0.044590|-2.51|-27.56|-2.12|9444552|2.24|
|XMR_USDT|593.370000|-2.28|1.86|-1.89|5779417|0.34|
|DOT_USDT|1.018500|-1.99|-4.75|-1.60|8992990|0.98|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APR_USDT|0.034810|0.033120|0.034810|0.81|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.427400|1.395000|1.426400|0.82|N|Y/Y|Y/Y|Y|N|
|CAP_USDT|0.080620|0.070960|0.080270|1.17|N|Y/Y|Y/N|Y|N|
|DOT_USDT|1.018500|1.015500|1.018500|1.29|N|N/Y|Y/Y|Y|N|
|IRYS_USDT|0.028230|0.027970|0.028230|0.97|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.093800|3.070000|3.093800|1.55|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.044590|0.044360|0.044630|0.76|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.440000|0.435800|0.440000|0.87|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|593.370000|588.790000|593.370000|0.81|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APR_USDT: quote_utc=2026-10-26T12:45:03+00:00, last15m_closed_end=2026-10-26T12:45+00:00, prior8high=0.034920, depth_time=2026-10-26T12:45:13+00:00, book20_bid_proxy_usdt=44840, book20_ask_proxy_usdt=63817, funding_indicative=0.000050, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-15.73%, turnover=7232036. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-26T12:45:03+00:00, last15m_closed_end=2026-10-26T12:45+00:00, prior8high=1.516100, depth_time=2026-10-26T12:45:16+00:00, book20_bid_proxy_usdt=17284, book20_ask_proxy_usdt=19741, funding_indicative=-0.014637, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-13.95%, turnover=11975095. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CAP_USDT: quote_utc=2026-10-26T12:45:03+00:00, last15m_closed_end=2026-10-26T12:45+00:00, prior8high=0.082200, depth_time=2026-10-26T12:45:11+00:00, book20_bid_proxy_usdt=59974, book20_ask_proxy_usdt=94494, funding_indicative=0.000050, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-24.99%, turnover=7274189. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-26T12:45:03+00:00, last15m_closed_end=2026-10-26T12:45+00:00, prior8high=1.028300, depth_time=2026-10-26T12:45:28+00:00, book20_bid_proxy_usdt=439406, book20_ask_proxy_usdt=348727, funding_indicative=-0.000088, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.99%, turnover=8992990. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T12:45:03+00:00, last15m_closed_end=2026-10-26T12:45+00:00, prior8high=0.029000, depth_time=2026-10-26T12:45:08+00:00, book20_bid_proxy_usdt=64931, book20_ask_proxy_usdt=90486, funding_indicative=-0.000574, next_funding_utc=2026-10-26T13:00:00+00:00, funding_cycle_h=1, 24h_change=-26.56%, turnover=12289655. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T12:45:03+00:00, last15m_closed_end=2026-10-26T12:45+00:00, prior8high=3.116600, depth_time=2026-10-26T12:45:20+00:00, book20_bid_proxy_usdt=27417, book20_ask_proxy_usdt=16948, funding_indicative=0.000050, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.66%, turnover=5427824. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-26T12:45:03+00:00, last15m_closed_end=2026-10-26T12:45+00:00, prior8high=0.045410, depth_time=2026-10-26T12:45:23+00:00, book20_bid_proxy_usdt=930318, book20_ask_proxy_usdt=706053, funding_indicative=-0.000023, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.51%, turnover=9444552. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T12:45:03+00:00, last15m_closed_end=2026-10-26T12:45+00:00, prior8high=0.444700, depth_time=2026-10-26T12:45:18+00:00, book20_bid_proxy_usdt=2925024, book20_ask_proxy_usdt=2646604, funding_indicative=-0.000164, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.63%, turnover=61362599. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T12:45:03+00:00, last15m_closed_end=2026-10-26T12:45+00:00, prior8high=592.990000, depth_time=2026-10-26T12:45:25+00:00, book20_bid_proxy_usdt=87458, book20_ask_proxy_usdt=19385, funding_indicative=0.000100, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.28%, turnover=5779417. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
