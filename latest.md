# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T16:00:21Z**
- feed_generated_utc: 2026-10-27T16:00:25+00:00
- source_sha256: `527c3e7448a8736d267eb8e1a46966eb651dafa4cbfa84be5a9958ddc37b0494`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T16:00+00:00, close=80529.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-27T16:00+00:00, close=80529.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-27T16:00+00:00, close=80529.9, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.024910|-9.68|102.85|-9.84|6451425|4.01|
|QNT_USDT|197.890000|-5.89|1.11|-6.05|92082437|0.51|
|DOT_USDT|0.991000|-3.09|-13.58|-3.25|11527616|1.01|
|AAVE_USDT|132.680000|-2.96|-9.87|-3.12|27159604|0.75|
|APT_USDT|0.687700|-2.03|-9.85|-2.19|5527840|1.46|
|STRK_USDT|0.046120|-0.85|-16.82|-1.01|5465044|2.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|132.680000|130.180000|132.670000|1.06|N|N/Y|Y/Y|N|N|
|APT_USDT|0.687700|0.672700|0.687700|0.46|N|N/Y|Y/Y|N|N|
|DOT_USDT|0.991000|0.977000|0.991000|1.37|N|Y/Y|Y/Y|N|N|
|IRYS_USDT|0.024910|0.024620|0.024910|1.06|N|Y/Y|Y/Y|N|N|
|QNT_USDT|197.890000|196.560000|197.890000|1.11|N|Y/Y|N/N|N|N|
|STRK_USDT|0.046120|0.045820|0.046120|0.84|N|N/N|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T15:59:59+00:00, last15m_closed_end=2026-10-27T16:00+00:00, prior8high=132.750000, depth_time=2026-10-27T16:00:15+00:00, book20_bid_proxy_usdt=367560, book20_ask_proxy_usdt=322956, funding_indicative=0.000100, next_funding_utc=2026-10-28T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.96%, turnover=27159604. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-27T15:59:59+00:00, last15m_closed_end=2026-10-27T16:00+00:00, prior8high=0.690400, depth_time=2026-10-27T16:00:17+00:00, book20_bid_proxy_usdt=117965, book20_ask_proxy_usdt=113107, funding_indicative=-0.000017, next_funding_utc=2026-10-28T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.03%, turnover=5527840. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T15:59:59+00:00, last15m_closed_end=2026-10-27T16:00+00:00, prior8high=0.997900, depth_time=2026-10-27T16:00:13+00:00, book20_bid_proxy_usdt=340886, book20_ask_proxy_usdt=547984, funding_indicative=-0.000104, next_funding_utc=2026-10-28T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.09%, turnover=11527616. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-27T15:59:59+00:00, last15m_closed_end=2026-10-27T16:00+00:00, prior8high=0.025580, depth_time=2026-10-27T16:00:08+00:00, book20_bid_proxy_usdt=93398, book20_ask_proxy_usdt=112803, funding_indicative=-0.000749, next_funding_utc=2026-10-27T17:00:00+00:00, funding_cycle_h=1, 24h_change=-9.68%, turnover=6451425. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-27T15:59:59+00:00, last15m_closed_end=2026-10-27T16:00+00:00, prior8high=200.970000, depth_time=2026-10-27T16:00:10+00:00, book20_bid_proxy_usdt=93146, book20_ask_proxy_usdt=47692, funding_indicative=-0.000218, next_funding_utc=2026-10-28T00:00:00+00:00, funding_cycle_h=8, 24h_change=-5.89%, turnover=92082437. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-27T16:00:00+00:00, last15m_closed_end=2026-10-27T16:00+00:00, prior8high=0.047280, depth_time=2026-10-27T16:00:21+00:00, book20_bid_proxy_usdt=1149263, book20_ask_proxy_usdt=1182237, funding_indicative=0.000001, next_funding_utc=2026-10-27T20:00:00+00:00, funding_cycle_h=4, 24h_change=-0.85%, turnover=5465044. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
