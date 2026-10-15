# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-15T16:45:13Z**
- feed_generated_utc: 2026-10-15T16:45:14+00:00
- source_sha256: `6be2364fc520d52a1b8cc79b37d561688033a072b425668e9561fc1a853d0fb8`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-15T16:45+00:00, close=82089.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-15T16:00+00:00, close=82375.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-15T16:00+00:00, close=82375.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|WAL_USDT|0.051460|-3.45|54.58|-3.11|14139161|1.94|
|BTW_USDT|1.877600|-1.56|35.24|-1.22|30456242|2.13|
|LIT_USDT|3.047700|-1.41|-14.90|-1.07|7428900|0.33|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.877600|1.878100|1.877600|0.42|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.047700|2.976000|3.047700|0.40|N|N/Y|Y/Y|Y|N|
|WAL_USDT|0.051460|0.051280|0.051460|1.79|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-15T16:45:00+00:00, last15m_closed_end=2026-10-15T16:45+00:00, prior8high=2.000700, depth_time=2026-10-15T16:45:10+00:00, book20_bid_proxy_usdt=17835, book20_ask_proxy_usdt=9023, funding_indicative=0.000050, next_funding_utc=2026-10-15T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.56%, turnover=30456242. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-15T16:45:00+00:00, last15m_closed_end=2026-10-15T16:45+00:00, prior8high=3.095900, depth_time=2026-10-15T16:45:12+00:00, book20_bid_proxy_usdt=28517, book20_ask_proxy_usdt=28948, funding_indicative=0.000050, next_funding_utc=2026-10-15T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.41%, turnover=7428900. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WAL_USDT: quote_utc=2026-10-15T16:45:00+00:00, last15m_closed_end=2026-10-15T16:45+00:00, prior8high=0.056770, depth_time=2026-10-15T16:45:07+00:00, book20_bid_proxy_usdt=161389, book20_ask_proxy_usdt=155673, funding_indicative=-0.000705, next_funding_utc=2026-10-15T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.45%, turnover=14139161. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
