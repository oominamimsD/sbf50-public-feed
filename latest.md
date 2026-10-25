# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T04:00:21Z**
- feed_generated_utc: 2026-10-25T04:00:24+00:00
- source_sha256: `4d3d0a78260837ca2cf9ffa61d3fd2ce02684a0afbb903ed193bf2e2cf941eb6`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T04:00+00:00, close=80826.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-25T04:00+00:00, close=80826.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-25T04:00+00:00, close=80826.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.044350|-22.08|247.57|-23.40|32335508|6.74|
|ORDER_USDT|0.056190|-17.45|81.55|-18.77|13526553|7.11|
|BTW_USDT|1.706000|-2.02|-24.82|-3.34|9820782|0.59|
|STRK_USDT|0.046780|-1.12|-29.28|-2.44|8397584|2.14|
|DOT_USDT|1.040200|-0.84|-6.90|-2.16|11358534|0.96|
|TIA_USDT|0.531900|-0.39|-19.16|-1.71|21744521|1.88|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.706000|1.696100|1.709600|1.17|N|Y/N|Y/Y|Y|N|
|DOT_USDT|1.040200|1.039600|1.040200|0.56|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.044350|0.031720|0.044360|1.41|N|Y/Y|Y/Y|Y|N|
|ORDER_USDT|0.056190|0.050530|0.056190|0.53|N|Y/Y|N/N|Y|N|
|STRK_USDT|0.046780|0.046250|0.046780|1.26|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.531900|0.529700|0.531900|0.10|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-25T04:00:01+00:00, last15m_closed_end=2026-10-25T04:00+00:00, prior8high=1.754800, depth_time=2026-10-25T04:00:12+00:00, book20_bid_proxy_usdt=11910, book20_ask_proxy_usdt=7837, funding_indicative=-0.003607, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.02%, turnover=9820782. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-25T04:00:01+00:00, last15m_closed_end=2026-10-25T04:00+00:00, prior8high=1.055200, depth_time=2026-10-25T04:00:18+00:00, book20_bid_proxy_usdt=307517, book20_ask_proxy_usdt=363777, funding_indicative=-0.000129, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.84%, turnover=11358534. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T04:00:01+00:00, last15m_closed_end=2026-10-25T04:00+00:00, prior8high=0.045340, depth_time=2026-10-25T04:00:08+00:00, book20_bid_proxy_usdt=36962, book20_ask_proxy_usdt=27355, funding_indicative=-0.000861, next_funding_utc=2026-10-25T05:00:00+00:00, funding_cycle_h=1, 24h_change=-22.08%, turnover=32335508. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T04:00:00+00:00, last15m_closed_end=2026-10-25T04:00+00:00, prior8high=0.058640, depth_time=2026-10-25T04:00:11+00:00, book20_bid_proxy_usdt=53753, book20_ask_proxy_usdt=58976, funding_indicative=-0.001192, next_funding_utc=2026-10-25T05:00:00+00:00, funding_cycle_h=1, 24h_change=-17.45%, turnover=13526553. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T04:00:01+00:00, last15m_closed_end=2026-10-25T04:00+00:00, prior8high=0.047120, depth_time=2026-10-25T04:00:15+00:00, book20_bid_proxy_usdt=882910, book20_ask_proxy_usdt=652345, funding_indicative=0.000050, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.12%, turnover=8397584. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-25T04:00:01+00:00, last15m_closed_end=2026-10-25T04:00+00:00, prior8high=0.539800, depth_time=2026-10-25T04:00:20+00:00, book20_bid_proxy_usdt=374515, book20_ask_proxy_usdt=326785, funding_indicative=-0.000024, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.39%, turnover=21744521. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
