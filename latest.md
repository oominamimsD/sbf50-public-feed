# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T20:30:17Z**
- feed_generated_utc: 2026-10-13T20:30:20+00:00
- source_sha256: `8f3578849aedd783f39554bacf403b1480d57e496fb4a5cf6825b36f80de88be`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T20:30+00:00, close=83179.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-13T20:00+00:00, close=83253, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-13T20:00+00:00, close=83253, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|CT_USDT|0.354860|-4.54|-4.50|-4.29|5785053|0.28|
|RLC_USDT|0.885000|-4.13|7.95|-3.88|5675800|3.39|
|DOS_USDT|0.208700|-3.06|-3.15|-2.81|9330124|4.79|
|STRK_USDT|0.084720|-2.54|62.32|-2.29|41861623|1.18|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|CT_USDT|0.354860|0.351000|0.354860|0.45|N|Y/Y|N/N|N|N|
|DOS_USDT|0.208700|0.206400|0.208700|0.70|N|Y/Y|Y/Y|N|N|
|RLC_USDT|0.885000|0.874600|0.885000|0.91|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.084720|0.084360|0.084730|0.65|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- CT_USDT: quote_utc=2026-10-13T20:30:02+00:00, last15m_closed_end=2026-10-13T20:30+00:00, prior8high=0.366930, depth_time=2026-10-13T20:30:07+00:00, book20_bid_proxy_usdt=40101, book20_ask_proxy_usdt=8465, funding_indicative=0.000050, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.54%, turnover=5785053. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOS_USDT: quote_utc=2026-10-13T20:30:02+00:00, last15m_closed_end=2026-10-13T20:30+00:00, prior8high=0.214000, depth_time=2026-10-13T20:30:12+00:00, book20_bid_proxy_usdt=122499, book20_ask_proxy_usdt=83459, funding_indicative=-0.000130, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.06%, turnover=9330124. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-13T20:30:02+00:00, last15m_closed_end=2026-10-13T20:30+00:00, prior8high=0.908000, depth_time=2026-10-13T20:30:10+00:00, book20_bid_proxy_usdt=49599, book20_ask_proxy_usdt=62794, funding_indicative=-0.000523, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.13%, turnover=5675800. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-13T20:30:02+00:00, last15m_closed_end=2026-10-13T20:30+00:00, prior8high=0.089710, depth_time=2026-10-13T20:30:16+00:00, book20_bid_proxy_usdt=185464, book20_ask_proxy_usdt=213558, funding_indicative=0.000033, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.54%, turnover=41861623. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
