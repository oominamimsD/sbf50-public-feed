# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T17:30:18Z**
- feed_generated_utc: 2026-10-18T17:30:20+00:00
- source_sha256: `3251f3542942969b016cb898237ffd0d87bc7ac52f4d1ab3ecdd836eeed4e6b4`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T17:30+00:00, close=81131.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-18T17:00+00:00, close=81040.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-18T16:00+00:00, close=81137.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.060160|-2.27|-49.55|-2.27|14845354|1.66|
|BAT_USDT|0.171440|-2.24|2.88|-2.24|10013538|0.58|
|PUMPFUN_USDT|0.004115|-1.90|-28.74|-1.90|29768652|2.43|
|BTW_USDT|2.272200|-1.44|35.07|-1.44|27442499|0.44|
|TIA_USDT|0.609300|-1.39|3.49|-1.39|55217590|4.92|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BAT_USDT|0.171440|0.171600|0.171440|0.33|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|2.272200|2.184900|2.273300|0.82|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004115|0.004108|0.004115|2.58|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.060160|0.060160|0.060150|1.21|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.609300|0.606500|0.608900|1.45|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BAT_USDT: quote_utc=2026-10-18T17:30:01+00:00, last15m_closed_end=2026-10-18T17:30+00:00, prior8high=0.178800, depth_time=2026-10-18T17:30:10+00:00, book20_bid_proxy_usdt=20063, book20_ask_proxy_usdt=27708, funding_indicative=-0.000010, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.24%, turnover=10013538. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-18T17:30:01+00:00, last15m_closed_end=2026-10-18T17:30+00:00, prior8high=2.405100, depth_time=2026-10-18T17:30:15+00:00, book20_bid_proxy_usdt=5896, book20_ask_proxy_usdt=16115, funding_indicative=-0.000488, next_funding_utc=2026-10-18T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.44%, turnover=27442499. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T17:30:01+00:00, last15m_closed_end=2026-10-18T17:30+00:00, prior8high=0.004220, depth_time=2026-10-18T17:30:12+00:00, book20_bid_proxy_usdt=2768308, book20_ask_proxy_usdt=1670228, funding_indicative=0.000050, next_funding_utc=2026-10-18T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.90%, turnover=29768652. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T17:30:01+00:00, last15m_closed_end=2026-10-18T17:30+00:00, prior8high=0.062250, depth_time=2026-10-18T17:30:07+00:00, book20_bid_proxy_usdt=528848, book20_ask_proxy_usdt=359262, funding_indicative=0.000050, next_funding_utc=2026-10-18T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.27%, turnover=14845354. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-18T17:30:01+00:00, last15m_closed_end=2026-10-18T17:30+00:00, prior8high=0.625200, depth_time=2026-10-18T17:30:17+00:00, book20_bid_proxy_usdt=174672, book20_ask_proxy_usdt=248144, funding_indicative=-0.000020, next_funding_utc=2026-10-18T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.39%, turnover=55217590. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
