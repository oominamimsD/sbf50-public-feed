# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T03:15:18Z**
- feed_generated_utc: 2026-10-25T03:15:21+00:00
- source_sha256: `a2123d7c01d6fe38e7da83afd2bbf7284d753ee7d655089cb86a40aa8cd91885`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T03:15+00:00, close=80940.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-25T03:00+00:00, close=80875.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-25T00:00+00:00, close=80845, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BIRB_USDT|0.078850|-19.26|62.51|-20.73|9214775|2.55|
|ORDER_USDT|0.055210|-18.08|78.38|-19.55|13458735|5.45|
|IRYS_USDT|0.040200|-12.70|215.04|-14.17|31939269|2.48|
|DOT_USDT|1.043200|0.39|-6.64|-1.08|11526496|0.96|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BIRB_USDT|0.078850|0.069370|0.078850|1.00|N|Y/Y|Y/N|Y|N|
|DOT_USDT|1.043200|1.041400|1.043200|0.93|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.040200|0.031610|0.040370|1.96|N|Y/Y|Y/Y|Y|N|
|ORDER_USDT|0.055210|0.050530|0.054920|0.76|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BIRB_USDT: quote_utc=2026-10-25T03:15:02+00:00, last15m_closed_end=2026-10-25T03:15+00:00, prior8high=0.078910, depth_time=2026-10-25T03:15:09+00:00, book20_bid_proxy_usdt=6790, book20_ask_proxy_usdt=12756, funding_indicative=-0.010796, next_funding_utc=2026-10-25T04:00:00+00:00, funding_cycle_h=4, 24h_change=-19.26%, turnover=9214775. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-25T03:15:03+00:00, last15m_closed_end=2026-10-25T03:15+00:00, prior8high=1.055300, depth_time=2026-10-25T03:15:17+00:00, book20_bid_proxy_usdt=301635, book20_ask_proxy_usdt=308227, funding_indicative=-0.000107, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=8, 24h_change=0.39%, turnover=11526496. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T03:15:02+00:00, last15m_closed_end=2026-10-25T03:15+00:00, prior8high=0.041220, depth_time=2026-10-25T03:15:14+00:00, book20_bid_proxy_usdt=30418, book20_ask_proxy_usdt=34664, funding_indicative=-0.000030, next_funding_utc=2026-10-25T04:00:00+00:00, funding_cycle_h=1, 24h_change=-12.70%, turnover=31939269. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T03:15:02+00:00, last15m_closed_end=2026-10-25T03:15+00:00, prior8high=0.057510, depth_time=2026-10-25T03:15:12+00:00, book20_bid_proxy_usdt=62040, book20_ask_proxy_usdt=55273, funding_indicative=-0.001007, next_funding_utc=2026-10-25T04:00:00+00:00, funding_cycle_h=1, 24h_change=-18.08%, turnover=13458735. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
