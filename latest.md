# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T17:30:14Z**
- feed_generated_utc: 2026-10-13T17:30:16+00:00
- source_sha256: `21cdd2f26e6a80d378725a517414947aa321001662164ea44b048d224fada312`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T17:30+00:00, close=83199.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-13T17:00+00:00, close=83347, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-13T16:00+00:00, close=83393, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.084670|-2.59|62.23|-2.37|50116286|1.18|
|RLC_USDT|0.902300|-2.26|10.06|-2.04|5898254|3.32|
|DOS_USDT|0.212500|-1.30|-1.39|-1.08|9503252|4.71|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOS_USDT|0.212500|0.212900|0.212500|0.89|N|Y/Y|Y/Y|N|N|
|RLC_USDT|0.902300|0.907000|0.902300|1.04|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.084670|0.082420|0.084680|0.70|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- DOS_USDT: quote_utc=2026-10-13T17:30:03+00:00, last15m_closed_end=2026-10-13T17:30+00:00, prior8high=0.218600, depth_time=2026-10-13T17:30:13+00:00, book20_bid_proxy_usdt=118345, book20_ask_proxy_usdt=100672, funding_indicative=0.000050, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.30%, turnover=9503252. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-13T17:30:03+00:00, last15m_closed_end=2026-10-13T17:30+00:00, prior8high=0.949500, depth_time=2026-10-13T17:30:11+00:00, book20_bid_proxy_usdt=61334, book20_ask_proxy_usdt=74738, funding_indicative=-0.000712, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.26%, turnover=5898254. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-13T17:30:03+00:00, last15m_closed_end=2026-10-13T17:30+00:00, prior8high=0.087530, depth_time=2026-10-13T17:30:08+00:00, book20_bid_proxy_usdt=241772, book20_ask_proxy_usdt=217603, funding_indicative=0.000013, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.59%, turnover=50116286. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
