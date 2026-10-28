# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T20:15:14Z**
- feed_generated_utc: 2026-10-28T20:15:17+00:00
- source_sha256: `4df5d267c52a1e77ff2dd550109a1ab9fb2a8efe717448b9cf95315f5f9a4c3b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T20:15+00:00, close=81244.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-28T20:00+00:00, close=81544.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T20:00+00:00, close=81544.7, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AIN_USDT|0.136250|-9.52|240.19|-10.40|7406908|5.86|
|BCH_USDT|288.670000|-1.45|-0.34|-2.33|5683058|3.46|
|XMR_USDT|601.440000|-0.44|0.87|-1.32|5326177|0.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AIN_USDT|0.136250|0.138880|0.136260|1.48|Y|Y/Y|N/N|N|N|
|BCH_USDT|288.670000|282.710000|288.890000|3.69|N|Y/Y|N/N|N|N|
|XMR_USDT|601.440000|598.000000|601.560000|0.56|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AIN_USDT: quote_utc=2026-10-28T20:15:02+00:00, last15m_closed_end=2026-10-28T20:15+00:00, prior8high=0.145810, depth_time=2026-10-28T20:15:08+00:00, book20_bid_proxy_usdt=13412, book20_ask_proxy_usdt=20284, funding_indicative=0.000848, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=4, 24h_change=-9.52%, turnover=7406908. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BCH_USDT: quote_utc=2026-10-28T20:15:02+00:00, last15m_closed_end=2026-10-28T20:15+00:00, prior8high=288.970000, depth_time=2026-10-28T20:15:10+00:00, book20_bid_proxy_usdt=54034, book20_ask_proxy_usdt=84588, funding_indicative=0.000027, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.45%, turnover=5683058. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-28T20:15:02+00:00, last15m_closed_end=2026-10-28T20:15+00:00, prior8high=604.050000, depth_time=2026-10-28T20:15:12+00:00, book20_bid_proxy_usdt=5970, book20_ask_proxy_usdt=18098, funding_indicative=0.000100, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.44%, turnover=5326177. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
