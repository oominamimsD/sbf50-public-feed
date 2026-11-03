# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-03T15:45:29Z**
- feed_generated_utc: 2026-11-03T15:45:31+00:00
- source_sha256: `1fdbc841de6744337772668b83e11077ae0a78a7c581a7613b390ff85f013d80`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-03T15:45+00:00, close=77580.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-03T15:00+00:00, close=77364.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-03T12:00+00:00, close=77085.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.004151|-24.55|-86.51|-24.68|12588233|2.41|
|XPL_USDT|0.064000|-8.01|-13.85|-8.14|11243026|3.12|
|BEAT_USDT|0.093350|-6.87|14.79|-7.00|8086208|2.14|
|TIA_USDT|0.435400|-4.70|-18.72|-4.83|13833128|4.59|
|NEAR_USDT|3.854000|-3.89|-15.72|-4.02|82419249|2.60|
|QNT_USDT|195.240000|-3.56|-7.15|-3.69|55033758|1.02|
|WLD_USDT|0.371000|-2.67|-16.62|-2.80|49713119|2.70|
|DASH_USDT|46.060000|-2.41|-11.79|-2.54|8828245|2.17|
|ENA_USDT|0.171320|-2.12|-18.56|-2.25|71087135|0.58|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004151|0.003997|0.004152|0.68|N|Y/Y|Y/Y|Y|N|
|BEAT_USDT|0.093350|0.092780|0.093350|1.05|N|Y/Y|N/N|Y|N|
|DASH_USDT|46.060000|45.740000|46.070000|0.69|N|Y/N|Y/Y|Y|N|
|ENA_USDT|0.171320|0.169080|0.171320|1.60|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|3.854000|3.822000|3.854000|1.01|N|Y/N|Y/Y|Y|N|
|QNT_USDT|195.240000|193.330000|195.280000|0.89|N|Y/N|Y/Y|Y|N|
|TIA_USDT|0.435400|0.432900|0.435400|1.04|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.371000|0.369000|0.371000|1.05|N|Y/N|Y/Y|Y|N|
|XPL_USDT|0.064000|0.063460|0.063990|0.46|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-03T15:45:01+00:00, last15m_closed_end=2026-11-03T15:45+00:00, prior8high=0.004298, depth_time=2026-11-03T15:45:08+00:00, book20_bid_proxy_usdt=21901, book20_ask_proxy_usdt=31540, funding_indicative=-0.000116, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-24.55%, turnover=12588233. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-11-03T15:45:01+00:00, last15m_closed_end=2026-11-03T15:45+00:00, prior8high=0.104130, depth_time=2026-11-03T15:45:13+00:00, book20_bid_proxy_usdt=20743, book20_ask_proxy_usdt=8704, funding_indicative=0.000336, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.87%, turnover=8086208. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-03T15:45:01+00:00, last15m_closed_end=2026-11-03T15:45+00:00, prior8high=46.820000, depth_time=2026-11-03T15:45:25+00:00, book20_bid_proxy_usdt=812787, book20_ask_proxy_usdt=693142, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.41%, turnover=8828245. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-03T15:45:01+00:00, last15m_closed_end=2026-11-03T15:45+00:00, prior8high=0.174220, depth_time=2026-11-03T15:45:28+00:00, book20_bid_proxy_usdt=113290, book20_ask_proxy_usdt=197172, funding_indicative=0.000050, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.12%, turnover=71087135. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-03T15:45:01+00:00, last15m_closed_end=2026-11-03T15:45+00:00, prior8high=3.945000, depth_time=2026-11-03T15:45:18+00:00, book20_bid_proxy_usdt=4152906, book20_ask_proxy_usdt=910316, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.89%, turnover=82419249. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-03T15:45:01+00:00, last15m_closed_end=2026-11-03T15:45+00:00, prior8high=200.480000, depth_time=2026-11-03T15:45:20+00:00, book20_bid_proxy_usdt=78627, book20_ask_proxy_usdt=42236, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.56%, turnover=55033758. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-03T15:45:01+00:00, last15m_closed_end=2026-11-03T15:45+00:00, prior8high=0.448700, depth_time=2026-11-03T15:45:15+00:00, book20_bid_proxy_usdt=334572, book20_ask_proxy_usdt=323644, funding_indicative=-0.000013, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.70%, turnover=13833128. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-03T15:45:01+00:00, last15m_closed_end=2026-11-03T15:45+00:00, prior8high=0.378300, depth_time=2026-11-03T15:45:22+00:00, book20_bid_proxy_usdt=3376379, book20_ask_proxy_usdt=1587812, funding_indicative=0.000039, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.67%, turnover=49713119. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-03T15:45:01+00:00, last15m_closed_end=2026-11-03T15:45+00:00, prior8high=0.065420, depth_time=2026-11-03T15:45:10+00:00, book20_bid_proxy_usdt=401877, book20_ask_proxy_usdt=425993, funding_indicative=0.000050, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.01%, turnover=11243026. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
