# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T01:45:15Z**
- feed_generated_utc: 2026-10-28T01:45:18+00:00
- source_sha256: `f6d5ca78eed0a492652ba3fa8b70f939c9bcb01f8cbeb18b5727bd3fea9fb505`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T01:45+00:00, close=80933, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-28T01:00+00:00, close=80713.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T00:00+00:00, close=80868.4, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.054006|-15.06|-56.00|-15.56|40520669|3.51|
|IRYS_USDT|0.022890|-8.10|75.80|-8.60|5047199|8.75|
|NIL_USDT|0.085990|-7.22|-3.22|-7.72|5851677|8.14|
|SYN_USDT|0.179800|-0.88|-2.06|-1.38|5315419|5.56|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|IRYS_USDT|0.022890|0.022840|0.022890|1.72|N|Y/Y|Y/Y|N|N|
|NIL_USDT|0.085990|0.085040|0.085990|0.71|N|Y/Y|N/N|N|N|
|Q_USDT|0.054006|0.051075|0.054006|1.68|N|Y/Y|Y/Y|N|N|
|SYN_USDT|0.179800|0.177200|0.179800|0.16|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- IRYS_USDT: quote_utc=2026-10-28T01:45:01+00:00, last15m_closed_end=2026-10-28T01:45+00:00, prior8high=0.026530, depth_time=2026-10-28T01:45:10+00:00, book20_bid_proxy_usdt=94368, book20_ask_proxy_usdt=97768, funding_indicative=-0.000554, next_funding_utc=2026-10-28T02:00:00+00:00, funding_cycle_h=1, 24h_change=-8.10%, turnover=5047199. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NIL_USDT: quote_utc=2026-10-28T01:45:01+00:00, last15m_closed_end=2026-10-28T01:45+00:00, prior8high=0.092250, depth_time=2026-10-28T01:45:10+00:00, book20_bid_proxy_usdt=12841, book20_ask_proxy_usdt=12395, funding_indicative=-0.000303, next_funding_utc=2026-10-28T04:00:00+00:00, funding_cycle_h=4, 24h_change=-7.22%, turnover=5851677. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-28T01:45:01+00:00, last15m_closed_end=2026-10-28T01:45+00:00, prior8high=0.054785, depth_time=2026-10-28T01:45:07+00:00, book20_bid_proxy_usdt=27506, book20_ask_proxy_usdt=28361, funding_indicative=-0.000183, next_funding_utc=2026-10-28T04:00:00+00:00, funding_cycle_h=4, 24h_change=-15.06%, turnover=40520669. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SYN_USDT: quote_utc=2026-10-28T01:45:01+00:00, last15m_closed_end=2026-10-28T01:45+00:00, prior8high=0.181600, depth_time=2026-10-28T01:45:14+00:00, book20_bid_proxy_usdt=101686, book20_ask_proxy_usdt=100608, funding_indicative=0.000050, next_funding_utc=2026-10-28T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.88%, turnover=5315419. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
