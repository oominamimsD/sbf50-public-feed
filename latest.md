# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T22:30:17Z**
- feed_generated_utc: 2026-10-18T22:30:19+00:00
- source_sha256: `3ea37eec1b130a1cc99782259f93eed8b8a7131be58c1cb0e7319d761e62697d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T22:30+00:00, close=81535.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-18T22:00+00:00, close=81181.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-18T20:00+00:00, close=80844.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.062389|-7.61|252.77|-8.11|10130932|0.96|
|STRK_USDT|0.059650|-3.10|-49.98|-3.60|15848453|1.68|
|TIA_USDT|0.601600|-2.63|2.19|-3.13|52038766|4.99|
|SAND_USDT|0.057550|-2.05|-13.38|-2.55|34414676|1.74|
|BAT_USDT|0.172380|-1.71|3.44|-2.21|7293342|0.58|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.062389|0.061280|0.062377|0.62|N|Y/Y|N/N|Y|N|
|BAT_USDT|0.172380|0.167530|0.172570|0.48|N|Y/Y|Y/Y|Y|N|
|SAND_USDT|0.057550|0.056220|0.057530|2.92|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.059650|0.058420|0.059650|2.05|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.601600|0.586400|0.601500|1.30|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-18T22:30:02+00:00, last15m_closed_end=2026-10-18T22:30+00:00, prior8high=0.066887, depth_time=2026-10-18T22:30:06+00:00, book20_bid_proxy_usdt=3040, book20_ask_proxy_usdt=2738, funding_indicative=0.000265, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=4, 24h_change=-7.61%, turnover=10130932. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-18T22:30:02+00:00, last15m_closed_end=2026-10-18T22:30+00:00, prior8high=0.177130, depth_time=2026-10-18T22:30:16+00:00, book20_bid_proxy_usdt=27286, book20_ask_proxy_usdt=24150, funding_indicative=0.000073, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.71%, turnover=7293342. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-18T22:30:02+00:00, last15m_closed_end=2026-10-18T22:30+00:00, prior8high=0.058220, depth_time=2026-10-18T22:30:13+00:00, book20_bid_proxy_usdt=721063, book20_ask_proxy_usdt=640750, funding_indicative=-0.002318, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.05%, turnover=34414676. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T22:30:02+00:00, last15m_closed_end=2026-10-18T22:30+00:00, prior8high=0.061020, depth_time=2026-10-18T22:30:09+00:00, book20_bid_proxy_usdt=530269, book20_ask_proxy_usdt=336535, funding_indicative=0.000050, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.10%, turnover=15848453. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-18T22:30:02+00:00, last15m_closed_end=2026-10-18T22:30+00:00, prior8high=0.605800, depth_time=2026-10-18T22:30:11+00:00, book20_bid_proxy_usdt=189125, book20_ask_proxy_usdt=293370, funding_indicative=0.000038, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.63%, turnover=52038766. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
