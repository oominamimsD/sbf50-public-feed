# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T20:45:14Z**
- feed_generated_utc: 2026-10-28T20:45:17+00:00
- source_sha256: `2848dea03dc948bf630038dae95009195bd5042d586163f0132607cb44c9e9a1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T20:45+00:00, close=81065.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-28T20:00+00:00, close=81544.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T20:00+00:00, close=81544.7, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BCH_USDT|289.370000|-1.21|-0.10|-1.88|5815373|1.38|
|XMR_USDT|596.820000|-1.20|0.09|-1.87|5428605|1.17|
|HBAR_USDT|0.075470|-0.57|-12.18|-1.24|12900404|1.32|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BCH_USDT|289.370000|283.370000|289.300000|0.78|N|Y/Y|N/N|N|N|
|HBAR_USDT|0.075470|0.074690|0.075470|0.69|N|N/Y|Y/Y|N|N|
|XMR_USDT|596.820000|598.000000|596.820000|1.26|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BCH_USDT: quote_utc=2026-10-28T20:45:03+00:00, last15m_closed_end=2026-10-28T20:45+00:00, prior8high=292.510000, depth_time=2026-10-28T20:45:08+00:00, book20_bid_proxy_usdt=50679, book20_ask_proxy_usdt=95996, funding_indicative=0.000029, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.21%, turnover=5815373. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-28T20:45:03+00:00, last15m_closed_end=2026-10-28T20:45+00:00, prior8high=0.076980, depth_time=2026-10-28T20:45:13+00:00, book20_bid_proxy_usdt=547120, book20_ask_proxy_usdt=894759, funding_indicative=0.000100, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.57%, turnover=12900404. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-28T20:45:03+00:00, last15m_closed_end=2026-10-28T20:45+00:00, prior8high=604.680000, depth_time=2026-10-28T20:45:10+00:00, book20_bid_proxy_usdt=12152, book20_ask_proxy_usdt=26486, funding_indicative=0.000100, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.20%, turnover=5428605. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
