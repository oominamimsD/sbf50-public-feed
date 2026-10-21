# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T02:00:25Z**
- feed_generated_utc: 2026-10-21T02:00:27+00:00
- source_sha256: `bf2903e72c374bd6f4309d97ad141b2ed0b4a0003923be63d6300cfc08023403`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T02:00+00:00, close=82965.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T02:00+00:00, close=82965.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T00:00+00:00, close=82984.8, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.188420|-13.72|6.22|-14.18|10324950|0.53|
|BR_USDT|0.624240|-7.09|44.16|-7.55|35998782|0.32|
|XMR_USDT|579.670000|-6.53|9.80|-6.99|19709956|0.17|
|PHA_USDT|0.057190|-5.04|3.92|-5.50|9349454|1.75|
|TIA_USDT|0.613900|-4.21|6.33|-4.67|49065879|1.63|
|AGT_USDT|0.061839|-2.88|282.26|-3.34|7077209|3.07|
|XAU_USDT|4126.830000|-0.57|-0.93|-1.03|403347983|0.02|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.061839|0.055769|0.061847|0.66|N|Y/Y|Y/Y|N|N|
|BAT_USDT|0.188420|0.189610|0.188420|2.85|Y|Y/Y|N/N|N|N|
|BR_USDT|0.624240|0.638730|0.624900|2.17|Y|Y/Y|N/N|N|N|
|PHA_USDT|0.057190|0.056840|0.057190|1.31|N|Y/Y|N/N|N|N|
|TIA_USDT|0.613900|0.605800|0.613900|2.11|N|Y/Y|Y/Y|N|N|
|XAU_USDT|4126.830000|4113.730000|4126.830000|2.06|N|Y/Y|Y/Y|N|N|
|XMR_USDT|579.670000|572.610000|579.410000|0.44|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-21T02:00:00+00:00, last15m_closed_end=2026-10-21T02:00+00:00, prior8high=0.069341, depth_time=2026-10-21T02:00:21+00:00, book20_bid_proxy_usdt=5699, book20_ask_proxy_usdt=6218, funding_indicative=0.000054, next_funding_utc=2026-10-21T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.88%, turnover=7077209. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T02:00:00+00:00, last15m_closed_end=2026-10-21T02:00+00:00, prior8high=0.194960, depth_time=2026-10-21T02:00:08+00:00, book20_bid_proxy_usdt=17478, book20_ask_proxy_usdt=27292, funding_indicative=0.000057, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-13.72%, turnover=10324950. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T02:00:00+00:00, last15m_closed_end=2026-10-21T02:00+00:00, prior8high=0.664000, depth_time=2026-10-21T02:00:11+00:00, book20_bid_proxy_usdt=2424, book20_ask_proxy_usdt=2390, funding_indicative=0.000026, next_funding_utc=2026-10-21T04:00:00+00:00, funding_cycle_h=4, 24h_change=-7.09%, turnover=35998782. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PHA_USDT: quote_utc=2026-10-21T02:00:00+00:00, last15m_closed_end=2026-10-21T02:00+00:00, prior8high=0.058370, depth_time=2026-10-21T02:00:15+00:00, book20_bid_proxy_usdt=61372, book20_ask_proxy_usdt=53237, funding_indicative=-0.000040, next_funding_utc=2026-10-21T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.04%, turnover=9349454. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T02:00:00+00:00, last15m_closed_end=2026-10-21T02:00+00:00, prior8high=0.625200, depth_time=2026-10-21T02:00:19+00:00, book20_bid_proxy_usdt=202358, book20_ask_proxy_usdt=214820, funding_indicative=-0.000048, next_funding_utc=2026-10-21T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.21%, turnover=49065879. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAU_USDT: quote_utc=2026-10-21T02:00:00+00:00, last15m_closed_end=2026-10-21T02:00+00:00, prior8high=4132.000000, depth_time=2026-10-21T02:00:24+00:00, book20_bid_proxy_usdt=203088, book20_ask_proxy_usdt=1072386, funding_indicative=0.000138, next_funding_utc=2026-10-21T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.57%, turnover=403347983. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-21T02:00:00+00:00, last15m_closed_end=2026-10-21T02:00+00:00, prior8high=604.700000, depth_time=2026-10-21T02:00:14+00:00, book20_bid_proxy_usdt=8196, book20_ask_proxy_usdt=11945, funding_indicative=0.000100, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.53%, turnover=19709956. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
