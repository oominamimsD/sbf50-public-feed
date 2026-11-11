# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T06:15:22Z**
- feed_generated_utc: 2026-11-11T06:15:24+00:00
- source_sha256: `7af2c514f5539015d886b817a2ef6a55a6091ba27035052f30500da039664a20`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T06:15+00:00, close=73823.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-11T06:00+00:00, close=73895.6, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-11-11T04:00+00:00, close=73740.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZEC_USDT|1006.690000|-7.92|-16.37|-8.78|2154048842|0.10|
|UNI_USDT|6.613000|-3.17|-10.06|-4.03|36469578|1.51|
|VVV_USDT|19.045000|-1.00|-14.82|-1.86|5331856|0.53|
|ARB_USDT|0.160250|-0.70|0.23|-1.56|31464164|1.25|
|QNT_USDT|179.730000|-0.53|-8.02|-1.39|45511560|0.56|
|DOT_USDT|0.839800|-0.22|-10.90|-1.08|8025374|1.19|
|HBAR_USDT|0.065660|-0.18|-6.24|-1.04|5673589|1.52|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.160250|0.162080|0.160280|1.74|Y|Y/Y|Y/Y|Y|Y|
|DOT_USDT|0.839800|0.841400|0.839800|1.87|Y|Y/Y|Y/Y|Y|Y|
|HBAR_USDT|0.065660|0.065430|0.065660|0.82|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|179.730000|179.480000|179.730000|0.90|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.613000|6.629000|6.618000|0.76|N|Y/Y|Y/Y|Y|N|
|VVV_USDT|19.045000|19.006000|19.045000|0.77|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1006.690000|1002.510000|1007.310000|1.15|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-11-11T06:15:01+00:00, last15m_closed_end=2026-11-11T06:15+00:00, prior8high=0.165060, depth_time=2026-11-11T06:15:14+00:00, book20_bid_proxy_usdt=39845, book20_ask_proxy_usdt=110852, funding_indicative=-0.000048, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.70%, turnover=31464164. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-11T06:15:01+00:00, last15m_closed_end=2026-11-11T06:15+00:00, prior8high=0.849100, depth_time=2026-11-11T06:15:15+00:00, book20_bid_proxy_usdt=691703, book20_ask_proxy_usdt=517698, funding_indicative=0.000035, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.22%, turnover=8025374. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-11-11T06:15:01+00:00, last15m_closed_end=2026-11-11T06:15+00:00, prior8high=0.066120, depth_time=2026-11-11T06:15:21+00:00, book20_bid_proxy_usdt=716224, book20_ask_proxy_usdt=656593, funding_indicative=-0.000013, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.18%, turnover=5673589. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-11T06:15:01+00:00, last15m_closed_end=2026-11-11T06:15+00:00, prior8high=181.590000, depth_time=2026-11-11T06:15:16+00:00, book20_bid_proxy_usdt=97838, book20_ask_proxy_usdt=57853, funding_indicative=-0.000109, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.53%, turnover=45511560. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T06:15:01+00:00, last15m_closed_end=2026-11-11T06:15+00:00, prior8high=6.722000, depth_time=2026-11-11T06:15:09+00:00, book20_bid_proxy_usdt=2440320, book20_ask_proxy_usdt=1714788, funding_indicative=0.000011, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.17%, turnover=36469578. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-11T06:15:01+00:00, last15m_closed_end=2026-11-11T06:15+00:00, prior8high=19.417000, depth_time=2026-11-11T06:15:11+00:00, book20_bid_proxy_usdt=77756, book20_ask_proxy_usdt=17354, funding_indicative=0.000050, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.00%, turnover=5331856. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T06:15:00+00:00, last15m_closed_end=2026-11-11T06:15+00:00, prior8high=1031.080000, depth_time=2026-11-11T06:15:07+00:00, book20_bid_proxy_usdt=271043, book20_ask_proxy_usdt=132497, funding_indicative=0.000083, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-7.92%, turnover=2154048842. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
