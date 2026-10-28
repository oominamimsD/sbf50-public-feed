# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T22:15:16Z**
- feed_generated_utc: 2026-10-28T22:15:20+00:00
- source_sha256: `582be9c10cd8891c1988c9efc23305f144197f4ea55dbcb0d335baee8ddb879c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.08 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T22:15+00:00, close=81251.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-28T22:00+00:00, close=81323.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T20:00+00:00, close=81544.7, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BCH_USDT|289.890000|-1.04|0.07|-1.93|5837131|3.10|
|BTW_USDT|1.723600|-0.82|17.26|-1.71|12182032|0.58|
|XMR_USDT|599.590000|-0.74|0.56|-1.63|5211296|0.17|
|HBAR_USDT|0.075390|-0.68|-12.27|-1.57|12450925|1.33|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BCH_USDT|289.890000|286.690000|289.890000|0.12|N|Y/Y|N/N|N|N|
|BTW_USDT|1.723600|1.721700|1.723600|0.89|N|N/N|N/N|N|N|
|HBAR_USDT|0.075390|0.075100|0.075410|0.77|N|Y/N|Y/Y|N|N|
|XMR_USDT|599.590000|595.790000|599.590000|0.37|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BCH_USDT: quote_utc=2026-10-28T22:15:01+00:00, last15m_closed_end=2026-10-28T22:15+00:00, prior8high=292.510000, depth_time=2026-10-28T22:15:08+00:00, book20_bid_proxy_usdt=44911, book20_ask_proxy_usdt=83401, funding_indicative=0.000012, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.04%, turnover=5837131. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-28T22:15:01+00:00, last15m_closed_end=2026-10-28T22:15+00:00, prior8high=1.751000, depth_time=2026-10-28T22:15:09+00:00, book20_bid_proxy_usdt=29096, book20_ask_proxy_usdt=14307, funding_indicative=0.000050, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.82%, turnover=12182032. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-28T22:15:01+00:00, last15m_closed_end=2026-10-28T22:15+00:00, prior8high=0.076980, depth_time=2026-10-28T22:15:13+00:00, book20_bid_proxy_usdt=860152, book20_ask_proxy_usdt=876781, funding_indicative=0.000100, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.68%, turnover=12450925. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-28T22:15:01+00:00, last15m_closed_end=2026-10-28T22:15+00:00, prior8high=604.680000, depth_time=2026-10-28T22:15:11+00:00, book20_bid_proxy_usdt=29201, book20_ask_proxy_usdt=10348, funding_indicative=0.000100, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.74%, turnover=5211296. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
