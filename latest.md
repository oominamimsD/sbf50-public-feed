# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T18:15:19Z**
- feed_generated_utc: 2026-10-13T18:15:22+00:00
- source_sha256: `47f69f9ce340a63e06a551e525f8eadc98e417ce947042baf89aecb4daa58274`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T18:15+00:00, close=83126.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-13T18:00+00:00, close=83063.9, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-10-13T16:00+00:00, close=83393, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|RLC_USDT|0.881600|-4.50|7.53|-4.19|5763545|1.13|
|W_USDT|0.016325|-2.84|12.49|-2.53|10610573|9.81|
|STRK_USDT|0.084890|-2.34|62.65|-2.03|46607484|1.18|
|DOS_USDT|0.210900|-2.04|-2.13|-1.73|9508447|4.74|
|STX_USDT|0.415200|-1.40|10.63|-1.09|18592939|2.41|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOS_USDT|0.210900|0.212000|0.210900|1.68|Y|Y/Y|Y/Y|N|Y|
|RLC_USDT|0.881600|0.896900|0.881600|1.54|Y|Y/Y|Y/Y|N|Y|
|STRK_USDT|0.084890|0.082420|0.084890|0.73|N|Y/Y|Y/Y|N|N|
|STX_USDT|0.415200|0.414200|0.415200|0.88|N|Y/N|N/N|N|N|
|W_USDT|0.016325|0.016124|0.016325|1.15|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- DOS_USDT: quote_utc=2026-10-13T18:14:59+00:00, last15m_closed_end=2026-10-13T18:15+00:00, prior8high=0.218600, depth_time=2026-10-13T18:15:16+00:00, book20_bid_proxy_usdt=136328, book20_ask_proxy_usdt=104610, funding_indicative=-0.000036, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.04%, turnover=9508447. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-13T18:14:59+00:00, last15m_closed_end=2026-10-13T18:15+00:00, prior8high=0.928600, depth_time=2026-10-13T18:15:09+00:00, book20_bid_proxy_usdt=55197, book20_ask_proxy_usdt=63814, funding_indicative=-0.000684, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.50%, turnover=5763545. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-13T18:14:59+00:00, last15m_closed_end=2026-10-13T18:15+00:00, prior8high=0.087530, depth_time=2026-10-13T18:15:13+00:00, book20_bid_proxy_usdt=226997, book20_ask_proxy_usdt=227146, funding_indicative=0.000025, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.34%, turnover=46607484. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STX_USDT: quote_utc=2026-10-13T18:14:59+00:00, last15m_closed_end=2026-10-13T18:15+00:00, prior8high=0.437700, depth_time=2026-10-13T18:15:19+00:00, book20_bid_proxy_usdt=212092, book20_ask_proxy_usdt=203763, funding_indicative=-0.000173, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.40%, turnover=18592939. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-13T18:14:59+00:00, last15m_closed_end=2026-10-13T18:15+00:00, prior8high=0.017236, depth_time=2026-10-13T18:15:11+00:00, book20_bid_proxy_usdt=19276, book20_ask_proxy_usdt=30822, funding_indicative=-0.000356, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.84%, turnover=10610573. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
