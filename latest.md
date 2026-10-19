# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T07:15:15Z**
- feed_generated_utc: 2026-10-19T07:15:17+00:00
- source_sha256: `7fd8d9754abea9145a11ea4916aee6a889d659de05eda986c62943dd8a41edce`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T07:15+00:00, close=82788.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-19T07:00+00:00, close=82812.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-19T04:00+00:00, close=82496.1, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ICNT_USDT|0.169100|-5.74|59.52|-7.77|7049721|5.92|
|STRK_USDT|0.059490|-3.36|-50.12|-5.39|17447645|1.68|
|BTW_USDT|2.242900|-2.71|33.33|-4.74|21680453|0.45|
|TIA_USDT|0.608500|-1.52|3.36|-3.55|56649750|1.64|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|2.242900|2.166400|2.242800|1.13|N|Y/Y|N/N|N|N|
|ICNT_USDT|0.169100|0.167400|0.169100|1.02|N|Y/Y|N/N|N|N|
|STRK_USDT|0.059490|0.059520|0.059490|1.32|Y|Y/Y|Y/Y|N|Y|
|TIA_USDT|0.608500|0.604400|0.608500|0.45|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-19T07:14:59+00:00, last15m_closed_end=2026-10-19T07:15+00:00, prior8high=2.321000, depth_time=2026-10-19T07:15:11+00:00, book20_bid_proxy_usdt=8994, book20_ask_proxy_usdt=8329, funding_indicative=-0.000218, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.71%, turnover=21680453. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-19T07:14:59+00:00, last15m_closed_end=2026-10-19T07:15+00:00, prior8high=0.194500, depth_time=2026-10-19T07:15:06+00:00, book20_bid_proxy_usdt=94683, book20_ask_proxy_usdt=112673, funding_indicative=-0.000084, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.74%, turnover=7049721. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-19T07:14:59+00:00, last15m_closed_end=2026-10-19T07:15+00:00, prior8high=0.060780, depth_time=2026-10-19T07:15:10+00:00, book20_bid_proxy_usdt=995257, book20_ask_proxy_usdt=674585, funding_indicative=0.000050, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.36%, turnover=17447645. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-19T07:14:59+00:00, last15m_closed_end=2026-10-19T07:15+00:00, prior8high=0.616500, depth_time=2026-10-19T07:15:14+00:00, book20_bid_proxy_usdt=238869, book20_ask_proxy_usdt=247420, funding_indicative=-0.000036, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.52%, turnover=56649750. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
