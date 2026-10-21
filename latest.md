# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T00:45:18Z**
- feed_generated_utc: 2026-10-21T00:45:20+00:00
- source_sha256: `976de9c75e629c2558fc55bb49d75c57f8852103c5b3b3f7f03e241ee551f1d9`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T00:45+00:00, close=83095.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T00:00+00:00, close=82984.8, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T00:00+00:00, close=82984.8, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.192050|-10.99|8.27|-11.61|10176630|0.52|
|XMR_USDT|584.980000|-5.67|10.81|-6.29|16759469|0.86|
|TIA_USDT|0.615200|-1.20|6.56|-1.82|46211729|1.62|
|ARB_USDT|0.188220|-0.38|1.93|-1.00|83850373|0.53|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.188220|0.186350|0.188220|0.16|N|Y/Y|Y/Y|N|N|
|BAT_USDT|0.192050|0.192790|0.192060|0.92|N|Y/Y|N/N|N|N|
|TIA_USDT|0.615200|0.613700|0.615200|1.20|N|Y/Y|Y/Y|N|N|
|XMR_USDT|584.980000|583.880000|584.980000|3.91|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-21T00:44:59+00:00, last15m_closed_end=2026-10-21T00:45+00:00, prior8high=0.189740, depth_time=2026-10-21T00:45:17+00:00, book20_bid_proxy_usdt=78026, book20_ask_proxy_usdt=78435, funding_indicative=-0.000088, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.38%, turnover=83850373. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T00:44:59+00:00, last15m_closed_end=2026-10-21T00:45+00:00, prior8high=0.195870, depth_time=2026-10-21T00:45:08+00:00, book20_bid_proxy_usdt=20014, book20_ask_proxy_usdt=21623, funding_indicative=0.000080, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-10.99%, turnover=10176630. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T00:44:59+00:00, last15m_closed_end=2026-10-21T00:45+00:00, prior8high=0.625800, depth_time=2026-10-21T00:45:14+00:00, book20_bid_proxy_usdt=193598, book20_ask_proxy_usdt=218726, funding_indicative=-0.000075, next_funding_utc=2026-10-21T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.20%, turnover=46211729. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-21T00:44:59+00:00, last15m_closed_end=2026-10-21T00:45+00:00, prior8high=624.900000, depth_time=2026-10-21T00:45:11+00:00, book20_bid_proxy_usdt=19480, book20_ask_proxy_usdt=15414, funding_indicative=0.000100, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.67%, turnover=16759469. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
