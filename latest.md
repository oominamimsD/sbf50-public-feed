# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T23:00:14Z**
- feed_generated_utc: 2026-10-19T23:00:17+00:00
- source_sha256: `693ffc067799422bf34d5ab720f94471790269a235193b992109c574b79d6ff9`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T23:00+00:00, close=82020.1, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-19T23:00+00:00, close=82020.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-19T20:00+00:00, close=81847.2, belowEMA20=True, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|SAND_USDT|0.058930|-1.05|-5.08|-1.17|8508808|1.70|
|OP_USDT|0.123910|-0.95|-8.42|-1.07|6704489|0.81|
|CT_USDT|0.327040|-0.92|-4.41|-1.04|5159880|0.92|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|CT_USDT|0.327040|0.324490|0.327040|0.41|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.123910|0.122890|0.123910|0.04|N|Y/Y|Y/Y|Y|N|
|SAND_USDT|0.058930|0.058650|0.058930|0.18|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- CT_USDT: quote_utc=2026-10-19T22:59:59+00:00, last15m_closed_end=2026-10-19T23:00+00:00, prior8high=0.329680, depth_time=2026-10-19T23:00:12+00:00, book20_bid_proxy_usdt=9334, book20_ask_proxy_usdt=13220, funding_indicative=-0.000717, next_funding_utc=2026-10-20T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.92%, turnover=5159880. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-19T23:00:00+00:00, last15m_closed_end=2026-10-19T23:00+00:00, prior8high=0.125400, depth_time=2026-10-19T23:00:10+00:00, book20_bid_proxy_usdt=111176, book20_ask_proxy_usdt=102821, funding_indicative=-0.000119, next_funding_utc=2026-10-20T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.95%, turnover=6704489. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-19T23:00:00+00:00, last15m_closed_end=2026-10-19T23:00+00:00, prior8high=0.059950, depth_time=2026-10-19T23:00:07+00:00, book20_bid_proxy_usdt=791379, book20_ask_proxy_usdt=889368, funding_indicative=-0.002250, next_funding_utc=2026-10-20T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.05%, turnover=8508808. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
