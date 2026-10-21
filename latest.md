# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T21:15:17Z**
- feed_generated_utc: 2026-10-21T21:15:20+00:00
- source_sha256: `8e60e0923a8b362b258fc799b7b36e6e5e90c1e78ed0b13bd44e8780a8de886d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T21:15+00:00, close=84653.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T21:00+00:00, close=84645, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T20:00+00:00, close=84445.3, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DOOD_USDT|0.002489|-12.48|75.52|-12.66|9117590|4.01|
|BR_USDT|0.485510|-10.34|19.07|-10.52|14778929|1.44|
|ZRO_USDT|2.001700|-4.55|5.69|-4.73|7315815|2.00|
|AKE_USDT|0.025512|-4.41|-1.42|-4.59|10278068|2.74|
|INJ_USDT|8.670000|-1.00|13.49|-1.18|57011762|2.31|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.025512|0.025195|0.025512|1.04|N|Y/Y|Y/Y|N|N|
|BR_USDT|0.485510|0.476600|0.485510|1.16|N|Y/Y|Y/Y|N|N|
|DOOD_USDT|0.002489|0.002323|0.002488|0.40|N|Y/Y|N/N|N|N|
|INJ_USDT|8.670000|8.474000|8.670000|0.95|N|Y/Y|Y/N|N|N|
|ZRO_USDT|2.001700|1.997600|2.001700|1.71|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-21T21:15:01+00:00, last15m_closed_end=2026-10-21T21:15+00:00, prior8high=0.026307, depth_time=2026-10-21T21:15:14+00:00, book20_bid_proxy_usdt=27409, book20_ask_proxy_usdt=16179, funding_indicative=0.000050, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.41%, turnover=10278068. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T21:15:01+00:00, last15m_closed_end=2026-10-21T21:15+00:00, prior8high=0.516520, depth_time=2026-10-21T21:15:10+00:00, book20_bid_proxy_usdt=5109, book20_ask_proxy_usdt=4446, funding_indicative=-0.000081, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-10.34%, turnover=14778929. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOOD_USDT: quote_utc=2026-10-21T21:15:01+00:00, last15m_closed_end=2026-10-21T21:15+00:00, prior8high=0.002549, depth_time=2026-10-21T21:15:07+00:00, book20_bid_proxy_usdt=119554, book20_ask_proxy_usdt=139065, funding_indicative=-0.000024, next_funding_utc=2026-10-21T22:00:00+00:00, funding_cycle_h=1, 24h_change=-12.48%, turnover=9117590. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-21T21:15:01+00:00, last15m_closed_end=2026-10-21T21:15+00:00, prior8high=8.686000, depth_time=2026-10-21T21:15:16+00:00, book20_bid_proxy_usdt=245991, book20_ask_proxy_usdt=213450, funding_indicative=0.000122, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.00%, turnover=57011762. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-21T21:15:01+00:00, last15m_closed_end=2026-10-21T21:15+00:00, prior8high=2.050700, depth_time=2026-10-21T21:15:10+00:00, book20_bid_proxy_usdt=29554, book20_ask_proxy_usdt=31647, funding_indicative=0.000017, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.55%, turnover=7315815. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
