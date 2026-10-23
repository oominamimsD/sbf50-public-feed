# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T03:00:26Z**
- feed_generated_utc: 2026-10-23T03:00:27+00:00
- source_sha256: `577bd7c8771c33d17bbfe26969db257b070ebd2153cfc73e02a4a196a0ee0a57`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1214; contracts: 1206; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T03:00+00:00, close=81942.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-23T03:00+00:00, close=81942.1, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T00:00+00:00, close=81384.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.004371|-5.14|120.20|-5.49|9624330|9.16|
|PHA_USDT|0.060330|-2.77|19.41|-3.12|8299420|1.66|
|LIT_USDT|3.520500|-2.59|13.88|-2.94|11829505|0.28|
|STRK_USDT|0.053040|-2.42|-44.95|-2.77|12391479|1.89|
|SILVER_USDT|54.190000|-1.93|-5.16|-2.28|388693113|1.85|
|TIA_USDT|0.563400|-0.87|-6.48|-1.22|23919730|1.77|
|XAU_USDT|4026.370000|-0.82|-3.12|-1.17|773917221|0.03|
|XAUT_USDT|4024.900000|-0.72|-2.89|-1.07|299740591|0.07|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|JCT_USDT|0.004371|0.004284|0.004371|1.03|N|Y/Y|N/N|Y|N|
|LIT_USDT|3.520500|3.385300|3.520500|2.37|N|Y/Y|Y/N|Y|N|
|PHA_USDT|0.060330|0.059190|0.060330|0.33|N|Y/Y|N/N|Y|N|
|SILVER_USDT|54.190000|53.570000|54.190000|0.27|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.053040|0.052520|0.053040|0.94|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.563400|0.554300|0.563400|0.44|N|Y/Y|Y/Y|Y|N|
|XAUT_USDT|4024.900000|3994.260000|4024.900000|1.11|N|Y/Y|Y/Y|Y|N|
|XAU_USDT|4026.370000|3989.000000|4026.370000|1.46|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- JCT_USDT: quote_utc=2026-10-23T02:59:59+00:00, last15m_closed_end=2026-10-23T03:00+00:00, prior8high=0.004565, depth_time=2026-10-23T03:00:08+00:00, book20_bid_proxy_usdt=26918, book20_ask_proxy_usdt=43390, funding_indicative=0.000097, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.14%, turnover=9624330. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T02:59:59+00:00, last15m_closed_end=2026-10-23T03:00+00:00, prior8high=3.521700, depth_time=2026-10-23T03:00:13+00:00, book20_bid_proxy_usdt=26791, book20_ask_proxy_usdt=30079, funding_indicative=0.000050, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.59%, turnover=11829505. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PHA_USDT: quote_utc=2026-10-23T02:59:59+00:00, last15m_closed_end=2026-10-23T03:00+00:00, prior8high=0.061050, depth_time=2026-10-23T03:00:09+00:00, book20_bid_proxy_usdt=67493, book20_ask_proxy_usdt=68241, funding_indicative=-0.000475, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.77%, turnover=8299420. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T02:59:59+00:00, last15m_closed_end=2026-10-23T03:00+00:00, prior8high=54.870000, depth_time=2026-10-23T03:00:17+00:00, book20_bid_proxy_usdt=35430343, book20_ask_proxy_usdt=27966750, funding_indicative=0.000090, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.93%, turnover=388693113. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T02:59:59+00:00, last15m_closed_end=2026-10-23T03:00+00:00, prior8high=0.053500, depth_time=2026-10-23T03:00:15+00:00, book20_bid_proxy_usdt=784886, book20_ask_proxy_usdt=490546, funding_indicative=0.000037, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.42%, turnover=12391479. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T02:59:59+00:00, last15m_closed_end=2026-10-23T03:00+00:00, prior8high=0.567500, depth_time=2026-10-23T03:00:18+00:00, book20_bid_proxy_usdt=376995, book20_ask_proxy_usdt=326261, funding_indicative=0.000006, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.87%, turnover=23919730. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAUT_USDT: quote_utc=2026-10-23T02:59:59+00:00, last15m_closed_end=2026-10-23T03:00+00:00, prior8high=4038.080000, depth_time=2026-10-23T03:00:25+00:00, book20_bid_proxy_usdt=66835, book20_ask_proxy_usdt=277448, funding_indicative=0.000050, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.72%, turnover=299740591. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAU_USDT: quote_utc=2026-10-23T02:59:59+00:00, last15m_closed_end=2026-10-23T03:00+00:00, prior8high=4040.120000, depth_time=2026-10-23T03:00:22+00:00, book20_bid_proxy_usdt=944469, book20_ask_proxy_usdt=593064, funding_indicative=0.000097, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.82%, turnover=773917221. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
