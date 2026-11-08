# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T16:00:24Z**
- feed_generated_utc: 2026-11-08T16:00:25+00:00
- source_sha256: `49afa43b04301216eb0f0f67eb33e3b31485c4f3331d837042b4a8396933bcf8`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T16:00+00:00, close=76037.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T16:00+00:00, close=76037.8, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-08T16:00+00:00, close=76037.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IDOL_USDT|0.030861|-7.31|76.13|-7.72|15317661|2.93|
|TIA_USDT|0.419900|-4.91|-14.32|-5.32|7161273|2.38|
|ONE_USDT|0.001958|-3.85|66.76|-4.26|22501034|0.51|
|WLD_USDT|0.326000|-2.86|-19.38|-3.27|24867577|3.07|
|ENA_USDT|0.153970|-2.66|-20.63|-3.07|25134858|0.65|
|AAVE_USDT|129.710000|-1.90|-4.28|-2.31|9522765|0.77|
|LINK_USDT|10.741000|-0.94|-7.17|-1.35|60318713|0.93|
|SUI_USDT|0.851600|-0.64|-5.58|-1.05|24930918|1.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|129.710000|128.470000|129.710000|1.22|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.153970|0.152750|0.153970|0.90|N|Y/Y|Y/Y|Y|N|
|IDOL_USDT|0.030861|0.029962|0.030860|0.34|N|Y/Y|N/N|Y|N|
|LINK_USDT|10.741000|10.691000|10.741000|0.90|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001958|0.001818|0.001958|1.05|N|Y/Y|N/N|Y|N|
|SUI_USDT|0.851600|0.845000|0.851600|0.19|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.419900|0.419200|0.419800|0.32|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.326000|0.323500|0.325900|0.25|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-08T15:59:59+00:00, last15m_closed_end=2026-11-08T16:00+00:00, prior8high=129.590000, depth_time=2026-11-08T16:00:18+00:00, book20_bid_proxy_usdt=326035, book20_ask_proxy_usdt=376371, funding_indicative=0.000076, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.90%, turnover=9522765. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-08T15:59:59+00:00, last15m_closed_end=2026-11-08T16:00+00:00, prior8high=0.155430, depth_time=2026-11-08T16:00:15+00:00, book20_bid_proxy_usdt=256213, book20_ask_proxy_usdt=226846, funding_indicative=-0.000060, next_funding_utc=2026-11-08T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.66%, turnover=25134858. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-08T15:59:59+00:00, last15m_closed_end=2026-11-08T16:00+00:00, prior8high=0.031336, depth_time=2026-11-08T16:00:07+00:00, book20_bid_proxy_usdt=5449, book20_ask_proxy_usdt=4302, funding_indicative=0.000984, next_funding_utc=2026-11-08T20:00:00+00:00, funding_cycle_h=4, 24h_change=-7.31%, turnover=15317661. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-08T15:59:59+00:00, last15m_closed_end=2026-11-08T16:00+00:00, prior8high=10.744000, depth_time=2026-11-08T16:00:20+00:00, book20_bid_proxy_usdt=535289, book20_ask_proxy_usdt=970519, funding_indicative=0.000026, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.94%, turnover=60318713. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T15:59:59+00:00, last15m_closed_end=2026-11-08T16:00+00:00, prior8high=0.001983, depth_time=2026-11-08T16:00:12+00:00, book20_bid_proxy_usdt=7869, book20_ask_proxy_usdt=14779, funding_indicative=-0.001490, next_funding_utc=2026-11-08T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.85%, turnover=22501034. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-11-08T15:59:59+00:00, last15m_closed_end=2026-11-08T16:00+00:00, prior8high=0.852800, depth_time=2026-11-08T16:00:23+00:00, book20_bid_proxy_usdt=1595236, book20_ask_proxy_usdt=1764689, funding_indicative=0.000064, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.64%, turnover=24930918. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T15:59:59+00:00, last15m_closed_end=2026-11-08T16:00+00:00, prior8high=0.422700, depth_time=2026-11-08T16:00:09+00:00, book20_bid_proxy_usdt=220341, book20_ask_proxy_usdt=247629, funding_indicative=0.000000, next_funding_utc=2026-11-08T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.91%, turnover=7161273. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T15:59:59+00:00, last15m_closed_end=2026-11-08T16:00+00:00, prior8high=0.328300, depth_time=2026-11-08T16:00:13+00:00, book20_bid_proxy_usdt=3067584, book20_ask_proxy_usdt=3250507, funding_indicative=-0.000110, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.86%, turnover=24867577. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
