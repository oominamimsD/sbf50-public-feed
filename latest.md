# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T02:30:16Z**
- feed_generated_utc: 2026-10-25T02:30:19+00:00
- source_sha256: `124cf92377b1a8805ce118b9ac5d6f531a8511bbb840faa4afd9d455dbca7b56`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T02:30+00:00, close=80818.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-25T02:00+00:00, close=80872.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-25T00:00+00:00, close=80845, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BIRB_USDT|0.074020|-24.20|52.55|-25.52|9578564|1.35|
|ORDER_USDT|0.053160|-21.12|71.76|-22.44|13399030|5.66|
|IRYS_USDT|0.036340|-21.08|184.79|-22.40|32786149|8.27|
|STRK_USDT|0.046570|-0.34|-29.59|-1.66|8313453|2.15|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BIRB_USDT|0.074020|0.069260|0.074020|0.89|N|Y/Y|Y/N|Y|N|
|IRYS_USDT|0.036340|0.031610|0.036340|2.35|N|Y/Y|Y/Y|Y|N|
|ORDER_USDT|0.053160|0.050660|0.053160|0.52|N|Y/N|N/N|Y|N|
|STRK_USDT|0.046570|0.046420|0.046600|1.48|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BIRB_USDT: quote_utc=2026-10-25T02:30:00+00:00, last15m_closed_end=2026-10-25T02:30+00:00, prior8high=0.089930, depth_time=2026-10-25T02:30:08+00:00, book20_bid_proxy_usdt=20201, book20_ask_proxy_usdt=14713, funding_indicative=-0.014895, next_funding_utc=2026-10-25T04:00:00+00:00, funding_cycle_h=4, 24h_change=-24.20%, turnover=9578564. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T02:30:00+00:00, last15m_closed_end=2026-10-25T02:30+00:00, prior8high=0.044410, depth_time=2026-10-25T02:30:13+00:00, book20_bid_proxy_usdt=34596, book20_ask_proxy_usdt=27981, funding_indicative=0.000012, next_funding_utc=2026-10-25T03:00:00+00:00, funding_cycle_h=1, 24h_change=-21.08%, turnover=32786149. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T02:30:00+00:00, last15m_closed_end=2026-10-25T02:30+00:00, prior8high=0.068630, depth_time=2026-10-25T02:30:11+00:00, book20_bid_proxy_usdt=73874, book20_ask_proxy_usdt=50951, funding_indicative=-0.001269, next_funding_utc=2026-10-25T03:00:00+00:00, funding_cycle_h=1, 24h_change=-21.12%, turnover=13399030. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T02:30:01+00:00, last15m_closed_end=2026-10-25T02:30+00:00, prior8high=0.047560, depth_time=2026-10-25T02:30:16+00:00, book20_bid_proxy_usdt=878273, book20_ask_proxy_usdt=664088, funding_indicative=0.000050, next_funding_utc=2026-10-25T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.34%, turnover=8313453. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
