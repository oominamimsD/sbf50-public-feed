# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T17:30:15Z**
- feed_generated_utc: 2026-10-14T17:30:17+00:00
- source_sha256: `3ee44b931e4f27842848bb3b9046874cc884512eff0862b7a89733733cf7ac61`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T17:30+00:00, close=81851.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T17:00+00:00, close=81967.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-14T16:00+00:00, close=81600.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|2.194100|-7.76|77.47|-8.06|57293989|3.19|
|S_USDT|0.052590|-4.01|32.00|-4.31|8162687|3.80|
|STRK_USDT|0.075560|-2.09|52.76|-2.39|25288012|1.32|
|BAT_USDT|0.171550|-1.64|73.00|-1.94|37974061|0.58|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BAT_USDT|0.171550|0.172360|0.171550|0.57|N|Y/Y|N/N|Y|N|
|BTW_USDT|2.194100|2.162500|2.189200|0.97|N|Y/Y|N/N|Y|N|
|STRK_USDT|0.075560|0.076280|0.075560|1.66|Y|Y/Y|Y/Y|Y|Y|
|S_USDT|0.052590|0.053370|0.052590|1.75|Y|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BAT_USDT: quote_utc=2026-10-14T17:30:01+00:00, last15m_closed_end=2026-10-14T17:30+00:00, prior8high=0.179690, depth_time=2026-10-14T17:30:14+00:00, book20_bid_proxy_usdt=32826, book20_ask_proxy_usdt=31467, funding_indicative=0.000014, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.64%, turnover=37974061. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-14T17:30:01+00:00, last15m_closed_end=2026-10-14T17:30+00:00, prior8high=2.425200, depth_time=2026-10-14T17:30:08+00:00, book20_bid_proxy_usdt=9435, book20_ask_proxy_usdt=7468, funding_indicative=-0.000012, next_funding_utc=2026-10-14T20:00:00+00:00, funding_cycle_h=4, 24h_change=-7.76%, turnover=57293989. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T17:30:01+00:00, last15m_closed_end=2026-10-14T17:30+00:00, prior8high=0.079670, depth_time=2026-10-14T17:30:12+00:00, book20_bid_proxy_usdt=147970, book20_ask_proxy_usdt=267547, funding_indicative=0.000039, next_funding_utc=2026-10-14T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.09%, turnover=25288012. target_RR/account_short_permission/settled_funding=UNKNOWN.
- S_USDT: quote_utc=2026-10-14T17:30:01+00:00, last15m_closed_end=2026-10-14T17:30+00:00, prior8high=0.055910, depth_time=2026-10-14T17:30:10+00:00, book20_bid_proxy_usdt=108223, book20_ask_proxy_usdt=123598, funding_indicative=-0.000032, next_funding_utc=2026-10-14T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.01%, turnover=8162687. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
