# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T23:45:15Z**
- feed_generated_utc: 2026-10-13T23:45:17+00:00
- source_sha256: `fca26d423908cc84d0b74462a86f1bc89af917e2f3fc31d712ea79f0a9b0a208`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T23:45+00:00, close=83208, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-13T23:00+00:00, close=83483.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-13T20:00+00:00, close=83253, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|1000RATS_USDT|0.016600|-10.22|-58.67|-10.00|5199639|6.02|
|RLC_USDT|0.894000|-3.16|9.05|-2.94|5114685|2.24|
|CT_USDT|0.361490|-2.76|-2.72|-2.54|5450243|6.36|
|STRK_USDT|0.085510|-1.63|63.84|-1.41|38031640|1.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|1000RATS_USDT|0.016600|0.015990|0.016600|0.85|N|Y/Y|Y/Y|N|N|
|CT_USDT|0.361490|0.356040|0.361490|0.92|N|N/Y|N/N|N|N|
|RLC_USDT|0.894000|0.887000|0.894000|0.10|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.085510|0.082530|0.085510|1.86|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- 1000RATS_USDT: quote_utc=2026-10-13T23:45:00+00:00, last15m_closed_end=2026-10-13T23:45+00:00, prior8high=0.017190, depth_time=2026-10-13T23:45:07+00:00, book20_bid_proxy_usdt=38507, book20_ask_proxy_usdt=59203, funding_indicative=0.000050, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-10.22%, turnover=5199639. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CT_USDT: quote_utc=2026-10-13T23:45:00+00:00, last15m_closed_end=2026-10-13T23:45+00:00, prior8high=0.366370, depth_time=2026-10-13T23:45:11+00:00, book20_bid_proxy_usdt=7397, book20_ask_proxy_usdt=9820, funding_indicative=0.000050, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.76%, turnover=5450243. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-13T23:45:00+00:00, last15m_closed_end=2026-10-13T23:45+00:00, prior8high=0.903000, depth_time=2026-10-13T23:45:09+00:00, book20_bid_proxy_usdt=50604, book20_ask_proxy_usdt=78767, funding_indicative=-0.000453, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.16%, turnover=5114685. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-13T23:45:00+00:00, last15m_closed_end=2026-10-13T23:45+00:00, prior8high=0.085400, depth_time=2026-10-13T23:45:14+00:00, book20_bid_proxy_usdt=295449, book20_ask_proxy_usdt=148737, funding_indicative=-0.000008, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.63%, turnover=38031640. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
