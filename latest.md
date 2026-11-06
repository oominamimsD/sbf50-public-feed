# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T05:30:15Z**
- feed_generated_utc: 2026-11-06T05:30:16+00:00
- source_sha256: `381c0204e5ea400b043a8ba2e91e31e26bd78691a4a564e301cd0717ebbba49d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T05:30+00:00, close=75476.8, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-06T05:00+00:00, close=75744, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T04:00+00:00, close=75880.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ELSA_USDT|0.076580|-5.63|2.51|-4.91|6236085|2.61|
|FLUID_USDT|2.430000|-4.02|17.73|-3.30|6431381|4.12|
|XRP_USDT|1.197800|-3.76|-8.52|-3.04|434247106|0.83|
|XPL_USDT|0.057010|-2.68|-27.77|-1.96|12484883|1.75|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ELSA_USDT|0.076580|0.076520|0.076580|0.69|N|Y/Y|Y/N|Y|N|
|FLUID_USDT|2.430000|2.411000|2.430000|0.42|N|Y/Y|N/N|Y|N|
|XPL_USDT|0.057010|0.056370|0.057010|0.28|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.197800|1.195700|1.198000|1.08|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ELSA_USDT: quote_utc=2026-11-06T05:30:02+00:00, last15m_closed_end=2026-11-06T05:30+00:00, prior8high=0.078830, depth_time=2026-11-06T05:30:07+00:00, book20_bid_proxy_usdt=30447, book20_ask_proxy_usdt=53407, funding_indicative=0.000079, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.63%, turnover=6236085. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FLUID_USDT: quote_utc=2026-11-06T05:30:02+00:00, last15m_closed_end=2026-11-06T05:30+00:00, prior8high=2.456000, depth_time=2026-11-06T05:30:09+00:00, book20_bid_proxy_usdt=194408, book20_ask_proxy_usdt=154565, funding_indicative=0.000264, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.02%, turnover=6431381. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-06T05:30:02+00:00, last15m_closed_end=2026-11-06T05:30+00:00, prior8high=0.057590, depth_time=2026-11-06T05:30:13+00:00, book20_bid_proxy_usdt=452204, book20_ask_proxy_usdt=490938, funding_indicative=0.000050, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.68%, turnover=12484883. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-06T05:30:01+00:00, last15m_closed_end=2026-11-06T05:30+00:00, prior8high=1.213200, depth_time=2026-11-06T05:30:11+00:00, book20_bid_proxy_usdt=3720553, book20_ask_proxy_usdt=4721997, funding_indicative=0.000100, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.76%, turnover=434247106. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
