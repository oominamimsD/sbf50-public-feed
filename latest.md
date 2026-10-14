# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T03:30:16Z**
- feed_generated_utc: 2026-10-14T03:30:18+00:00
- source_sha256: `b43adb1b832896cc4de87903928604f56c1b32e9d6516923f344f63a72aac862`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T03:30+00:00, close=83738.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-14T03:00+00:00, close=83609.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-14T00:00+00:00, close=83125.7, belowEMA20=True, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.083780|-3.62|60.52|-4.03|30162639|1.19|
|OGN_USDT|0.034080|-3.18|52.07|-3.59|5031663|5.87|
|MAGIC_USDT|0.115000|-3.07|68.81|-3.48|6051984|7.83|
|W_USDT|0.016339|-2.76|12.58|-3.17|7224506|1.83|
|TIA_USDT|0.573200|-0.71|20.34|-1.12|47208740|1.75|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|MAGIC_USDT|0.115000|0.115000|0.115060|0.39|N|Y/Y|N/N|N|N|
|OGN_USDT|0.034080|0.033730|0.034080|0.47|N|Y/Y|Y/N|N|N|
|STRK_USDT|0.083780|0.083660|0.083780|1.14|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.573200|0.566300|0.573200|6.38|N|Y/Y|N/N|N|N|
|W_USDT|0.016339|0.016370|0.016339|1.16|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- MAGIC_USDT: quote_utc=2026-10-14T03:30:00+00:00, last15m_closed_end=2026-10-14T03:30+00:00, prior8high=0.121200, depth_time=2026-10-14T03:30:11+00:00, book20_bid_proxy_usdt=184730, book20_ask_proxy_usdt=187868, funding_indicative=-0.000157, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.07%, turnover=6051984. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OGN_USDT: quote_utc=2026-10-14T03:30:00+00:00, last15m_closed_end=2026-10-14T03:30+00:00, prior8high=0.034740, depth_time=2026-10-14T03:30:08+00:00, book20_bid_proxy_usdt=162619, book20_ask_proxy_usdt=145843, funding_indicative=-0.000290, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.18%, turnover=5031663. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T03:30:00+00:00, last15m_closed_end=2026-10-14T03:30+00:00, prior8high=0.086310, depth_time=2026-10-14T03:30:06+00:00, book20_bid_proxy_usdt=177090, book20_ask_proxy_usdt=172999, funding_indicative=0.000020, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.62%, turnover=30162639. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-14T03:30:00+00:00, last15m_closed_end=2026-10-14T03:30+00:00, prior8high=0.580000, depth_time=2026-10-14T03:30:15+00:00, book20_bid_proxy_usdt=97723, book20_ask_proxy_usdt=153089, funding_indicative=0.000022, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.71%, turnover=47208740. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-14T03:30:00+00:00, last15m_closed_end=2026-10-14T03:30+00:00, prior8high=0.017059, depth_time=2026-10-14T03:30:13+00:00, book20_bid_proxy_usdt=37571, book20_ask_proxy_usdt=57986, funding_indicative=-0.000255, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.76%, turnover=7224506. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
