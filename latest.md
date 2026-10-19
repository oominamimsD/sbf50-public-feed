# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T05:15:15Z**
- feed_generated_utc: 2026-10-19T05:15:17+00:00
- source_sha256: `90972b7fca7fc3a1ac5cb5bca169d570c0fb15bea9408295661e0a4ed90dc625`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T05:15+00:00, close=82598.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-19T05:00+00:00, close=82748.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-19T04:00+00:00, close=82496.1, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|2.238700|-2.89|33.08|-4.69|21606684|1.34|
|HBAR_USDT|0.084030|-2.04|-10.39|-3.84|50725032|1.19|
|TIA_USDT|0.606800|-1.79|3.07|-3.59|56780210|1.65|
|STRK_USDT|0.060530|-1.67|-49.24|-3.47|17530195|1.65|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|2.238700|2.217800|2.238700|0.92|N|Y/Y|N/N|N|N|
|HBAR_USDT|0.084030|0.083880|0.084030|1.20|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.060530|0.059440|0.060530|1.18|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.606800|0.606900|0.607000|1.13|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-19T05:15:00+00:00, last15m_closed_end=2026-10-19T05:15+00:00, prior8high=2.328900, depth_time=2026-10-19T05:15:06+00:00, book20_bid_proxy_usdt=11672, book20_ask_proxy_usdt=8314, funding_indicative=-0.000027, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.89%, turnover=21606684. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-19T05:15:01+00:00, last15m_closed_end=2026-10-19T05:15+00:00, prior8high=0.084640, depth_time=2026-10-19T05:15:07+00:00, book20_bid_proxy_usdt=1034060, book20_ask_proxy_usdt=805151, funding_indicative=-0.000042, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.04%, turnover=50725032. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-19T05:15:01+00:00, last15m_closed_end=2026-10-19T05:15+00:00, prior8high=0.061000, depth_time=2026-10-19T05:15:15+00:00, book20_bid_proxy_usdt=516642, book20_ask_proxy_usdt=684258, funding_indicative=0.000050, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.67%, turnover=17530195. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-19T05:15:01+00:00, last15m_closed_end=2026-10-19T05:15+00:00, prior8high=0.620700, depth_time=2026-10-19T05:15:12+00:00, book20_bid_proxy_usdt=320768, book20_ask_proxy_usdt=326909, funding_indicative=0.000009, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.79%, turnover=56780210. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
