# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-24T19:45:14Z**
- feed_generated_utc: 2026-10-24T19:45:17+00:00
- source_sha256: `09b4a2645449dd32999b6774f9c61e436b9335b24caefed03ea79dac824ef761`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-24T19:45+00:00, close=80513.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-24T19:00+00:00, close=80503.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-24T16:00+00:00, close=79763.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BIRB_USDT|0.092130|-5.66|89.88|-6.60|11899320|1.08|
|IRYS_USDT|0.044810|-2.69|251.17|-3.63|61506312|4.47|
|BTW_USDT|1.722200|-1.09|-24.11|-2.03|14452196|1.74|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BIRB_USDT|0.092130|0.088740|0.092130|0.44|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.722200|1.704100|1.722400|1.38|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.044810|0.042300|0.044740|0.97|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BIRB_USDT: quote_utc=2026-10-24T19:45:02+00:00, last15m_closed_end=2026-10-24T19:45+00:00, prior8high=0.096610, depth_time=2026-10-24T19:45:08+00:00, book20_bid_proxy_usdt=21384, book20_ask_proxy_usdt=19939, funding_indicative=-0.007617, next_funding_utc=2026-10-24T20:00:00+00:00, funding_cycle_h=4, 24h_change=-5.66%, turnover=11899320. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-24T19:45:02+00:00, last15m_closed_end=2026-10-24T19:45+00:00, prior8high=1.733500, depth_time=2026-10-24T19:45:13+00:00, book20_bid_proxy_usdt=14132, book20_ask_proxy_usdt=21056, funding_indicative=-0.006315, next_funding_utc=2026-10-24T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.09%, turnover=14452196. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-24T19:45:02+00:00, last15m_closed_end=2026-10-24T19:45+00:00, prior8high=0.051740, depth_time=2026-10-24T19:45:11+00:00, book20_bid_proxy_usdt=54646, book20_ask_proxy_usdt=65226, funding_indicative=0.000012, next_funding_utc=2026-10-24T20:00:00+00:00, funding_cycle_h=1, 24h_change=-2.69%, turnover=61506312. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
