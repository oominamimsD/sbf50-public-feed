# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T16:45:16Z**
- feed_generated_utc: 2026-10-18T16:45:17+00:00
- source_sha256: `9b62359ff3907953b5d608aaa1e5dea02cbec8cc529a98957784b6d74eb02ae5`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T16:45+00:00, close=81069.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-18T16:00+00:00, close=81137.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-18T16:00+00:00, close=81137.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|2.193600|-4.84|30.40|-4.76|28687846|2.28|
|PUMPFUN_USDT|0.004124|-1.69|-28.58|-1.61|30915948|2.42|
|STRK_USDT|0.060520|-1.68|-49.25|-1.60|15215011|1.65|
|BAT_USDT|0.172490|-1.64|3.51|-1.56|11278187|1.74|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BAT_USDT|0.172490|0.174400|0.172490|2.40|Y|Y/Y|Y/Y|Y|Y|
|BTW_USDT|2.193600|2.209900|2.193000|1.23|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004124|0.004108|0.004124|1.44|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.060520|0.060400|0.060520|1.54|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BAT_USDT: quote_utc=2026-10-18T16:45:02+00:00, last15m_closed_end=2026-10-18T16:45+00:00, prior8high=0.180190, depth_time=2026-10-18T16:45:15+00:00, book20_bid_proxy_usdt=20055, book20_ask_proxy_usdt=31890, funding_indicative=-0.000031, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.64%, turnover=11278187. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-18T16:45:02+00:00, last15m_closed_end=2026-10-18T16:45+00:00, prior8high=2.405100, depth_time=2026-10-18T16:45:08+00:00, book20_bid_proxy_usdt=14006, book20_ask_proxy_usdt=167183, funding_indicative=-0.000362, next_funding_utc=2026-10-18T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.84%, turnover=28687846. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T16:45:02+00:00, last15m_closed_end=2026-10-18T16:45+00:00, prior8high=0.004253, depth_time=2026-10-18T16:45:09+00:00, book20_bid_proxy_usdt=2315877, book20_ask_proxy_usdt=2235300, funding_indicative=0.000033, next_funding_utc=2026-10-18T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.69%, turnover=30915948. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T16:45:02+00:00, last15m_closed_end=2026-10-18T16:45+00:00, prior8high=0.062250, depth_time=2026-10-18T16:45:12+00:00, book20_bid_proxy_usdt=388283, book20_ask_proxy_usdt=453510, funding_indicative=0.000050, next_funding_utc=2026-10-18T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.68%, turnover=15215011. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
