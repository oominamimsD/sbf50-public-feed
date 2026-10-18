# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T22:15:25Z**
- feed_generated_utc: 2026-10-18T22:15:27+00:00
- source_sha256: `dc14f29f7c1f8c532a81c0cb95ef2d7252db179ebbcc836eac649459c88713ac`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T22:15+00:00, close=81547.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-18T22:00+00:00, close=81181.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-18T20:00+00:00, close=80844.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.062012|-8.16|250.64|-8.66|10108180|5.97|
|PUMPFUN_USDT|0.004048|-3.50|-29.90|-4.00|33816824|2.47|
|TIA_USDT|0.604400|-2.18|2.66|-2.68|51567463|1.65|
|STRK_USDT|0.060490|-1.73|-49.28|-2.23|15486883|1.65|
|SAND_USDT|0.057860|-1.53|-12.91|-2.03|34227813|1.73|
|QNT_USDT|187.750000|-0.77|-22.68|-1.27|64123195|1.60|
|ASTER_USDT|0.693000|-0.61|-3.26|-1.11|10537387|1.44|
|XPL_USDT|0.075480|-0.60|-15.42|-1.10|6539136|2.65|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.062012|0.061280|0.062012|1.23|N|Y/Y|N/N|Y|N|
|ASTER_USDT|0.693000|0.679100|0.693000|1.84|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004048|0.003864|0.004048|2.08|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|187.750000|182.140000|187.750000|2.98|N|Y/Y|Y/Y|Y|N|
|SAND_USDT|0.057860|0.056220|0.057860|9.11|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.060490|0.058420|0.060490|2.69|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.604400|0.586400|0.604400|3.11|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.075480|0.073340|0.075480|2.07|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-18T22:14:59+00:00, last15m_closed_end=2026-10-18T22:15+00:00, prior8high=0.067059, depth_time=2026-10-18T22:15:07+00:00, book20_bid_proxy_usdt=6369, book20_ask_proxy_usdt=3919, funding_indicative=0.000278, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=4, 24h_change=-8.16%, turnover=10108180. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ASTER_USDT: quote_utc=2026-10-18T22:14:59+00:00, last15m_closed_end=2026-10-18T22:15+00:00, prior8high=0.688800, depth_time=2026-10-18T22:15:19+00:00, book20_bid_proxy_usdt=701939, book20_ask_proxy_usdt=699076, funding_indicative=0.000046, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.61%, turnover=10537387. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T22:14:59+00:00, last15m_closed_end=2026-10-18T22:15+00:00, prior8high=0.003989, depth_time=2026-10-18T22:15:09+00:00, book20_bid_proxy_usdt=1026618, book20_ask_proxy_usdt=827091, funding_indicative=0.000030, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.50%, turnover=33816824. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-18T22:14:59+00:00, last15m_closed_end=2026-10-18T22:15+00:00, prior8high=185.740000, depth_time=2026-10-18T22:15:19+00:00, book20_bid_proxy_usdt=70585, book20_ask_proxy_usdt=41615, funding_indicative=0.000040, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.77%, turnover=64123195. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-18T22:14:59+00:00, last15m_closed_end=2026-10-18T22:15+00:00, prior8high=0.057040, depth_time=2026-10-18T22:15:17+00:00, book20_bid_proxy_usdt=593161, book20_ask_proxy_usdt=336698, funding_indicative=-0.002353, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.53%, turnover=34227813. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T22:14:59+00:00, last15m_closed_end=2026-10-18T22:15+00:00, prior8high=0.060290, depth_time=2026-10-18T22:15:15+00:00, book20_bid_proxy_usdt=554077, book20_ask_proxy_usdt=380612, funding_indicative=0.000050, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.73%, turnover=15486883. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-18T22:14:59+00:00, last15m_closed_end=2026-10-18T22:15+00:00, prior8high=0.597600, depth_time=2026-10-18T22:15:12+00:00, book20_bid_proxy_usdt=217343, book20_ask_proxy_usdt=207594, funding_indicative=0.000050, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.18%, turnover=51567463. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-10-18T22:14:59+00:00, last15m_closed_end=2026-10-18T22:15+00:00, prior8high=0.075060, depth_time=2026-10-18T22:15:24+00:00, book20_bid_proxy_usdt=568678, book20_ask_proxy_usdt=252477, funding_indicative=0.000008, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.60%, turnover=6539136. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
