# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-05T22:15:22Z**
- feed_generated_utc: 2026-11-05T22:15:23+00:00
- source_sha256: `92c12721ebeee6df7e1d23931db2790fc4b895a9a2101a52c7a74b1716f44d83`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-05T22:15+00:00, close=76077.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-05T22:00+00:00, close=75826.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-05T20:00+00:00, close=76344.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002181|-15.46|-89.64|-15.54|19473438|4.59|
|FLUID_USDT|2.406000|-4.97|16.56|-5.05|8022663|4.16|
|BCH_USDT|271.560000|-2.70|-5.79|-2.78|8881354|1.84|
|ATOM_USDT|1.391000|-2.04|-14.71|-2.12|5275096|7.19|
|XRP_USDT|1.226300|-1.47|-6.35|-1.55|434994062|0.81|
|HYPE_USDT|77.620000|-1.37|-17.36|-1.45|89075219|0.13|
|QNT_USDT|189.400000|-1.26|-4.69|-1.34|42759113|0.53|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002181|0.002009|0.002181|0.09|N|Y/Y|Y/Y|Y|N|
|ATOM_USDT|1.391000|1.392000|1.391000|1.71|Y|Y/Y|Y/N|Y|N|
|BCH_USDT|271.560000|271.110000|271.560000|1.34|N|Y/Y|Y/N|Y|N|
|FLUID_USDT|2.406000|2.355000|2.406000|1.31|N|Y/Y|N/N|Y|N|
|HYPE_USDT|77.620000|77.493000|77.620000|2.31|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|189.400000|187.390000|189.400000|0.78|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.226300|1.217300|1.226300|0.51|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-05T22:14:59+00:00, last15m_closed_end=2026-11-05T22:15+00:00, prior8high=0.002263, depth_time=2026-11-05T22:15:07+00:00, book20_bid_proxy_usdt=32964, book20_ask_proxy_usdt=43605, funding_indicative=-0.000646, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-15.46%, turnover=19473438. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ATOM_USDT: quote_utc=2026-11-05T22:14:59+00:00, last15m_closed_end=2026-11-05T22:15+00:00, prior8high=1.447000, depth_time=2026-11-05T22:15:12+00:00, book20_bid_proxy_usdt=2205093, book20_ask_proxy_usdt=1473514, funding_indicative=-0.000045, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.04%, turnover=5275096. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BCH_USDT: quote_utc=2026-11-05T22:14:59+00:00, last15m_closed_end=2026-11-05T22:15+00:00, prior8high=278.650000, depth_time=2026-11-05T22:15:11+00:00, book20_bid_proxy_usdt=45554, book20_ask_proxy_usdt=63459, funding_indicative=0.000100, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.70%, turnover=8881354. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FLUID_USDT: quote_utc=2026-11-05T22:14:59+00:00, last15m_closed_end=2026-11-05T22:15+00:00, prior8high=2.408000, depth_time=2026-11-05T22:15:07+00:00, book20_bid_proxy_usdt=184106, book20_ask_proxy_usdt=140143, funding_indicative=0.000096, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.97%, turnover=8022663. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-05T22:14:59+00:00, last15m_closed_end=2026-11-05T22:15+00:00, prior8high=78.964000, depth_time=2026-11-05T22:15:18+00:00, book20_bid_proxy_usdt=97189, book20_ask_proxy_usdt=79834, funding_indicative=0.000050, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.37%, turnover=89075219. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-05T22:14:59+00:00, last15m_closed_end=2026-11-05T22:15+00:00, prior8high=192.290000, depth_time=2026-11-05T22:15:20+00:00, book20_bid_proxy_usdt=70741, book20_ask_proxy_usdt=58904, funding_indicative=-0.000011, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.26%, turnover=42759113. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-05T22:14:59+00:00, last15m_closed_end=2026-11-05T22:15+00:00, prior8high=1.244300, depth_time=2026-11-05T22:15:16+00:00, book20_bid_proxy_usdt=3181757, book20_ask_proxy_usdt=3550805, funding_indicative=0.000100, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.47%, turnover=434994062. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
