# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T01:00:15Z**
- feed_generated_utc: 2026-10-14T01:00:17+00:00
- source_sha256: `acc45eec4c525637cf4e606019e9c140eaf72d787beb88ab3bd8bb309964f0e5`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T01:00+00:00, close=83370.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-14T01:00+00:00, close=83370.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-14T00:00+00:00, close=83125.7, belowEMA20=True, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|W_USDT|0.016991|-5.45|17.08|-5.43|8193368|1.18|
|CT_USDT|0.361860|-5.00|-2.62|-4.98|5132095|4.42|
|OGN_USDT|0.034670|-3.56|54.70|-3.54|5194914|2.89|
|PYTH_USDT|0.079960|-3.47|2.73|-3.45|5345514|1.25|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|CT_USDT|0.361860|0.356040|0.361770|1.54|N|Y/Y|N/N|N|N|
|OGN_USDT|0.034670|0.034530|0.034670|0.71|N|Y/Y|Y/N|N|N|
|PYTH_USDT|0.079960|0.077650|0.079960|1.78|N|Y/Y|Y/Y|N|N|
|W_USDT|0.016991|0.016675|0.016991|0.70|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- CT_USDT: quote_utc=2026-10-14T01:00:00+00:00, last15m_closed_end=2026-10-14T01:00+00:00, prior8high=0.366370, depth_time=2026-10-14T01:00:07+00:00, book20_bid_proxy_usdt=8527, book20_ask_proxy_usdt=8581, funding_indicative=0.000050, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.00%, turnover=5132095. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OGN_USDT: quote_utc=2026-10-14T01:00:00+00:00, last15m_closed_end=2026-10-14T01:00+00:00, prior8high=0.035070, depth_time=2026-10-14T01:00:10+00:00, book20_bid_proxy_usdt=180472, book20_ask_proxy_usdt=164963, funding_indicative=-0.000080, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.56%, turnover=5194914. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PYTH_USDT: quote_utc=2026-10-14T01:00:00+00:00, last15m_closed_end=2026-10-14T01:00+00:00, prior8high=0.080390, depth_time=2026-10-14T01:00:14+00:00, book20_bid_proxy_usdt=217940, book20_ask_proxy_usdt=126123, funding_indicative=-0.000015, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.47%, turnover=5345514. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-14T01:00:00+00:00, last15m_closed_end=2026-10-14T01:00+00:00, prior8high=0.017305, depth_time=2026-10-14T01:00:07+00:00, book20_bid_proxy_usdt=23010, book20_ask_proxy_usdt=20892, funding_indicative=-0.000485, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.45%, turnover=8193368. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
