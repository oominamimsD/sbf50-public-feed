# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-24T17:45:16Z**
- feed_generated_utc: 2026-10-24T17:45:19+00:00
- source_sha256: `d1fdfcde7ea12abf51d35453f27a708396e3d745e759f062f20ef8aabe25ad58`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-24T17:45+00:00, close=80119.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-24T17:00+00:00, close=80182.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-24T16:00+00:00, close=79763.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BIRB_USDT|0.093130|-4.63|91.94|-5.07|12040607|2.15|
|TIA_USDT|0.519100|-1.25|-21.10|-1.69|31202566|1.93|
|DOT_USDT|1.030800|-0.79|-7.75|-1.23|13363492|1.94|
|ARB_USDT|0.164520|-0.73|-10.54|-1.17|24382720|0.61|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.164520|0.163700|0.164520|0.59|N|Y/Y|Y/Y|Y|N|
|BIRB_USDT|0.093130|0.091630|0.092770|0.39|N|Y/Y|N/N|Y|N|
|DOT_USDT|1.030800|1.022300|1.030800|0.23|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.519100|0.516000|0.518800|1.77|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-24T17:45:02+00:00, last15m_closed_end=2026-10-24T17:45+00:00, prior8high=0.166400, depth_time=2026-10-24T17:45:15+00:00, book20_bid_proxy_usdt=67574, book20_ask_proxy_usdt=68088, funding_indicative=0.000043, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.73%, turnover=24382720. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BIRB_USDT: quote_utc=2026-10-24T17:45:02+00:00, last15m_closed_end=2026-10-24T17:45+00:00, prior8high=0.099680, depth_time=2026-10-24T17:45:07+00:00, book20_bid_proxy_usdt=22655, book20_ask_proxy_usdt=18291, funding_indicative=-0.007804, next_funding_utc=2026-10-24T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.63%, turnover=12040607. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-24T17:45:02+00:00, last15m_closed_end=2026-10-24T17:45+00:00, prior8high=1.042100, depth_time=2026-10-24T17:45:13+00:00, book20_bid_proxy_usdt=416812, book20_ask_proxy_usdt=309190, funding_indicative=-0.000064, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.79%, turnover=13363492. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-24T17:45:02+00:00, last15m_closed_end=2026-10-24T17:45+00:00, prior8high=0.527500, depth_time=2026-10-24T17:45:09+00:00, book20_bid_proxy_usdt=208894, book20_ask_proxy_usdt=279579, funding_indicative=-0.000011, next_funding_utc=2026-10-24T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.25%, turnover=31202566. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
