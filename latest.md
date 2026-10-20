# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T03:30:19Z**
- feed_generated_utc: 2026-10-20T03:30:21+00:00
- source_sha256: `ce29357ef47f29fa216a76a7c316c435f55452720ab4d9e3db25eda8b47bec46`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T03:30+00:00, close=81846.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-20T03:00+00:00, close=81763.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T00:00+00:00, close=81903.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.123087|-2.29|299.74|-2.21|14202886|0.73|
|ZRO_USDT|1.860500|-2.18|-17.71|-2.10|7619487|1.07|
|NEAR_USDT|4.814000|-1.83|-13.24|-1.75|167219950|2.08|
|SAND_USDT|0.058280|-1.45|-6.13|-1.37|9041956|1.72|
|PUMPFUN_USDT|0.004399|-1.27|-17.14|-1.19|31937752|2.27|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|NEAR_USDT|4.814000|4.788000|4.814000|0.47|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004399|0.004327|0.004399|0.52|N|N/N|N/N|Y|N|
|Q_USDT|0.123087|0.122974|0.123189|1.12|N|Y/Y|N/N|Y|N|
|SAND_USDT|0.058280|0.057140|0.058280|0.13|N|Y/Y|N/Y|Y|N|
|ZRO_USDT|1.860500|1.836000|1.860500|0.44|N|Y/Y|N/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- NEAR_USDT: quote_utc=2026-10-20T03:30:00+00:00, last15m_closed_end=2026-10-20T03:30+00:00, prior8high=4.885000, depth_time=2026-10-20T03:30:13+00:00, book20_bid_proxy_usdt=3722130, book20_ask_proxy_usdt=3630583, funding_indicative=0.000059, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.83%, turnover=167219950. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-20T03:30:00+00:00, last15m_closed_end=2026-10-20T03:30+00:00, prior8high=0.004470, depth_time=2026-10-20T03:30:18+00:00, book20_bid_proxy_usdt=1199836, book20_ask_proxy_usdt=1463294, funding_indicative=0.000050, next_funding_utc=2026-10-20T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.27%, turnover=31937752. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-20T03:30:00+00:00, last15m_closed_end=2026-10-20T03:30+00:00, prior8high=0.128625, depth_time=2026-10-20T03:30:06+00:00, book20_bid_proxy_usdt=18354, book20_ask_proxy_usdt=23800, funding_indicative=-0.000189, next_funding_utc=2026-10-20T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.29%, turnover=14202886. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-20T03:30:00+00:00, last15m_closed_end=2026-10-20T03:30+00:00, prior8high=0.058600, depth_time=2026-10-20T03:30:15+00:00, book20_bid_proxy_usdt=647550, book20_ask_proxy_usdt=917393, funding_indicative=-0.002148, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.45%, turnover=9041956. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-20T03:30:00+00:00, last15m_closed_end=2026-10-20T03:30+00:00, prior8high=1.883500, depth_time=2026-10-20T03:30:10+00:00, book20_bid_proxy_usdt=59158, book20_ask_proxy_usdt=34908, funding_indicative=0.000050, next_funding_utc=2026-10-20T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.18%, turnover=7619487. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
