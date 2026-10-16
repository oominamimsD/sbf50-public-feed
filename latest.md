# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T13:00:22Z**
- feed_generated_utc: 2026-10-16T13:00:24+00:00
- source_sha256: `237d07aa534c20462c5318cd0a40c01b23066166f3502f5238ce77f4347ba091`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T13:00+00:00, close=82010.8, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-16T13:00+00:00, close=82010.8, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-10-16T12:00+00:00, close=82599.5, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.075790|-21.34|25.98|-20.90|41392688|1.32|
|ZEREBRO_USDT|0.041948|-18.22|52.77|-17.78|5113516|1.43|
|PYTH_USDT|0.087920|-9.67|19.45|-9.23|10016769|2.27|
|BTW_USDT|1.733800|-9.10|24.88|-8.66|22601966|0.58|
|AKE_USDT|0.029685|-6.07|2.28|-5.63|18371937|0.34|
|NIL_USDT|0.081960|-5.66|-5.34|-5.22|5484900|1.22|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.029685|0.029345|0.029685|0.74|N|Y/Y|N/N|N|N|
|BTW_USDT|1.733800|1.611400|1.733800|0.61|N|Y/Y|Y/Y|N|N|
|NIL_USDT|0.081960|0.081930|0.081960|1.79|N|Y/Y|Y/Y|N|N|
|PYTH_USDT|0.087920|0.088440|0.087920|2.86|Y|Y/Y|N/N|N|N|
|STRK_USDT|0.075790|0.075650|0.075790|1.30|N|Y/Y|Y/Y|N|N|
|ZEREBRO_USDT|0.041948|0.037647|0.041948|0.90|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-16T12:59:59+00:00, last15m_closed_end=2026-10-16T13:00+00:00, prior8high=0.030310, depth_time=2026-10-16T13:00:19+00:00, book20_bid_proxy_usdt=13719, book20_ask_proxy_usdt=11506, funding_indicative=0.000050, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.07%, turnover=18371937. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-16T12:59:59+00:00, last15m_closed_end=2026-10-16T13:00+00:00, prior8high=1.924700, depth_time=2026-10-16T13:00:16+00:00, book20_bid_proxy_usdt=10226, book20_ask_proxy_usdt=11976, funding_indicative=-0.000550, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.10%, turnover=22601966. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NIL_USDT: quote_utc=2026-10-16T12:59:59+00:00, last15m_closed_end=2026-10-16T13:00+00:00, prior8high=0.083950, depth_time=2026-10-16T13:00:20+00:00, book20_bid_proxy_usdt=16757, book20_ask_proxy_usdt=27564, funding_indicative=0.000038, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.66%, turnover=5484900. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PYTH_USDT: quote_utc=2026-10-16T12:59:59+00:00, last15m_closed_end=2026-10-16T13:00+00:00, prior8high=0.092450, depth_time=2026-10-16T13:00:11+00:00, book20_bid_proxy_usdt=84288, book20_ask_proxy_usdt=109668, funding_indicative=0.000029, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.67%, turnover=10016769. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-16T12:59:59+00:00, last15m_closed_end=2026-10-16T13:00+00:00, prior8high=0.080420, depth_time=2026-10-16T13:00:08+00:00, book20_bid_proxy_usdt=168613, book20_ask_proxy_usdt=374648, funding_indicative=-0.000008, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-21.34%, turnover=41392688. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEREBRO_USDT: quote_utc=2026-10-16T12:59:59+00:00, last15m_closed_end=2026-10-16T13:00+00:00, prior8high=0.048095, depth_time=2026-10-16T13:00:10+00:00, book20_bid_proxy_usdt=25218, book20_ask_proxy_usdt=15847, funding_indicative=0.000050, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-18.22%, turnover=5113516. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
