# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T00:15:20Z**
- feed_generated_utc: 2026-11-04T00:15:22+00:00
- source_sha256: `a3fdef7f8b9f093c298db596a39a1e52d9ab404012ddce8dd79e7b99f5058081`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T00:15+00:00, close=77315, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-04T00:00+00:00, close=77441.6, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T00:00+00:00, close=77441.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.003903|-6.08|-81.52|-5.65|13511267|2.56|
|XLM_USDT|0.161600|-1.93|-4.49|-1.50|32106396|1.24|
|XPL_USDT|0.062860|-1.85|-14.84|-1.42|6918287|1.59|
|QNT_USDT|192.060000|-1.71|-2.94|-1.28|58338784|1.04|
|LINK_USDT|10.992000|-1.45|-4.00|-1.02|154375466|0.91|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.003903|0.003903|0.003905|2.70|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|10.992000|11.018000|10.991000|1.85|Y|Y/Y|Y/Y|Y|Y|
|QNT_USDT|192.060000|191.930000|192.060000|0.81|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.161600|0.162210|0.161610|2.03|Y|Y/Y|Y/Y|Y|Y|
|XPL_USDT|0.062860|0.062610|0.062880|0.93|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-04T00:15:03+00:00, last15m_closed_end=2026-11-04T00:15+00:00, prior8high=0.004047, depth_time=2026-11-04T00:15:08+00:00, book20_bid_proxy_usdt=23848, book20_ask_proxy_usdt=42394, funding_indicative=-0.000876, next_funding_utc=2026-11-04T04:00:00+00:00, funding_cycle_h=4, 24h_change=-6.08%, turnover=13511267. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-04T00:15:03+00:00, last15m_closed_end=2026-11-04T00:15+00:00, prior8high=11.155000, depth_time=2026-11-04T00:15:19+00:00, book20_bid_proxy_usdt=464389, book20_ask_proxy_usdt=558701, funding_indicative=0.000100, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.45%, turnover=154375466. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-04T00:15:03+00:00, last15m_closed_end=2026-11-04T00:15+00:00, prior8high=194.210000, depth_time=2026-11-04T00:15:17+00:00, book20_bid_proxy_usdt=63868, book20_ask_proxy_usdt=64968, funding_indicative=0.000017, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.71%, turnover=58338784. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-04T00:15:03+00:00, last15m_closed_end=2026-11-04T00:15+00:00, prior8high=0.164130, depth_time=2026-11-04T00:15:11+00:00, book20_bid_proxy_usdt=152067, book20_ask_proxy_usdt=127982, funding_indicative=0.000100, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.93%, turnover=32106396. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-04T00:15:03+00:00, last15m_closed_end=2026-11-04T00:15+00:00, prior8high=0.064650, depth_time=2026-11-04T00:15:13+00:00, book20_bid_proxy_usdt=403340, book20_ask_proxy_usdt=458834, funding_indicative=0.000050, next_funding_utc=2026-11-04T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.85%, turnover=6918287. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
