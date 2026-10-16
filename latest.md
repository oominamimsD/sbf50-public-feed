# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T13:15:16Z**
- feed_generated_utc: 2026-10-16T13:15:18+00:00
- source_sha256: `f14439e4db5617f0afbe112229c3b7d7e3d7e9d800758b28c989faaa700b7625`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T13:15+00:00, close=82013.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-16T13:00+00:00, close=82010.8, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-10-16T12:00+00:00, close=82599.5, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.076160|-20.96|26.59|-20.51|39647552|1.31|
|PYTH_USDT|0.088190|-9.40|19.82|-8.95|9270292|4.54|
|BTW_USDT|1.750600|-8.22|26.09|-7.77|20832010|8.00|
|AKE_USDT|0.029260|-7.41|0.81|-6.96|17045657|1.37|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.029260|0.029345|0.029256|1.84|Y|Y/Y|N/N|N|N|
|BTW_USDT|1.750600|1.611400|1.749700|0.74|N|Y/Y|Y/Y|N|N|
|PYTH_USDT|0.088190|0.086360|0.088260|1.12|N|Y/Y|N/N|N|N|
|STRK_USDT|0.076160|0.075410|0.076160|0.41|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-16T13:15:01+00:00, last15m_closed_end=2026-10-16T13:15+00:00, prior8high=0.030310, depth_time=2026-10-16T13:15:15+00:00, book20_bid_proxy_usdt=14223, book20_ask_proxy_usdt=20607, funding_indicative=0.000050, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.41%, turnover=17045657. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-16T13:15:01+00:00, last15m_closed_end=2026-10-16T13:15+00:00, prior8high=1.852200, depth_time=2026-10-16T13:15:13+00:00, book20_bid_proxy_usdt=12388, book20_ask_proxy_usdt=18087, funding_indicative=-0.000449, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.22%, turnover=20832010. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PYTH_USDT: quote_utc=2026-10-16T13:15:01+00:00, last15m_closed_end=2026-10-16T13:15+00:00, prior8high=0.092450, depth_time=2026-10-16T13:15:10+00:00, book20_bid_proxy_usdt=103463, book20_ask_proxy_usdt=122167, funding_indicative=0.000021, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.40%, turnover=9270292. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-16T13:15:01+00:00, last15m_closed_end=2026-10-16T13:15+00:00, prior8high=0.080420, depth_time=2026-10-16T13:15:08+00:00, book20_bid_proxy_usdt=293921, book20_ask_proxy_usdt=314510, funding_indicative=-0.000002, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-20.96%, turnover=39647552. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
