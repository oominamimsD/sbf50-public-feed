# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-03T18:00:16Z**
- feed_generated_utc: 2026-11-03T18:00:17+00:00
- source_sha256: `bbd627f2ebff09c7083e5ffeb9ff91d8fca27263dcd18932a6e7191f6631798c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-03T18:00+00:00, close=77626.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-03T18:00+00:00, close=77626.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-03T16:00+00:00, close=77664.3, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.003933|-5.36|-81.38|-5.32|12420890|5.08|
|BEAT_USDT|0.091660|-3.31|0.62|-3.27|8763954|3.27|
|TIA_USDT|0.429900|-2.27|-19.80|-2.23|12213579|2.33|
|TRUMPOFFICIAL_USDT|1.581000|-1.55|-6.33|-1.51|6442507|6.32|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.003933|0.003956|0.003929|1.67|Y|Y/Y|Y/Y|N|Y|
|BEAT_USDT|0.091660|0.089460|0.091700|0.13|N|Y/Y|Y/N|N|N|
|TIA_USDT|0.429900|0.430000|0.430000|0.74|N|Y/Y|Y/Y|N|N|
|TRUMPOFFICIAL_USDT|1.581000|1.580000|1.581000|0.70|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-03T18:00:02+00:00, last15m_closed_end=2026-11-03T18:00+00:00, prior8high=0.004206, depth_time=2026-11-03T18:00:08+00:00, book20_bid_proxy_usdt=37410, book20_ask_proxy_usdt=48247, funding_indicative=-0.000786, next_funding_utc=2026-11-03T20:00:00+00:00, funding_cycle_h=4, 24h_change=-5.36%, turnover=12420890. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-11-03T18:00:02+00:00, last15m_closed_end=2026-11-03T18:00+00:00, prior8high=0.095420, depth_time=2026-11-03T18:00:10+00:00, book20_bid_proxy_usdt=20557, book20_ask_proxy_usdt=20334, funding_indicative=0.000232, next_funding_utc=2026-11-03T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.31%, turnover=8763954. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-03T18:00:02+00:00, last15m_closed_end=2026-11-03T18:00+00:00, prior8high=0.437300, depth_time=2026-11-03T18:00:13+00:00, book20_bid_proxy_usdt=434704, book20_ask_proxy_usdt=340140, funding_indicative=-0.000010, next_funding_utc=2026-11-03T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.27%, turnover=12213579. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-03T18:00:02+00:00, last15m_closed_end=2026-11-03T18:00+00:00, prior8high=1.613000, depth_time=2026-11-03T18:00:15+00:00, book20_bid_proxy_usdt=1782969, book20_ask_proxy_usdt=2025471, funding_indicative=0.000027, next_funding_utc=2026-11-03T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.55%, turnover=6442507. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
