# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-03T18:30:18Z**
- feed_generated_utc: 2026-11-03T18:30:20+00:00
- source_sha256: `8da2144f696765dcff6f784200654c28f813c0d04508f79122896c9c37b1f00d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-03T18:30+00:00, close=77646.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-03T18:00+00:00, close=77626.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-03T16:00+00:00, close=77664.3, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.003851|-7.33|-81.77|-7.31|12898197|2.60|
|BEAT_USDT|0.093100|-1.79|2.20|-1.77|8911338|1.07|
|TRUMPOFFICIAL_USDT|1.580000|-1.74|-6.39|-1.72|6559545|6.33|
|TIA_USDT|0.430200|-1.28|-19.75|-1.26|12373059|4.65|
|QNT_USDT|193.070000|-1.20|-2.43|-1.18|56281862|3.62|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.003851|0.003806|0.003851|0.74|N|Y/Y|Y/Y|N|N|
|BEAT_USDT|0.093100|0.089460|0.093100|0.69|N|Y/Y|Y/N|N|N|
|QNT_USDT|193.070000|192.330000|192.960000|1.37|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.430200|0.429100|0.430100|0.52|N|Y/Y|Y/Y|N|N|
|TRUMPOFFICIAL_USDT|1.580000|1.580000|1.581000|0.63|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-03T18:30:04+00:00, last15m_closed_end=2026-11-03T18:30+00:00, prior8high=0.004096, depth_time=2026-11-03T18:30:08+00:00, book20_bid_proxy_usdt=56000, book20_ask_proxy_usdt=95225, funding_indicative=-0.000829, next_funding_utc=2026-11-03T20:00:00+00:00, funding_cycle_h=4, 24h_change=-7.33%, turnover=12898197. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-11-03T18:30:04+00:00, last15m_closed_end=2026-11-03T18:30+00:00, prior8high=0.093110, depth_time=2026-11-03T18:30:10+00:00, book20_bid_proxy_usdt=16902, book20_ask_proxy_usdt=15431, funding_indicative=0.000209, next_funding_utc=2026-11-03T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.79%, turnover=8911338. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-03T18:30:04+00:00, last15m_closed_end=2026-11-03T18:30+00:00, prior8high=195.800000, depth_time=2026-11-03T18:30:17+00:00, book20_bid_proxy_usdt=105182, book20_ask_proxy_usdt=98317, funding_indicative=0.000100, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.20%, turnover=56281862. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-03T18:30:04+00:00, last15m_closed_end=2026-11-03T18:30+00:00, prior8high=0.437100, depth_time=2026-11-03T18:30:15+00:00, book20_bid_proxy_usdt=294244, book20_ask_proxy_usdt=400811, funding_indicative=-0.000006, next_funding_utc=2026-11-03T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.28%, turnover=12373059. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-03T18:30:04+00:00, last15m_closed_end=2026-11-03T18:30+00:00, prior8high=1.603000, depth_time=2026-11-03T18:30:11+00:00, book20_bid_proxy_usdt=2353971, book20_ask_proxy_usdt=2252578, funding_indicative=0.000032, next_funding_utc=2026-11-03T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.74%, turnover=6559545. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
