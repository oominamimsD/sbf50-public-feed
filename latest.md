# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T22:45:17Z**
- feed_generated_utc: 2026-10-28T22:45:21+00:00
- source_sha256: `b26d7c076a0116c3a7060bfce43cc385964aac37d174c7fe20c0cc5b6277abdd`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T22:45+00:00, close=81286.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-28T22:00+00:00, close=81323.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T20:00+00:00, close=81544.7, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BLESS_USDT|0.010840|-1.06|34.69|-2.00|23851752|0.92|
|HBAR_USDT|0.075240|-0.88|-12.45|-1.82|12713751|1.33|
|BCH_USDT|291.350000|-0.54|0.57|-1.48|5876110|4.46|
|BTW_USDT|1.729400|-0.49|17.66|-1.43|12290843|1.16|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BCH_USDT|291.350000|286.970000|291.190000|0.47|N|Y/Y|N/N|N|N|
|BLESS_USDT|0.010840|0.010757|0.010840|0.72|N|N/N|N/N|N|N|
|BTW_USDT|1.729400|1.721600|1.729200|0.67|N|N/N|N/N|N|N|
|HBAR_USDT|0.075240|0.075040|0.075240|0.34|N|Y/N|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BCH_USDT: quote_utc=2026-10-28T22:45:03+00:00, last15m_closed_end=2026-10-28T22:45+00:00, prior8high=291.470000, depth_time=2026-10-28T22:45:12+00:00, book20_bid_proxy_usdt=46853, book20_ask_proxy_usdt=72901, funding_indicative=0.000010, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.54%, turnover=5876110. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-10-28T22:45:02+00:00, last15m_closed_end=2026-10-28T22:45+00:00, prior8high=0.011275, depth_time=2026-10-28T22:45:09+00:00, book20_bid_proxy_usdt=6413, book20_ask_proxy_usdt=7421, funding_indicative=0.000159, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.06%, turnover=23851752. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-28T22:45:03+00:00, last15m_closed_end=2026-10-28T22:45+00:00, prior8high=1.751000, depth_time=2026-10-28T22:45:14+00:00, book20_bid_proxy_usdt=23330, book20_ask_proxy_usdt=20764, funding_indicative=0.000050, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.49%, turnover=12290843. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-28T22:45:03+00:00, last15m_closed_end=2026-10-28T22:45+00:00, prior8high=0.076200, depth_time=2026-10-28T22:45:11+00:00, book20_bid_proxy_usdt=1349103, book20_ask_proxy_usdt=1334435, funding_indicative=0.000100, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.88%, turnover=12713751. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
