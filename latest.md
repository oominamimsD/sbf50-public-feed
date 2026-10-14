# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T17:00:17Z**
- feed_generated_utc: 2026-10-14T17:00:19+00:00
- source_sha256: `2bbb7e64e5d21bf6db475cda7b7cbaa87b37b470e9f9e7c1bf9fbb5a63612d04`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T17:00+00:00, close=81967.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T17:00+00:00, close=81967.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-14T16:00+00:00, close=81600.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|S_USDT|0.053710|-3.29|34.81|-3.74|7977273|1.86|
|INJ_USDT|7.669000|-2.15|4.92|-2.60|47382237|1.30|
|TIA_USDT|0.536600|-2.09|21.04|-2.54|29631783|1.86|
|PUMPFUN_USDT|0.004773|-1.54|-23.88|-1.99|20067922|2.09|
|STRK_USDT|0.077000|-1.12|55.68|-1.57|24550763|1.30|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|INJ_USDT|7.669000|7.587000|7.669000|1.31|N|Y/Y|Y/N|Y|N|
|PUMPFUN_USDT|0.004773|0.004659|0.004773|0.49|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.077000|0.076280|0.077000|0.34|N|Y/Y|Y/Y|Y|N|
|S_USDT|0.053710|0.053450|0.053710|0.78|N|Y/Y|Y/N|Y|N|
|TIA_USDT|0.536600|0.528700|0.536600|2.15|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- INJ_USDT: quote_utc=2026-10-14T17:00:01+00:00, last15m_closed_end=2026-10-14T17:00+00:00, prior8high=7.873000, depth_time=2026-10-14T17:00:10+00:00, book20_bid_proxy_usdt=177533, book20_ask_proxy_usdt=224747, funding_indicative=0.000022, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.15%, turnover=47382237. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-14T17:00:01+00:00, last15m_closed_end=2026-10-14T17:00+00:00, prior8high=0.004848, depth_time=2026-10-14T17:00:15+00:00, book20_bid_proxy_usdt=864853, book20_ask_proxy_usdt=1352337, funding_indicative=0.000050, next_funding_utc=2026-10-14T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.54%, turnover=20067922. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T17:00:01+00:00, last15m_closed_end=2026-10-14T17:00+00:00, prior8high=0.079670, depth_time=2026-10-14T17:00:16+00:00, book20_bid_proxy_usdt=229722, book20_ask_proxy_usdt=310160, funding_indicative=0.000035, next_funding_utc=2026-10-14T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.12%, turnover=24550763. target_RR/account_short_permission/settled_funding=UNKNOWN.
- S_USDT: quote_utc=2026-10-14T17:00:01+00:00, last15m_closed_end=2026-10-14T17:00+00:00, prior8high=0.055930, depth_time=2026-10-14T17:00:06+00:00, book20_bid_proxy_usdt=179007, book20_ask_proxy_usdt=156161, funding_indicative=-0.000049, next_funding_utc=2026-10-14T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.29%, turnover=7977273. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-14T17:00:01+00:00, last15m_closed_end=2026-10-14T17:00+00:00, prior8high=0.548400, depth_time=2026-10-14T17:00:12+00:00, book20_bid_proxy_usdt=187229, book20_ask_proxy_usdt=219931, funding_indicative=-0.000047, next_funding_utc=2026-10-14T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.09%, turnover=29631783. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
