# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T18:00:18Z**
- feed_generated_utc: 2026-10-13T18:00:21+00:00
- source_sha256: `f5c871d08b7d2115eb230f5f3bb8ac59d3bdb602b3fd480c3b28bf852c41c79f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T18:00+00:00, close=83063.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-13T18:00+00:00, close=83063.9, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-10-13T16:00+00:00, close=83393, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|PYTH_USDT|0.077780|-6.10|-0.06|-5.71|7350517|1.28|
|STRK_USDT|0.084190|-3.15|61.31|-2.76|46313023|1.19|
|OGN_USDT|0.034930|-2.83|55.86|-2.44|7389639|2.86|
|RLC_USDT|0.899600|-2.55|9.73|-2.16|5669655|1.11|
|DOS_USDT|0.212200|-1.43|-1.53|-1.04|9498599|4.71|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOS_USDT|0.212200|0.212000|0.212300|0.31|N|Y/Y|Y/Y|N|N|
|OGN_USDT|0.034930|0.034850|0.034930|0.38|N|Y/Y|N/N|N|N|
|PYTH_USDT|0.077780|0.077410|0.077780|0.83|N|Y/Y|Y/N|N|N|
|RLC_USDT|0.899600|0.897900|0.898300|0.51|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.084190|0.082420|0.084280|0.57|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- DOS_USDT: quote_utc=2026-10-13T18:00:03+00:00, last15m_closed_end=2026-10-13T18:00+00:00, prior8high=0.218600, depth_time=2026-10-13T18:00:17+00:00, book20_bid_proxy_usdt=149085, book20_ask_proxy_usdt=139772, funding_indicative=-0.000011, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.43%, turnover=9498599. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OGN_USDT: quote_utc=2026-10-13T18:00:03+00:00, last15m_closed_end=2026-10-13T18:00+00:00, prior8high=0.035580, depth_time=2026-10-13T18:00:11+00:00, book20_bid_proxy_usdt=140864, book20_ask_proxy_usdt=160576, funding_indicative=-0.000373, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.83%, turnover=7389639. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PYTH_USDT: quote_utc=2026-10-13T18:00:03+00:00, last15m_closed_end=2026-10-13T18:00+00:00, prior8high=0.080250, depth_time=2026-10-13T18:00:06+00:00, book20_bid_proxy_usdt=63128, book20_ask_proxy_usdt=113641, funding_indicative=-0.000002, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-6.10%, turnover=7350517. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-13T18:00:03+00:00, last15m_closed_end=2026-10-13T18:00+00:00, prior8high=0.933600, depth_time=2026-10-13T18:00:12+00:00, book20_bid_proxy_usdt=51965, book20_ask_proxy_usdt=50891, funding_indicative=-0.000694, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.55%, turnover=5669655. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-13T18:00:03+00:00, last15m_closed_end=2026-10-13T18:00+00:00, prior8high=0.087530, depth_time=2026-10-13T18:00:11+00:00, book20_bid_proxy_usdt=151101, book20_ask_proxy_usdt=181052, funding_indicative=0.000018, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.15%, turnover=46313023. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
