# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-03T17:45:18Z**
- feed_generated_utc: 2026-11-03T17:45:19+00:00
- source_sha256: `54dd41adf3c600cb74e3b7f7c00c815613cbe86f05a16c5f98b7ea026ec6393e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-03T17:45+00:00, close=77652.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-03T17:00+00:00, close=77713.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-03T16:00+00:00, close=77664.3, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.004003|-3.68|-81.05|-3.67|12386218|2.50|
|BEAT_USDT|0.091510|-3.47|0.46|-3.46|8977575|6.55|
|TRUMPOFFICIAL_USDT|1.583000|-1.55|-6.22|-1.54|7187744|6.32|
|TIA_USDT|0.431000|-1.10|-19.60|-1.09|13223471|2.32|
|NEAR_USDT|3.818000|-1.06|-16.30|-1.05|81571676|2.62|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004003|0.003956|0.004002|1.08|N|Y/Y|Y/Y|N|N|
|BEAT_USDT|0.091510|0.089460|0.091510|0.86|N|Y/Y|Y/N|N|N|
|NEAR_USDT|3.818000|3.799000|3.818000|0.49|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.431000|0.430000|0.431000|0.74|N|Y/Y|Y/Y|N|N|
|TRUMPOFFICIAL_USDT|1.583000|1.584000|1.583000|0.48|N|Y/N|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-03T17:45:01+00:00, last15m_closed_end=2026-11-03T17:45+00:00, prior8high=0.004218, depth_time=2026-11-03T17:45:07+00:00, book20_bid_proxy_usdt=41579, book20_ask_proxy_usdt=50601, funding_indicative=-0.000655, next_funding_utc=2026-11-03T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.68%, turnover=12386218. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-11-03T17:45:01+00:00, last15m_closed_end=2026-11-03T17:45+00:00, prior8high=0.095420, depth_time=2026-11-03T17:45:10+00:00, book20_bid_proxy_usdt=19312, book20_ask_proxy_usdt=15738, funding_indicative=0.000257, next_funding_utc=2026-11-03T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.47%, turnover=8977575. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-03T17:45:01+00:00, last15m_closed_end=2026-11-03T17:45+00:00, prior8high=3.873000, depth_time=2026-11-03T17:45:17+00:00, book20_bid_proxy_usdt=5729762, book20_ask_proxy_usdt=3896930, funding_indicative=0.000100, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.06%, turnover=81571676. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-03T17:45:01+00:00, last15m_closed_end=2026-11-03T17:45+00:00, prior8high=0.437300, depth_time=2026-11-03T17:45:14+00:00, book20_bid_proxy_usdt=391005, book20_ask_proxy_usdt=333638, funding_indicative=-0.000011, next_funding_utc=2026-11-03T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.10%, turnover=13223471. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-03T17:45:01+00:00, last15m_closed_end=2026-11-03T17:45+00:00, prior8high=1.613000, depth_time=2026-11-03T17:45:12+00:00, book20_bid_proxy_usdt=2197518, book20_ask_proxy_usdt=2407055, funding_indicative=0.000023, next_funding_utc=2026-11-03T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.55%, turnover=7187744. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
