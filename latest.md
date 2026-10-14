# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T04:00:24Z**
- feed_generated_utc: 2026-10-14T04:00:27+00:00
- source_sha256: `cecc58300f30177bf4ad78f6e9f4dbea112e1a3a6d5fd41e629863c2590512f6`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T04:00+00:00, close=83663.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-14T04:00+00:00, close=83663.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-14T04:00+00:00, close=83663.4, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|S_USDT|0.059690|-15.45|36.59|-15.66|24062510|1.68|
|W_USDT|0.016208|-9.81|11.68|-10.02|6994124|0.62|
|MAGIC_USDT|0.115390|-2.67|69.39|-2.88|5572805|0.87|
|STRK_USDT|0.083270|-2.51|59.55|-2.72|29345205|1.20|
|TIA_USDT|0.573500|-1.96|20.40|-2.17|46440319|1.74|
|DOT_USDT|1.162500|-1.85|-3.23|-2.06|19655126|0.86|
|XLM_USDT|0.189810|-1.14|-11.17|-1.35|9295557|0.53|
|ICP_USDT|3.116000|-0.79|-8.40|-1.00|11682239|3.21|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOT_USDT|1.162500|1.159300|1.162500|0.86|N|Y/Y|Y/Y|N|N|
|ICP_USDT|3.116000|3.107000|3.116000|0.39|N|Y/Y|Y/Y|N|N|
|MAGIC_USDT|0.115390|0.114950|0.115390|0.33|N|Y/Y|Y/N|N|N|
|STRK_USDT|0.083270|0.083350|0.083270|1.09|N|Y/Y|Y/Y|N|N|
|S_USDT|0.059690|0.058010|0.059690|0.39|N|N/N|N/N|N|N|
|TIA_USDT|0.573500|0.568100|0.573500|0.99|N|Y/Y|N/N|N|N|
|W_USDT|0.016208|0.016278|0.016208|0.74|N|Y/Y|Y/Y|N|N|
|XLM_USDT|0.189810|0.189470|0.189810|2.61|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- DOT_USDT: quote_utc=2026-10-14T04:00:00+00:00, last15m_closed_end=2026-10-14T04:00+00:00, prior8high=1.173400, depth_time=2026-10-14T04:00:18+00:00, book20_bid_proxy_usdt=345175, book20_ask_proxy_usdt=297410, funding_indicative=-0.000013, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.85%, turnover=19655126. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-14T04:00:00+00:00, last15m_closed_end=2026-10-14T04:00+00:00, prior8high=3.139000, depth_time=2026-10-14T04:00:23+00:00, book20_bid_proxy_usdt=802043, book20_ask_proxy_usdt=768937, funding_indicative=0.000100, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.79%, turnover=11682239. target_RR/account_short_permission/settled_funding=UNKNOWN.
- MAGIC_USDT: quote_utc=2026-10-14T04:00:00+00:00, last15m_closed_end=2026-10-14T04:00+00:00, prior8high=0.118420, depth_time=2026-10-14T04:00:10+00:00, book20_bid_proxy_usdt=187835, book20_ask_proxy_usdt=181522, funding_indicative=-0.000164, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.67%, turnover=5572805. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T04:00:00+00:00, last15m_closed_end=2026-10-14T04:00+00:00, prior8high=0.085610, depth_time=2026-10-14T04:00:14+00:00, book20_bid_proxy_usdt=225012, book20_ask_proxy_usdt=178153, funding_indicative=0.000036, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.51%, turnover=29345205. target_RR/account_short_permission/settled_funding=UNKNOWN.
- S_USDT: quote_utc=2026-10-14T04:00:00+00:00, last15m_closed_end=2026-10-14T04:00+00:00, prior8high=0.060300, depth_time=2026-10-14T04:00:07+00:00, book20_bid_proxy_usdt=103222, book20_ask_proxy_usdt=87749, funding_indicative=-0.000008, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-15.45%, turnover=24062510. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-14T04:00:00+00:00, last15m_closed_end=2026-10-14T04:00+00:00, prior8high=0.580000, depth_time=2026-10-14T04:00:16+00:00, book20_bid_proxy_usdt=175056, book20_ask_proxy_usdt=195074, funding_indicative=0.000015, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.96%, turnover=46440319. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-14T04:00:00+00:00, last15m_closed_end=2026-10-14T04:00+00:00, prior8high=0.016791, depth_time=2026-10-14T04:00:10+00:00, book20_bid_proxy_usdt=18985, book20_ask_proxy_usdt=47631, funding_indicative=-0.000212, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-9.81%, turnover=6994124. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-10-14T04:00:00+00:00, last15m_closed_end=2026-10-14T04:00+00:00, prior8high=0.191080, depth_time=2026-10-14T04:00:21+00:00, book20_bid_proxy_usdt=204255, book20_ask_proxy_usdt=207784, funding_indicative=0.000073, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.14%, turnover=9295557. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
