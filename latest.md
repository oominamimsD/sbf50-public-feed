# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-03T19:00:20Z**
- feed_generated_utc: 2026-11-03T19:00:22+00:00
- source_sha256: `c2ec93412bb8ddad80fe0d917b9b3322650a630059d72c4ca78a057f9c60f032`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-03T19:00+00:00, close=77569.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-03T19:00+00:00, close=77569.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-03T16:00+00:00, close=77664.3, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.003981|-4.21|-81.15|-4.09|13168552|2.51|
|BEAT_USDT|0.096040|-3.45|5.43|-3.33|8460119|1.04|
|TIA_USDT|0.430900|-2.04|-19.62|-1.92|11782755|2.32|
|QNT_USDT|192.000000|-1.75|-2.97|-1.63|54661719|0.52|
|TRUMPOFFICIAL_USDT|1.579000|-1.68|-6.45|-1.56|6110390|6.33|
|XPL_USDT|0.063570|-1.13|-13.88|-1.01|9613888|4.72|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.003981|0.003757|0.003984|1.88|N|Y/Y|Y/Y|N|N|
|BEAT_USDT|0.096040|0.089610|0.096040|1.30|N|Y/Y|Y/N|N|N|
|QNT_USDT|192.000000|191.690000|191.970000|0.41|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.430900|0.429100|0.430900|0.62|N|Y/Y|Y/Y|N|N|
|TRUMPOFFICIAL_USDT|1.579000|1.574000|1.579000|2.14|N|Y/Y|Y/Y|N|N|
|XPL_USDT|0.063570|0.063250|0.063570|1.45|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-03T19:00:01+00:00, last15m_closed_end=2026-11-03T19:00+00:00, prior8high=0.004095, depth_time=2026-11-03T19:00:08+00:00, book20_bid_proxy_usdt=41189, book20_ask_proxy_usdt=41736, funding_indicative=-0.000659, next_funding_utc=2026-11-03T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.21%, turnover=13168552. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-11-03T19:00:01+00:00, last15m_closed_end=2026-11-03T19:00+00:00, prior8high=0.095180, depth_time=2026-11-03T19:00:10+00:00, book20_bid_proxy_usdt=14073, book20_ask_proxy_usdt=20585, funding_indicative=0.000229, next_funding_utc=2026-11-03T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.45%, turnover=8460119. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-03T19:00:01+00:00, last15m_closed_end=2026-11-03T19:00+00:00, prior8high=195.800000, depth_time=2026-11-03T19:00:15+00:00, book20_bid_proxy_usdt=86403, book20_ask_proxy_usdt=81594, funding_indicative=0.000100, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.75%, turnover=54661719. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-03T19:00:01+00:00, last15m_closed_end=2026-11-03T19:00+00:00, prior8high=0.437100, depth_time=2026-11-03T19:00:12+00:00, book20_bid_proxy_usdt=398540, book20_ask_proxy_usdt=362578, funding_indicative=-0.000029, next_funding_utc=2026-11-03T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.04%, turnover=11782755. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-03T19:00:01+00:00, last15m_closed_end=2026-11-03T19:00+00:00, prior8high=1.599000, depth_time=2026-11-03T19:00:16+00:00, book20_bid_proxy_usdt=2175997, book20_ask_proxy_usdt=2157685, funding_indicative=0.000037, next_funding_utc=2026-11-03T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.68%, turnover=6110390. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-03T19:00:01+00:00, last15m_closed_end=2026-11-03T19:00+00:00, prior8high=0.064200, depth_time=2026-11-03T19:00:19+00:00, book20_bid_proxy_usdt=342260, book20_ask_proxy_usdt=446044, funding_indicative=0.000050, next_funding_utc=2026-11-03T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.13%, turnover=9613888. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
