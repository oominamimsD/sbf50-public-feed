# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T00:00:15Z**
- feed_generated_utc: 2026-10-19T00:00:16+00:00
- source_sha256: `9495fcf291a983751258f54fa65ea173f6196a65a5ab6858895d1b7eacb8ffd0`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T00:00+00:00, close=82076.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-19T00:00+00:00, close=82076.8, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-19T00:00+00:00, close=82076.8, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|SAND_USDT|0.058550|-2.78|-11.87|-4.03|33749261|1.71|
|AGT_USDT|0.067300|-2.75|280.54|-4.00|10006103|7.43|
|Q_USDT|0.112355|-2.00|296.70|-3.25|9900690|0.36|
|STRK_USDT|0.060420|-0.65|-49.34|-1.90|15976200|1.66|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.067300|0.060544|0.067300|0.60|N|Y/Y|N/N|N|N|
|Q_USDT|0.112355|0.111654|0.112355|0.62|N|Y/Y|N/N|N|N|
|SAND_USDT|0.058550|0.056400|0.058560|1.49|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.060420|0.059380|0.060420|1.53|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-19T00:00:00+00:00, last15m_closed_end=2026-10-19T00:00+00:00, prior8high=0.068584, depth_time=2026-10-19T00:00:10+00:00, book20_bid_proxy_usdt=2627, book20_ask_proxy_usdt=5355, funding_indicative=0.000235, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.75%, turnover=10006103. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-19T00:00:00+00:00, last15m_closed_end=2026-10-19T00:00+00:00, prior8high=0.122022, depth_time=2026-10-19T00:00:12+00:00, book20_bid_proxy_usdt=6313, book20_ask_proxy_usdt=7614, funding_indicative=0.000086, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.00%, turnover=9900690. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-19T00:00:00+00:00, last15m_closed_end=2026-10-19T00:00+00:00, prior8high=0.058900, depth_time=2026-10-19T00:00:07+00:00, book20_bid_proxy_usdt=399854, book20_ask_proxy_usdt=304943, funding_indicative=-0.002790, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.78%, turnover=33749261. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-19T00:00:00+00:00, last15m_closed_end=2026-10-19T00:00+00:00, prior8high=0.061020, depth_time=2026-10-19T00:00:14+00:00, book20_bid_proxy_usdt=618934, book20_ask_proxy_usdt=338779, funding_indicative=0.000050, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.65%, turnover=15976200. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
