# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T02:15:19Z**
- feed_generated_utc: 2026-11-09T02:15:20+00:00
- source_sha256: `2d163ffb27f342654f790a4d3454e879c56152445e87cdc9d7c53bbb96ca8234`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T02:15+00:00, close=75221.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-09T02:00+00:00, close=75130.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T00:00+00:00, close=74823.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001709|-12.73|46.72|-11.65|11266556|0.58|
|HOT_USDT|0.000398|-7.30|10.73|-6.22|6246076|5.03|
|AKE_USDT|0.005049|-5.74|-44.87|-4.66|13015264|3.96|
|XRP_USDT|1.115900|-3.45|-10.72|-2.37|229127324|0.90|
|HYPE_USDT|74.977000|-3.16|-14.49|-2.08|39920809|0.13|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.005049|0.004921|0.005043|0.51|N|Y/Y|N/N|Y|N|
|HOT_USDT|0.000398|0.000395|0.000398|0.25|N|Y/Y|N/N|Y|N|
|HYPE_USDT|74.977000|74.059000|74.977000|0.40|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001709|0.001687|0.001709|0.57|N|Y/Y|Y/N|Y|N|
|XRP_USDT|1.115900|1.105100|1.115900|0.61|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-09T02:15:01+00:00, last15m_closed_end=2026-11-09T02:15+00:00, prior8high=0.005297, depth_time=2026-11-09T02:15:13+00:00, book20_bid_proxy_usdt=48639, book20_ask_proxy_usdt=27105, funding_indicative=0.000050, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.74%, turnover=13015264. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HOT_USDT: quote_utc=2026-11-09T02:15:01+00:00, last15m_closed_end=2026-11-09T02:15+00:00, prior8high=0.000411, depth_time=2026-11-09T02:15:09+00:00, book20_bid_proxy_usdt=68541, book20_ask_proxy_usdt=132994, funding_indicative=-0.000160, next_funding_utc=2026-11-09T03:00:00+00:00, funding_cycle_h=1, 24h_change=-7.30%, turnover=6246076. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-09T02:15:01+00:00, last15m_closed_end=2026-11-09T02:15+00:00, prior8high=75.415000, depth_time=2026-11-09T02:15:17+00:00, book20_bid_proxy_usdt=92311, book20_ask_proxy_usdt=93860, funding_indicative=0.000050, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.16%, turnover=39920809. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T02:15:01+00:00, last15m_closed_end=2026-11-09T02:15+00:00, prior8high=0.001763, depth_time=2026-11-09T02:15:08+00:00, book20_bid_proxy_usdt=6335, book20_ask_proxy_usdt=10457, funding_indicative=-0.000878, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-12.73%, turnover=11266556. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T02:15:01+00:00, last15m_closed_end=2026-11-09T02:15+00:00, prior8high=1.125700, depth_time=2026-11-09T02:15:14+00:00, book20_bid_proxy_usdt=3609453, book20_ask_proxy_usdt=2919966, funding_indicative=0.000009, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.45%, turnover=229127324. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
