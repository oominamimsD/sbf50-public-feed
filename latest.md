# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-03T17:30:16Z**
- feed_generated_utc: 2026-11-03T17:30:17+00:00
- source_sha256: `d4982aede69d07ea26af891e5a7ff4a90076f48337905e726b2d5ec02e611150`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-03T17:30+00:00, close=77660.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-03T17:00+00:00, close=77713.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-03T16:00+00:00, close=77664.3, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BEAT_USDT|0.091140|-3.86|0.05|-3.86|8868758|1.10|
|AKE_USDT|0.004076|-1.92|-80.70|-1.92|12248102|2.45|
|TRUMPOFFICIAL_USDT|1.590000|-1.11|-5.80|-1.11|7157803|6.29|
|WLD_USDT|0.368300|-1.02|-15.52|-1.02|47091745|2.71|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004076|0.003956|0.004076|0.65|N|Y/Y|Y/Y|N|N|
|BEAT_USDT|0.091140|0.089460|0.091130|0.37|N|Y/Y|Y/N|N|N|
|TRUMPOFFICIAL_USDT|1.590000|1.584000|1.590000|0.71|N|Y/N|Y/Y|N|N|
|WLD_USDT|0.368300|0.366300|0.368300|0.55|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-03T17:30:00+00:00, last15m_closed_end=2026-11-03T17:30+00:00, prior8high=0.004218, depth_time=2026-11-03T17:30:09+00:00, book20_bid_proxy_usdt=39347, book20_ask_proxy_usdt=29555, funding_indicative=-0.000545, next_funding_utc=2026-11-03T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.92%, turnover=12248102. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-11-03T17:30:00+00:00, last15m_closed_end=2026-11-03T17:30+00:00, prior8high=0.095770, depth_time=2026-11-03T17:30:08+00:00, book20_bid_proxy_usdt=23220, book20_ask_proxy_usdt=23564, funding_indicative=0.000271, next_funding_utc=2026-11-03T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.86%, turnover=8868758. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-03T17:30:00+00:00, last15m_closed_end=2026-11-03T17:30+00:00, prior8high=1.613000, depth_time=2026-11-03T17:30:11+00:00, book20_bid_proxy_usdt=2203868, book20_ask_proxy_usdt=1833132, funding_indicative=0.000020, next_funding_utc=2026-11-03T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.11%, turnover=7157803. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-03T17:30:00+00:00, last15m_closed_end=2026-11-03T17:30+00:00, prior8high=0.372800, depth_time=2026-11-03T17:30:13+00:00, book20_bid_proxy_usdt=4047527, book20_ask_proxy_usdt=3440383, funding_indicative=0.000090, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.02%, turnover=47091745. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
