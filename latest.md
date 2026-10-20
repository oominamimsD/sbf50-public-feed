# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T18:15:11Z**
- feed_generated_utc: 2026-10-20T18:15:13+00:00
- source_sha256: `0a8bb2d6c02c634f148edfe897ece5bb542793ff63c0d6c37715fd26b7ca135c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T18:15+00:00, close=82620, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-20T18:00+00:00, close=82781.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-20T16:00+00:00, close=82581.9, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.700600|-8.05|-12.90|-8.09|33426100|1.18|
|AGT_USDT|0.061681|-4.56|281.28|-4.60|7327978|8.75|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.061681|0.061895|0.061681|1.01|N|Y/Y|Y/Y|N|N|
|BTW_USDT|1.700600|1.711000|1.700600|0.61|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T18:14:59+00:00, last15m_closed_end=2026-10-20T18:15+00:00, prior8high=0.066255, depth_time=2026-10-20T18:15:10+00:00, book20_bid_proxy_usdt=10605, book20_ask_proxy_usdt=9385, funding_indicative=0.000047, next_funding_utc=2026-10-20T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.56%, turnover=7327978. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-20T18:14:59+00:00, last15m_closed_end=2026-10-20T18:15+00:00, prior8high=1.869900, depth_time=2026-10-20T18:15:08+00:00, book20_bid_proxy_usdt=53332, book20_ask_proxy_usdt=10546, funding_indicative=-0.002747, next_funding_utc=2026-10-20T20:00:00+00:00, funding_cycle_h=4, 24h_change=-8.05%, turnover=33426100. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
