# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T23:00:21Z**
- feed_generated_utc: 2026-10-13T23:00:23+00:00
- source_sha256: `b94caff3912990b686b7815d286b480eb939bda277222e01e629b415f522d674`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T23:00+00:00, close=83483.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-13T23:00+00:00, close=83483.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-13T20:00+00:00, close=83253, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|S_USDT|0.057180|-19.00|30.84|-19.00|24068172|1.75|
|1000RATS_USDT|0.017010|-11.31|-57.65|-11.31|5004670|5.88|
|PYTH_USDT|0.078200|-5.60|0.47|-5.60|5512373|1.28|
|CT_USDT|0.364720|-4.25|-1.85|-4.25|5434638|6.86|
|W_USDT|0.017230|-4.12|18.72|-4.12|8763751|5.80|
|OGN_USDT|0.034960|-2.75|56.00|-2.75|5335510|2.86|
|STRK_USDT|0.084440|-1.14|61.79|-1.14|37486291|1.18|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|1000RATS_USDT|0.017010|0.016630|0.017010|1.45|N|Y/Y|Y/Y|N|N|
|CT_USDT|0.364720|0.357960|0.364720|0.21|N|N/Y|N/N|N|N|
|OGN_USDT|0.034960|0.034650|0.034960|0.40|N|Y/Y|N/N|N|N|
|PYTH_USDT|0.078200|0.077550|0.078200|0.80|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.084440|0.082530|0.084440|1.26|N|Y/Y|Y/Y|N|N|
|S_USDT|0.057180|0.055920|0.057180|0.32|N|Y/Y|N/N|N|N|
|W_USDT|0.017230|0.017021|0.017230|0.36|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- 1000RATS_USDT: quote_utc=2026-10-13T23:00:00+00:00, last15m_closed_end=2026-10-13T23:00+00:00, prior8high=0.017890, depth_time=2026-10-13T23:00:07+00:00, book20_bid_proxy_usdt=50094, book20_ask_proxy_usdt=60220, funding_indicative=-0.000076, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-11.31%, turnover=5004670. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CT_USDT: quote_utc=2026-10-13T23:00:00+00:00, last15m_closed_end=2026-10-13T23:00+00:00, prior8high=0.367810, depth_time=2026-10-13T23:00:13+00:00, book20_bid_proxy_usdt=11402, book20_ask_proxy_usdt=11748, funding_indicative=0.000050, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.25%, turnover=5434638. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OGN_USDT: quote_utc=2026-10-13T23:00:00+00:00, last15m_closed_end=2026-10-13T23:00+00:00, prior8high=0.035130, depth_time=2026-10-13T23:00:15+00:00, book20_bid_proxy_usdt=192304, book20_ask_proxy_usdt=128255, funding_indicative=-0.000081, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.75%, turnover=5335510. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PYTH_USDT: quote_utc=2026-10-13T23:00:00+00:00, last15m_closed_end=2026-10-13T23:00+00:00, prior8high=0.078780, depth_time=2026-10-13T23:00:07+00:00, book20_bid_proxy_usdt=114062, book20_ask_proxy_usdt=231404, funding_indicative=0.000011, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-5.60%, turnover=5512373. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-13T23:00:00+00:00, last15m_closed_end=2026-10-13T23:00+00:00, prior8high=0.085530, depth_time=2026-10-13T23:00:19+00:00, book20_bid_proxy_usdt=242062, book20_ask_proxy_usdt=324473, funding_indicative=0.000003, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.14%, turnover=37486291. target_RR/account_short_permission/settled_funding=UNKNOWN.
- S_USDT: quote_utc=2026-10-13T23:00:00+00:00, last15m_closed_end=2026-10-13T23:00+00:00, prior8high=0.057700, depth_time=2026-10-13T23:00:07+00:00, book20_bid_proxy_usdt=146447, book20_ask_proxy_usdt=111826, funding_indicative=-0.000041, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-19.00%, turnover=24068172. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-13T23:00:00+00:00, last15m_closed_end=2026-10-13T23:00+00:00, prior8high=0.017719, depth_time=2026-10-13T23:00:15+00:00, book20_bid_proxy_usdt=28443, book20_ask_proxy_usdt=14008, funding_indicative=-0.000455, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.12%, turnover=8763751. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
