# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T21:30:17Z**
- feed_generated_utc: 2026-10-28T21:30:20+00:00
- source_sha256: `bb3303b477620c77b37d964bbf28118e9241515edec257ee50e19c0015c1731d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T21:30+00:00, close=81167.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-28T21:00+00:00, close=81291.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T20:00+00:00, close=81544.7, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BCH_USDT|289.300000|-1.24|-0.13|-2.03|5871641|3.46|
|XMR_USDT|598.510000|-0.92|0.38|-1.71|5412974|0.17|
|HBAR_USDT|0.075390|-0.68|-12.27|-1.47|12985034|1.33|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BCH_USDT|289.300000|286.080000|289.300000|0.54|N|Y/Y|N/N|N|N|
|HBAR_USDT|0.075390|0.075110|0.075380|1.23|N|Y/Y|Y/Y|N|N|
|XMR_USDT|598.510000|595.790000|598.510000|0.82|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BCH_USDT: quote_utc=2026-10-28T21:30:03+00:00, last15m_closed_end=2026-10-28T21:30+00:00, prior8high=292.510000, depth_time=2026-10-28T21:30:10+00:00, book20_bid_proxy_usdt=50606, book20_ask_proxy_usdt=96170, funding_indicative=0.000022, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.24%, turnover=5871641. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-28T21:30:03+00:00, last15m_closed_end=2026-10-28T21:30+00:00, prior8high=0.076980, depth_time=2026-10-28T21:30:16+00:00, book20_bid_proxy_usdt=1401037, book20_ask_proxy_usdt=440585, funding_indicative=0.000100, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.68%, turnover=12985034. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-28T21:30:03+00:00, last15m_closed_end=2026-10-28T21:30+00:00, prior8high=604.680000, depth_time=2026-10-28T21:30:13+00:00, book20_bid_proxy_usdt=37352, book20_ask_proxy_usdt=12602, funding_indicative=0.000100, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.92%, turnover=5412974. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
