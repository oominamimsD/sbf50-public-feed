# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-03T14:45:29Z**
- feed_generated_utc: 2026-11-03T14:45:30+00:00
- source_sha256: `e8ea123fdbf9bb914f09efa7cf302025d369a8cd1974133810ef9841103fafd1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-03T14:45+00:00, close=77354.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-03T14:00+00:00, close=77368.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-03T12:00+00:00, close=77085.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.004011|-27.09|-86.96|-26.93|12731899|2.49|
|XPL_USDT|0.064700|-7.01|-12.90|-6.85|11547849|1.55|
|QNT_USDT|194.950000|-3.70|-7.29|-3.54|54023779|0.51|
|TIA_USDT|0.441200|-3.43|-17.64|-3.27|13772717|2.27|
|NEAR_USDT|3.883000|-3.16|-15.08|-3.00|82643902|2.58|
|ENA_USDT|0.170930|-2.34|-18.74|-2.18|71734929|0.58|
|DASH_USDT|46.280000|-1.94|-11.37|-1.78|9407853|2.16|
|BEAT_USDT|0.098520|-1.71|21.15|-1.55|7515311|7.11|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004011|0.004076|0.004006|3.57|Y|Y/Y|Y/Y|Y|Y|
|BEAT_USDT|0.098520|0.098170|0.098520|1.29|N|Y/N|N/N|Y|N|
|DASH_USDT|46.280000|45.970000|46.280000|1.61|N|N/N|Y/Y|Y|N|
|ENA_USDT|0.170930|0.169280|0.170950|0.87|N|Y/N|Y/Y|Y|N|
|NEAR_USDT|3.883000|3.854000|3.883000|0.42|N|N/N|Y/Y|Y|N|
|QNT_USDT|194.950000|194.220000|194.950000|0.57|N|N/N|Y/Y|Y|N|
|TIA_USDT|0.441200|0.438000|0.441100|1.15|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.064700|0.064060|0.064670|1.32|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-03T14:45:03+00:00, last15m_closed_end=2026-11-03T14:45+00:00, prior8high=0.004513, depth_time=2026-11-03T14:45:09+00:00, book20_bid_proxy_usdt=38929, book20_ask_proxy_usdt=68855, funding_indicative=-0.000620, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-27.09%, turnover=12731899. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-11-03T14:45:03+00:00, last15m_closed_end=2026-11-03T14:45+00:00, prior8high=0.105300, depth_time=2026-11-03T14:45:27+00:00, book20_bid_proxy_usdt=13100, book20_ask_proxy_usdt=15984, funding_indicative=0.000383, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.71%, turnover=7515311. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-03T14:45:03+00:00, last15m_closed_end=2026-11-03T14:45+00:00, prior8high=46.820000, depth_time=2026-11-03T14:45:24+00:00, book20_bid_proxy_usdt=481849, book20_ask_proxy_usdt=677617, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.94%, turnover=9407853. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-03T14:45:03+00:00, last15m_closed_end=2026-11-03T14:45+00:00, prior8high=0.174220, depth_time=2026-11-03T14:45:22+00:00, book20_bid_proxy_usdt=165490, book20_ask_proxy_usdt=202813, funding_indicative=0.000050, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.34%, turnover=71734929. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-03T14:45:03+00:00, last15m_closed_end=2026-11-03T14:45+00:00, prior8high=3.945000, depth_time=2026-11-03T14:45:19+00:00, book20_bid_proxy_usdt=503757, book20_ask_proxy_usdt=3897548, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.16%, turnover=82643902. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-03T14:45:03+00:00, last15m_closed_end=2026-11-03T14:45+00:00, prior8high=200.480000, depth_time=2026-11-03T14:45:14+00:00, book20_bid_proxy_usdt=51063, book20_ask_proxy_usdt=81206, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.70%, turnover=54023779. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-03T14:45:03+00:00, last15m_closed_end=2026-11-03T14:45+00:00, prior8high=0.449000, depth_time=2026-11-03T14:45:17+00:00, book20_bid_proxy_usdt=388929, book20_ask_proxy_usdt=409707, funding_indicative=-0.000020, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.43%, turnover=13772717. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-03T14:45:03+00:00, last15m_closed_end=2026-11-03T14:45+00:00, prior8high=0.065540, depth_time=2026-11-03T14:45:12+00:00, book20_bid_proxy_usdt=290480, book20_ask_proxy_usdt=421729, funding_indicative=0.000050, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.01%, turnover=11547849. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
