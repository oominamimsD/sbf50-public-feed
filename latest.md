# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-24T22:00:22Z**
- feed_generated_utc: 2026-10-24T22:00:25+00:00
- source_sha256: `6a82beeec5549dcaac777bb69f530b6705bca57f9b6336627611890f68dbb8d9`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-24T22:00+00:00, close=80383.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-24T22:00+00:00, close=80383.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-24T20:00+00:00, close=80455.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.043790|-23.06|243.18|-23.83|35898995|2.28|
|ORDER_USDT|0.055220|-18.87|78.41|-19.64|12701181|3.62|
|BIRB_USDT|0.085250|-12.70|75.70|-13.47|11660031|2.34|
|STRK_USDT|0.046360|-2.00|-29.91|-2.77|8765881|2.16|
|DOT_USDT|1.034500|-1.39|-7.41|-2.16|12256985|0.97|
|TIA_USDT|0.530300|-0.69|-19.40|-1.46|28289568|1.89|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BIRB_USDT|0.085250|0.089570|0.085410|1.94|Y|Y/Y|N/N|Y|N|
|DOT_USDT|1.034500|1.033000|1.034500|1.73|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.043790|0.043660|0.043790|0.74|N|Y/Y|Y/N|Y|N|
|ORDER_USDT|0.055220|0.056100|0.055220|1.40|Y|Y/N|N/N|Y|N|
|STRK_USDT|0.046360|0.046250|0.046360|0.09|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.530300|0.527500|0.530300|0.13|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BIRB_USDT: quote_utc=2026-10-24T22:00:01+00:00, last15m_closed_end=2026-10-24T22:00+00:00, prior8high=0.094440, depth_time=2026-10-24T22:00:13+00:00, book20_bid_proxy_usdt=5453, book20_ask_proxy_usdt=19440, funding_indicative=-0.008614, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=4, 24h_change=-12.70%, turnover=11660031. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-24T22:00:01+00:00, last15m_closed_end=2026-10-24T22:00+00:00, prior8high=1.047500, depth_time=2026-10-24T22:00:19+00:00, book20_bid_proxy_usdt=291174, book20_ask_proxy_usdt=305670, funding_indicative=-0.000089, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.39%, turnover=12256985. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-24T22:00:00+00:00, last15m_closed_end=2026-10-24T22:00+00:00, prior8high=0.045590, depth_time=2026-10-24T22:00:09+00:00, book20_bid_proxy_usdt=52073, book20_ask_proxy_usdt=51288, funding_indicative=0.000012, next_funding_utc=2026-10-24T23:00:00+00:00, funding_cycle_h=1, 24h_change=-23.06%, turnover=35898995. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-24T22:00:01+00:00, last15m_closed_end=2026-10-24T22:00+00:00, prior8high=0.064800, depth_time=2026-10-24T22:00:11+00:00, book20_bid_proxy_usdt=58597, book20_ask_proxy_usdt=53519, funding_indicative=-0.001106, next_funding_utc=2026-10-24T23:00:00+00:00, funding_cycle_h=1, 24h_change=-18.87%, turnover=12701181. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-24T22:00:01+00:00, last15m_closed_end=2026-10-24T22:00+00:00, prior8high=0.047580, depth_time=2026-10-24T22:00:16+00:00, book20_bid_proxy_usdt=839371, book20_ask_proxy_usdt=884868, funding_indicative=0.000034, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.00%, turnover=8765881. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-24T22:00:01+00:00, last15m_closed_end=2026-10-24T22:00+00:00, prior8high=0.534900, depth_time=2026-10-24T22:00:19+00:00, book20_bid_proxy_usdt=274770, book20_ask_proxy_usdt=253209, funding_indicative=-0.000046, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.69%, turnover=28289568. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
