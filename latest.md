# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T03:30:17Z**
- feed_generated_utc: 2026-10-16T03:30:18+00:00
- source_sha256: `4223bb8a2d1d7e632bdc1f21100268627bce1dd1376274bee01d92278048ee7e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T03:30+00:00, close=82010.8, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-16T03:00+00:00, close=82016.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-16T00:00+00:00, close=82195.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|WAL_USDT|0.045480|-14.67|36.61|-14.23|5540824|4.40|
|ZEREBRO_USDT|0.044137|-13.95|60.74|-13.51|6992251|8.61|
|AKE_USDT|0.030515|-3.44|5.14|-3.00|20363225|2.29|
|BTW_USDT|1.862900|-2.33|34.18|-1.89|21847728|3.22|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.030515|0.030214|0.030500|1.18|N|Y/N|N/N|Y|N|
|BTW_USDT|1.862900|1.800900|1.862900|1.04|N|N/Y|Y/Y|Y|N|
|WAL_USDT|0.045480|0.044820|0.045480|0.39|N|Y/Y|N/N|Y|N|
|ZEREBRO_USDT|0.044137|0.048277|0.044246|4.51|Y|N/N|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-16T03:30:00+00:00, last15m_closed_end=2026-10-16T03:30+00:00, prior8high=0.032381, depth_time=2026-10-16T03:30:13+00:00, book20_bid_proxy_usdt=10218, book20_ask_proxy_usdt=15720, funding_indicative=0.000114, next_funding_utc=2026-10-16T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.44%, turnover=20363225. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-16T03:30:00+00:00, last15m_closed_end=2026-10-16T03:30+00:00, prior8high=1.994900, depth_time=2026-10-16T03:30:15+00:00, book20_bid_proxy_usdt=10046, book20_ask_proxy_usdt=17506, funding_indicative=0.000050, next_funding_utc=2026-10-16T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.33%, turnover=21847728. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WAL_USDT: quote_utc=2026-10-16T03:30:00+00:00, last15m_closed_end=2026-10-16T03:30+00:00, prior8high=0.051560, depth_time=2026-10-16T03:30:08+00:00, book20_bid_proxy_usdt=202311, book20_ask_proxy_usdt=78981, funding_indicative=-0.000569, next_funding_utc=2026-10-16T04:00:00+00:00, funding_cycle_h=4, 24h_change=-14.67%, turnover=5540824. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEREBRO_USDT: quote_utc=2026-10-16T03:30:00+00:00, last15m_closed_end=2026-10-16T03:30+00:00, prior8high=0.059435, depth_time=2026-10-16T03:30:11+00:00, book20_bid_proxy_usdt=4524, book20_ask_proxy_usdt=10470, funding_indicative=0.000066, next_funding_utc=2026-10-16T04:00:00+00:00, funding_cycle_h=4, 24h_change=-13.95%, turnover=6992251. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
