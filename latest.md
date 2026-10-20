# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T03:15:16Z**
- feed_generated_utc: 2026-10-20T03:15:18+00:00
- source_sha256: `0357bdc31bf02022f682e1d078282491f2335adff0ae4fa2416f02cadff99e5f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T03:15+00:00, close=81875.1, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-20T03:00+00:00, close=81763.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T00:00+00:00, close=81903.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.123012|-2.35|299.50|-2.31|14172587|0.81|
|ZRO_USDT|1.861800|-2.11|-17.65|-2.07|7604924|0.54|
|NEAR_USDT|4.818000|-1.75|-13.17|-1.71|166567489|2.07|
|SAND_USDT|0.058380|-1.28|-5.97|-1.24|9033640|1.71|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|NEAR_USDT|4.818000|4.785000|4.818000|0.54|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.123012|0.123924|0.123012|0.97|N|Y/Y|N/N|Y|N|
|SAND_USDT|0.058380|0.057130|0.058380|0.45|N|Y/Y|N/Y|Y|N|
|ZRO_USDT|1.861800|1.833600|1.861800|0.23|N|Y/Y|N/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- NEAR_USDT: quote_utc=2026-10-20T03:15:02+00:00, last15m_closed_end=2026-10-20T03:15+00:00, prior8high=4.885000, depth_time=2026-10-20T03:15:13+00:00, book20_bid_proxy_usdt=3247644, book20_ask_proxy_usdt=2889154, funding_indicative=0.000064, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.75%, turnover=166567489. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-20T03:15:02+00:00, last15m_closed_end=2026-10-20T03:15+00:00, prior8high=0.128625, depth_time=2026-10-20T03:15:07+00:00, book20_bid_proxy_usdt=18148, book20_ask_proxy_usdt=15130, funding_indicative=-0.000174, next_funding_utc=2026-10-20T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.35%, turnover=14172587. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-20T03:15:02+00:00, last15m_closed_end=2026-10-20T03:15+00:00, prior8high=0.058560, depth_time=2026-10-20T03:15:15+00:00, book20_bid_proxy_usdt=693060, book20_ask_proxy_usdt=603736, funding_indicative=-0.002161, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.28%, turnover=9033640. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-20T03:15:02+00:00, last15m_closed_end=2026-10-20T03:15+00:00, prior8high=1.883500, depth_time=2026-10-20T03:15:10+00:00, book20_bid_proxy_usdt=56714, book20_ask_proxy_usdt=40651, funding_indicative=0.000050, next_funding_utc=2026-10-20T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.11%, turnover=7604924. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
