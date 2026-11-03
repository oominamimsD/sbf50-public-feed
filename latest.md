# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-03T17:00:16Z**
- feed_generated_utc: 2026-11-03T17:00:18+00:00
- source_sha256: `9bca94b1fbe7480037b1b321e94ceaf471cb745c89b3b98d4b937928bfac866d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-03T17:00+00:00, close=77713.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-03T17:00+00:00, close=77713.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-03T16:00+00:00, close=77664.3, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BEAT_USDT|0.091090|-8.43|0.00|-8.48|8727404|2.20|
|AKE_USDT|0.004031|-3.00|-80.91|-3.05|12035851|2.48|
|TIA_USDT|0.434800|-1.15|-18.89|-1.20|12773415|2.30|
|WLD_USDT|0.369000|-1.04|-15.36|-1.09|46343614|2.71|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004031|0.003956|0.004029|0.65|N|Y/Y|Y/Y|N|N|
|BEAT_USDT|0.091090|0.089460|0.091090|1.92|N|Y/Y|Y/N|N|N|
|TIA_USDT|0.434800|0.430000|0.434800|0.33|N|Y/Y|Y/Y|N|N|
|WLD_USDT|0.369000|0.366300|0.369000|1.39|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-03T17:00:00+00:00, last15m_closed_end=2026-11-03T17:00+00:00, prior8high=0.004218, depth_time=2026-11-03T17:00:10+00:00, book20_bid_proxy_usdt=35586, book20_ask_proxy_usdt=50970, funding_indicative=-0.000337, next_funding_utc=2026-11-03T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.00%, turnover=12035851. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-11-03T17:00:01+00:00, last15m_closed_end=2026-11-03T17:00+00:00, prior8high=0.099590, depth_time=2026-11-03T17:00:08+00:00, book20_bid_proxy_usdt=20871, book20_ask_proxy_usdt=23449, funding_indicative=0.000321, next_funding_utc=2026-11-03T20:00:00+00:00, funding_cycle_h=4, 24h_change=-8.43%, turnover=8727404. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-03T17:00:01+00:00, last15m_closed_end=2026-11-03T17:00+00:00, prior8high=0.441900, depth_time=2026-11-03T17:00:13+00:00, book20_bid_proxy_usdt=317026, book20_ask_proxy_usdt=400688, funding_indicative=-0.000009, next_funding_utc=2026-11-03T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.15%, turnover=12773415. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-03T17:00:00+00:00, last15m_closed_end=2026-11-03T17:00+00:00, prior8high=0.374900, depth_time=2026-11-03T17:00:15+00:00, book20_bid_proxy_usdt=4483965, book20_ask_proxy_usdt=4411190, funding_indicative=0.000073, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.04%, turnover=46343614. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
