# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T17:30:16Z**
- feed_generated_utc: 2026-10-27T17:30:19+00:00
- source_sha256: `be5d91a78e930e5fb187f2b77e9c7cf3136ca68adc2143b39bbc7a936e7d92d8`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T17:30+00:00, close=80723.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-27T17:00+00:00, close=80620.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-27T16:00+00:00, close=80529.9, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.056530|-11.09|-53.94|-11.31|60931553|1.06|
|IRYS_USDT|0.024590|-1.28|88.86|-1.50|5993191|8.13|
|NIL_USDT|0.091610|-1.16|3.09|-1.38|5580455|5.46|
|TIA_USDT|0.531700|-0.82|-14.61|-1.04|16769896|1.88|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|IRYS_USDT|0.024590|0.024340|0.024580|0.60|N|Y/Y|Y/Y|N|N|
|NIL_USDT|0.091610|0.089860|0.091610|0.10|N|Y/Y|N/N|N|N|
|Q_USDT|0.056530|0.052960|0.056788|1.37|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.531700|0.530300|0.531600|0.52|N|N/N|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- IRYS_USDT: quote_utc=2026-10-27T17:30:03+00:00, last15m_closed_end=2026-10-27T17:30+00:00, prior8high=0.025550, depth_time=2026-10-27T17:30:10+00:00, book20_bid_proxy_usdt=103499, book20_ask_proxy_usdt=95022, funding_indicative=-0.000451, next_funding_utc=2026-10-27T18:00:00+00:00, funding_cycle_h=1, 24h_change=-1.28%, turnover=5993191. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NIL_USDT: quote_utc=2026-10-27T17:30:04+00:00, last15m_closed_end=2026-10-27T17:30+00:00, prior8high=0.092950, depth_time=2026-10-27T17:30:12+00:00, book20_bid_proxy_usdt=4095, book20_ask_proxy_usdt=9349, funding_indicative=-0.000401, next_funding_utc=2026-10-27T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.16%, turnover=5580455. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-27T17:30:03+00:00, last15m_closed_end=2026-10-27T17:30+00:00, prior8high=0.069329, depth_time=2026-10-27T17:30:08+00:00, book20_bid_proxy_usdt=3384, book20_ask_proxy_usdt=2514, funding_indicative=0.000050, next_funding_utc=2026-10-27T20:00:00+00:00, funding_cycle_h=4, 24h_change=-11.09%, turnover=60931553. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-27T17:30:04+00:00, last15m_closed_end=2026-10-27T17:30+00:00, prior8high=0.541400, depth_time=2026-10-27T17:30:16+00:00, book20_bid_proxy_usdt=290566, book20_ask_proxy_usdt=356465, funding_indicative=-0.000044, next_funding_utc=2026-10-27T20:00:00+00:00, funding_cycle_h=4, 24h_change=-0.82%, turnover=16769896. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
