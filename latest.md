# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-30T16:15:11Z**
- feed_generated_utc: 2026-10-30T16:15:12+00:00
- source_sha256: `4a9a81dfc05e49aadeec21a0b8be33655824fd85a87ef61d94b1da23c240db9b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-30T16:15+00:00, close=77563.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-30T16:00+00:00, close=77579.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-30T16:00+00:00, close=77579.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.166100|-2.78|-31.50|-2.76|9874246|1.72|
|BLESS_USDT|0.009615|-2.39|17.81|-2.37|19270856|9.34|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BLESS_USDT|0.009615|0.009737|0.009626|3.72|Y|Y/Y|Y/N|Y|N|
|BTW_USDT|1.166100|1.178400|1.166100|0.98|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BLESS_USDT: quote_utc=2026-10-30T16:15:01+00:00, last15m_closed_end=2026-10-30T16:15+00:00, prior8high=0.013878, depth_time=2026-10-30T16:15:10+00:00, book20_bid_proxy_usdt=7028, book20_ask_proxy_usdt=11451, funding_indicative=0.000268, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.39%, turnover=19270856. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-30T16:15:01+00:00, last15m_closed_end=2026-10-30T16:15+00:00, prior8high=1.262000, depth_time=2026-10-30T16:15:08+00:00, book20_bid_proxy_usdt=16872, book20_ask_proxy_usdt=24370, funding_indicative=-0.000073, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.78%, turnover=9874246. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
