# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T08:15:16Z**
- feed_generated_utc: 2026-10-16T08:15:18+00:00
- source_sha256: `2ff477ae389c1906b106f47e8c695a9cff28851735669e4afb7b5731c20bb5d7`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1196; contracts: 1188; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T08:15+00:00, close=82213.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-16T08:00+00:00, close=82258.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-16T08:00+00:00, close=82258.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.078800|-18.22|30.98|-18.03|47397459|2.54|
|ZEREBRO_USDT|0.046896|-8.57|70.79|-8.38|6589113|4.06|
|AKE_USDT|0.028991|-8.27|-0.11|-8.08|21019410|6.57|
|NIL_USDT|0.082910|-4.56|-4.24|-4.37|8344165|3.62|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.028991|0.029859|0.028980|2.23|Y|Y/Y|N/N|Y|N|
|NIL_USDT|0.082910|0.083680|0.082910|1.70|Y|Y/Y|Y/N|Y|N|
|STRK_USDT|0.078800|0.079300|0.078800|2.14|Y|Y/Y|Y/Y|Y|Y|
|ZEREBRO_USDT|0.046896|0.040071|0.046896|0.96|N|N/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-16T08:15:01+00:00, last15m_closed_end=2026-10-16T08:15+00:00, prior8high=0.031274, depth_time=2026-10-16T08:15:13+00:00, book20_bid_proxy_usdt=13158, book20_ask_proxy_usdt=17823, funding_indicative=0.000050, next_funding_utc=2026-10-16T12:00:00+00:00, funding_cycle_h=4, 24h_change=-8.27%, turnover=21019410. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NIL_USDT: quote_utc=2026-10-16T08:15:01+00:00, last15m_closed_end=2026-10-16T08:15+00:00, prior8high=0.086860, depth_time=2026-10-16T08:15:15+00:00, book20_bid_proxy_usdt=34275, book20_ask_proxy_usdt=17675, funding_indicative=0.000050, next_funding_utc=2026-10-16T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.56%, turnover=8344165. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-16T08:15:01+00:00, last15m_closed_end=2026-10-16T08:15+00:00, prior8high=0.084360, depth_time=2026-10-16T08:15:07+00:00, book20_bid_proxy_usdt=300112, book20_ask_proxy_usdt=318473, funding_indicative=-0.000020, next_funding_utc=2026-10-16T12:00:00+00:00, funding_cycle_h=4, 24h_change=-18.22%, turnover=47397459. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEREBRO_USDT: quote_utc=2026-10-16T08:15:01+00:00, last15m_closed_end=2026-10-16T08:15+00:00, prior8high=0.047183, depth_time=2026-10-16T08:15:10+00:00, book20_bid_proxy_usdt=7794, book20_ask_proxy_usdt=25142, funding_indicative=0.000050, next_funding_utc=2026-10-16T12:00:00+00:00, funding_cycle_h=4, 24h_change=-8.57%, turnover=6589113. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
