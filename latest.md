# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T05:30:16Z**
- feed_generated_utc: 2026-10-19T05:30:17+00:00
- source_sha256: `b11587af0fea3c0273ed7ad7cbded5f61e953784b120c493acd35ca525444440`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T05:30+00:00, close=82650, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-19T05:00+00:00, close=82748.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-19T04:00+00:00, close=82496.1, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|2.238300|-2.91|33.05|-4.77|21685941|4.46|
|HBAR_USDT|0.084030|-2.04|-10.39|-3.90|50815080|1.19|
|STRK_USDT|0.060310|-2.03|-49.43|-3.89|17661194|3.32|
|TIA_USDT|0.611000|-1.11|3.78|-2.97|57264419|1.64|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|2.238300|2.217800|2.238700|0.64|N|Y/Y|N/N|N|N|
|HBAR_USDT|0.084030|0.083880|0.084030|0.61|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.060310|0.059440|0.060280|1.34|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.611000|0.604400|0.610700|1.23|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-19T05:30:01+00:00, last15m_closed_end=2026-10-19T05:30+00:00, prior8high=2.328900, depth_time=2026-10-19T05:30:08+00:00, book20_bid_proxy_usdt=6944, book20_ask_proxy_usdt=14128, funding_indicative=-0.000028, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.91%, turnover=21685941. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-19T05:30:01+00:00, last15m_closed_end=2026-10-19T05:30+00:00, prior8high=0.084640, depth_time=2026-10-19T05:30:10+00:00, book20_bid_proxy_usdt=549551, book20_ask_proxy_usdt=1102886, funding_indicative=-0.000045, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.04%, turnover=50815080. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-19T05:30:01+00:00, last15m_closed_end=2026-10-19T05:30+00:00, prior8high=0.060800, depth_time=2026-10-19T05:30:12+00:00, book20_bid_proxy_usdt=587341, book20_ask_proxy_usdt=724323, funding_indicative=0.000049, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.03%, turnover=17661194. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-19T05:30:01+00:00, last15m_closed_end=2026-10-19T05:30+00:00, prior8high=0.619700, depth_time=2026-10-19T05:30:14+00:00, book20_bid_proxy_usdt=303414, book20_ask_proxy_usdt=216953, funding_indicative=0.000004, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.11%, turnover=57264419. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
