# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T11:30:16Z**
- feed_generated_utc: 2026-11-06T11:30:17+00:00
- source_sha256: `d508cd82ee3fa354e012084dbdc896045e56614a8ca3db16465fd32a086d1bdd`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T11:30+00:00, close=76084.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-06T11:00+00:00, close=76033.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T08:00+00:00, close=75573.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|XRP_USDT|1.190500|-4.34|-9.08|-4.43|486598689|0.84|
|BCH_USDT|268.290000|-3.88|-6.93|-3.97|7520055|3.73|
|XPL_USDT|0.057750|-1.41|-26.83|-1.50|12189995|1.73|
|QNT_USDT|189.140000|-1.39|-4.83|-1.48|35236933|0.53|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BCH_USDT|268.290000|266.560000|268.290000|2.52|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|189.140000|188.460000|189.140000|1.37|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.057750|0.057490|0.057750|0.27|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.190500|1.190800|1.190500|1.13|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BCH_USDT: quote_utc=2026-11-06T11:30:03+00:00, last15m_closed_end=2026-11-06T11:30+00:00, prior8high=269.310000, depth_time=2026-11-06T11:30:10+00:00, book20_bid_proxy_usdt=45570, book20_ask_proxy_usdt=89127, funding_indicative=-0.000051, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.88%, turnover=7520055. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-06T11:30:03+00:00, last15m_closed_end=2026-11-06T11:30+00:00, prior8high=189.720000, depth_time=2026-11-06T11:30:15+00:00, book20_bid_proxy_usdt=76167, book20_ask_proxy_usdt=92187, funding_indicative=-0.000003, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.39%, turnover=35236933. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-06T11:30:03+00:00, last15m_closed_end=2026-11-06T11:30+00:00, prior8high=0.057900, depth_time=2026-11-06T11:30:06+00:00, book20_bid_proxy_usdt=534094, book20_ask_proxy_usdt=422382, funding_indicative=0.000050, next_funding_utc=2026-11-06T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.41%, turnover=12189995. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-06T11:30:03+00:00, last15m_closed_end=2026-11-06T11:30+00:00, prior8high=1.201800, depth_time=2026-11-06T11:30:07+00:00, book20_bid_proxy_usdt=3253498, book20_ask_proxy_usdt=3547237, funding_indicative=0.000100, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.34%, turnover=486598689. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
