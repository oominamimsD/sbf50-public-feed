# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T04:00:24Z**
- feed_generated_utc: 2026-10-21T04:00:26+00:00
- source_sha256: `b594699ce538aca644c791954e886f7e6b3919de558f483a66a1e75e3f8c2a66`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1201; contracts: 1193; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T04:00+00:00, close=82699, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-21T04:00+00:00, close=82699, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T04:00+00:00, close=82699, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.186160|-13.72|4.94|-13.86|10576808|0.54|
|XMR_USDT|575.560000|-7.19|9.02|-7.33|20742311|0.17|
|BR_USDT|0.615290|-5.43|42.09|-5.57|35558663|0.16|
|AGT_USDT|0.061220|-5.27|278.43|-5.41|7014485|8.98|
|Q_USDT|0.118150|-3.75|187.28|-3.89|5105895|4.65|
|TIA_USDT|0.614500|-1.31|6.44|-1.45|48892620|1.63|
|PHA_USDT|0.057230|-1.02|3.99|-1.16|9152039|1.75|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.061220|0.061376|0.061245|1.11|N|Y/Y|Y/Y|N|N|
|BAT_USDT|0.186160|0.185410|0.186160|0.55|N|Y/Y|Y/N|N|N|
|BR_USDT|0.615290|0.613570|0.615290|0.83|N|Y/Y|N/N|N|N|
|PHA_USDT|0.057230|0.056980|0.057230|1.65|N|Y/Y|N/N|N|N|
|Q_USDT|0.118150|0.116120|0.118150|1.35|N|Y/Y|N/N|N|N|
|TIA_USDT|0.614500|0.608800|0.614500|0.21|N|Y/Y|Y/Y|N|N|
|XMR_USDT|575.560000|571.180000|575.560000|0.46|N|Y/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-21T03:59:59+00:00, last15m_closed_end=2026-10-21T04:00+00:00, prior8high=0.064559, depth_time=2026-10-21T04:00:16+00:00, book20_bid_proxy_usdt=6583, book20_ask_proxy_usdt=6848, funding_indicative=0.000047, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.27%, turnover=7014485. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T03:59:59+00:00, last15m_closed_end=2026-10-21T04:00+00:00, prior8high=0.191200, depth_time=2026-10-21T04:00:09+00:00, book20_bid_proxy_usdt=23210, book20_ask_proxy_usdt=25213, funding_indicative=0.000031, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-13.72%, turnover=10576808. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T03:59:59+00:00, last15m_closed_end=2026-10-21T04:00+00:00, prior8high=0.652610, depth_time=2026-10-21T04:00:13+00:00, book20_bid_proxy_usdt=4045, book20_ask_proxy_usdt=2905, funding_indicative=-0.000013, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.43%, turnover=35558663. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PHA_USDT: quote_utc=2026-10-21T03:59:59+00:00, last15m_closed_end=2026-10-21T04:00+00:00, prior8high=0.058840, depth_time=2026-10-21T04:00:20+00:00, book20_bid_proxy_usdt=70672, book20_ask_proxy_usdt=92978, funding_indicative=0.000022, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.02%, turnover=9152039. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-21T03:59:59+00:00, last15m_closed_end=2026-10-21T04:00+00:00, prior8high=0.121697, depth_time=2026-10-21T04:00:18+00:00, book20_bid_proxy_usdt=17209, book20_ask_proxy_usdt=19497, funding_indicative=-0.000217, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.75%, turnover=5105895. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T03:59:59+00:00, last15m_closed_end=2026-10-21T04:00+00:00, prior8high=0.619700, depth_time=2026-10-21T04:00:21+00:00, book20_bid_proxy_usdt=179756, book20_ask_proxy_usdt=303628, funding_indicative=-0.000048, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.31%, turnover=48892620. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-21T03:59:59+00:00, last15m_closed_end=2026-10-21T04:00+00:00, prior8high=588.450000, depth_time=2026-10-21T04:00:10+00:00, book20_bid_proxy_usdt=30238, book20_ask_proxy_usdt=9585, funding_indicative=0.000100, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-7.19%, turnover=20742311. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
