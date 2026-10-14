# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T23:15:16Z**
- feed_generated_utc: 2026-10-14T23:15:18+00:00
- source_sha256: `a672e6146b59421101f72e8ec4441c290d03fe503310ce1d623f27138d22fa6d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T23:15+00:00, close=81669.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T23:00+00:00, close=81624.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-14T20:00+00:00, close=81798.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|FET_USDT|0.198400|-2.69|-12.40|-2.76|10722038|5.04|
|S_USDT|0.053800|-1.80|35.04|-1.87|5301394|5.58|
|BAT_USDT|0.171340|-1.76|72.79|-1.83|24973702|4.09|
|AAVE_USDT|154.290000|-1.02|-10.17|-1.09|26278144|0.65|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|154.290000|152.860000|154.290000|0.65|N|Y/Y|Y/Y|Y|N|
|BAT_USDT|0.171340|0.167700|0.171340|0.88|N|Y/Y|Y/N|Y|N|
|FET_USDT|0.198400|0.194800|0.198400|0.58|N|Y/Y|Y/Y|Y|N|
|S_USDT|0.053800|0.052410|0.053790|1.54|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-14T23:15:01+00:00, last15m_closed_end=2026-10-14T23:15+00:00, prior8high=154.420000, depth_time=2026-10-14T23:15:15+00:00, book20_bid_proxy_usdt=284382, book20_ask_proxy_usdt=381423, funding_indicative=0.000080, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.02%, turnover=26278144. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-14T23:15:01+00:00, last15m_closed_end=2026-10-14T23:15+00:00, prior8high=0.170730, depth_time=2026-10-14T23:15:12+00:00, book20_bid_proxy_usdt=39420, book20_ask_proxy_usdt=23409, funding_indicative=0.000045, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.76%, turnover=24973702. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-14T23:15:01+00:00, last15m_closed_end=2026-10-14T23:15+00:00, prior8high=0.198600, depth_time=2026-10-14T23:15:08+00:00, book20_bid_proxy_usdt=980152, book20_ask_proxy_usdt=1436450, funding_indicative=0.000030, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.69%, turnover=10722038. target_RR/account_short_permission/settled_funding=UNKNOWN.
- S_USDT: quote_utc=2026-10-14T23:15:01+00:00, last15m_closed_end=2026-10-14T23:15+00:00, prior8high=0.053480, depth_time=2026-10-14T23:15:09+00:00, book20_bid_proxy_usdt=157146, book20_ask_proxy_usdt=183520, funding_indicative=-0.000078, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.80%, turnover=5301394. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
