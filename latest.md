# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T00:30:16Z**
- feed_generated_utc: 2026-10-21T00:30:18+00:00
- source_sha256: `10a8522a8850ade658f7b4eec17c7d431c311c443baf2f55d61798cae0866736`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T00:30+00:00, close=83139.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T00:00+00:00, close=82984.8, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T00:00+00:00, close=82984.8, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.193990|-10.09|9.36|-10.77|10133187|0.52|
|XMR_USDT|589.440000|-4.95|11.65|-5.63|16488709|0.34|
|AGT_USDT|0.061849|-4.30|282.32|-4.98|7239999|7.77|
|TIA_USDT|0.616600|-0.97|6.80|-1.65|45862444|1.62|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.061849|0.055541|0.061849|2.38|N|Y/Y|Y/Y|N|N|
|BAT_USDT|0.193990|0.193360|0.193990|2.52|N|Y/Y|N/N|N|N|
|TIA_USDT|0.616600|0.616700|0.616600|2.06|Y|Y/Y|Y/Y|N|Y|
|XMR_USDT|589.440000|583.880000|589.440000|9.49|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-21T00:29:59+00:00, last15m_closed_end=2026-10-21T00:30+00:00, prior8high=0.063454, depth_time=2026-10-21T00:30:13+00:00, book20_bid_proxy_usdt=13107, book20_ask_proxy_usdt=5021, funding_indicative=0.000047, next_funding_utc=2026-10-21T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.30%, turnover=7239999. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T00:29:59+00:00, last15m_closed_end=2026-10-21T00:30+00:00, prior8high=0.196640, depth_time=2026-10-21T00:30:07+00:00, book20_bid_proxy_usdt=30171, book20_ask_proxy_usdt=26642, funding_indicative=0.000080, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-10.09%, turnover=10133187. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T00:29:59+00:00, last15m_closed_end=2026-10-21T00:30+00:00, prior8high=0.629000, depth_time=2026-10-21T00:30:14+00:00, book20_bid_proxy_usdt=166872, book20_ask_proxy_usdt=279178, funding_indicative=-0.000077, next_funding_utc=2026-10-21T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.97%, turnover=45862444. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-21T00:29:59+00:00, last15m_closed_end=2026-10-21T00:30+00:00, prior8high=624.900000, depth_time=2026-10-21T00:30:10+00:00, book20_bid_proxy_usdt=8908, book20_ask_proxy_usdt=11018, funding_indicative=0.000100, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.95%, turnover=16488709. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
