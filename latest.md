# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T21:00:18Z**
- feed_generated_utc: 2026-10-21T21:00:21+00:00
- source_sha256: `86ef1bb950fb705af954905b488eaffba3e0e8f2594e7ebe871bd418390aaee2`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T21:00+00:00, close=84645, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T21:00+00:00, close=84645, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T20:00+00:00, close=84445.3, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DOOD_USDT|0.002473|-13.04|74.40|-13.21|9135725|8.10|
|BR_USDT|0.484870|-10.46|18.91|-10.63|15281509|1.24|
|AKE_USDT|0.025508|-4.42|-1.44|-4.59|10336805|7.84|
|TIA_USDT|0.620000|-1.97|16.21|-2.14|40279609|1.61|
|INJ_USDT|8.681000|-0.87|13.64|-1.04|58470388|1.15|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.025508|0.025195|0.025512|1.00|N|Y/Y|Y/Y|N|N|
|BR_USDT|0.484870|0.476600|0.484870|1.49|N|Y/Y|Y/Y|N|N|
|DOOD_USDT|0.002473|0.002239|0.002468|0.32|N|Y/Y|N/N|N|N|
|INJ_USDT|8.681000|8.474000|8.681000|1.73|N|Y/Y|Y/N|N|N|
|TIA_USDT|0.620000|0.614400|0.620000|1.01|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-21T20:59:59+00:00, last15m_closed_end=2026-10-21T21:00+00:00, prior8high=0.026307, depth_time=2026-10-21T21:00:12+00:00, book20_bid_proxy_usdt=12267, book20_ask_proxy_usdt=10876, funding_indicative=0.000050, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.42%, turnover=10336805. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T20:59:59+00:00, last15m_closed_end=2026-10-21T21:00+00:00, prior8high=0.519450, depth_time=2026-10-21T21:00:11+00:00, book20_bid_proxy_usdt=4139, book20_ask_proxy_usdt=4678, funding_indicative=-0.000097, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-10.46%, turnover=15281509. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOOD_USDT: quote_utc=2026-10-21T20:59:59+00:00, last15m_closed_end=2026-10-21T21:00+00:00, prior8high=0.002549, depth_time=2026-10-21T21:00:08+00:00, book20_bid_proxy_usdt=131713, book20_ask_proxy_usdt=123723, funding_indicative=0.000005, next_funding_utc=2026-10-21T22:00:00+00:00, funding_cycle_h=1, 24h_change=-13.04%, turnover=9135725. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-21T20:59:59+00:00, last15m_closed_end=2026-10-21T21:00+00:00, prior8high=8.680000, depth_time=2026-10-21T21:00:17+00:00, book20_bid_proxy_usdt=314001, book20_ask_proxy_usdt=207015, funding_indicative=0.000112, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.87%, turnover=58470388. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T20:59:59+00:00, last15m_closed_end=2026-10-21T21:00+00:00, prior8high=0.634000, depth_time=2026-10-21T21:00:15+00:00, book20_bid_proxy_usdt=297544, book20_ask_proxy_usdt=500329, funding_indicative=-0.000095, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.97%, turnover=40279609. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
